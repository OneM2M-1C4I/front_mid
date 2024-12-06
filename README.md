# TinyIot 구동
tinyIot를 미리 설치합니다.

## CORS 에러 해결
tinyIot config에서 CORS를 허용해야함.

## 실행
pm2 start tinyIoT/source/server/server

## 실행중인지 확인
pm2 list

## 모니터링
pm2 monit {번호}

## 종료
pm2 stop {이름}

# 서버 구동
## 실행
npm install
node app.js