https://github.com/scouter-project/scouter
모니터링 오픈소스
모니터링 시스템은 프로젝트 또는 프로그램에서 발생하는 활동을 정기적으로 관찰하고 기록하는 것
또한 프로젝트의 모든 측면에 대한 정보를 일상적으로 수집하는 프로세스
즉, 강의실에서 학생들의 출석 및 활성을 실시간으로 모니터링 하기 위한 시스템입니다.
라이센스는 Apache Lucebse를 사용합니다
선정 이유 : 웹 기반이 아닌 이클립스 기반의 애플리케이션 클라이언트로 빠른 반응 속도로 실시간 모니터링에 적합함
또한 간단한 설치와 한글을 지원합니다.
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3e9628a9-4ace-4e4a-8107-0bf48cc45b57/Untitled.png)
위의 표를 보았을 때 사용자에 대한 지표로 활성 사용자, 최근 사용자와 오늘 방문자를 확인할 수 있습니다.
사용자는 시스템에서 응용 프로그램 서비스를 사용하고 서비스는 시스템에서 리소스를 사용합니다.
웹 API : HTTP 프로토콜을 통해 카운터, XLog, 프로필 및 기타 성능 메트릭을 가져오기 위한 스카우터 웹 API입니다.
모듈로는 Agent, Java Agent, Host Agent, Server, Client, ... 등이 존재합니다

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
