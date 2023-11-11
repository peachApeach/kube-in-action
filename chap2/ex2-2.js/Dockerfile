# 이미지 생성의 기반이 되는 기본 이미지
FROM node:7

# 로컬 티렉토리의 app.js 파일을 이미지의 루트 디렉토리에 동일한 이름으로 추가
ADD app.js /app.js

# 이미지를 실행했을 때 수행해야할 명령어
# > node app.js 실행
ENTRYPOINT [ "node", "app.js" ]