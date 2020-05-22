# 인공지능 사관학교 프리코스 과제 목차

# 1주차 과제 (2020.05.21)
# __개요__
* __작성자__ : 전진환
* __목적__ : 언어, 음성, 이미지, 자율주행(4가지) 제품 및 서비스를 자료조사.
* __기한 및 분량__ : 1주차 종료까지 / 분량 제한 없음  

# __목차__
**1. 언어**
**2. 음성**
**3. 이미지**
**4. 자율주행**
**5. 기타**

## __1. 언어__
* 구글 번역기(Google Translate)
 * 번역기의 변천과정
   * 최근 몇년간 Transformer 모델 기반 NMT( neural machine translation )사용
   * 모델의 견고성을 개선하기 위한 방법으로 Adversarial Generation (AdvGen)을 사용
   * Recurrent Neural Network(초창기) -> Transformer(2017) -> AdvGen(2019.07.29)

* 네이버 파파고(Naver Papago)
  * NMT (Neural Machine Translation)로 텍스트를 번역
  * SMT (Statistical Machine Translation) 번역도 지원함
    * 인공신경망 기반과 통계기반의 차이로 속도는 SMT가 더 빠르나 정확도는 NMT가 좋음.

* 심심이(Chat-bot, 대화형 기반 자연어처리 챗봇)
  * 2000년대 하드코딩으로 짜여졌던 챗봇, 현재는 딥러닝 기술을 적용
  * 욕설과 선정적인 언어로 이슈가 되었음(CNN에서 착안한 AICR Engine V2 :욕설필터 사용)
  * 현재 문장 분류 모델(Deep Bad Sentence Classifier) 한국어 기준 F1 score 0.98 이상의 높은 정확도를 가짐
    * 아마존 알렉사는 데이터 5만건, 심심이는 1억2천만건 보유

## __2. 음성__
* 구글 AI Voice kit
  * 구글 Google assistant의 프로토타입(chat-bot, 음성인식 기반 자연어처리 챗봇)
  * 라즈베리파이를 활용한 IoT + Chatbot을 통해 음성인식기능 체험 가능
  * 음성인식에 필요한 하드웨어와 소프트웨어 구성을 확인하고 셋팅 가능

* 삼성 무풍에어컨
  * 빅스비 탑재 에어컨

* 가상비서(chat-bot, 음성인식 기반 자연어처리 챗봇)
  * 삼성 빅스비
    * 2017.08 갤럭시 S8부터 탑재
    * 인공지능 스피커 개발부분 후발주자
 
 * 구글 어시스턴스
    * 구글 홈과 스마트가전서비스 및 안드로이드(OS) 스마트폰 탑재, 선두주자
   
 * 아마존 알렉사
 * 마이크로소프트 코타나
 * 알리바바 알리지니

## __3. 이미지__
* 빅스비 비전
  * 인터넷 쇼핑, 갤러리, 바코드 인식

* 구글 문자인식 Cloud vision API
  * 책을 복합기를 통한 복사로 텍스트, md, PDF등으로 변환해서 사용가능

* 애플 및 삼성의 얼굴인식
  * 애플 Face ID
    * 트루뎁스 카메라를 통해 스캔 후 A11칩의 뉴럴엔진이 얼굴정보와 비교, 얼굴인식처리 기법(CNN 추정) 활용

  * 삼성 AR 이모지
    * 카메라 기능을 통해 내 표정을 따라하는 마이 이모지를 사진 및 동영상으로 촬영하거나 마이 이모지로 만들어진 스티커를 다른 사람들과 공유할 수 있음.

* 위변조 사진 판별 기술 
  * GAN(Generative Adversarial Network) 생성적 적대 신경망을 사용

* 의료영상분석장치 소프트웨어 ‘뷰노메드 본에이지(VUNOmed-BoneAge)'
  * AI로 뼈 나이를 판독해 성조숙증이나 저성장 진단을 함.
  * X-ray, CT 사진과 같은 영상 의료 정보와 생리학적 신호 데이터, EMR 등의 진단기록을 종합적으로 통합 분석함으로써 질병의 유무를 진단

## __4. 자율주행__
* 테슬라 모델3
  * 자율 주행레벨 1~4단계까지 존재

* 라이다 센서, 레이더 센서, AI칩
  * 라이다 센서
    * SOS랩 라이다 제품군(SL-1,ML-1,GL-3)
    * 카네비컴 라이다 제품군(3CH/4CH, 16CH, 360°SCANNING LIDAR 등)
    * 주로 중고도 항공측량 및 30m이내의 수로 연안측량에서 사용
    * 가격이 매우 비싸고, 시장가격 안정화가 안됨
    * 비싼가격으로 인해 테슬라에서 AI칩을 대안으로 대체하려고 시도함. 

  * 레이더 센서
    * 스마트레이더시스템 제품군(4D 레이더 레티나)
    * 비트센싱(AIR 4D)
    * 기존의 낡은 2D에서 4D센서로 개선하려고 함. 라이다처럼 정밀함.

  * AI칩
    * 퓨리오사AI


