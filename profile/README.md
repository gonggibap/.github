<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=header" width="100%" >


# 공기밥
공공기관이 찾는 로컬 찐 맛집! “**공기밥**”

공공기관의 업무추진비 데이터를 활용해 해당 지역의 맛집 정보를 제공하는 서비스

(삼성 청년SW아카데미 자율 프로젝트 **🏆우수상🏆**)

**배포 주소** : [https://gonggibap.co.kr](https://gonggibap.co.kr)

___

`SSAFY 11th 자율 PJT`

`개발기간: 24.10.14 ~ 24.11.21 (6주)`


![서비스 설명](https://github.com/user-attachments/assets/9d04755f-b97a-46b4-a893-b873c15033d3)


# 목차
1. [서비스 소개](#-서비스-소개)
2. [화면 소개](#-화면-소개)
3. [기술 스택](#-기술-스택)
4. [서비스 아키텍처](#-서비스-아키텍처)
5. [프로젝트 산출물](#-프로젝트-산출물)
6. [팀원 구성](#-팀원-구성)


---

# ✨ 서비스 소개
## 기획 배경

인터넷에 소개되는 맛집들은 대부분 광고, 홍보인 경우가 잦아 조사 결과 소비자의 피로도가 증가하고 있었습니다. 따라서 광고, 협찬 없는 진짜 로컬 맛집을 제공하고자 하였고, 이를 위해 공공기관의 업무추진비 데이터를 활용하기로 기획하였습니다. 

**AS-IS**
- 바이럴 마케팅으로 인한 정확한 정보 획득 어려움
- 소비자의 피로도 증가
- 로컬 맛집에 대한 수요

**TO-BE**
- 공공기관이 인증한 로컬 맛집 정보 제공
- 소비자의 만족도 향상
- 로컬 맛집 플랫폼으로의 성장

### 타켓
- 인터넷의 바이럴 마케팅에 피로감을 느끼는 사람
- 실제 로컬 찐 맛집을 찾고자 하는 사람




## 주요기능 🔍

<div align="left">

### 📌 공공기관 맛집 지도 기능

    - 공기밥은 업무추진비 데이터를 활용해 추출한 맛집을 지도를 통해 보여줍니다.
      - 마커 : 실제 위치를 확인할 수 있습니다.
      - 클러스터링 : 인접한 데이터를 그룹화 하여 요약
    - 음식점, 카페, 술집과 한식, 중식 등 카테고리별로 지도 데이터를 수정할 수 있습니다.

### 📌 맛집 상세정보 기능

    - 실제 업무추진비로 사용된 내역을 제공하여 사용자가 데이터를 직접 확인하고 믿을 수 있게 하였습니다.
    - 블로그 API를 통해 해당 맛집의 사용자 리뷰도 확인할 수 있습니다.
    - 사이트 내의 리뷰 서비스를 제공하고 있으며, 점수와 사진을 등록할 수 있습니다. 이때 유익한 리뷰의 사진 중 하나는 썸네일 사진으로 업데이트 됩니다.
    
### 📌 공기밥 익스텐션 기능
	- 카카오맵 웹에서 공기밥 서비스가 인증한 맛집을 표시하는 확장프로그램 제공합니다.
	- 크롬 익스텐션 스토어에서 익스텐션을 설치할 수 있습니다.

### 📌 편의 기능

    - 맛집 공유하기 : 공유 링크를 복사하여 카카오톡에 전송하면 해당 맛집의 썸네일 사진이 나오도록 구현하였습니다. 
    - 관심 맛집 : 로그인 이후 "내 지도에 추가하기" 버튼을 클릭시 나만의 맛집여지도를 만들 수 있습니다.
    - 다크 모드 : 사용자는 라이트모드/다크모드 를 선택하여 UI를 업데이트 할 수 있습니다.
    - 모바일 UI : 사용자는 서비스를 모바일 UI로도 이용할 수 있습니다. 이때, 제스처 기능 또한 제공됩니다.
</div>

# 💻 화면 소개

<details>
 <summary>📢 페이지 상세설명</summary>
 <div markdonw="1">

![슬라이드1](https://github.com/user-attachments/assets/fc6ebd49-f461-48ce-8750-db2bda70a40b)
![슬라이드2](https://github.com/user-attachments/assets/d882600f-bb70-4f97-90ce-96d6e62b7794)
![슬라이드3](https://github.com/user-attachments/assets/922690e6-c7be-4f8a-ab81-a37d67305ee8)
![슬라이드4](https://github.com/user-attachments/assets/5cad931f-3115-4fa4-8753-94f615333e28)
![슬라이드5](https://github.com/user-attachments/assets/69ee9028-3bd6-48ab-a1bc-16b6ba5f8aaa)
![슬라이드6](https://github.com/user-attachments/assets/f64e51b5-8f2c-48af-86cc-156a350cbf3e)
![슬라이드7](https://github.com/user-attachments/assets/0eba6d5f-6e26-401e-a676-b752af9a7f9b)
![슬라이드8](https://github.com/user-attachments/assets/19cb5b92-8877-4e70-99c5-e531426ce0c0)
![슬라이드9](https://github.com/user-attachments/assets/874e4e5b-1256-4439-ac33-3ba94beabf7c)
![슬라이드10](https://github.com/user-attachments/assets/7179020d-8075-43c4-8907-91167c1f7aa0)
![슬라이드11](https://github.com/user-attachments/assets/717ab1fa-40a4-4d45-841a-5f4bef09004b)
![슬라이드12](https://github.com/user-attachments/assets/a04a1054-d71d-47c3-a38e-2ea5bd6bfff1)
![슬라이드13](https://github.com/user-attachments/assets/c08ae48a-c39d-4b1c-8d3c-e434155eb124)
![슬라이드14](https://github.com/user-attachments/assets/f9fb139a-9725-4b20-ab42-a69a742e7a7d)
![슬라이드15](https://github.com/user-attachments/assets/bd2a5a1b-b86d-469e-8d14-1793f8d3b362)
![슬라이드16](https://github.com/user-attachments/assets/d1e76deb-235b-447d-b254-dbcdfb8b539c)
![슬라이드17](https://github.com/user-attachments/assets/fd55a949-06c4-4944-b0fb-4dc392247f5b)
![슬라이드18](https://github.com/user-attachments/assets/c5d3a556-b32a-48b7-89b2-c846d6fa3395)
![슬라이드19](https://github.com/user-attachments/assets/ce9a66d9-1fa9-4cf9-9ebe-6902ee3db5ef)
![슬라이드20](https://github.com/user-attachments/assets/9404eaaa-dc3e-4500-aed4-b435826671a2)
![슬라이드21](https://github.com/user-attachments/assets/7d8ca7b5-ecb7-41db-a5b4-2570a1d772f3)
![슬라이드22](https://github.com/user-attachments/assets/c65ba35f-4beb-446a-9c44-25d6dd04f502)
![슬라이드23](https://github.com/user-attachments/assets/c178b97f-f69d-4fef-a5a1-ef022c82c0a5)


 </div>
</details>


# 🛠 기술 스택
<div align="center">

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) 
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React-Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=ReactQuery&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Infrastructure

![Jenkins](https://img.shields.io/badge/jenkins-D24939.svg?style=flat&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=Amazon S3&logoColor=white">
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white">
<img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=Amazon RDS&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white">

### Backend

![Spring](https://img.shields.io/badge/spring-6DB33F.svg?style=flat&logo=spring&logoColor=white)
<img src ="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=Spring-Security&logoColor=white">
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=OpenAI&logoColor=white">
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white">
![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=JSON%20web%20tokens)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)



### DB

![Redis](https://img.shields.io/badge/Redis-FF4438.svg?style=flat&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat&logo=mysql&logoColor=white)

### TOOL
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white">
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=GitLab&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitBook-BBDDE5?style=flat&logo=GitBook&logoColor=white">
<img src="https://img.shields.io/badge/Mattermost-0058CC?style=flat&logo=mattermost&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white">

### Data

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)

</div>

# 📌 기술 상세 설명

## 1. 전체적인 아키텍쳐
![](https://i.imgur.com/1pffjb5.png)

## 2. 공간 인덱싱 성능 조회
<img width="100%" alt="공간데이터타입" src="https://github.com/user-attachments/assets/5959e7d9-0bfa-4830-82ea-0a4771d8b96b" />

### 공간 인덱스란?
> 공간 데이터는 **위치 정보**를 저장할 수 있는 데이터 타입입니다.  
MySQL은 다음과 같은 공간 데이터 타입과 함수들을 지원하여 효율적인 데이터 조회를 가능하게 합니다.

- 공간 데이터 타입: `Point`, `Polygon` 등
- 공간 함수: `ST_Contains`, `ST_Distance` 등

### 기존 방식의 문제점 (BETWEEN 조건)
``` sql
SELECT *
FROM restaurant
WHERE latitude BETWEEN 37.560997 AND 37.568698
AND longitude BETWEEN 126.994728 AND 127.006782;
```
- BETWEEN 조건을 활용하면 DB에 식당의 수가 1,000,000개가 존재한다면 이를 모두 검색하는 **FULL SCAN** 방식으로 식당 데이터가 늘어난다면 조회 성능 저하가 발생한다.

### Decimal Type -> Point Type
- 기존의 latitude, longitude 두 개의 Decimal 타입 필드를 하나의 Point 타입 필드로 변경할 수 있습니다.
- MySQL은 Point와 같은 공간 데이터 타입에서 공간 함수를 사용할 수 있습니다. **BETWEEN** 조건 대신 **공간 함수(ST_Contains)를 사용해 특정 범위 내 식당을 조회할 수 있습니다.
- 공간 데이터 타입은 공간(SPATIAL) 인덱스를 적용해 FULL SCAN 방식 보다 조회 성능

[자세한 내용](https://www.notion.so/MySQL-127dfffbb40780308ee3d29ef1d37906)

## 3. 고가용성 시스템 구축
![고가용성 시스템](https://i.imgur.com/JVGj9Pw.png)

### 구성 요소
1. **Route 53**
    - **역할**: 사용자 요청을 최초에 처리하는 DNS 서비스
    - **기능**: 트래픽을 WAF로 라우팅
2. **AWS WAF**
    - **역할**: 서비스의 악의적인 요청을 필터링.
    - **기능**: SQL Injection, XSS 같은 보안 위협을 방지하고 악성 트래픽을 차단함
3. **Application Load Balancer (ALB)**
    - **역할**: 사용자 트래픽을 EC2 인스턴스에 분산하고 장애 발생 시 스탠바이 인스턴스로 라우팅
    - **기능**: Auto Scaling Group 내의 백엔드 인스턴스로 요청 전달.
4. **Private Subnet**
    - **구성**:
        - **Backend & Extension**:
            - Auto Scaling Group으로 주요 애플리케이션 로직 처리
        - **Standby Instance**:
            - 장애 발생 시 대체 역할
        - **Aurora Database**:
            - 데이터 저장소로 Write 작업은 Primary, Read 작업은 Read Replica에서 처리
### 특징
1. **고가용성**:
    - Auto Scaling Group과 Multi-AZ 구성을 통해 장애를 최소화
2. **보안 강화**:
    - WAF로 외부 트래픽 필터링, EC2, Aurora와 같은 민감한 리소스는 Private Subnet에 배치
3. **확장성**:
    - 트래픽 변화에 따라 인스턴스를 동적으로 확장/축소
4. **최적화**:
    - Read Replica를 활용하여 데이터베이스 성능 향상

### 트래픽 흐름
1. 클라이언트 → **Route 53** → **WAF** → **ALB**
2. ALB → **Private Subnet의 Backend/Extension**
3. 데이터 요청 → **Aurora Database (Write: Primary, Read: Replica)**

## 4. 데이터 수집   
다음과 같은 흐름으로 업무추진비 데이터를 수집
### 1. 서울, 광주 30개 구 데이터 수집
- 각각의 구청에서 업무추진비가 공개되어 있음
- 예시 사이트 : [서울특별시 중구 업무추진비](https://www.junggu.seoul.kr/content.do?cmsid=15383&exclude=Y)

### 2. PDF, Excel파일 등 파일 전처리
- 업무추진비에서 수집되는 대부분의 데이터는 pdf, Excel파일 형식이어서 python 라이브러리인 `pandas` 및 `pdfplumber`를 활용하여 excel파일 및 pdf파일을 각각 csv파일로 형식 변환

### 3. OpenAI 활용 전처리
- 많은 수의 식당을 일일히 수작업으로 하기는 현실적으로 힘드므로 OpenAI API를 활용해 전처리 자동화
- 사용 모델 : **GPT 4o-mini**

### 4. Kakao Map API 활용 추가 데이터 수집
- 식당 정보(업종, 전화번호 등), 위경도 등 추가적인 데이터를 수집하기 위해 Kakao Map API 활용

### 5. 데이터 적재
- 최종적으로 식당 21,150곳, 사용내역 163,736건 수집

## 5. Extension 개발
- 공기밥 Extension은 공기밥 서비스에서 제공하는 맛집 정보를 카카오맵에서 조회하기 편하게 익스텐션 개발
- 카카오맵에서 맛집 검색 시 나오는 공기밥 이모티콘을 클릭하거나 맛집 상세페이지에서 팝업으로 등장하는 `공기밥에서 방문 횟수 확인하기` 클릭 시 공기밥 서비스로 접속 가능하여 서비스의 접근성 향상 및 유입 유저수 증가
<img width="1582" alt="image" src="https://github.com/user-attachments/assets/405af9a7-6cd6-4702-99c4-83512bf404f4" />
<img width="1582" alt="image" src="https://github.com/user-attachments/assets/33b65fe5-bcc8-4c24-a698-7a7a136e392b" />
<img width="1582" alt="image" src="https://github.com/user-attachments/assets/54dd45d4-bff8-4a1b-84b0-eddb29104721" />



## 6. 성과 및 팀 문화
### 개발 플로우
![](https://i.imgur.com/CJfkTue.png)

### 지속적인 홍보
![](https://i.imgur.com/cyJXrl3.png)
![](https://i.imgur.com/gHfqm9T.png)
![](https://i.imgur.com/rjRdMGO.png)

> 여러 홍보 수단을 사용해 해당 서비스의 프로모션을 진행한 모습 </br>
> 실제로 링크드인 게시물 게시 이후에는 트래픽이 꽤 많이 발생하였음

### 사용자 트래픽 분석

![](https://i.imgur.com/nI3Ava8.png)
![](https://i.imgur.com/cP7Qxl4.png)
![](https://i.imgur.com/Jb0p6ob.png)

> 다양한 프로모션 이후에 실제 트래픽이 발생하여 </br>
> MAU는 `330명`을 달성하였으며, 재방문자 수는 `47명`을 달성하였음

![](https://i.imgur.com/LaGU4CO.png)
![](https://i.imgur.com/EOnZnet.png)


> 해당 트래픽을 분석한 결과 모바일의 비중이 높은 것을 확인하였음 </br>
> 이후 모바일 UI를 출시하는 등 계속해서 사용자 경험을 향상시켰음

### 기술 세미나

![](https://i.imgur.com/vQXYnvy.jpeg)

저희 팀은 **함께 성장**하는 문화를 지향하여 프로젝트를 진행했습니다.
프로젝트를 진행하는 동안 배운 기술과 관심사를 **서로 공유**하며 개인의 성장 뿐만이 아니라 **팀의 성장을 유도**하였습니다.

- 다양한 주제를 다루는 **기술 세미나**를 격주마다 진행하여 팀원 간의 기술적 이해도를 향상시켰습니다.
- **질문과 토론**을 통해 서로 다른 포지션의 팀원들도 **시야를 확장**할 수 있었고, 함께 성장하는 발판이 되었습니다.

**세미나 주제**
- 자바의 멀티쓰레드
- 데이터베이스 샤딩
- 공간 인덱싱
- RAG 성능 향상 기법
- 컨테이너 가상화 기술과 도커
- MSA vs Monolithic 아키텍처

[자료 링크](https://drive.google.com/drive/folders/11Hh5dCcfakOTE4eBqaMN6pRWv76_ueex?usp=sharing)

# 📚 프로젝트 산출물

## 1. 🍚 공기밥 서비스

|    공기밥 웹 서비스    |    공기밥 Chrome 익스텐션    |
|:-----------------:|:-------------------------:|
| ![웹 서비스](https://github.com/user-attachments/assets/aff4de95-00f1-4123-bd0f-ce552f179832) | ![익스텐션](https://github.com/user-attachments/assets/de5f4979-0598-4dfe-a616-62b534431aa1) |
| [🔗 사이트 방문하기](https://gonggibap.co.kr/) | [🔗 익스텐션 설치하기](https://chromewebstore.google.com/detail/%EA%B3%B5%EA%B8%B0%EB%B0%A5-extension-%EB%A7%9B%EC%A7%91-%EA%B2%80%EC%83%89-%EC%84%9C%EB%B9%84%EC%8A%A4/poifnfdoponfeneednggfmdoabddncdk?hl=ko&utm_source=ext_sidebar) |



## 2. ERD
![ERD](https://i.imgur.com/FmmsHJ2.png)

# 👨‍👨‍👧‍👦 팀원 구성

|       BackEnd       |       BackEnd       |       Infra        |       Infra        |
|:------------------:|:-------------------:|:-----------------:|:------------------:|
| <img src="https://avatars.githubusercontent.com/u/101318473?v=4" width=100px alt="고민호"/> | <img src="https://avatars.githubusercontent.com/u/62554639?v=4" width=100px alt="박선홍"/> | <img src="https://avatars.githubusercontent.com/u/105180696?v=4" width=100px alt="손지석"/> | <img src="https://avatars.githubusercontent.com/u/92447290?v=4" width=100px alt="남보우"/> |
| [고민호](https://github.com/MinhoKK) | [박선홍](https://github.com/chestnut1717) | [손지석](https://github.com/sonjiseokk) | [남보우](https://github.com/Nbowow) |

|       FrontEnd      |       FrontEnd      |       기획         |
|:------------------:|:-------------------:|:-----------------:|
| <img src="https://avatars.githubusercontent.com/u/123948643?v=4" width=100px alt="이명욱"/> | <img src="https://avatars.githubusercontent.com/u/156316110?v=4" width=100px alt="임준희"/> | <img src="https://avatars.githubusercontent.com/u/91084695?v=4" width=100px alt="박준엽"/> |
| [이명욱](https://github.com/LEEMYEONGUK) | [임준희](https://github.com/ljjunh) | [박준엽](https://github.com/JuneYub) |


<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=footer" width="100%" >
