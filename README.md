# spring boot Rest API

## 概要
- Spring Bootを使用してREST API(CRUD)基本的な扱い
- 確認方法はPostmanを使用しリクエストの結果チェック

## API URL
- method get
- https://localhost/api/employees select all 
- https://localhost/api/employees/{id} select 
- method post
- https://localhost/api/employees create
- https://localhost/api/employees/{id} update
- method delete
- https://localhost/api/employees/{id} delete

## 使用DB
- mariadb

## entity
- Long id;
- String firstName
- String lastName
- String email