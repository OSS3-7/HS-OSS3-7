Promatheus오픈소스(https://github.com/prometheus/prometheus)
Promatheus는 메트릭 기반의 오픈소스 모니터링 시스템이며 ELK와 같은 로깅이 아니라, 
대상 시스템으로부터 각종 모니터링 지표를 수집하여 저장하고 검색할 수 있는 시스템입니다, 
또한 Cloud native Computing Foundation사에서 만든 오픈소스입니다.

Promatheus 사용 가능 조건
promatheus는 빌드하고 실행하려면 GO언어의 설치가 필요합니다. 

Promatheus 라이센스 
Apache License 2.0를 사용합니다.

Promatheus가 우리 서비스에서 하는 역활
모니터링에 대한 결과 정보를 User에 전달합니다.

Promatheus의 특징
첫 번째 특징은 고차원 데이터 모델을 구현, 시계열은 메트릭 이름과 Key-value 쌍으로 식별됨, 두 번째 특징, 유연한 쿼리 언어인 PromQL을 통해 성능 분석, 실시간 경고도 가능합니다, 
세 번째 특징 구조가 간단해서 운영이 쉽고, 강력한 쿼리 기능을 가지고 있으며, Grafana를 통한 뛰어난 데이터 시각화를 지원합니다. 
네 번째 특징으로는 Promatheus는 안정성을 추구하기에 각 서버에 독립적이며 로컬 저장소에만 의존합니다. 또한 많은 클라이언트 라이브러리들도 존재합니다. 
다섯 번째 특징 Pulling 방식입니다, Promatheus는 Taget System에서 메트릭을 수집하는 방식으로 Pulling 방식을 사용하는데, Promatheus는 주기적으로 Exporter로 부터 메트릭을 읽어와서 수집하는 방식입니다, 보통 모니터링 시스템의 에이전트들은 에이전트가 모니터링 시스템으로 메트릭을 보내는 Push 방식을 사용합니다, 특히 Push 방식은 서비스가 오토 스켈링 등으로 가변적일 경우에 유리합니다, Pulling 방식은 모니터링 대상이 가변적을 변경될 경우, 모니터링 대상의 IP 주소들을 알 수 없기 때문에 어려운 점이 존재합니다. 
여섯 번째 특징 Metric 수집, 수집하려는 대상 시스템이 Target System입니다. MySQL이나, Tomcat또는 VM과 같이 여러가지 자원이 모니터링 대상이 될 수 있습니다. 이 대상 시스템에서 메트릭을 Promatheus로 전송하기 위해서는 Exporter라는 것을 사용합니다. 



https://github.com/rinaldoclemente/Airplane-Seats-Reservation
비행기 좌석 예약 관리 웹사이트,
직사각형 패턴(6x10자석) 예약된 좌석(빨간색), 예약 안된 자석(녹색) 등 다양한 색상으로
보여주는 좌석 배치도를 볼 수 있음. 홈 페이지에는 총 좌석 수, 예약된, 안된 자석 표시
예약은 사이트에서 등록 or 인증을 통해서만 가능(유효한 이메일 등 서버에서 등록을 방지함)
실시간 업데이트, 서버가 인지하고 있는 모든 장소의 실제 상태 보여주는 페이지 존재
인증 후 제한시간안에 작업 완료 해야함(2분)

https://github.com/superbly/Library_alpha
대전대학교에서 만든 도서관 좌석 예약 APPLICATION, open source
회원가능 및 로그인 기능, 
메인 화면에 로그인 시 바코드 생성 > 현재 열람실 입장 시 모바일 학생증 로그인 필요,
즉 이 앱에 연동 가능. 
예약했던 열람실의 좌석번호와 남은 시간만 보여주며 이름/학번까지 학사정보 출력
좌석 예약 코드, 좌석 이동 코드, 좌석 반납, 연장 코드 등 다양하게 이용가능

https://github.com/sooftware/kospeech
음성 언어를 컴퓨터가 해석해 그 내용을 문자데이터로 전환하는 처리를 말함 
STT(Speech-to-Text)
2010년대 들어서면서 딥러닝 기분 인식 오류 20% 향상
대부분 오픈소스 STT모델들은 영어에 한정, KoSpeech는 한국어 음성 검증
한국어 자연어 처리 딥 러닝 라이브러리 PyTorch를 기반으로 하는 모듈식의 확장 가능한 종단 간 한국어 자동 음성 인식 툴킷입니다.
Input을 예상할 수가 없음 > 거의 무한한 주제, 문맥, 노이즈 등에 따른 무한한 경우의 수가 존재
최근 딥러닝의 발전으로 상당한 개선이 이루어짐
Deep Learning Boom 음성인식 방법, End-to-End 학습
음성 전처리 > 특징 추출 > 득징 to 문장
즉, 그냥 통째로 Input, Output넣어서 문법과 발음까지 한꺼번에 모두 학습
자연어처리 분야에서 제안된 RNN기반 Seq2seq를 음성인식에 적용

https://songys.github.io/2021Langcon/data/%5BLangCon2021%5D%20Korean-Speech-Recognition.pdf Kospeech관련 PPT

https://github.com/react-native-voice/voice
ios 및 Android 지원, 온라인, 오프라인 지원
plug in가능

https://github.com/coqui-ai/STT
딥러닝 실행, 생산과 연구에서 테스트 통과, 설치 부피 작음, 다양한 프로그래밍 언어 binding
