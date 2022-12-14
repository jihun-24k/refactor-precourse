## ✍️ 프리코스 2주차 소감문
깃허브의 위키를 활용해서 프리코스를 진행하면서 정리한 부분과 느낀점을 기술했다.  
[프리코스 2주차 위키](https://github.com/jihun-24k/java-baseball/wiki)

## 🛠 요구사항 분석

요구사항 분석은 기능별로 분석한 뒤 그에따른 테스트 케이스를 하위로 분리해 분석한다.

### 기능 분석

**게임 시작**

- [x] `숫자 야구 게임을 시작합니다.`라는 문구를 출력

**사용자는 서로 다른 세자리 숫자를 입력해야한다.**

- [x] 서로 다른 세자리 숫자가 맞다면 게임 진행
- [x] `숫자를 입력해주세요 : `라는 문구를 출력
- [x] 입력값이 1부터 9까지 숫자가 아니라면 에러 발생
- [x] 입력값이 세자리가 아니라면 에러 발생
- [x] 입력값이 중복된 숫자가 존재한다면 에러 발생

**게임 진행**

- [x] 위치와 숫자가 같을 때 `스트라이크`를 출력
- [x] 위치는 다르고 숫자만 맞았을 때 `볼`을 출력
- [x] 볼과 스트라이크가 혼합되어 있을 때 `N볼 N스트라이크` 출력
- [x] 하나도 맞추지 못했을 때 `낫싱`을 출력
- [x] 3개의 숫자를 모두 맞힐 경우 `3개의 숫자를 모두 맞히셨습니다! 게임종료`를 출력하며 게임종료

**게임 종료**

- [x] 게임이 종료되면 `게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.`를 출력
- [x] 1을 입력하면 다시 게임을 재시작
- [x] 2를 입력하면 프로그램 종료
- [x] 1,2 이외의 값을 입력하면 에러 발생
