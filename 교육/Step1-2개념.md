## 개발자 교육 과정1 Step 1-2
### 동영상 시청 후 퀴즈 제출

- 20강 데이터 준비 및 모델링

|질문|답|
|---|---|
|1. 머신러닝, 딥러닝 학습에 바로 적용할 수 있는 공개데이터 저장소의 사례 세 가지 이상 제시?|Visualdata, Pytorch Datasets, TensorFlow Datasets, huggingface Datasets, AIHub|
|2. 데이터 어노테이션 방법 중 크라우드 소싱 방법의 장점과 단점은?|싸고 확장성이 좋지만 품질 검수 비용이 클 수 있다|
|3. 반복 학습 과정 중 성능 지표의 변화를 살표보기 위해 머신러닝 모델링 과정에서 생성하는 차트는?|학습 곡선|
|4. 학습이 완료된 모델에, 학습에 적용하지 않은 입력을 넣어 출력값을 확인하는 단계는?|추론|
|5. 모델 학습과정에서 과적합(overfitting) 발생시 학습데이터와 테스트 데이터의 성능 지표 경향은?|학습이 진행될수록 학습 데이터에서는 높은 성능을 보이고, 테스트 데이터에서는 낮은 성능을 보이는 경향이 있다.|

- 20강 AI(인공지능) 프로젝트 사례

|질문|답|
|---|---|
|1. 카메라를 이용한 차량번호 인식 시스템을 머신러닝을 적용하여 구현하고자 한다. 인식의 3단계 설정을 제시해보시오.|자동차의 경계 상자 인식 -> 번호판의 경계 상자 인식 -> 번호판 인식|
|2. 데이터 선순환 구조의 3단계를 설명하시오.|더 많은 데이터, 더 나은 모델, 더 많은 사용자|
|3. 차종 인식시 번호판을 인식하여 DB에서 조회하는 대신, 사진에서 바로 판별하고자 한다. 지도학습 기반 입력과 출력 설정은 어떻게 해야 하는가?|입력 : 자동차 사진 출력: 자동차, 번호판의 경계 상자(bounding box)|
|4. 번호판 인식의 어려움 중 조명 관련 환경적 요인은 어떤 것이 있는가?|야간/일출/일몰, 역광, 그림자, 반사광, 눈/비/안개|
|5. 객체 탐지 문제의 경우, 탐지한 객체의 영역을 표현하는 방식은?|경계 상자(bounding box)|
