# CX Chat Tester

클래스101 CX팀을 위한 Webhook 테스트 도구입니다.

## 🚀 사용 방법

### 온라인 (GitHub Pages)
배포 후 `https://[username].github.io/[repo-name]` 에서 바로 사용 가능

### 로컬
```bash
# 파일 열기
open index.html
```

## 📡 기본 설정

| 항목 | 기본값 |
|------|--------|
| Webhook URL | `https://mkt-n8n.class101.net/webhook-test/chat` |
| User ID | `cx_tester_001` |

## 📤 요청 형식

```json
{
  "message": "사용자가 입력한 메시지",
  "userId": "cx_tester_001"
}
```

## 📥 응답 형식

n8n 워크플로우에서 반환하는 JSON 응답이 그대로 표시됩니다.

## 🛠 GitHub Pages 배포

1. GitHub에 레포지토리 생성
2. 코드 푸시
3. Settings > Pages > Source: `main` branch 선택
4. 배포 완료!

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/[username]/[repo-name].git
git push -u origin main
```

## 📝 라이선스

MIT License - 클래스101 내부 사용

