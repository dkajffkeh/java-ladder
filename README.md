## 기능요구사항

- 사다리 게임에 참여하는 사람에 이름을 최대5글자까지 부여할 수 있다. 사다리를 출력할 때 사람 이름도 같이 출력한다.
- 사람 이름은 쉼표(,)를 기준으로 구분한다.
- 사람 이름을 5자 기준으로 출력하기 때문에 사다리 폭도 넓어져야 한다.
- 사다리 타기가 정상적으로 동작하려면 라인이 겹치지 않도록 해야 한다.
- |-----|-----| 모양과 같이 가로 라인이 겹치는 경우 어느 방향으로 이동할지 결정할 수 없다.

### 묵시적 요구사항
- 참여자가 없을 경우 게임을 진행할 수 없다 (익셉션 발생)
- 사다리 높이가 1 이하인 경우 게임을 진행할 수 없다(익셉션 발생)
- 사다리 맨 왼쪽부분은 항상 일자로 쭉 떨어져야한다.
