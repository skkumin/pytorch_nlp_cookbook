[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fskkumin%2Fpytorch_nlp_cookbook&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)<br/>

# pytorch_nlp_cookbook

## 1. 스터디 소개

#### 1) Members

서울대학교 핀테크 6기 
: Pytorch를 이용한 NLP STUDY

|                           Mingue                            |                           Woorim                           |                           Subin                           |                           Minji                            |                           Sunkyung                            |  
|:----------------------------------------------------------:|:----------------------------------------------------------:|:----------------------------------------------------------:|:----------------------------------------------------------:|:----------------------------------------------------------:|  
| <img src="https://github.com/skkumin/pytorch_nlp_cookbook/blob/main/asset/profile/mingue.png" width=150px> | <img src="https://github.com/skkumin/pytorch_nlp_cookbook/blob/main/asset/profile/woorim.png" width=150px> | <img src="https://github.com/skkumin/pytorch_nlp_cookbook/blob/main/asset/profile/subin.png" width=150px> | <img src="https://github.com/skkumin/pytorch_nlp_cookbook/blob/main/asset/profile/minji.png" width=150px> | <img src="https://github.com/skkumin/pytorch_nlp_cookbook/blob/main/asset/profile/sunkyung.png" width=150px> |
|         **[Github](https://github.com/skkumin)**          |        **[Github](https://github.com/eva268)**         |           **[Github](https://github.com/subinchang)**            |          **[Github](https://github.com/MANMANJIJI)**           |        **[Github](https://github.com/mongshil)**         

#### 2) 기간

1주차: RNN & LSTM -> 2023/10/31 ~ 2023/11/05<br/> 
2주차: Seq2seq & Attention -> <br/> 
3주차: Transformer -> <br/> 
4주차: ELMO -> <br/> 
5주차: GPT -> <br/> 
6주차: BERT -> <br/> 
7주차: GPT-2 -> <br/> 
8주차: LLAMA -> <br/> 


## 2. 스터디 내용
📄 이론 -> 각 참고자료로부터 공부한 내용을 정리해 Velog에 포스팅해두었습니다.<br/> 
💻 코드 -> 각 참고자료로부터 모델에 맞는 Task를 정해 코드로 실습<br/>
📁 참고한 자료들 -> 공부하는데 참고한 자료들 입니다.<br/>

## Contents  
#### 1️⃣ RNN
- 전민규: 네이버 영화 리뷰데이터를 이용한 감정분석(Binary Classification)/[📄이론](https://velog.io/@skkumin/RNN-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-%EC%8B%9C%ED%80%80%EC%8A%A4-%EB%AA%A8%EB%8D%B8%EC%9D%B4%EB%A1%A0Pytorch)[💻코드](https://github.com/skkumin/DeepLearning-Study/blob/main/RNN/RNN%EC%A3%BC%EC%8B%9D(many%20to%20one).ipynb)<br/>
- 서우림: 문자메세지 스팸 분류(Binary Classification)/[📄이론](https://velog.io/@skkumin/RNN-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-%EC%8B%9C%ED%80%80%EC%8A%A4-%EB%AA%A8%EB%8D%B8%EC%9D%B4%EB%A1%A0Pytorch)[💻코드](https://github.com/eva268/RNN-Study)<br/>
- 장수빈: 주가 예측(Regression)/[📄이론](https://velog.io/@skkumin/RNN-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-%EC%8B%9C%ED%80%80%EC%8A%A4-%EB%AA%A8%EB%8D%B8%EC%9D%B4%EB%A1%A0Pytorch)[💻코드](https://github.com/skkumin/DeepLearning-Study/blob/main/RNN/RNN%EC%A3%BC%EC%8B%9D(many%20to%20one).ipynb)<br/>
- 황선경: 기상 예측/[📄이론](https://velog.io/@skkumin/RNN-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-%EC%8B%9C%ED%80%80%EC%8A%A4-%EB%AA%A8%EB%8D%B8%EC%9D%B4%EB%A1%A0Pytorch)[💻코드](https://github.com/skkumin/DeepLearning-Study/blob/main/RNN/RNN%EC%A3%BC%EC%8B%9D(many%20to%20one).ipynb)<br/>
- 박민지: 뉴스 데이터 분류/[📄이론](https://velog.io/@skkumin/RNN-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%98-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-%EC%8B%9C%ED%80%80%EC%8A%A4-%EB%AA%A8%EB%8D%B8%EC%9D%B4%EB%A1%A0Pytorch)[💻코드](https://github.com/skkumin/DeepLearning-Study/blob/main/RNN/RNN%EC%A3%BC%EC%8B%9D(many%20to%20one).ipynb)<br/>

<details>
<summary>📁참고한 자료들</summary>
  <br><br/>
<div markdown="1">

RNN이론 설명 👉 [Kaist 딥러닝 홀로서기 RNN(이론편)](https://youtu.be/bPRfnlG6dtU?si=OtprAftMuki6V_Oi)<br/>
RNN코드 👉 [Kaist 딥러닝 홀로서기 RNN(코드 실습)](https://youtu.be/tlyzfIYvMWE?si=fDUGbdoX5uhxfJrM)<br/> 
참고한 책 👉 딥러닝 파이토치 교과서<br/>  

</div>
</details> 


