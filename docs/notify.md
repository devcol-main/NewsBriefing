# 알림 유틸

## slack (사용 중)
Incoming Webhook 으로 보낸다. 발신자가 "DevCol Bot" 앱이라 폰 푸시 알림이 온다.
(Slack 커넥터/MCP 는 오너 본인 계정으로 발신되어 푸시가 오지 않으므로 알림에는 쓰지 않는다.)

| 채널 | 환경변수 | 용도 |
|---|---|---|
| #ai-newsbriefing (private) | `SLACK_WEBHOOK_URL` | stock-news 브리핑·에러 알림 |

- URL 은 비밀값이다. 클라우드 루틴은 claude.ai 클라우드 환경 변수에, 로컬은 `.env` 에만 둔다. 출력·커밋·로그 금지.
- 클라우드 환경 Network access 는 도메인 지정 방식이다. 허용 목록: `hooks.slack.com`, `api.frankfurter.app`. 새 외부 호출이 필요하면 여기에 추가하고 오너가 환경 설정에 반영한다.
- 채널을 추가하려면 Slack 앱(DevCol Bot) → Incoming Webhooks → Add New Webhook 으로 채널별 URL 을 발급하고 환경변수 이름을 이 표에 추가한다.

보내는 방법 (본문을 파일에 쓴 뒤 JSON 이스케이프):
```bash
python3 -c 'import json,sys; print(json.dumps({"text": sys.stdin.read()}))' < /tmp/slack_msg.txt \
  | curl -sS -o /dev/null -w '%{http_code}\n' -X POST -H 'Content-type: application/json' --data @- "$SLACK_WEBHOOK_URL"
```
응답 코드 200 이면 성공.

