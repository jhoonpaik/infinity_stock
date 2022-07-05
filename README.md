# 프로젝트 주제: 특정 ETF 미래 주가예측 및 태블로 시각화

구성원: HK.LEE, JM.lEE, JCH.KIM, JH.PAEK

## 배경
· 수많은 주가예측 서비스가 보편화되었지만 특정 종목에 국한되어 이루어지고 있음  
· 변동성이 안정적인 국내 ETF 시장에 주목하고 특정 ETF 상품군을 예측대상으로 선정  
· 최종적으로 다양한 모델 지표를 제공하여 이용자의 투자 의사결정에 정보를 반영하고자 함

## 주가예측 ETF종목

- KODEX 코스피
- KODEX 운송
- KODEX 반도체

## 주가예측 기간

- 1주일
- 1개월
- 3개월

## 선정 시계열 모델(AI분석가로 명명)
1. 아리(ARIMA)  
자기 회귀 모델(AR)과 이동 평균 모델(MA)과 데이터의 정상성을 확보하기 위한 차분을 합친(I) 모델

2. 마크(FBprophet)  
페이스북이 만든 시계열 예측 오픈소스 라이브러리

3. 매타(Nueral prophet)  
Fbprophet에서 업그레이드된 딥러닝 시계열 예측 라이브러리

4. JCH KIM(LSTM)  
장기 메모리를 위해 개발된 인공지능 알고리즘

5. 그루(GRU)  
LSTM에서 학습할 가중치 수를 줄여 간소화한 버전

## 시연화면

### 웹화면
![image](https://user-images.githubusercontent.com/45068747/177231200-5822e4c4-6b88-4e23-bc5f-d7d0cb4f3953.png)

### 태블로
![image](https://user-images.githubusercontent.com/45068747/177231218-62364a5e-e582-4f62-b6d2-6c1d19e8f196.png)



# Github

## infinity stock 깃허브 폴더

dataset 폴더 - 수집한 데이터  
model 폴더 - 모델 파일  
web 폴더 - 웹개발 관련 파일


## github guideline

복제할 로컬 위치에서 git bash or cmder 실행

깃허브 repo에서 파일을 복제  
git clone https://github.com/qorwlgns11123/stock1.git

추가, 수정, 삭제 등 진행

로컬저장소 생성  
git init

로컬저장소에 파일 올림  
git add .

git status  #현재 add 내역 확인

본인이 수정한 부분 comment "어디어디 수정함"  
git commit -m "어디어디 수정함"

원격저장소와 연결  
git remote add origin https://github.com/qorwlgns11123/stock1.git

git push



다른 사람이 원격저장소에 업데이트한 파일 있을 때 원격저장소와 본인 로컬저장소 상태 동일하게 만들기 위해 pull 이용  
git pull



## 기타

현재 branch확인(main이어야함)  
git branch



현재 연결된 원격저장소 확인  
git remote -v

