# Data-Crawling

### 데이터 수집

- 알라딘 데이터 크롤링 : 질의응답 쌍으로 학습시켜야 함
- 컬럼 : 제목, 저자, 목차, 줄거리, 구매 링크, 가격, 장르, 책속에서(책 페이지 문구)
- answer : 15000원이야, question : 총균쇠의 책 가격은 얼마야?
- answer : 책속에서 책페이지 문구 한 줄 , question : 총균쇠의 인상깊은 문구 말해줘
- 한 row에서 생성될 수 있는 쌍이 여러개 있음


## To do

- Dialogflow를 우리 검색 모델에 활용할 수 있을지 확인해보기
    - 데이터 학습 or 생성 시
- 추천 모델링 어떻게 구상할지 생각
    - 1차) 장르별 분류 Group by 트리 구조
    - 2차) 트위터 추천 알고리즘 스터디 (사용자 맞춤형 추천)
    - ppt 사진
    - 추천 페이지 UI
    - ![image](https://github.com/Chatgpt-Project-BookContextAI/Data-Crawling/assets/109809978/d3896a87-1a7a-4d48-a6d5-a41c155286c9) 




- 알라딘 데이터 수집 : 30개
- 컬럼 : 제목, 저자, 목차, 책소개, 구매 링크, 가격, 장르, 책속에서(책 페이지 문구), 편집장의 선택
- 장르(주제 분류) : 무조건 첫번째 줄의 세번째까지만 수집
- 한명당 한 섹터씩 → 10년치 (2013-08-17 ~ 2023-08-27) / 너무 버겁다 : 5년치
    - 유빈 : 경제경영
    - 승훈 : 사회과학
    - 서영 : 소설/시/희곡
    - 국내도서 카테고리
    - ![image](https://github.com/Chatgpt-Project-BookContextAI/Data-Crawling/assets/109809978/9c87843d-6a2c-4e66-bb95-2e62b909bb3a)
 
