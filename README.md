# 학교 시간표

학교 시간표를 조회하고, 수업 교체·보강을 찾아 등록하고, 시간표를 자동으로 편성하는 웹앱입니다.

## 깃허브에 올리기

1. github.com에서 새 저장소를 만듭니다(Public).
2. 이 폴더의 파일을 모두 저장소에 올립니다(Add file → Upload files).
3. 저장소 Settings → Pages → Branch를 `main`으로 고르고 Save를 누릅니다.
4. 1~2분 뒤 `https://<아이디>.github.io/<저장소 이름>/` 주소로 접속합니다.
5. 휴대폰에서는 브라우저 메뉴의 "홈 화면에 추가"로 앱처럼 설치합니다.

## 시간표를 모두에게 반영하기

앱에서 고친 내용은 고친 기기에만 저장됩니다. 모두에게 보이게 하려면
앱의 데이터 메뉴에서 `data.json`을 내려받아 저장소의 `data.json`을 바꿔 올립니다.

## 파일

- `index.html` 앱 본체
- `data.json` 게시된 시간표와 교체·보강 내역
- `manifest.webmanifest`, `sw.js`, `icon-*.png` 휴대폰 설치용
