# 🛒 쇼핑 리스트 앱

할 일 관리 방식으로 오늘 살 물건을 간편하게 기록하는 순수 HTML/CSS/JS 단일 파일 웹 앱입니다.

## 🔗 데모

**https://youngsooklim.github.io/shopping-listapp/**

## ✨ 주요 기능

- **아이템 추가** — 입력창에 입력 후 버튼 클릭 또는 Enter
- **완료 체크** — 체크박스 클릭으로 완료/미완료 토글
- **아이템 삭제** — 개별 삭제 버튼 또는 완료 항목 일괄 삭제
- **필터** — 전체 / 미완료 / 완료 탭으로 목록 필터링
- **로컬 저장** — `localStorage`를 통해 새로고침 후에도 데이터 유지

## 🛠 기술 스택

| 항목 | 내용 |
|------|------|
| 언어 | HTML5 · CSS3 · Vanilla JavaScript |
| 저장소 | `localStorage` |
| 빌드 도구 | 없음 (단일 파일) |
| 배포 | GitHub Pages |

## 🚀 로컬 실행

별도 설치 없이 `index.html` 파일을 브라우저에서 바로 열면 됩니다.

```bash
git clone https://github.com/youngsooklim/shopping-listapp.git
cd shopping-listapp
open index.html   # macOS
# 또는 index.html 파일을 더블클릭
```

## 📁 프로젝트 구조

```
shopping-listapp/
└── index.html   # 앱 전체 (HTML + CSS + JS)
```

## ♿ 접근성

- 커스텀 체크박스에 `role="checkbox"` 및 `aria-checked` 적용
- 키보드(Enter / Space)로 체크박스 조작 가능
- `aria-live="polite"`로 목록 변경 시 스크린리더 알림
- 모든 버튼에 `aria-label` 제공
