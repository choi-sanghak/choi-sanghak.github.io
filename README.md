# 최상학 | 재무학 | 연세대학교

연세대학교 미래캠퍼스 경영학부 최상학 교수의 학술 홈페이지입니다.

**홈페이지:** https://choi-sanghak.github.io/

**저장소:** https://github.com/choi-sanghak/choi-sanghak.github.io

## 운영 안내

GitHub Pages로 공개하는 정적 홈페이지입니다. 기본 언어는 한국어이며 화면 상단에서 영어로 전환할 수 있습니다. 논문 제목, 학술지명, 학위명 등은 원래 언어로 표시합니다.

GitHub Pages 설정은 **Settings > Pages**에서 확인할 수 있습니다.

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/(root)`

변경사항을 `main` 브랜치에 반영하면 GitHub Pages 배포가 실행됩니다. 배포 상태는 **Actions** 탭에서 확인하세요.

## 파일 구성

| 파일 | 내용 |
| --- | --- |
| `index.html` | 소개, 연구분야, 강의, 약력, 연락처 및 연세대학교 로고 |
| `styles.css` | 글꼴, 색상, 레이아웃, 모바일 화면 대응 |
| `app.js` | 언어 전환, 논문 검색, 연도 필터, 모바일 메뉴 |
| `publications.json` | 게재 논문과 Working Papers 목록 |

연세대학교 로고는 현재 `index.html` 안에 이미지 데이터 형태로 포함되어 있습니다. 별도의 `assets/yonsei-logo.png` 파일을 필요로 하지 않습니다.

## 홈페이지 편집

- 논문 추가 및 서지정보 수정: `publications.json`
- 소개문, 강의, 학력 및 연락처 수정: `index.html`
- 한국어와 영어 화면 문구 변경: `index.html` 및 `app.js`
- 글꼴, 글자 크기 및 레이아웃 조정: `styles.css`

글꼴은 **Noto Sans KR**, 글자 크기는 **13, 15, 20, 28px** 네 단계로 제한합니다. 사진은 사용하지 않습니다.

## 공개 정보 및 기준

- 논문과 Working Papers는 **2026년 10월 CV**에 근거합니다.
- 한국어 페이지가 기본 화면입니다.
- 학력의 연도와 개인 휴대전화 번호는 공개하지 않습니다.
- 과거 박사학위 취득과 BK21 박사후연구원 경력을 설명하는 짧은 소개문은 요청에 따라 제거했습니다. 경력 및 학력 항목 자체는 유지됩니다.
- 논문 링크는 확인되지 않은 DOI를 임의로 제시하지 않고, 학술 검색 결과로 연결합니다.
- CV 항목의 '인쇄 / PDF로 저장' 기능은 브라우저의 인쇄 기능을 사용합니다.

이 문서는 `choi-sanghak.github.io` 저장소 및 짧은 홈페이지 주소에 맞게 갱신되었습니다.
