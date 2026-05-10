---
title: 프론트가 n8n으로 보내는 데이터
---

# 프론트가 n8n으로 보내는 데이터

프론트 화면은 사용자가 입력한 내용을 n8n Webhook으로 보냅니다.

```json
{
  "reference_text": "참고자료",
  "mode": "text",
  "content": "노트 내용"
}
```

파일 업로드는 base64로 변환해 `file_base64`, `file_name`, `mime_type` 필드에 담습니다.
