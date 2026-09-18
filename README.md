# 강태원 · 源 웹페이지

GitHub Pages에 바로 올릴 수 있는 정적 사이트입니다.

## 파일
- `index.html` : 강태원 캐릭터 소개 페이지
- `won.html` : 源 레스토랑 페이지
- `.nojekyll` : GitHub Pages가 파일을 그대로 서빙하도록 하는 빈 파일

## 源 운영시간
- 화요일 ~ 일요일
- 1부 18:00
- 2부 20:30
- 월요일 정기휴무
- 완전 예약제

## GitHub Pages 올리기
1. GitHub에서 새 Public repository를 만듭니다.
2. 이 폴더의 `index.html`, `won.html`, `.nojekyll`을 저장소 최상단에 업로드합니다.
3. 저장소 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main`, Folder를 `/(root)`로 선택하고 Save합니다.
6. 잠시 뒤 `https://아이디.github.io/저장소이름/` 주소로 공개됩니다.

## 참고
`index.html`의 태원 이미지는 현재 외부 이미지 URL을 사용합니다.
`won.html`의 오늘의 코스는 방문자의 현재 날짜를 기준으로 계절별 후보군에서 자동 선택되며,
같은 날짜에는 새로고침해도 동일한 구성이 유지됩니다.
