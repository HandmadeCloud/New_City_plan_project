# [도시 물류 혁신 계획 프로젝트](https://handmadecoding.tistory.com/56)
## 기획 배경
코로나 시기를 겪으며 물류 시스템은 크게 발달했다.
당일 배송, 새벽 배송 등 운송 시스템을 최적화 시키고 운송 시간을 단축 시키기 위해 노력하고 있다.
이러한 과정에 있어 운송 시스템을 최적화 시키기 위해서 미래 이루어질 수 있는 도시 계획을 상상해보며
현실성 운송 아이디어를 보고, 이에 대한 서울 지역별 수요를 소개하고자 한다.

## 문제
현재 대부분의 택배 물류는 도로 운송을 통해 이루어진다.
하지만 도로 운송에는 안전문제, 비용과 시간 문제, 노동자의 피로 문제 등이 있다.
반면 철도 운송은 현재 원자재 운송만 이루어질 뿐, 유럽에 비해 수요와 공급이 모두 적은 편이다.
또한, 지하철의 경우에도 대부분 사람을 대상으로 하는 시스템만 갖추어져 있다.

## 주제
이러한 점에 비추어 볼때, 
도로 운송과 철도 운송 시스템의 장점을 결합한 새로운 운송 시스템을 제안한다.
이 프로젝트에서는 서울 법정동별 택배 수요 예측과 임의로 결정한 도시계획 비용을 계산하고자 한다.

## 아이디어
1. 지하철 역을 운송 통로 거점으로 이용한다.
지하철 유휴시간(배차 간격이 큰 시간대, 새벽 시간)을 통해 물류를 실어 운송한다.
2. 지하철 역과 수요에 맞춰 설정할 **지역 물류 거점**을 연결하는 지하 철로를 개통해 물류를 운송한다.
3. 지하철 구간마다 유휴 시간을 활용해 지역 물류 거점으로 운송한다 (자율주행)
4. 지역 물류 거점간 이동은 도로로 운송한다.

## 데이터 분석 스택
데이터 전처리, K-MEANS 클러스터링, MIN-MAX scaling, 시각화

### 사용 기술 스택
- Python 3.8 ver
- Jupyter
- Rapid miner
- matplotlib
- numpy
- pandas
- sklearn (kmeans clustring)
- seaboarn

