# 이모지톡 ( 지능형 채팅 서비스)

[![](https://postfiles.pstatic.net/MjAyMDEyMDFfNjgg/MDAxNjA2ODAwNjc3OTg0.TvdqrxblsLT8j4QHvmzLPtwFLg0HNHmw5ZCJE2u931Ig.rVRw0hmT7UycSnqbhRvJsSuIi8nAwIsFWh_lH2yA_90g.PNG.jodawooooon/%EC%95%84%EC%9D%B4%EC%BD%98.png?type=w773)](https://blog.naver.com/PostList.nhn?blogId=jodawooooon&from=postList&categoryNo=12#)

## 1. 개요

메신저 프로그램의 등장으로 인해 과거 가장 중요한 커뮤니케이션 매체였던 전화의 사용률이 급격히 감소하고, 카카오톡의 월간 이용자수는 4,300만명을 웃돌 정도로 현대사회의 대부분의 사람들은 채팅으로 의사소통을 하고 있다. 현재 우리 삶에서 빼놓을 수 없는 어플리케이션 하나를 꼽자면 10명중 9명은“카카오톡”을 꼽을 정도로 메신저 프로그램은 우리 삶에서 빼 놓을 수 없는 중요한 커뮤니케이션 플랫폼이다. 메신저 응용 프로그램은 쉽고 간결하며, 실제로 목소리를 주고받지 않아도 실시간 의사소통의 가능하다는 장점이 있다. 이 메신저 프로그램에 인공지능을 결합하여 인간중심적이고 사용자를 이해할 수 있는 메신저 프로그램을 만든다면 어떨까 라고 생각을 하게 되어 감정 기반 채팅 어플리케이션을 선택하게 되었다.

​

## 2. 필요성

기존 메신저 응용 프로그램은 쉽고 간결하며, 실제로 목소리를 주고받지 않아도 실시간 의사소통의 가능하다는 장점이 있지만, 채팅 사용 시 텍스트에 의존하여 대화를 하게 되고, 이 때 말투나 표정이 드러나지 않기 때문에 감정이 온전하게 전달되지 못하여 오해가 생기는 경우가 많다.

이러한 단점을 보완하고 좀 더 감정적이고 효과적인 대화를 위하여 사용자의 표정을 통해 감정을 분석하고 대화의 전체적인 내용 분석을 제공하는 지능적인 채팅 플랫폼 “이모지톡”(지능형 채팅 서비스)를 제안하였다.

“이모지톡”은 메신저 프로그램과 인공지능이 결합된 형태로 얼굴 인식 및 감정 분석, 텍스트 분석 등 전망 있는 차세대 기술들이 활용된 작품을 만드는 것에도 의의가 있다. 현재 상용화된 채팅 메신저의 기능을 포함하는 것에서 더 나아가 감정을 표현하는 새로운 세대의 채팅 프로그램을 목표로 하고 있으며, 추가적으로 대화 종료 후 해당 채팅의 내용을 이용하여 전체적인 감정을 분석하여 감정 빈도수 그래프 및 대화 내용을 한 눈에 정리해주는 기능과 사용자에게 편리한 기능을 추가 제공할 예정이다. 이러한 과정을 통해 사용자에게 지능적이고 유능한 채팅 서비스를 제공할 수 있을 것으로 기대하고 있다.

​

## 3. 목표

이번 프로젝트 목표는 다중 채팅과 동시에 감정을 분석해 상대의 감정을 실시간으로 알 수 있는 채팅 플랫폼을 만드는 것이다. 이 채팅 플랫폼을 통하여 얼굴을 마주하지 않고 채팅을 하면서도 상대방의 감정을 파악할 수 있고 대화 종료 후 어떤 대화를 했는지 분석할 수 있다.

본 어플리케이션의 기능은 다음과 같다.

​

1) 로그인, 친구목록, 프로필 수정, 사진 및 파일 전송 등의 기능을 지닌 채팅 어플리케이션

2) 채팅 방 접근 후 전면 카메라로 사용자 얼굴 인식

3) 실시간 감정 분석 후 이모티콘으로 변환하여 대화방 안의 사용자들에게 공유

감정은 다음과 같이 6가지로 분류된다. (무표정, 기쁨, 화남, 슬픔, 놀람, 경멸)

