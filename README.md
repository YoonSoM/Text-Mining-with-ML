# text_mining_ML

### Objectives(목적)
- 국민 청원 데이터 분석(청원 분야별 개수, EDA 자동화, 마스크 이미지에서 워드 클라우드 생성)
- 카카오_2020년도 3,4분기 실적분석(영업이익, 영업비용 변화, 고용분석과 매출액 비교 당기 순이익 계산)
- 문서 요약 및 키워드 추출(많은 양의 데이터 처리, 실시간 분섣 가능, 문서 내 키워드나 문장을 추출해서 요약, 문서 내 포함된 단어 외에 새로운 단어나 문장을 사용해서 요약)
- 서울시 구별 범죄 분석(법죄 발생 횟수와 연도별 발생 횟수, 검거율)


### Models(라이브러리) and Data
- BeautifulSoup
- pandas에서 plotly로 그래프를 제작하기 위해 chart_studio 사용
- EDA
- kakao 3,4분기 실적발표
- Text rank를 활용한 키워드 추출
- 서울시 5대 범죄 발생현황 통계




### Envs and Requirements
- Colab
- BeautifulSoup, Pandas, Matplotlib, Seaborn, networkx, gensim, cufflinks


### Progress
- 데이터 분석 및 시각화
- 데이터 정제
- 텍스트 마이닝
- 웹 크롤링 
- 불용어 사전 구축
- TF-IDF 워드 클라우드

### Retrospective
- 웹 크롤링과 ML 기초를 바탕으로 진행한 프로젝트
- BeautifulSoup을 사용해 데이터를 크롤링하는 코드를 작성
- 웹 크롤링을 기법으로 단기간에 방대한 데이터 확보가 가능함을 알게 되었고, 재사용 가능한 코드 작성의 중요성에 대해 배울 수 있었음
- 정규표현식을 활용해 불필요한 문자 및 패턴이 있는 노이즈를 찾아 제거
- Gensim 사용으로 결과 도출
- KoNLPy의 사용자 사전 등록이 가능한 Komoran을 토크나이저로 선택
- 실험을 통한 최적 에폭 및 토픽 갯수 설정(어떤 실험인지 적기)
- 함수 Seed를 넣어 결과값을 고정시킨다는 것을 알게됨
