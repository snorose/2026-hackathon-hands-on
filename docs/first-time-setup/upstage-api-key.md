---
title: Upstage API Key 준비하기
---

# Upstage API Key 준비하기

Upstage API Key는 OCR과 AI 답변 생성을 사용하기 위한 열쇠입니다.

## `.env`에 넣기

```env
UPSTAGE_API_KEY=up_여기에_내_API_KEY
UPSTAGE_CHAT_MODEL=solar-pro
N8N_SECURE_COOKIE=false
N8N_BLOCK_ENV_ACCESS_IN_NODE=false
```

:::warning
API Key는 다른 사람에게 공유하지 마세요.
:::

## Key를 바꾼 뒤에는 n8n을 다시 시작해야 합니다

NPX 방식이라면 실행 중인 터미널에서 `Ctrl + C`로 n8n을 끄고, `.env`를 다시 불러온 뒤 `npx n8n`을 실행합니다.

Docker Compose 방식이라면 n8n 컨테이너를 재생성합니다.

```bash
docker compose up -d --force-recreate
```
