> # 🚀 기능 목록

<br><br>

> ###

- [V] 게임 시작 문구를 출력한다.
- [V] 다리 길이를 입력 받는다.

- ### 🚨 예외 처리

  - [V] 사용자가 입력이 숫자로만 이루어지게 한다. 아닐시 throw
  - [V] 다리 길이는 3이상 20이하로 제한한다. 아닌 숫자가 입력시 throw
  - [V] 맞지 않는 입력시 throw후 해당 위치에서 재시작

- [V] 입력받은 길이의 경로를 넣을 다리를 생성한다.
- [V] 생성한 다리에서 이동 가능한 배열 경로를 만든다.
  - [V] 이동 가능한 경로는 미션 유틸을 사용한다. 단 BridgeRandomGenerator를 수정해선 안된다.
  - [V] 무작위 값이 0이라면 아래 칸, 1이라면 위 칸을 선택한다.
- [V] 시도 횟수를 0으로 초기화 한다.
- [V] 이동 할 칸을 입력 받는다.
- ### 🚨 예외 처리

  - [V] U와 D가 아닐시 throw
  - [V] 맞지 않는 입력시 throw후 해당 위치에서 재시작

- [V] 입력한 이동 방향의 길이 맞는 길인지 아닌지 판단한다.

  - [V] 윗칸이고 맞는 길이라면 윗 칸에는 O를, 아래 칸에는 공백을 넣는다.
  - [V] 아래칸이고 맞는 길이라면 아래 칸에는 O를, 윗 칸에는 공백을 넣는다.

  - [V] 그려넣은 그림을 출력한다.

> ### 틀린 길일때.

- [V] 틀린 길이라면 게임을 다시 시도할지 여부를 묻는다.

  - ### 🚨 예외 처리
  - [V] R과 Q가 아닐시 throw
  - [V] 맞지 않는 입력시 throw후 해당 위치에서 재시작
    > #### 재시작

- [V] 시도 횟수를 한번 증가한다.
- [V] 재시작 한다면, 현재 위치와 현재 맵을 초기화 한다. (유효 경로는 그대로)
  > #### 종료
- [V] Q를 입력 받았다면, 틀린 길을 선택한 최종 결과 맵을 출력한다.
- [V] 게임 성공 여부를 출력한다.
- [V] 총 시도한 횟수를 출력한다.
- [V] 게임을 종료한다.

> ### 맞는 길 일때.

- [V] 맞는 길이 라면 다음 입력을 받아 이후 과정을 반복하게 한다.

- [V] 입력한 다리 길이 만큼 게임이 진행되었다면 게임을 중지한다.
- [V] 전부 다 맞은 길이 되었다면 최종 결과 표를 도출한다.
- [V] 전부 다 맞은 길이 되었다면 게임 성공 여부를 도출한다.
- [V] 전부 다 맞은 길이 되었다면 총 시도 횟수를 도출한다.
- [V] 게임을 종료한다.