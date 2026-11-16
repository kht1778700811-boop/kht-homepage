# (주)금호테크닉스 홈페이지

햇빛소득마을 재생에너지 종합서비스기업(ReSCO) (주)금호테크닉스 홈페이지와 사업안내서입니다.

## 파일 구성

| 파일 | 내용 |
|---|---|
| `index.html` | 홈페이지 (한 페이지 구성) |
| `brochure.html` | 사업안내서 웹 보기용 (A4 9쪽) |
| `kht-brochure.pdf` | 사업안내서 PDF (홈페이지의 "소개서" 버튼으로 다운로드) |
| `img/` | 로고, 시공 실적 사진 |

## GitHub Pages로 배포

1. GitHub에서 새 저장소를 만듭니다. 예: `kht-homepage`
2. 이 폴더의 파일을 모두 올립니다. 웹에서 "Add file → Upload files"로 끌어다 놓아도 됩니다.
3. 저장소의 Settings → Pages에서 Source를 `main` 브랜치, `/ (root)`로 지정합니다.
4. 1~2분 뒤 `https://<아이디>.github.io/kht-homepage/` 주소로 접속됩니다.

회사 도메인(예: kumhotechnics.co.kr)을 연결하려면 Settings → Pages → Custom domain에 도메인을 입력합니다. 그다음 도메인 업체 DNS에 GitHub Pages용 CNAME 또는 A 레코드를 추가합니다.

## 수정 방법

- **글자 수정:** `index.html`에서 해당 문구를 찾아 바꿉니다.
- **실적 사진 교체:** `img/p1.jpg` ~ `img/p6.jpg`를 같은 이름의 원본 사진으로 덮어씁니다. 가로 1600px 정도를 권장합니다.
- **소개서 수정:** `brochure.html`을 고친 뒤 크롬에서 열어 인쇄 → PDF로 저장합니다. 용지는 A4, 여백은 없음, 배경 그래픽은 켜 둡니다. 저장한 파일을 `kht-brochure.pdf`로 덮어씁니다.
