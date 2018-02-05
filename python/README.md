# Python 입문(18.01.29 ~ )
> https://programmers.co.kr/learn/courses/2  링크에서 강의를 듣고 정리한 내용입니다.


> ##### 1. Python 설치
> + www.python.org 에서 다운로드 메뉴 - Python 3.5이상 선택
> + 설치 과정에서 "Add Python 3.5 to Path" 반드시 체크
> + 설치 확인
> 	+ 윈도우키 + R : powershell 실행
>	+ powershell 화면에서 pthon 입력, 오류 나지 않으면 설치 완료


> ##### 2. 에디터 설치
> + NotePad++ 다운로드
> + 메뉴-파일-다른 이름으로 저장-test.py 내문서에 저장
> + test.py에 테스트 코드 작성 print("Hello!")
> + powershell에서 저장한 코드 실행 방법 python test.py


> ##### 3. Hello World! 실습
> + powershell 명령
> 	+ ls: 현재 디렉토리(폴더)의 내용을 확인하는 명령
> 	+ cd: powershell에서 현재 디렉토리(폴더)를 바꾸는명령
> + print() 함수
> 	+ 괄호 안에 있는 내용을 화면에 출력하는 명령
> 	+ 화면에 표시하고 싶은 글은 따옴표(')로 묶어서 표현
> + 함수란?
> 	+ 파이썬이 특정한 기능을 수행하도록 하는 명령


> ##### 4. 변수 사용하기
> + 변수의 선언
> 	+ identity = '지구인'
>	+ 변수의 이름: 가장 왼쪽에 identity 부분
>	+ =(등호): 변수에 값을 저장하라는 의미
>	+ 값: '지구인'
> 	+ identity라는 변수에 '지구인'이라는 값을 저장하라는 명령
> + 변수의 사용
>	+ 변수 선언 후에, 변수의 이름을 이용하여 그 값을 불러올 수 있다.
>	+ 다음 두 코드는 같은 결과를 출력
>		+ print('안녕 나는', '지구인', '이야')
>		+ print('안녕 나는', identity, '이야')
>	+ 변수에 새로운 겂을 입력하는 방법을 선언과 동일하다.
>	+ identity = '외계인' 이라고 적으면, 이후부터 변수 identity의 값은 '외계인'이다.
