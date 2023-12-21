# setting local mariadb

## 개요
- local 환경에 개발용 mariadb 를 구성하기 위한 docker-compose 정의

## 사용 방법
- docker & docker-compose 설치
- cd 를 통해 해당 폴더로 이동
- 명령어
  - 실행 : <code>$ docker-compose up -d</code>
  - 종료 : <code>$ docker-compose down</code>

## 주요 설정 내용
- version : 10.4
- port : 3306
- database root account : root / abcde12#
- database name : capstone
- database service account : capstone / abcde12#
- char-set : utf8mb4 / utf8mb4_unicode_ci
- docker restart : unless-stopped # 수동 종료 전까지 자동 시작
- 