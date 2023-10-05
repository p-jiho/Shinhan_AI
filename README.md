# Shinhan_AI(팀장)
- 금융 생활을 위한 AI 서비스 아이디어 공모전
- https://dacon.io/competitions/official/236088/overview/description
- 팀명 : 퍼셉트립, 4인
- 주제 : 해외여행객, 해외 주식 투자자들을 위한 환전 타이밍 제공
- 1. 날짜 추천 서비스 : 국가를 지정하면 3개월동안 환율을 예측해 환율이 가장 낮은 날을 추천
  2. 국가 추천 서비스 : 날짜를 지정하면 오늘 대비 지정 날짜에 가장 환율이 낮은 나라를 추천
- 기대효과 : 환율은 많은 사람의 관심사이기 때문에 환율을 예측해 정보를 제공해주는 것은 충분히 흥미를 끌만한 주제라고 생각함, 환전 타이밍 추천 서비스를 웹 및 앱으로 제공함으로써 기존 신한은행의 환전 관련 서비스를 홍보, 연계할 수 있음


##### 공모전 참여
- 팀장 : 날짜 조율 및 회의록 작성, 데이터 정리, 모든 코드 통합, 정리 및 제출
- 경상수지, 무역수지, 실업률, 소비자 신뢰지수, 금값, 원유, 소비자 물가지수 등 수출/수입 관련 산업, 관광 산업, 금융 상품 데이터
- 전처리가 되지 않은 데이터 -> 정형화, 보간, 전처리, 이상치 제거
- 시계열분석, KNN과 같은 머신러닝 기법 적용 -> 최종적으로 딥러닝 모형만 사용하여 실질적으로 사용되지 않음
- 최종 서비스 제공 코드 생성 및 전반적인 코드 마무리 수정
- 팀원 코드 피드백 및 수정사항 건의


##### 코드
- data_organize : 데이터 정형화
- Interpolate : 결측치 제거, 데이터 정형화
- Outlier_remove : 이상치 제거 및 보간, 데이터 특징 분석
- 시계열 분석 및 KNN은 완벽하지 못한 코드로 업로드하지 않음
- Total code는 다른 팀원들의 코드도 포함되어있으므로 업로드하지 않음, 전반적인 코드 수정 부분과 최종 서비스 제공 코드, 함수 생성 등은 Total code에 포함되어있음
  (Total code는 https://dacon.io/competitions/official/236088/codeshare/8187?page=1&dtype=random 이곳에서 볼 수 있음)
