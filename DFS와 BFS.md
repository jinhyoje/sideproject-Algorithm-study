- ## DFS와 BFS는 대표적인 그래프 탐색 알고리즘이다.

- ### DFS : 루트 노드 혹은 임의 노드에서 다음 노드로 넘어가기 전에, 해당 노드를 모두 탐색하는 방법
  -  보통 스택 or 재귀함수를 통해 구현한다.
  -  그래프의 깊이(depth)가 깊을 수록 빠름
  -  모든 경로를 방문해야 할 경우 사용에 적합
  -  예 : 경로의 특징을 저장해야 하는 경우, 미로 문제
  
- ### BFS : 루트 노드 또는 임의 노드에서 인접한 노드부터 먼저 탐색하는 방법
  - 큐를 통해 구현한다.
  - 찾는 노드가 인접할 때 유리
  - 최소 비용(즉, 모든 곳을 탐색하는 것보다 최소 비용이 우선일 때)에 적합
  - 예 : 길 찾기, 소셜 네트워크에서 멀리 떨어진 사람 찾기

## 참고자료
https://devraphy.tistory.com/629
