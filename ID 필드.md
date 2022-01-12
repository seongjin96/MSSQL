> ID 필드

* 자동 생성 시퀀스 기능과 유사

* 자동으로 일련번호가 매겨진다.

  ```MSSQL
  -- 1부터 1씩 증가하는 ID 필드 생성
  CREATE TABLE tSaleId
  (
  	saleno INT IDENTITY PRIMARY KEY,
    	customer VARCHAR(20),
    	product	VARCHAR(30)
  );
  ```
