Row-oriented Database
=====================
## 목차
1. [비교](#비교)
2. [파일 시스템](#파일-시스템)
3. [참고문헌](#참고문헌)

## 비교
> Oracle Database is a row format database.

Row oriented | Column oriented
------------ | ---------------
읽기/쓰기 빠름 | 읽기/쓰기 (행 지향에 비해) 느림
OLTP(운영계) | OLAP(분석계)
조회 느림(불필요한 데이터 조회) | 조회 빠름

* The major difference in both the datastores lies in the way they physically store the data on the disk.
	* 행 지향 DB는 동일한 `블록`에 전체 행을 저장하려고 시도하지만  
	* 컬럼 지향 DB는 동일한 블록에 후속 열의 값을 저장한다

##### [목차로 이동](#목차)

## 파일 시스템


##### [목차로 이동](#목차)

## 참고문헌
+ [DBMS|Row oriented vs. column oriented data stores](https://www.geeksforgeeks.org/dbms-row-oriented-vs-column-oriented-data-stores/)
+ [Rowise vs. Columnar Database? Theory and in Practice](https://medium.com/@mangatmodi/rowise-vs-columnar-database-theory-and-in-practice-53f54c8f6505)
+ [Oracle|Question](https://asktom.oracle.com/pls/asktom/f?p=100:11:0::::P11_QUESTION_ID:9530427800346499360)
+ [Wiki](https://en.wikipedia.org/wiki/Column-oriented_DBMS)

##### [목차로 이동](#목차)