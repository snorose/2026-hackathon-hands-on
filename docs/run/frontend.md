---
title: 프론트 화면 실행하기
---

# 프론트 화면 실행하기

프론트 화면은 `frontend/` 폴더에 들어 있습니다.

```bash
cd "/Users/esc/Desktop/2026-hackathon/Solar Teacher Low-Code/frontend"
python3 -m http.server 3010
```

브라우저에서 아래 주소를 엽니다.

```text
http://localhost:3010
```

n8n Webhook URL이 아래 주소인지 확인합니다.

```text
http://localhost:5678/webhook/solar-teacher/analyze
```