## __5. 기타__
음성, 이미지등 인공지능의 기술이 결합된 복합적인 제품 및 서비스를 기타로 분류 
* 카카오 아이
  * 카카오 인공지능 플랫폼

* LG ThinQ와 Deep ThinQ
  * 스마트폰을 통한 가전제품 제어
  * ThinQ는 브랜드, Deep ThinQ는 플랫폼
 
* LG 코드제로 씽큐 R9 보이스 무선로봇청소기
  * 이미지처리 + 음성인식

* 네이버 쇼핑
  * 상품 카테고리, 카테고리 자동매칭
  * 이미지처리 + 자연어처리
  * Multi-input model(CNN + LSTM + Simple CNN + Mobilnet)
    * MobileNet이 나오기전에는 VGG모델(Deep Neural Network)사용

* 중국 코로나 인공지능(A) 진단 세트(Dharma Hospital Medical AI)
  * 20초만에 진단 자연어처리(NLP/RNN) + 합성곱신경망(CNN) 사용
  * CT 이미지의 인식 네트워크를 훈련시켜 새로운 관상 폐렴 이미지와 일반 폐렴 이미지의 차이를 신속하게 식별

* 가천대 길병원, 부산대학교병원 IBM 왓슨도입
  * 암진단 '왓슨 포 온콜로지
  * 암환자의 종양세포와 유전자 염기서열을 분석해 맞춤형 치료법을 추천하는 '왓슨 포 지노믹스
  * 환자의 생존률이 몇퍼센트인지 의사에게 약 추천도 할 수 있다고 함.
-------------------------------------------------------------------------------------------------

# __<링크>__

