# PitcherBatter2Vec (KBO ver.)



## 🖥️ 프로젝트 소개
- 소개 : 야구선수들의 경기 데이터를 통해 투수 대 타자 타석 결과 (투수 포함) 예측
- 참고 논문: (BatterPitcher)2vec: Statistic-Free Talent Modeling With Neural Player Embeddings
- 주요 역할 : 3년 간(2017~2020년) KBO 각 팀 선수들의 날짜 별 경기 성적, 선수 신체 정보, 연봉 등 데이터 크롤링, 전처리, MLB 경기 내용을 기반으로 발표된 논문을 참고하여 KBO 정보를 적용하여 모델링 구현.

<br>

## 🕰️ 개발 기간
* 22.04.24-22.05.18

### 🧑‍🤝‍🧑 맴버구성
- 남현수, 송현서, 장중백, 이상기

### ⚙️ 기술 스택 & 환경
<div align=center> 
    <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">
    <img src="https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
    <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
    <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white">
    <img src="https://img.shields.io/badge/keras-D00000?style=for-the-badge&logo=keras&logoColor=white">
    <img src="https://img.shields.io/badge/selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white">
</div>   

## 📌 결론

- 업무 성과 : 
 1. MLB 선수들의 정보만을 가지고 설계되어 있던 모델을 KBO 데이터를 적용해서 코드 구현
 2. 2017년~ 2019년 시즌 내 타자와 투수 간 타석 결과를 분석하여 경우의 수 구현
 3. 투수와 타자 간 타석 결과를 학습하여 앞으로의 타석 결과를 예측 가능.
 4. 그리고 한 선수와 비슷하게 Vectorizing 된 선수들을 찾을 수 있었다. 
 5. 이걸 기반으로 다양한 선수들의 성적 예측, 에이징 커브(은퇴시기 예측), 투수의 구종 선택 비율을 예측할 수 있는 모델로 발전시킬 수 있다.

- 비고: 참고한 논문에서 사용된 DB는 매우 깔끔히 정제된 DB들이었고, 수많은 정보를 한 번에 파악할 수 있는 DB들이었다.
- 어려웠던 점 : KBO 선수들의 DB가 정확하지 않음 -> DB 전처리에 어려움이 생김 -> 모델링 구현 정확도에 차질이 생김.

