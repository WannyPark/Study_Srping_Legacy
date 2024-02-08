1. node.js 다운로드
2. sts 3.9.14 버전 다운로드
3. npm 을 통해서 react 프로젝트 생성
4. db 안에 있는 텍스트 문서 복사해서 시퀀스 생성, erd를 사용하여 테이블 생성
5. 생성된 react 프로젝트 폴더에서 src 폴더안에 css, components 폴더와 App.js, App.css, index.js, setupProxy.js 를 넣어준다. 겹치는 파일은 덮어쓰기 (setupProxy.js 안에 url spring 서버의 포트번호로 변경!!)
6. sts 를 실행하여 spring-legacy 를 import 해준다.
7. oracle driver 라이브러리가 없으면 프로젝트 라이브러리에 따로 추가해줘야함.
8. servlet-context 에 데이터베이스 유저 아이디와 비밀번호 변경
9. root-context 에 구글 계정 정보 변경
10. controller 에 이미지 업로드 로직에서 저장 주소 변경 (react 프로젝트 폴더에 public/images)
11. test !
