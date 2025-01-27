# ✏️ 과제 진행 요구 사항

---
 주의 사항
---
### 0. 예외 처리
- 잘못된 값(이름 6글자 이상, 횟수에 숫자 외 입력, 이름 같을 시 ) 입력 시 `IllegalArgumentException` 발생
- 예외 처리 시 해결 방안 출력

---
구현 사항
---
- 각 자동차에 대한 이름 입력받기
- 전진하는 차 출력 시 차 이름 같이 출력하기
- 차 이름은 쉼표 기준으로 5글자 까지 가능
- 횟수 입력 받기(게임 횟수)
- 그 횟수동안 전진 또는 멈추기 기능 
- 몇번의 이동 할 것인지 입력하기
- 전진 조건 -> 0~9 무작위 값 생성 후 4 이상일 경우에만
- 게임 종료 후 우승자 출력(1명 이상 가능, 여러명이면 쉼표로 구분)

---
구현 세부 사항
- 자동차의 이름, 전진 여부, 게임 횟수 입력 받아야 함
- 게임 횟수 만큼 반복하되 자동차의 위치는 계속 1이 아닌 갱신을 해줘야 함
- 자동차 객체의 속성 이용하기 
- 랜덤 값 통해 이동여부 결정
- 게임 횟수 충족 시, 우승자 결정

- 시도할 횟수동안 반복하며(while 루프), **조건 만족 시 이름 리스트 출력 후 반환**
- 실행 결과는 1번만 출력되게 하기
- 전진 또는 멈춤에 대한 값 받아서 이름 리스트 값에 대해 연결
- 출력 형식 `'이름 ' : ( - * ((이전 값) + 전진 또는 멈춤값) )`
  - 최종 우승자 리스트에 값 추가 후 2명 이상 시 쉼표 통해 구분



