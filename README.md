[README.md](https://github.com/user-attachments/files/28040179/README.md)
# CustomerMeetingNotes
Notes for Customer Meetings # CSU Meeting Note — Zivid

HubSpot과 연동되는 미팅 노트 작성 앱입니다.  
GitHub Pages로 바로 배포해서 사용할 수 있어요.

## 기능

- HubSpot 연락처 / 딜 검색 후 노트 연결
- 미팅 정보 섹션별 입력 
- **ZDF · PNG 파일 첨부** (드래그 앤 드롭 지원, PNG 미리보기)
- 작성 완료 후 HubSpot Note로 바로 저장

---

## GitHub Pages 배포

## 필요한 것

| 항목 | 설명 |
|------|------|
| Anthropic API Key | [console.anthropic.com](https://console.anthropic.com) 에서 발급 |
| HubSpot MCP | Anthropic API에서 HubSpot MCP 사용 권한 필요 |

---

## 파일 구조

```
csu-meeting-note/
└── index.html   # 앱 전체 (HTML + CSS + JS 단일 파일)
```

단일 HTML 파일이라 별도 빌드 과정 없이 바로 배포 가능합니다.

