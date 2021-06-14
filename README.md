# KoGPT2_Example

## 한국어 문장 생성기
* GPT-2 모델을 Fine-Tuning한 한국어 언어 모델
* 2020년 2월에 SKT-AI에서 1.0 버전, 지난 5월 2.0버전이 새로 업데이트 되었다.
* 2.0버전은 1.0버전보다 데이터의 학습량을 2배이상 늘려서 40GB이상의 텍스트를 학습시킨 한국어 Decoder 언어 모델이다.
* 데이터를 늘린 만큼 1.0보다 성능이 개선되었고, 이모티콘과 이모지등을 추가해서 토큰의 인식능력도 올렸다고 한다.

* code는 SKT-AI 오픈소스 깃업 참고 (https://github.com/kairess/KoGPT2)
* 실행 결과 연습1
<img width="913" alt="실행" src="https://user-images.githubusercontent.com/56244207/121860304-b0502280-cd33-11eb-9285-4bf705c58ce5.PNG">
* 실행 결과 연습2
<img width="902" alt="실행2" src="https://user-images.githubusercontent.com/56244207/121860454-d1b10e80-cd33-11eb-8f2c-ef7ea434b6b1.PNG">
* 실행 결과 연습3
<img width="901" alt="실행3" src="https://user-images.githubusercontent.com/56244207/121860472-d8d81c80-cd33-11eb-88da-984bc5a380ae.PNG">

* 결과
1. 확실히 데이터에 많이 의존하는 결과가 나온다는 것을 느낄 수 있었다.
2. 뉴스 기사, 책? 내용이 많이 학습되었다는 생각을 받았는데 다양한 시도를 통해서 앞으로 어떤 문장을 생성시킬지 기대된다
3. 또한, 데이터의 증강기법으로 사용이 되어서 원하는 모델을 학습시킬 때, 부족한 데이터를 채울수 있는 방법으로 사용해봐도 좋은 방법 중 하나가 될 것 같다.


