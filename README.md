본 프로젝트는 한남대학교 문헌정보학과 정보처리연습 과목의 2024년도 최종 프로젝트 입니다
마이크로소프트 엑세스 형식의 데이터베이스 파일(.accdb)과 유저 정보, 책 정보를 담고 있는 user.txt / book.txt가 필요합니다.


1. 

도서와 이용자 클래스를 파일로 저장하시오.(과제3)
도서는 book.py, 이용자는 user.py로 저장하시오.
클래스 파일은 class 키워드를 사용하시오.
Main.py에서 각 클래스(Book, User) 모듈을 import하시오.


2.

도서 목록 5개를 파일(book.txt)에 입력하고 도서입력프로그램(register_book.py)을 작성하여 도서 데이터 파일(book.txt)부터 데이터베이스에 저장하시오.
사용할 파이썬 주제: 사용자 입력, 변수, 할당연산자, 파일열기, 파일 저장(write)
예) 서명 저자 출판사 출판년도 대분류 유형

B. 데이터베이스에서 SQL의 “create table”문을 이용하여 Book table을 생성

C. 도서는 “Insert into  set”을 이용하시오.

2-1.
회원 목록 5개를 파일(user.txt)에 입력하고 회원 입력프로그램(register_user.py)을 작성하여 회원 데이터 파일(user.txt)부터 데이터베이스에 저장하시오.
사용할 파이썬 주제: 사용자 입력, 변수, 할당연산자, 파일열기, 파일 저장(write)
예) 이름 성별 출생년도 주소 관심주제

B. 데이터베이스에서 SQL의 “create table”문을 이용하여 User table을 생성

C. 회원정보는 “Insert into   values”을 이용하시오.


3.

이용자와 도서에 대하여 데이터베이스 검색프로그램을 작성하시오
예) 검색할 데이터? 1.이용자 2.도서

1번선택의 경우, 검색할 항목은? 1. 이름, 2. 성별, 3. 나이



4.

이용자와 도서에 대하여 대출반납 데이터를 파일(use.txt) 로 저장하시오.
예) 대출할 이용자는? 회원등록된 경우 이용자 파일에서 찾아오고 그렇지 않으면 회원등록을 해야 함.

 대출할 도서는? 소장한 자료인지 아니면 없는 자료인지 검색을 통해 확인하고, 없을 때는 구입할 것인지 아니면 대출을 안 할 것인지?

대출/반납 데이터를 파일을 저장합니다.

저장되는 정보: 대출일자, 반납일자, 대출자, 대출도서

5.

대출 반납(use.txt)에 대하여 검색을 수행하시오.

입력: 도서명? 대출 내역을 출력할 수 있는 프로그램

         회원명? 대출 내역을 출력할 수 있는 프로그램


