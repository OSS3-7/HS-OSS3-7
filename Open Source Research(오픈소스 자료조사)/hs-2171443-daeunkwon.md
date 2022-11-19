### **DB 관련 오픈소스 자료조사**

오픈소스: MySQL

1. 오픈 소스 설명
- MySQL
    - MySQL은 구조화된 쿼리 언어(SQL)를 기반으로 하는 오픈소스 관계형 데이터베이스 관리 시스템(RDBMS)
    - 웹사이트 및 애플리케이션을 위한 기본 관계형 데이터 스토리지 솔루션
- 기능
    - 만들 수 있는 서버, 사용자 또는 데이터베이스 수에 제한 X
    - 웹사이트, 웹 애플리케이션 및 모바일 어플 데이터를 저장
    - Google 클라우드 플랫폼, Amazon Web Services, Rackspace Cloud 및 Azure 등의 서비스를 사용하면 웹 브라우저를 사용하여 데이터베이스 생성 및 관리 가능
- 일반적인 용도
    - 웹사이트, 웹 애플리케이션용 데이터 저장
    - 모바일 앱용 데이터 저장
    - 기업 애플리케이션용 데이터 저장
    - 고객 또는 클라이언트의 DB생성
    - 의료, 금융 정보 저장
- 장점
    - 대규모 사용자 커뮤니티가 있으면 다양한 상업적 지원 옵션 사용 가능
    - 대규모 웹 사이트용 데이터를 저장하기에 적합하고 발생할 수 있는 트래픽 처리율이 높고 안전하다.
- 라이선스
    - GPL
- 언어
    - C, C++, SQL, PHP 등
    
1. 해당 오픈소스 선정 이유
- 위에서 말한 대규모 사용자 커뮤니티가 곧 학교에서 운영하는 전자출결 웹 또는 앱 어플리케이션인데, 이런 대규모의 사용자(학생)들의 데이터를 효과적으로 저장하고 관리할 수 있는 시스템이라는 생각이 들었고, 일시적으로 접속하다보면 트래픽이 커질 수 있는데 이를 효과적으로 처리 가능한 시스템이라고 하여 학생들의 음성 DB 저장 및 관리에 적합하다고 생각함.
1. 참고 자료 Link
    - [https://www.websiterating.com/ko/web-hosting/glossary/what-is-mysql/](https://www.websiterating.com/ko/web-hosting/glossary/what-is-mysql/)
    - [https://github.com/mysql/mysql-server](https://github.com/mysql/mysql-server)

====================================

- MySQL에 음성 데이터를 저장할 수 있는가(별도 조사)
    - DB에는 음성 파일의 경로(path정보)를 저장해두고 실제 데이터 전송 시에는 path정보를 가지고 파일 저장소에 저장된 데이터를 보내주는 방식이 있다고 함
    - 이미지 데이터나 음성 데이터 모두 저장 시에는 이진 파일 형태로 저장되므로 상관 없음
        
        용량이 큰 파일은 따로 저장하고 path 정보를 따로 가지고 있는 게 좋음
        
- 수연 선배님이 작성한 서비스 구상도에서
    - 학생의 수강 중 수업 정보(텍스트), 학교 좌석 배치도(텍스트+이미지), 학생 정보 관련 DB 모두 MySQL로 처리 가능
    
    * DB관련 오픈소스
    PostgreSQL
    :  PostgreSQL is released under the PostgreSQL License, a liberal Open Source license, similar to the BSD or MIT licenses.
    MySQL(GPL 2.0)
    MariaDB(GPL 2.0)
    MongoDB(AGPL 3.0 -> SSPL(Open Source X)
    HeidiSQL(GPL 2.0)
   
