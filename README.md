# typescript-node-framework
- 타입스크립트로 노드를 돌리기 위한 기본 프레임워크 입니다.

# 폴더
- src -> *.ts 파일
- dist -> *.ts 파일이 컴파일 되어서 *.js 로 변환된 후 들어가게 됩니다.

# package.json scripts
- start -> nodemon ./dist/app.js
- build -> tsc -w (타입스크립트 변화를 실시간으로 추적하여 컴파일 합니다.) 
- start 명령어가 되지 않을 시에는 npm install -g nodemon 
- build 명령어가 되지 않을 시에는 npm install -g typescript

# .gitignore
- .gitignore 에 /node_modules 만 추가해 놓았습니다.

# 기타사항
- tsconfig.json 은 타입스크립트 공식 홈에서 참고함.