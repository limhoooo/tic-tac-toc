### React-basic


### husky 로 git hook 사용
허스키 설치 <br>
만약 github desktop 에서 커밋 에러시 node 버전확인 ( 16v 안됨 2023.01.06)
```
npm i husky -D
```
프로젝트에 허스키 설치
```
npx husky install
```
pre-commit 시 npx lint-staged 라는 명령어 실행 (lint-staged 는 package.json 에 작성)
```
npx husky add .husky/pre-commit "npx lint-staged" <br>
```
lint-staged
```
npm i lint-staged -D
```
쿼리스트링 라이브러리 설치
```
npm i query-string
```