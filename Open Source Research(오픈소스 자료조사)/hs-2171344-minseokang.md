오픈소스소프트웨어 팀플 자료조사
---
<hr>


* __[Alf.io 오픈소스]__ (https://github.com/alfio-event/alf.io)
Alf.io는 고객의 개인 정보 보호, 보안 및 공정한 정책에 관심이 있는 이벤트 주최자를 위해 개발된 무료 오픈 소스 이벤트 참석 관리 시스템으로, 티켓 예약 처리를 주 목적으로 한다.
<br>

* __[ Alf.io 사용 전제 조건 ]__
  Alf.io를 빌드하고 실행하려면 Java 버전 17(예: Oracle, OpenJDK 또는 기타 배포판) 설치가 필요하다. 빌드 프로세스에는 JDK가 필요하다. PostgreSQL의 버전은 10 이상이어야 한다. 테이블을 생성하고 사용하는 데이터베이스 사용자는 슈퍼유저가 아니어야 한다. 그렇지 않으면 보안 정책 검사가 적용되지 않는다.
<br>

* __[ Alf.io의 특징 ]__
  첫 번째 특징은 보안이다. 사용자의 데이터를 중요하게 생각하기 때문에 Alf.io는 보안을 염두에 두고 구축되었다. HTTPS 프로토콜과 엄격한 콘텐츠 보안 정책 규칙을 사용하여 페이지를 제공한다. 두 번째 특징은 모바일 환경 구축을 위한 준비이다. Alf.io의 GUI는 "모바일 우선"인 Twitter Bootstrap 프레임워크를 기반으로 구축되었다. 세 번째 특징은 공정함이다. 활동을 계속 제어한다. 네 번째 특징은 다국어이다. 현재 이탈리아어, 영어, 독일어, 네덜란드어, 프랑스어, 터키어, 루마니아어 및 포르투갈어로 제공되므로 원하는 언어로 번역 및 사용이 가능하다. 다섯 번째 특징은 PCI를 준수한다는 것이다. Alf.io는 Stripe를 신용 카드 결제를 위한 게이트웨이로 사용함으로써, 서버에 민감한 데이터가 저장되지 않는다. 여섯 번째는 유연성으로, 결제 방식을 결정할 수 있다. 사용자가 티켓을 신용 카드 또는 페이팔로 선불로 결제하거나 은행 송금으로 후불로 결제할 수 있다. 혹은 행사 입구 데스크에서 결제도 가능하다. 일곱 번째는 측정 가능함이다. Google Analytics 계정을 만들고 메트릭을 구성하기만 하면 사용 가능하다. 모든 URL은 고유하고 출입하는 트래픽을 분석할 수 있다. 여덟 번째는 클라우드에서 사용 준비가 완료되었다는 것이다. Openshift, Pivotal Cloud Foundr, SAP Cloud Platform, Heroku, Google Kubernetes Engine, Clever Cloud 에서 이미 테스트를 완료했고 배포되었다.

<br>

* __[ Alf.io의 License ]__
 GPL 3.0 : 본 라이선스에 의거하여 전체 작업을 누구에게나 공개해야 한다. 독점 SW와 결합 불가능하며, 라이선스와 동일한 라이선스로 배포해야 한다.

<br>

* __[ 참고 ]__
 Apache License와 GPL 2.0으로 배포되는 코드는 결합 불가능하지만, 해당 오픈소스 라이선스는 GPL 3.0이므로 Apache License와 같이 사용 가능하다.

<br>

* __[ Alf.io 가 우리 서비스에서 하는 역할]__
유저로부터 예약 정보를 받아 예약자 정보 및 좌석 정보를 Kafka에게 전달한다.

<br>

* __[ Alf.io가 사용하는 언어 ]__
Java가 대부분을 차지고, 나머지는 Html, JavaScript 등으로 이루어져 있다.


