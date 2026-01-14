# CX Chat Tester

클래스101 CX팀을 위한 Webhook 테스트 도구입니다.

## 🚀 사용 방법

### 온라인
https://hyo4b.github.io/cx-chat-tester/

### 로컬
```bash
open index.html
```

## 🔐 보안

- Webhook URL은 코드에 포함되지 않습니다
- 설정은 브라우저 localStorage에 Base64 인코딩되어 저장됩니다
- URL 입력 필드는 기본적으로 `password` 타입으로 마스킹됩니다
- "설정 초기화" 버튼으로 저장된 정보를 삭제할 수 있습니다

## ⚙️ 최초 설정

1. 사이트 접속 시 설정 패널이 자동으로 열립니다
2. Webhook URL 입력 (팀 내부에서 공유받은 URL)
3. User ID 설정 (선택)
4. 설정은 자동 저장됩니다

## 📤 요청 형식

```json
{
  "message": "사용자가 입력한 메시지",
  "userId": "cx_tester_001"
}
```

## 📥 응답 형식

n8n 워크플로우에서 반환하는 JSON 응답이 그대로 표시됩니다.

## 🛠 기능

- ⌨️ Enter로 전송, Shift+Enter로 줄바꿈
- 👁 URL 보기/숨기기 토글
- 💾 설정 자동 저장 (localStorage)
- 📱 모바일 반응형 지원

## 📝 라이선스

MIT License - 클래스101 내부 사용
