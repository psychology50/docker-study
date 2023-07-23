# docker-study
🐋 Docker를 정복하기 위한 스터디입니다.<br/>

### 🕖 기간
매주 일요일 19:00~21:00

### 스터디원
- [양재서](https://github.com/psychology50)
- [최희진](https://github.com/heejinnn)
- [임태규](https://github.com/TaeKyuIm)
- [조예림](https://github.com/J0YERIM)

### 진행 방식
1. 매주 2장씩 각자 공부한 내용을 정리합니다.
2. 스터디 당일에 챕터 별 발표자를 랜덤으로 뽑습니다.
3. 발표자는 질문자의 질문에 적절한 답을 하지 못한 경우, git issue에 내용을 보완합니다.

## 1부. 도커 컨테이너와 이미지 이해하기
### 1장. 시작하기 전에
- 발표자 : 양재서

|진행 여부|챕터|
|:---:|:---|
|✔️| 1.1 컨테이너가 IT 세상을 점령한 이유 |
|✔️| 1.2 대상 독자 |
|✔️| 1.3 실습 환경 구축하기 |
|✔️| 1.4 바로 활용하기 |

### 2장. 도커의 기본적인 사용법
- 발표자 : 양재서

|진행 여부|챕터|
|:---:|:---|
|✔️| 2.1 컨테이너로 Hello World 실행하기 |
|✔️| 2.2 컨테이너란 무엇인가? |
|✔️| 2.3 컨테이너를 원격 컴퓨터처럼 사용하기 |
|✔️| 2.4 컨테이너를 사용해 웹 사이트 호스팅하기 |
|✔️| 2.5 도커가 컨테이너를 실행하는 원리 |
|✔️| 2.6 연습 문제: 컨테이너 파일 시스템 다루기 |

### 3장. 도커 이미지 만들기
- 발표자 : 조예림

|진행 여부|챕터|
|:---:|:---|
|✔️| 3.1 도커 허브에 공유된 이미지 사용하기 |
|✔️| 3.2 Dockerfile 작성하기 |
|✔️| 3.3 컨테이너 이미지 빌드하기 |
|✔️| 3.4 도커 이미지와 이미지 레이어 이해하기 |
|✔️| 3.5 이미지 레이어 캐시를 이용한 Dockerfile 스크립트 최적화 |
|✔️| 3.6 연습 문제 |

### 4장. 애플리케이션 소스 코드에서 도커 이미지까지
- 발표자 : 임태규

|진행 여부|챕터|
|:---:|:---|
|✔️| 4.1 Dockerfile이 있는데 빌드 서버가 필요할까? |
|✔️| 4.2 애플리케이션 빌드 실전 예제: 자바 소스 코드 |
|✔️| 4.3 애플리케이션 빌드 실전 예제: Node.js 소스 코드 |
|✔️| 4.4 애플리케이션 빌드 실전 예제: Go 소스 코드 |
|✔️| 4.5 멀티 스테이지 Dockerfile 스크립트 이해하기 |
|✔️| 4.6 연습 문제 |

### 5장. 도커 허브 등 레지스트리에 이미지 공유하기
- 발표자 : 최희진

|진행 여부|챕터|
|:---:|:---|
|| 5.1 레지스트리, 리포지터리, 이미지 태그 다루기 |
|| 5.2 도커 허브에 직접 빌드한 이미지 푸시하기 |
|| 5.3 나만의 도커 레지스트리 운영하기 |
|| 5.4 이미지 태그를 효율적으로 사용하기 |
|| 5.5 공식 이미지에서 골든 이미지로 전환하기 |
|| 5.6 연습 문제 |

### 6장. 도커 볼륨을 이용한 퍼시스턴트 스토리지
- 발표자 : 조예림

|진행 여부|챕터|
|:---:|:---|
|| 6.1 컨테이너 속 데이터가 사라지는 이유 |
|| 6.2 도커 볼륨을 사용하는 컨테이너 실행하기 |
|| 6.3 파일 시스템 마운트를 사용하는 컨테이너 실행하기 |
|| 6.4 파일 시스템 마운트의 한계점 |
|| 6.5 컨테이너 파일 시스템은 어떻게 만들어지는가? |
|| 6.6 연습 문제 |

<br/>

## 2부. 컨테이너로 분산 애플리케이션 실행하기
### 7장. 도커 컴포즈로 분산 애플리케이션 실행하기
- 발표자 : 조예림

|진행 여부|챕터|
|:---:|:---|
|| 7.1 도커 컴포즈 파일의 구조 |
|| 7.2 도커 컴포즈를 사용해 여러 컨테이너로 구성된 애플리케이션 실행하기 |
|| 7.3 도커 컨테이너 간의 통신 |
|| 7.4 도커 컴포즈로 애플리케이션 설정값 지정하기 |
|| 7.5 도커 컴포즈도 만능은 아니다 |
|| 7.6 연습 문제|

### 8장. 헬스 체크와 디펜던시 체크로 애플리케이션의 신뢰성 확보하기
- 발표자 : 양재

|진행 여부|챕터|
|:---:|:---|
|| 8.1 헬스 체크를 지원하는 도커 이미지 빌드하기 |
|| 8.2 디펜던시 체크가 적용된 컨테이너 실행하기 |
|| 8.3 애플리케이션 체크를 위한 커스텀 유틸리티 만들기 |
|| 8.4 도커 컴포즈에 헬스 체크와 디펜던시 체크 정의하기 |
|| 8.5 헬스 체크와 디펜던시 체크로 복원력 있는 애플리케이션을 만들 수 있는 이유 |
|| 8.6 연습 문제|