4) 사용자가 원하는 경우 버튼을 눌러 감정 분석을 중지하거나 재개할 수 있다.

5) 채팅 분석 버튼 클릭 시 해당 채팅방의 대화내용을 분석한다.

분석 결과는 다음과 같이 4개이다.

wordcloud, 사용자 별 빈도수, 요일 별 빈도수, 사용자들의 감정 빈도수

6) 저장된 이미지를 웹페이지에 파싱하여 안드로이드 어플리케이션에 연결한다.

​

해당 채팅 어플리케이션을 실행하게 되면 먼저 로그인을 통해서 자신의 정보를 등록할 수 있고, 채팅 서비스를 이용할 수 있는 UI로 넘어갈 수 있다. 그리고 채팅방을 개설하여 채팅에 참여할 수 있고 해당 채팅을 통해 텍스트뿐만 아니라 사진, 파일 등의 추가적인 데이터도 전송할 수 있다. 음성인식을 적용하여 채팅을 음성인식으로 키보드뿐만 아니라 채팅을 입력할 수 있게 한다.

그리고 채팅 시 카메라를 통해 사용자의 얼굴 표정을 분석하여 사용자들의 감정을 이모티콘으로 공유한다. 이는 채팅방 안의 구성원들이 모두 확인할 수 있다. 이 때 감정 공개를 원하지 않는 사용자는 감정 가리기 기능을 사용할 수 있다.

대화가 끝난 뒤에는 채팅 내용을 분석하여 주제별 빈도수 그래프를 만들고 핵심 단어들을 정리한다. 해당 채팅방에서 어떤 대화가 오고 갔는지, 중심 내용이 무엇이었는지 한 눈에 볼 수 있게 요약하여 제공한다.

​

​
## 4. 연구 환경

개발언어 :Java, Python

개발도구 : Android Studio, Spyder, Putty

데이터베이스 : Firebase (Cloud Firestore)


## 5. 연구 결과


캡스톤 포스터

​[![](https://postfiles.pstatic.net/MjAyMDEyMDFfMjY3/MDAxNjA2ODAxMTM3NjAy.qt95CHDHV2oW1q-yxGm72s7UKpd2tHaXEuyDAjPOfC0g.oduNa8XlllBH_RSYi3oUs2rY5W79hRSULi5HnlO9Z2wg.PNG.jodawooooon/SE-ba7da886-2359-4c74-a916-3620ec683828.png?type=w773)](https://blog.naver.com/PostList.nhn?blogId=jodawooooon&from=postList&categoryNo=12#)

https://youtu.be/-DK67gsgLS8


시연 동영상



## 참고 자료

​

한예림, 한국통신학회, “최신 정보통신기술 Google에서 제공하는 Firebase의 실시간 데이터베이스 이용에 관한 연구”, 2017년

허경무, “얼굴 표정 인식 기술”, 2014년

강민구, “인공지능 기반의 비주얼 인식 오픈소스 비교연구 : 인물 감정 분석 중심으로”, 2017년 12월

​

기본적인 채팅 어플리케이션을 구현하는 것은 github의 directTalk9를 참조하였습니다. 

A messenger app for Android based on Firebase, https://github.com/gujc71/DirectTalk9

https://firebase.google.com/docs/android/setup?hl=ko


firebase.google.com

얼굴 인식과 표정 분석은 android faceDetector, android affdex sdk를 사용하였습니다.

https://developer.android.com/reference/android/media/FaceDetector


FaceDetector  |  Android 개발자  |  Android Developers
Google은 흑인 공동체를 위한 인종 간 평등을 진전시키기 위해 노력하고 있습니다. Google에서 어떤 노력을 하고 있는지 확인하세요 . Android 개발자 Docs Reference Table of contents Summary Nested classes Public constructors Public methods Protected methods FaceDetector Kotlin | Java public class FaceDetector extends Object java.lang.Object   ...

developer.android.com

​

채팅 중 실시간으로 전면 카메라를 통해 사용자의 표정을 인식하여 이모티콘으로 출력됨을 확인하였고, 서버에서 채팅 데이터를 수신하여 word cloud 및 사용자, 요일, 감정 별 빈도수 그래프 생성 후 웹 서버에 파싱됨을 확인함.

​
