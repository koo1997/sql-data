# -데이터 유형

간단 분류

상세

NUMBER(n, m)

숫자

n : 저장될 숫자의 최대 전체 자리수. 1≤n≤38

m : 소숫점 이하 자리수

VARCHAR2(n)

문자

가변 길이 문자열 저장. 저장되는 문자열의 길이가 n byte 범위 내에서 제한이 없음

n ≤ 4000 (byte)

DATE

날짜

날짜를 저장

CHAR(n)

문자

고정 길이 문자열 저장.

n ≤2000 (byte)

LONG

문자

가변 길이의 아주 긴 문자열을 저장.

2GB까지 저장 가능 (대용량)

CLOB

문자

가변 길이의 아주 긴 문자열을 저장

4GB까지 저장 가능

BLOB

2진수

가변 길이, 최대 4GB까지 저장(대용량)

RAW(n)

RAW

RAW데이터를 2000byte까지 저장

LONG RAW(n)

RAW

RAW데이터를 2GB까지 저장(대용량)

BFILE

외부 파일

외부에 저장된 대용량 데이터를 4GB까지 저장

​
[출처] [오라클/SQL] 데이터 타입 : 종류와 설명, 예시 (CHAR, VARCHAR2, NUMBER, DATE, CLOB, BLOG, RAW, LONG RAW, BFILE 등)|작성자 리제
