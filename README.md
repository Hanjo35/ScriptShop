[프로그래머스 데브코스 사전 제공강의 백엔드/프론트엔드]

쇼핑몰 만들기

# ScriptShop

ScriptShop은 간단한 주문 및 관리 시스템을 제공하는 Node.js 기반 웹 애플리케이션입니다.

## 기능
- 상품 주문 및 관리
- 주문 내역 조회
- 간단한 데이터베이스 연동

## 설치 및 실행 방법

### 1. 프로젝트 클론
```sh
git clone https://github.com/Hanjo35/ScriptShop.git
cd ScriptShop
```

### 2. 패키지 설치
```sh
npm install
```

### 3. 서버 실행
```sh
node server.js
```

서버가 실행된 후 브라우저에서 `http://localhost:3000`으로 접속하면 사용할 수 있습니다.

## 주요 파일 및 폴더 구조
```
ScriptShop/
├── server.js          # 메인 서버 파일
├── router.js          # 라우터 설정
├── requestHandler.js  # 요청 처리 핸들러
├── index.js           # 엔트리 포인트
├── database/          # 데이터베이스 관련 파일
├── img/               # 이미지 파일 저장 폴더
├── main.html          # 메인 페이지
├── orderlist.html     # 주문 목록 페이지
├── package.json       # 프로젝트 설정 및 의존성 정보
└── README.md          # 프로젝트 설명 파일
```

## 기여 방법
1. 이 저장소를 포크합니다.
2. 새로운 브랜치를 생성합니다: `git checkout -b feature-branch`
3. 변경 사항을 커밋합니다: `git commit -m 'Add new feature'`
4. 브랜치에 푸시합니다: `git push origin feature-branch`
5. Pull Request를 생성합니다.

## 라이선스
이 프로젝트는 MIT 라이선스 하에 배포됩니다.


# 느낀점
1. 강의 주차별로 issues 를 나눠놓을 걸 후회되는 점이 있다.
2. 간단하게나마 백엔드와 프론트엔드 양쪽을 둘 다 맛보는 기회였는데, 전체적인 구조를 아는 데에는 도움이 되었던 것 같다. 
