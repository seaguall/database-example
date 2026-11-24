# dababase-example

1. mongoos를 이용하여 MongoDB로 데이터베이스에 데이터를 저장하고 조회하기
2. MySQL 데이터베이스에 데이터를 저장하고 조회하기

## mongoose

Elegant MongoDB object modeling for Node.js

* mongoose 홈페이지 : [Go](https://mongoosejs.com)
* read the docs : [See](https://mongoosejs.com/docs/guide.html)

git clone으로 GitHub 원격저장소 내용 복제하기

```sh
> git clone https://github.com/seaguall/database-example.git
> cd database-example
> git log --oneline
> git remote show origin
```

# 프로그램 실행

1. MongoDB 사용

* 서버 실행

```sh
> node app.js
```

* 웹브라우저에서 사용자 추가

```sh
http://localhost:3000/public/adduser.html
```

* 웹브라우저에서 로그인

```sh
http://localhost:3000/public/login.html
```

2. MySQL 사용

```sh
> node app2.js
```
