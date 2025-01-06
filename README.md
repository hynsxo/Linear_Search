# Linear_Search


**linearsearch.cpp파일**
- 각 x값 마다 Y축 Min값, Max값 범위 range탐색하여 점을 잇는 최단거리 지점을 찾아내어 선형으로 구현하는 알고리즘, 다익스트라 알고리즘 활용함
+ 시뮬레이션을 위한 MATLAB코드 첨부함

---

**linearsearch_top10th.cpp파일**

- 다음 y 범위 값 생성
- 현재 y 값을 기준으로 다음 y 범위 내 가능한 모든 y 값을 생성
- 거리 계산 및 정렬
- 생성된 y 값들과 현재 y 값 사이의 거리를 계산하고, 이 거리를 기준으로 정렬
- 상위 10% 추출: 정렬된 거리에서 상위 10%를 선택
- 중앙값과 가장 가까운 값 선택 = 상위 10%에서 y 범위의 중앙값에 가장 가까운 y 값을 선택
- 다익스트라 경로 계산, 선택된 y 값을 이용해 다익스트라 알고리즘을 통해 최적 경로를 계산
> y 범위 내 값들의 끝 값이 되지 않기 위함
