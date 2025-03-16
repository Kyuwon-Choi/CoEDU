# Coedu
<img width="525" alt="스크린샷 2025-02-27 오후 6 40 04" src="https://github.com/user-attachments/assets/47b17280-8605-405f-bae7-249cb20b30ed" />

🖥️실시간으로 소통하는 참여형 교육 WEB IDE 플랫폼 [Coedu]🖥️

## 목차

- [프로젝트 개요](#프로젝트-개요)
- [프로젝트 설명](#프로젝트-설명)
  1. [Backend Tech](#1-backend-tech)
  2. [Database ERD](#2-database-erd)
  3. [Architecture](#3-architecture)
- [기능 설명](#기능-설명)
  1. [회원 가입 및 로그인](#1-회원-가입-및-로그인)
  2. [홈 화면](#2-홈-화면)
  3. [IDE](#3-IDE)
  4. [마이 페이지](#4-마이-페이지)
- [기여](#기여)
  

## 프로젝트 개요

| 항목       | 내용                                          |
|------------|---------------------------------------------|
| 프로젝트 소개 | 실시간으로 소통하는 참여형 교육 WEB IDE 플랫폼 [Coedu]  |
| 개발 인원    | 7명 (프론트엔드 4명 + 백엔드 3명) |
| 개발 기간    | 2025. 01. 14 ~ 2025. 02. 28               |

## 프로젝트 설명

### 1. Backend Tech

## 기술 스택

| 기술             | 사용                             |
|------------------|--------------------------------|
| **Language**         | ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) |
| **Framework**        | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white) |
| **Database**         | ![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) |
| **Deploy**           | ![AWS EC2](https://img.shields.io/badge/Amazon%20EC2-%23FF9900.svg?style=for-the-badge&logo=amazon-ec2&logoColor=white)  ![AWS Elastic Beanstalk](https://img.shields.io/badge/AWS%20Elastic%20Beanstalk-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) |
| **API**              | ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-%23Clojure.svg?style=for-the-badge&logo=swagger&logoColor=white) |
| **Monitoring**       | ![Node Exporter](https://img.shields.io/badge/Node%20Exporter-%230077B5.svg?style=for-the-badge&logo=prometheus&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![AWS CloudWatch](https://img.shields.io/badge/AWS%20CloudWatch-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) |
| **CDN**             | ![AWS CloudFront](https://img.shields.io/badge/AWS%20CloudFront-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white) |
| **Cooperative Tool** | ![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) |
| **IDE**              | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) |


### 2. Database ERD

![408855779-8f4a3dfa-ab98-4796-a255-3262b709b7e1](https://github.com/user-attachments/assets/01e28622-5ad1-4ab4-8128-4fd06dec1480)


### 3. Architecture

<img width="532" alt="스크린샷 2025-03-16 오후 11 02 13" src="https://github.com/user-attachments/assets/7af9fe69-c478-4b7b-b194-b6e49842a3dc" />



## 기능 설명

### 1. 회원 가입 및 로그인

![coedu - 로그인](https://github.com/user-attachments/assets/9ef07cb6-5a9c-411a-902b-deceafab831c)


- **로그인**: 카카오 회원가입/로그인, jwt spring security, Aouth를 통한 인증-인가

### 2. 홈 화면

<div style="display: flex;">
  <img src="https://github.com/user-attachments/assets/1dcebeee-f9ae-403d-8740-a86d3018db60" alt="홈화면" loading="lazy"/>
  <img src="https://github.com/user-attachments/assets/8997fd02-ab28-43bd-bc28-166d4165ccf1" alt="일정" loading="lazy" />
</div>

- 교육자는 교실을 생성하여 학생들을 초대하고, 수업 진행을 위한 강의실을 생성할 수 있음
- 교실 참여자는 일정을 생성하고, 일정을 카카오 캘린더에 추가 및 관리 가능

### 3. IDE

![coedu게시글](https://github.com/user-attachments/assets/12422cd7-3a77-4bb1-a76a-153708adfb6e)

- 웹 상에서 실시간으로 코드를 작성할 수 있는 편집기 기능
- 실시간 채팅을 통해 양방향 소통 가능

### 4. 마이 페이지

![coedu 마이 페이지](https://github.com/user-attachments/assets/5c4edd86-e50d-40b5-8fdb-0079096d9ac5)


- 개인에게 부여된 초대 코드를 통해 교실 초대
- 초대 알림, 초대 수락/거절 알림 제공
- 다크/라이트 모드 테마 제공

## 기여

- **AWS 배포**: EC2와 배포 스크립트를 활용한 배포  
- **실시간 코드 편집기 개발**: STOMP,ProcessBuilder, AWS S3를 활용한 실시간 협업 IDE 구현 
- **강의실 기능 설계 및 개발**: 사용자별 강의실 관리 및 참여 기능 개발  
- **사용자 초대 기능 개발**: 개인 코드 기반 초대 기능 구현  
- **CDN 및 보안성 강화**: AWS CloudFront를 활용한 콘텐츠 전송 최적화 및 보안성 증가  

