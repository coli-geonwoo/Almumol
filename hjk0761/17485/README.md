# Info
[진우의 달 여행 (Large)](https://boj.kr/17485)

- 난이도: 골드 5
- 분류: 다이나믹 프로그래밍

## 💡 풀이 방법 요약

DP 를 사용했습니다.

두 번 연속된 방향으로 이동하지 못하기 때문에, 각 좌표마다 직전에 어느 방향에서 왔는지에 따라 세 가지 값을 가지게 했습니다.

이에 따라 죄상단에서 온 경우 좌상단좌표 중 상단, 우상단에서 온 값의 최소값을 가져가도록 했고, 나머지 방향에서도 이와 같게 최소값을 계산하였습니다.

## 👀 실패 이유

문제를 제대로 읽지 않아 같은 방향으로 두 번 연속으로 움직일 수 있다는 조건을 빼먹었습니다.

어쩐지 골드 치고 쉽더라니,,,

## 🙂 마무리
