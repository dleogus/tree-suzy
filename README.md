# 🎄 Tree Suzy

수지를 위한 인터랙티브 **3D ASCII 크리스마스트리** 웹페이지입니다.

## 데모

GitHub Pages 활성화 후 접속 주소:

**https://dleogus.github.io/tree-suzy/**

> 첫 배포 전 GitHub 저장소 **Settings → Pages → Build and deployment → Source**를 **GitHub Actions**로 선택해야 합니다. 그 뒤 **Actions**에서 `Deploy Tree Suzy to GitHub Pages` 워크플로를 실행하거나 master 브랜치에 커밋을 푸시하세요.

## 기능

- 3D 문자 파티클로 만든 크리스마스트리와 장식
- 자동 회전 / 드래그 및 터치 회전
- 눈 내리는 효과 on/off
- 조명 반짝임 강화
- PNG 이미지 다운로드
- 모바일/데스크톱 대응, 별도 서버 및 외부 라이브러리 불필요

## 로컬 실행

`index.html`을 브라우저에서 직접 열거나, 아래 명령을 실행합니다.

```bash
python3 -m http.server 3000
```

브라우저에서 http://localhost:3000 으로 접속합니다.

## 배포

`master` 브랜치에 푸시하면 GitHub Actions가 자동으로 정적 파일을 GitHub Pages에 배포합니다. 배포 주소는 `https://dleogus.github.io/tree-suzy/`입니다.

## 수정 방법

- 제목: `index.html`의 `<h1>` 요소
- 안내 문구: `subtitle`, `love` 요소
- 나무 밀도: `makeTree()` 함수의 반복 횟수
- 색상: `greens`, `lights` 배열

© 2026 Tree Suzy.
