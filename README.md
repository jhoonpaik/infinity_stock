# infinity stock 깃허브

dataset 폴더 - 수집한 데이터
model 폴더 - 모델 파일
web 폴더 - 웹개발 관련 파일



## guideline

복제할 로컬 위치에서 git bash or cmder 실행



깃허브 repo에서 파일을 복제

$ git clone https://github.com/qorwlgns11123/stock1.git



추가, 수정, 삭제 등 진행



로컬저장소 생성

git init



로컬저장소에 파일 올림

git add .



git status

#현재 add 내역 확인



본인이 수정한 부분 comment "어디어디 수정함"

git commit -m "어디어디 수정함"



원격저장소와 연결

git remote add origin https://github.com/qorwlgns11123/stock1.git

git push



다른 사람이 원격저장소에 업데이트한 파일 있을 때 원격저장소와 본인 로컬저장소 상태 동일하게 만들기 위해 pull 이용

git pull





## 기타

현재 branch확인(main이어야 함)

git branch



현재 연결된 원격저장소 확인

git remote -v