[구글 번역기 논문](https://ai.googleblog.com/2019/07/robust-neural-machine-translation.html)

[네이버 파파고](https://biz.chosun.com/site/data/html_dir/2016/11/08/2016110802495.html)

[구글과 네이버 번역기 성능차이](https://yeolco.tistory.com/165)

[챗봇 종류 5가지](https://www.google.com/search?sxsrf=ALeKk03GH1WCBCU4Z8zJdV9hxSrKmhuJVQ%3A1590078322420&ei=cqvGXueUGYO0mAXJr4HwAQ&q=%EC%B1%97%EB%B4%87+%EC%A2%85%EB%A5%98&oq=%EC%B1%97%EB%B4%87+%EC%A2%85%EB%A5%98&gs_lcp=CgZwc3ktYWIQAzICCAAyBggAEAgQHjIGCAAQBRAeOgcIIxDqAhAnOgoIIxDqAhAnEIsDOgQIIxAnOgUIABCDAToICAAQgwEQiwM6BAgAEAo6BAgAEEM6BwgAEEMQiwM6BQgAEIsDOgQIABADOgUIABDNAjoECAAQEzoHCAAQExCLAzoKCAAQgwEQFBCHAjoHCAAQFBCHAjoHCAAQChCLA1DmEVjMkgFg_pMBaBhwAHgCgAGoAYgBtiSSAQQwLjMymAEAoAEBqgEHZ3dzLXdperABBrgBAg&sclient=psy-ab&ved=0ahUKEwjnlcqsr8XpAhUDGqYKHclXAB4Q4dUDCAw&uact=5)

[대화형 기반 자연어처리 챗봇 심심이](http://www.engjournal.co.kr/news/articleView.html?idxno=429)




[구글 AI Voice kit](https://aiyprojects.withgoogle.com/voice/)

[빅스비](https://www.etoday.co.kr/news/view/1550759)

[삼성무풍에어컨 빅스비](https://www.samsung.com/sec/air-conditioners/floor-standing-af25n9970mfk/)

[가상비서의 종류](https://ko.wikipedia.org/wiki/%EA%B0%80%EC%83%81_%EB%B9%84%EC%84%9C)




[구글 클라우드 비전](https://cloud.google.com/vision/docs/ocr?hl=ko)

[애플 Face ID, true Depth](https://news.joins.com/article/22090087)

[삼성 AR 이모지](https://www.samsungsvc.co.kr/online/faqView.do?faqId=KNOW0000039282)

[위변조 사진 판별 기술](http://www.bigbangangels.com/%EB%A1%9C%EB%AF%BC/)

[뷰노메드 본에이지(VUNOmed-BoneAge)](http://www.biospectator.com/view/news_view.php?varAtcId=5485)




[테슬라 모델3](https://namu.wiki/w/%ED%85%8C%EC%8A%AC%EB%9D%BC%20%EB%AA%A8%EB%8D%B8%203)

[라이다·레이더 센서, AI칩](https://blog.naver.com/kpfisnet/221907981114)

[SOS랩 라이다](http://soslab.co/ko/home-ko/)

[카네비컴](http://www.carnavi.com/product-lidar)

[스마트레이더시스템](https://www.kipost.net/news/articleView.html?idxno=202280)

[비트센싱](http://bitsensing.com/kor/product/air.php)

[퓨리오사AI](http://d2startup.com/portfolio/19)




[카카오 아이](https://ko.wikipedia.org/wiki/%EC%B9%B4%EC%B9%B4%EC%98%A4_%EC%95%84%EC%9D%B4)

[LG ThinQ와 Deep ThinQ](https://post.naver.com/viewer/postView.nhn?volumeNo=13990306&memberNo=516856)

[LG 코드제로 씽큐 R9 보이스 무선로봇청소기](https://m.blog.naver.com/itcools/221835405877)

[네이버 쇼핑 상품카테고리 분류](https://d2.naver.com/helloworld/1264836)

[중국 코로나 인공지능(A) 진단 세트](http://www.aitimes.kr/news/articleView.html?idxno=15514)

[가천대 길병원, 부산대학교병원 IBM 왓슨](https://biz.chosun.com/site/data/html_dir/2017/01/24/2017012401959.html)

[가천대 길병원](https://medigatenews.com/news/747834046)
-----------------------------------------------------------------------------
# __<이미지>__

![구글 번역기 AdvGAN](https://feedforward.github.io/blog/assets/img/ddfsfsafdafas.png)

![네이버 파파고](https://image.chosun.com/sitedata/image/201611/08/2016110802419_1.jpg)

![챗봇 심심이](https://img7.yna.co.kr/etc/inner/KR/2017/10/13/AKR20171013150500887_13_i_P4.jpg)

![google voice kit v2](https://mblogthumb-phinf.pstatic.net/MjAxODAzMjBfMTQ3/MDAxNTIxNTI3MjExODUw.xC5OQ9BX11FvritrMQ-nDXsu8TkSOM9iEIWo7NxQR_Qg.oK5P-Dv_F5y4jDW6_t9lRqbFPVdAD4rqXBbB-gxlU2kg.PNG.roboholic84/image_6825359401521527158183.png?type=w800)

![삼성 무풍에어컨 빅스비](http://image.etland.co.kr/nas/cdn/editor/attach/2018/05/25/ec89978c-2142-45d1-a49d-8bc1a4fabc96.jpg)

![가상비서 음성인식 챗봇](http://m.ddaily.co.kr/data/photos/cdn/20180731/art_1532932291.png)

![구글 클라우드 비전](https://cloud.google.com/vision/docs/images/document_text_highlighted.png?hl=ko)

![애플 Face ID](http://www.digitaltoday.co.kr/news/photo/201710/112706_161081_4714.jpg)

![삼성 AR 이모지](https://image.chosun.com/sitedata/image/201803/05/2018030502466_0.jpg)

![위변조 판별기술](http://www.bigbangangels.com/wp-content/uploads/2019/01/img_20.jpg)

![뷰노메이드 본에이지](http://img.etoday.co.kr/pto_db/2018/05/20180516105110_1213502_350_233.jpg)

![테슬라 자율주행](http://www.autoherald.co.kr/news/photo/201804/31049_47407_3438.png)

![스마트 레이더 시스템](https://postfiles.pstatic.net/MjAyMDA0MTRfMjIg/MDAxNTg2ODQ5NzUzNDA1.Fr4-d767JAgyx58zO0woKPQqhnLVwsiZ707R6yfcvokg.2xkg2Sgi0TUw3Bf82tDLsuOGaSpVwZ2M0UQ7gIv_z0gg.JPEG.kpfisnet/01_02.jpg?type=w773)

![SOS랩 라이다](http://soslab.co/wp-content/uploads/2020/01/CES-%ED%99%88%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%9D%B4%EB%AF%B8%EC%A7%80-03-1.png)

![카네비컴 라이다](http://www.elec4.co.kr/photo/2018/20180103(0).jpg)

![스마트레이더시스템](https://www.kipost.net/news/photo/201911/202280_42732_2339.png)

![퓨리오사AI 반도체](https://image.slidesharecdn.com/241deview2018furiosafinal-181012001208/95/241-ai-33-638.jpg?cb=1539307310)

![카카오 아이](http://image.dongascience.com/Photo/2017/09/15058805908355.jpg)

![LG ThinQ와 Deep ThinQ](http://thinq.developer.lge.com/application/thinq_platform/img/feature/Architecture.png)

![LG R9 코드제로](https://www.lge.co.kr/uploads/product/media/2020/01/r969ia.akor/usp_0102_s2.jpg)

![네이버 쇼핑 상품카테고리 분류_feature](https://d2.naver.com/content/images/2019/04/helloworld-201904-tensorflow_navershopping-05.png)

![네이버 쇼핑 상품카테고리 분류](https://d2.naver.com/content/images/2019/04/helloworld-201904-tensorflow_navershopping-11.png)

![중국 코로나 진단세트](http://www.aitimes.kr/news/photo/202003/15514_16806_423.jpg)

![가천대 길병원 왓슨](http://www.medigatenews.com/file/news/42074)
