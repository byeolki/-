# 네이버 뉴스 성소수자 관련 댓글을 분류한 데이터셋

1. 데이터 출처 : https://www.kaggle.com/datasets/junbumlee/lgbt-hatespeech-comments-at-naver-news-korean
![image](https://github.com/byeolki/Naver-News-categorizes-comments-related-to-sexual-minorities/assets/97008863/af00a5b5-b83a-487f-9e42-ae3a1be689cb)

- 훈련 데이터 갯수 : 7068
- 검증 데이터 갯수 : 1767
- 테스트 데이터 갯수 : 2205


사용 모델 : LSTM
![image](https://github.com/byeolki/Naver-News-categorizes-comments-related-to-sexual-minorities/assets/97008863/8fece408-4201-48ad-91c6-429e5d52ae26)


훈련 횟수 : 100 epoch

최저 손실 : 0.0184
최대 정확도 : 0.9434
![image](https://github.com/byeolki/Naver-News-categorizes-comments-related-to-sexual-minorities/assets/97008863/d01b6695-dfff-4cb3-b27f-2ddbcf0bc188)

고찰 : 위 데이터를 학습시켜보면서 토큰화와 LSTM을 복습할 수 있었고, 데이터가 적어서 좋은 결과가 안 나와서 아쉬웠음.
