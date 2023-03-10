> # 🚀 기능 목록
>
> <br>

<br>

> ### 1. 값 생성 단계

- [V] 금액 입력받기

  - ### 🚨 예외 처리
    - [V] 입력 받은 금액이 숫자가 아니라면 throw
    - [V] 입력 받은 금액이 1000원 단위가 아니라면 throw
    - [V] 입력 받은 것이 없다면 throw
    - [V] 입력 받은 금액이 양수가 아니라면 throw

- [V] 내가 구매한 로또 개수 출력
- [V] 만든 나의 로또 번호 리스트 출력

- [V] 만들 번호 배열 갯수 n 구하기 ( 금액 / 1000 )

- [V] 랜덤 번호 6개가 담긴 배열 생성하기

  - [V] 중복되지 않게 생성하기
  - [V] 오름 차순으로 정렬하기
  - [V] 한 배열에 담기

- [V] 윗 단계로써 구입한 로또번호 n개 배열 생성

- [V] 당첨번호 만들기

  - ### 🚨 예외 처리

    - [V] 입력 받은 당첨 번호가 여섯 자리가 아니라면 throw
    - [V] 입력 받은 당첨 번호에 전부 숫자로 구성 되어있지 않다면 throw
    - [V] 입력 받은 당첨 번호 각각의 범위가 1미만 45초과 라면 throw
    - [V] 입력 받은 당첨 번호에서 중복된 수가 있다면 throw

- [V] 보너스 입력 받기

  - ### 🚨 예외 처리

    - [V] 입력 받은 보너스 번호가 한자리가 아니라면 throw
    - [V] 입력 받은 보너스 번호가 숫자가 아니라면 throw
    - [V] 입력 받은 보너스 번호가 당첨 번호중 하나와 중복된다면 throw

  <br>

> ### 2. 결과 도출 단계

<br>

- [V] 당첨 통계 도출 하기

  - [V] 두 숫자 배열의 일치 개수 구하는 로직 작성

  - [V] 1등, 3등, 4등, 5등 당첨 배열 개수 구하기
  - [V] 2등 (5개 번호 + 보너스 번호 일치) 배열 갯수 구하기
  - [V] 1~5등에 따른 결과 출력하기
  - [V] 총 수익률 계산하기
  - [V] 총 수익률 결과 출력하기
  - [V] 게임 종료
