# Real MySQL 8.0 예제 도커 컴포즈
### 실행방법
```bash
$ docker-compose up -d
```

`employees.zip` 압축해제 및 MySQL 접속 후 아래명령 실행
```bash
mysql> USE employees
mysql> Source employees.sqml
```