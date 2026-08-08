# 엘림이레교회 홈페이지

대한예수교장로회 백석총회 충청노회 **엘림이레교회** 공식 홈페이지입니다.

- **구조** — `index.html` 파일 하나로 동작하는 정적 사이트 (서버·데이터베이스 없음)
- **배포** — GitHub Pages
- **작업 문서** — [`PROJECT.md`](PROJECT.md) 를 먼저 읽어주세요. 작업 원칙과 남은 할 일이 정리되어 있습니다.

## 파일

| 파일 | 설명 |
|---|---|
| `index.html` | 전체 사이트 (HTML + CSS + JS + 이미지 base64) |
| `404.html` | 없는 주소로 들어왔을 때 보이는 안내 페이지 |
| `og-image.jpg` | 카카오톡·페이스북 공유 시 표시되는 미리보기 이미지 (1200×630) |
| `robots.txt` / `sitemap.xml` | 검색엔진 안내 |
| `PROJECT.md` | 인계 문서 |

## 내용 수정하기

`index.html` 안의 `<script>` 첫 부분에 있는 **`CONFIG`** 와 그 아래 목록(`HISTORY`, `PEOPLE`, `CREED`, `NOTICES`, `FAQS`)만 고치면 화면이 바뀝니다. 자세한 방법은 `PROJECT.md` 5·7번 항목을 참고하세요.

## 로컬에서 확인하기

브라우저로 파일을 직접 열면(`file://`) 유튜브 영상이 차단됩니다. 아래처럼 실행한 뒤 `http://localhost:8000` 으로 접속하세요.

```bash
python3 -m http.server 8000
```

## 주소

`https://intoedu.github.io/Elim-ire-Church-Home-Page/` (GitHub Pages)

## 이전 버전

커밋 `697482c` (2026-08-05) 의 초기 버전에는 지금은 빠져 있는 **복음(`#gospel`) 섹션**과
**AI 말씀 안내 로드맵**이 들어 있습니다. 되살리실 수 있으니 `PROJECT.md` 12번 항목을 참고하세요.
