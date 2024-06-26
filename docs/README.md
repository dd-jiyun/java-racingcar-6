## 구현할 기능 목록

- [x] 자동차 이름
  - [x] 자동차 이름을 입력받기 위한 메시지 출력하기
  - [x] 사용자에게 입력받기
- [x] 시도 회수
  - [x] 시도할 회수를 입력받기 위한 메시지 출력하기
  - [x] 사용자에게 입력받기
- [x] 자동차 경주
  - [x] 라운드 별 경주 과정 출력하기
  - [x] 최종 우승자 출력하기

## 사용자 입력 규칙

- 자동차 이름은 `5자 이하`여야 한다.
- 자동차 이름은 `,(쉼표)`로 구분해야 한다.
- 시도할 회수는 `음이 아닌 정수`여야 한다.

## 우리가 생각한 필요한 아이들

### 자동차

- 전진하는 역할을 수행합니다.
- 전진 회수(현재 위치)를 알고 있습니다.

### 자동차들

- 자동차들을 알고 있고, 자동차들에게 전진 명령을 하는 역할을 수행합니다.

### 레이싱

- 게임 규칙에 따라 라운드를 진행하는 역할을 수행합니다.

### 전진 전략

- 자동차가 전진할지 말지를 결정하는 역할을 수행합니다.  
(게임 규칙에 따라 변경될 수 있습니다. 예를 들어 자동차의 스펙 또는 아이템에 의해 전진 여부를 결정하는 규칙이 추가된다면 쉽게 대응할 수 있을 것 같습니다.)

### 심판

- 우승자를 판단하는 역할을 수행합니다.

### 입력 인터페이스

- 사용자에게 입력받기 위해 도움을 주는 역할을 수행합니다.

### 출력 인터페이스

- 사용자에게 결과를 알려주는 역할을 수행합니다.