# PHP
***
> [생활코딩 PHP 강의](https://opentutorials.org/course/3130/19316) 를 듣고 스터디
### 강의요약
#### 설치 및 기본
+ PHP설치는 WAMP(google 검색)
+ HTML과 다른 동적 웹페이지
+ PHP 문법은 <?php ?> 안에서 구현
#### PHP 문법
+ echo 또는 print() 로 출력
+ 문장 끝날 때 세미콜론(;) !!
+ 산술연산자(+,-,*,/)
+ 비교연산자
+ 문자열 처리는 "" 또는 '', ""또는 ''를 문자 그대로 처리하려면 역슬래시이용
+ 문자열을 연결 시켜줄 때 . 사용
+ 변수는 $을 이용
+ 불리언
+ 조건문, 반복문
+ array('','','')
+ 주석 /* */
#### PHP의 URL 파라미터
+ URL:127.0.0.1/test.php?name=KimSeungJu&address=seoul 에서 $_GET['name'] , $_GET['address']를 통해 값을 가져올 수 있음

#### PHP 내장함수
+ strlen - 문자열의 길이를 계산하는 함수
+ nl2br - 문자열의 모든 줄바꿈 앞에 HTML 줄바꿈 태그를 삽입
+ file_get_contents (파일명) - 파일의 내용에 대한 표현식이 됨
+ file_put_contents (파일명, [변수 등]) - 파일에 출력
+ var_dump , print_r() - 입력값을 출력, 데이터 타입까지 출력해줌
+ isset - 값이 있냐 없냐에 따라 불리언 값 반환
+ array_push(변수, 값(''), 값(''))등 array function들 있음
+ scandir - 스캔하려는 디렉토리, 파일의 이름이 배열에 담겨 제공됨
+ count - 배열 원소 개수

#### PHP 함수
+ function 함수이름(parameter) {  // return 값}
+ 호출 : 함수이름(argument);
+ 하나의 함수는 하나의 기능을 갖게 하면 좋음

#### 기타
+ google 에서 특정 사이트에서 검색하고 싶을 때 site:php.net [주제] 검색
+ ./ 현재디렉토리, ../ 부모디렉토리

