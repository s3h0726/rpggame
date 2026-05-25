# 유물 핵 키우기 RPG

GitHub Pages에서 바로 실행할 수 있는 정적 웹 게임입니다.

## 파일 구성

- `index.html` : 게임 화면 구조
- `style.css` : 디자인과 모바일 레이아웃
- `game.js` : 게임 로직
- `.nojekyll` : GitHub Pages에서 Jekyll 처리를 끄는 파일

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 파일들을 저장소 최상위에 업로드합니다.
3. 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, Folder는 `/root`를 선택하고 저장합니다.
6. 잠시 뒤 `https://사용자명.github.io/저장소명/` 주소로 접속합니다.

## 모바일 실행

휴대폰 브라우저에서도 실행할 수 있습니다. GitHub Pages 주소를 모바일 브라우저에서 열면 됩니다.

## 주의

저장 데이터는 브라우저의 `localStorage`에 저장됩니다. 브라우저 데이터를 삭제하면 게임 진행도도 초기화될 수 있습니다.
