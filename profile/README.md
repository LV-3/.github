<div align="center">
  <img width="203" alt="image" src="https://github.com/LV-3/.github/assets/111716640/74553b0e-787e-4113-b25e-3908c8977dcc">




<h1> Hello GPTv 🎯  VOD 개인화 추천 서비스</h1>
<br>
 프롬프트 엔지니어링 활용 개인화 맞춤 VOD 추천 서비스
</br>

VOD 소비 이력을 바탕으로 세부 취향을 고려한 추천 서비스를 경험해보세요.!

---
🔗[서비스 링크](https://www.hellogptv.com)  
`테스트 ID`: 66885000
---

</div>

## 프로젝트 소개


  * LG HelloVision DX Data School 에서 진행한 VOD 개인화 추천 서비스 프로젝트입니다.

  * 줄거리 데이터를 기반으로 **Prompt Engineering**을 통해 메타 데이터를 생성하였습니다.
    
  * 생성한 메타 데이터를 추천 시스템에 적용하여 사용자에게 **설명 가능한 추천 시스템**을 기획하였습니다.
  

  

## 🤼‍♀️ 팀원 소개

  <img width="443" alt="image" src="https://github.com/LV-3/.github/assets/111716640/c5bd9a71-8f1c-4ef1-aee5-9649df801827">


## 요청 흐름도
![Flow chart](/figures/flowchart.png)

## 서비스 아키텍쳐
![Architecture](/figures/architecture.png)

## 인프라 아키텍쳐
![Infrastructure](/figures/infra.png)


## Recommendation System Using GPT

* Prompt Engineering을 하기 위해 LLM FrameWork인 **LangChain**을 사용하였습니다.
  
* LangChain에 사용한 LLM은 OpenAI의 **GPT 3.5 turbo**을 사용하였습니다.

* LangChain을 활용하여 Prompt Engineering을 통해 **VOD에 대한 메타 데이터**를 구축하였습니다.
  
    
  <img width="799" alt="image" src="https://github.com/LV-3/.github/assets/111716640/1625d0cc-db88-420e-8610-b31c482854f1">


  * LangChain을 활용하여 Prompt Engineering을 활용한 방안은 다음과 같습니다.
    1. LangChain의 입력값으로 VOD의 줄거리를 넣습니다.
    2. 입력값을 통해 추출해야할 데이터들을 통해 LangChain의 템플릿으로 설정합니다.
       

  ![image](https://github.com/LV-3/.github/assets/111716640/0dd08494-3983-4259-9087-1d720e5ce162)

  * 템플릿들을 통해 구축된 메타 데이터들의 예시이며
    메타 데이터들을 통해 컨텐츠들을 더 세분화된 특징으로 다룰 수 있습니다.

## Explainable Recommender System

* 개인화 추천모델로는 **DeepFM**을 사용하였습니다.
* 설명가능한 추천 시스템을 구축하기위해 DeepFM의 추천 결과의 메타 데이터 속성을 **UI를 통해 명시** 하였습니다.

  ![image](https://github.com/LV-3/.github/assets/111716640/a0608f6a-e832-4a07-80d3-f0ae4dd2af53)









---


