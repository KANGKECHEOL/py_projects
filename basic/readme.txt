1. 파이썬 기본
 - 단일데이터(단일 타입)
  > 수치형 : 정수 , 부동소수 , 진법 , ...
  > 문자열(연속이지만, 이쪽으로도 분류한다)] 
            :표현, 사용이유, 인덱싱, 슬라이싱, 포멧팅,
             유니버셜함수(주요 멤버함수) -> 가장 중요하기 때문에
             전처리과정을 통한 정규식 체크(데이터 수집 이후 등장)
  > 블린형: -> 조건문 연결, 결론:False 상황만 기억한다 (나머지는 다 참)
               False인 것 = 0 , "" ,[] , {} , () , None 다 False

 - 연속데이터(시퀀스 타입)
  > 리스트   : [ ] -> js의 배열과 동일, 순서가 존재, 값중복 ok,
                      인덱스는 정방향/역방향(-1,-2,...) 존재
  > 딕셔너리 : { } -> js의 객체와 동일, 순서x , {키:값}
                      키는 중복되면 x , 값은 중복 ok
  > 튜플     : ( ) -> 수정불가, 값을 묶는다!!(관계없는 데이터들을 묶는다)
                      순서ok, 정방향/역방향(확인)
  > 집합     : set() -> 목적은 중복제거이고 제거 후 리스트로 변환해서 처리
                        교집합, 합집합, 차집합 => 느려서 => pandas에서 해결

 - 반복문, 조건문, 제어문 , 등등 => 코드블럭 등장(;)
  > if , while , for , ... , break, continue
 => 절차적 프로그램 (동기식) (노드는 비동기식 프로그램)
 ----------------------------------------------------------------------------
 - 함수
 - 함수종류
    => 내장함수, 외장함수, 사용자 정의함수,
       람다표현(데이터 분석시 등장) -> 처리속도나 메모리 점유가 더 좋다.
 => 함수 지향적 프로그램(동기식)
  -> 엔트리 포인트를 구성
 ------------------------------------------------------------------------------
 - 클래스
  > 상속, 멤버, 생성자, 객체생성
 - 모듈화 + 패키지
  > 모듈 만들기, 테스트 코드 배치, 모듈 가져오기, 패키지 사용
 - 예외처리
  > 풀코드 형태 확인
 => 객체 지향적 프로그램
   -> GUI 모드 구성, 파이썬 웹 구성시 모듈 부분으로 사용
 --------------------------------------------------------------------------------
