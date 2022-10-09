# MiniProject02

https://github.com/Thxnya/MiniProject02

## 미니 프로젝트02 - 개인성향에 따른 어학시험 종류 및 점수 예측



📰 프로젝트 개요<br/>
---
자신에게 맞는 어학시험, 공부방법 등을 정하는 데에 고민이 많은 취업준비생에게<br/>
이 분석을 통해서 도움을 주려고 합니다.<br/>
<br/>
영어는 취업준비에서 꼭 필요한 스펙입니다.<br/>
취업준비생은 자신에게 맞는 어학시험, 공부방법 등을 정하는 데에 고민이 많을 것입니다.<br/>
성향(MBTI), 공부방법에 따른 적합한 어학시험, 목표점수, 전공 별 시험종류 성취도 차이 데이터 분석을 통해<br/>
설문자에게 맞는 최적의 어학시험과 공부방법을 머신러닝으로 학습하여 도출할 것 입니다.



💬 프로젝트 결론<br/>
---
카이제곱검정을 통한 분석결과 MBTI중 E와 I 성향은 어학시험의 유형별로 선호도에 차이가 있다는 결과를 얻었습니다.<br/>

설문조사로 수집한 데이터로 데이터 분석을 진행했고, 어학시험 및 점수 예측 모델을 만들었습니다.<br/>
프로젝트 시작시 예상했던 대로 MBTI중 E(외향)와 I(내향) 성향의 사람은<br/>
어학시험에서 말하기 혹은 필기 시험를 선택할 때, 선호도에 차이가 있다는 것을 확인했습니다.<br/>
충분한 데이터를 쌓고, 같은 분석방법을 적용하여 다른 어학시험 혹은 자격증 시험에도 적용할 수 있게 하여<br/>
취업준비생들의 취준이 조금이라도 수월해졌으면 합니다.<br/>



⚡ 구현된 기능<br/>
---
## 장고를 이용한 웹 구축
### - 메인페이지
<img src="https://user-images.githubusercontent.com/104615422/193897322-e089726e-0e21-4070-913a-009f539c5445.JPG" width="60%" height="60%">

---

## 설문조사 페이지 구현과 오라클 연동을 이용한 데이터 수집(설문조사)
### - 설문조사 페이지
### - 데이터베이스 저장
<img src="https://user-images.githubusercontent.com/104615422/193896336-b0779ff6-14e0-4a4a-ba78-c678c8b1635a.JPG" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193897621-9d0e33a0-2a43-4384-b50f-b7afbd53298a.JPG" width="60%" height="60%">
---

## 수집된 데이터를 기반으로 MBTI, 전공, 공부방법별 선호도, 집단간 차이분석
<img src="https://user-images.githubusercontent.com/104615422/193896346-dfef0de9-d29f-4dec-be91-dba1d86544fb.JPG" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193896348-6cad7bcd-c648-4558-87e4-aab2c9ede3bd.JPG" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193896354-e28680ca-9e6d-4107-98fd-d36a6dbe23ab.JPG" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193896357-c4db695b-5939-4b5b-a167-2287ca1aec2f.JPG" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193896363-0225e2a7-d5b2-4e06-875b-8e1157c1856d.JPG" width="60%" height="60%">
---

## 머신러닝을 기반으로 하여 사용자의 정보를 이용한 적합 어학시험과 점수 예측
### - 앙상블 랜덤포레스트 모델 사용
<img src="https://user-images.githubusercontent.com/104615422/193896365-3192ea71-01c7-4e5f-96ed-e9fdaf383c6b.JPG" width="60%" height="60%">
