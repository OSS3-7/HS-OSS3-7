### OSS Team Project_ Week11 개인별 과제

##### 2171443 권다은

------

Main idea: 전자출결 + 강의실 좌석 예약
Sub idea: 음성 인식을 통한 수업 내용 정리

*Seat_Reservation_System 위주로 진행함

조건1) 계획한 서비스의 방향성을 고려해야함
조건2) 마크다운문서(.md)로 작성해야함

------

> 오픈 소스 설명

1. 기능 정의

- 회원 가입 & 로그인
  - admin, user
  - 학교 이메일 인증

1. 기술 스펙

   1) FE

   - 안드로이드, iOS, Firebase

   2) BE

   - Spring Boot, JPA, MySQL, Redis, JWT

   3) DevOps(Development Operations)

   - 도커, 젠킨스 CI/CD, Nginx, AWS(EC2, RDS, S3)


1. LICENSE

   - MIT License

2. Languages

   - Java, CSS, HTML

3. Server Architecture

   ![server architecture](C:\Users\user\Desktop\server architecture.png)

4. 강의실 자리 예약 시스템 구조

- 강의실 별 자리 지정

- 시간순으로 예약 내역이 기록됨

- 노쇼 관련(출튀 방지)

  - QR 코드 또는 GPS로 파악
  - 학교 승인이 된다면, 학교 api로 파악

- 시간제(계속 사용하려면 연장가능, 6시간)

  ​

> 오픈 소스 선정 이유

계획했던 서비스와 가장 부합.



> Source Link

https://github.com/hs-2171443-daeunkwon/Seat-Reservation-System.git

