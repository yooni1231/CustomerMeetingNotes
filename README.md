[README.md](https://github.com/user-attachments/files/28040179/README.md)
# CustomerMeetingNotes
Notes for Customer Meetings # CSU Meeting Note — Zivid

HubSpot과 연동되는 CSU 미팅 노트 작성 앱입니다.  
GitHub Pages로 바로 배포해서 사용할 수 있어요.

## 기능

- HubSpot 연락처 / 딜 검색 후 노트 연결
- 미팅 정보 섹션별 입력 (기본 정보, 고객, 로봇 환경, Application, 규모/타임라인, CSU 지원 예측, 액션 아이템)
- **ZDF · PNG 파일 첨부** (드래그 앤 드롭 지원, PNG 미리보기)
- 작성 완료 후 HubSpot Note로 바로 저장

---

## GitHub Pages 배포 방법

### 1단계 — 레포지토리 생성

1. GitHub에서 새 레포지토리 생성 (예: `csu-meeting-note`)
2. `index.html` 파일을 레포지토리 루트에 업로드

```bash
git init
git add index.html
git commit -m "init: CSU meeting note app"
git remote add origin https://github.com/<your-org>/csu-meeting-note.git
git push -u origin main
```

### 2단계 — GitHub Pages 활성화

1. 레포지토리 → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)` 선택 후 **Save**
4. 잠시 후 `https://<your-org>.github.io/csu-meeting-note/` 에서 접속 가능

---

## 사용 방법

1. 페이지 상단 **Anthropic API Key** 입력 후 저장  
   (세션 동안만 유지 — 페이지를 닫으면 재입력 필요)
2. 회사명 또는 이름으로 HubSpot 연락처 검색
3. 연락처 선택 후 미팅 노트 양식 작성
4. Application & 프로젝트 섹션에서 ZDF / PNG 파일 첨부 가능
5. **HubSpot에 저장** 버튼으로 노트 등록

---

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

