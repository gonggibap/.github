<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=header" width="100%" >


# 공기밥
공공기관이 찾는 로컬 찐 맛집! “**공기밥**”

공공기관의 업무추진비 데이터를 활용해 해당 지역의 맛집 정보를 제공하는 서비스

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
<img width="695" alt="공간데이터타입" src="https://github.com/user-attachments/assets/5959e7d9-0bfa-4830-82ea-0a4771d8b96b" />

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
![](https://i.imgur.com/JVGj9Pw.png)
#### 구성 요소
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
#### 특징
1. **고가용성**:
    - Auto Scaling Group과 Multi-AZ 구성을 통해 장애를 최소화
2. **보안 강화**:
    - WAF로 외부 트래픽 필터링, EC2, Aurora와 같은 민감한 리소스는 Private Subnet에 배치
3. **확장성**:
    - 트래픽 변화에 따라 인스턴스를 동적으로 확장/축소
4. **최적화**:
    - Read Replica를 활용하여 데이터베이스 성능 향상

#### 트래픽 흐름
1. 클라이언트 → **Route 53** → **WAF** → **ALB**
2. ALB → **Private Subnet의 Backend/Extension**
3. 데이터 요청 → **Aurora Database (Write: Primary, Read: Replica)**
## 4. ✔ MSA 아키텍쳐
### Spring 서버 및 DB를 기능별로 분리

MSA란 `MicroService Architecture`의 약자로, 기존의 Monolithic Architecture의 한계를 벗어나 애플리케이션을 느슨하게 결합된 서비스의 모임으로 구조화하는 서비스 지향 아키텍처(SOA) 스타일의 일종인 소프트웨어 개발 기법입니다.

기능을 크게 6가지로 분류하고, 서버와 데이터베이스를 각 기능에 맞게 분류하여 구현하였습니다.

| 기능     | Server           | DB             |
| ------ | ---------------- | -------------- |
| 사용자    | Member Server    | Member DB      |
| 주식     | Stock Server     | Stock DB       |
| 뉴스     | News Server      | News DB        |
| 뉴스 데이터 | News-Data Server | Hadoop         |
| 인증     | Auth Server      | Redis          |
| 챗봇     | News-AI Server   | AI DB & Hadoop |

### MSA 설계도

![](https://i.imgur.com/dW3dhTr.png)
![](https://i.imgur.com/kh0ktLZ.png)

저희는 `MSA` 를 통해 다음과 같은 장점을 가질 수 있었습니다.

1. 배포
    - 서비스별 개별 배포가 가능합니다.
    - 특정 서비스의 요구사항만을 반영하여, 빠르게 배포 가능합니다.
    - 특히, 젠킨스와 쿠버네티스, Mattermost로 이어지는 배포 파이프라인을 구축하여 빠르고 간편한 배포가 수행되게 하였습니다.
2. 확장
    - 특정 서비스에 대한 확장성(scale-out)이 유리합니다.
    - 클라우드 기반 서비스 사용에 적합합니다.
    - 특히, 뉴스와 뉴스 데이터(하둡 기반) 서버를 분리하여 최신 뉴스 데이터와 관련된 기능들을 빠르게 처리할 수 있게 했습니다.
3. 장애
    - 일부 장애가 전체 서비스로 확장될 가능성이 적습니다.
    - 부분적으로 발생하는 장애에 대한 격리가 수월합니다.
    - 특히, 한국투자증권의 실시간 가격 데이터와 대용량의 뉴스 데이터를 한 서버에서 처리할 경우 장애가 발생할 확률이 높은데, 이를 분리하여 처리했습니다.
4. 그 외
    - 새로운 기술을 적용하기 유연합니다.
    - 각각의 서비스에 대한 구조 파악 및 분석이 모놀리식 구조에 비해 쉽습니다.

### Feign Client를 이용한 서버 간 통신

MSA를 적용함으로써 서버들이 기능별로 분리됨에 따라 각 서버는 자신이 관할하는 DB에만 직접 접근할 수 있게 되었습니다. 그로 인해 자신이 관할하지 않는 DB의 데이터가 필요할 경우, 해당 DB를 담당하고 있는 서버에게 데이터를 요청해야합니다.  
저희는 서버 간 통신을 하기 위해 `Feign Client`를 사용하여 기존의 RestTemplate 보다 Rest API를 사용하는데 필요한 설정을 간소화하였고, 이로 인해 비지니스 로직에 더 집중할 수 있었습니다.

- Feign - Netflix 에서 개발된 Http client binder
- 웹 서비스 클라이언트를 보다 쉽게 작성하여 사용
- interface 를 작성하고 annotation 을 선언하여 사용
- `@EnableFeignClients` 을 통해 `@FeignClient`의 구현체를 구현
### NGINX Ingrees Controller

저희는 API Gateway Server를 NGINX로 활용하였습니다.

다음과 같은 규칙으로 URL 기반 라우팅을 수행하였습니다.
- 인증이 필요한 요청 URL의 경우 Ingress.yaml 에 정의
- 인증이 필요하지 않은 요청 URL의 경우 front-inress.yaml 에 정의

![](https://i.imgur.com/iUscTZW.png)

추가적으로 다음과 같은 기능들도 적용하였습니다.
- nginx ingress의 auth-url 옵션을 통해 auth 처리 후 라우팅
- tls 옵션을 통해 HTTPS 적용
- API Gateway용 CORS 헤더를 추가

``` yaml
apiVersion: networking.k8s.io/v1  
kind: Ingress  
metadata:  
  name: my-app-ingress  
  namespace: default  
  annotations:  
    nginx.ingress.kubernetes.io/auth-url: "http://${인증_URL}/api/auth/verify"  
    nginx.ingress.kubernetes.io/use-regex: "true"  
    nginx.ingress.kubernetes.io/enable-cors: "true"  
    nginx.ingress.kubernetes.io/cors-allow-origin: "http://localhost:5173, https://newstock.info"  
    nginx.ingress.kubernetes.io/cors-allow-methods: "PUT, GET, POST, DELETE, OPTIONS"  
    nginx.ingress.kubernetes.io/cors-allow-headers: "Authorization, Content-Type"  
    cert-manager.io/cluster-issuer: "letsencrypt-prod"  
    nginx.ingress.kubernetes.io/ssl-redirect: "true"  
spec:  
  tls:  
    - hosts:  
        - newstock.info  
      secretName: tls-secret   # 앞서 생성한 시크릿 이름  
  ingressClassName: nginx
```

## 5. Kubernetes

**쿠버네티스 아키텍쳐**

![](https://i.imgur.com/2xiuQm6.png)

저희는 MSA 서버들을 쉽게 관리 및 배포하기 위해 Kubernetes를 활용했습니다.
- **Member Service** : 회원 정보와 포인트 관련 비즈니스 로직 수행
- **Auth Service** : OAuth 관련 비즈니스 로직 수행
- **Stock Service** : 모의투자 관련 비즈니스 로직 수행
- **News Service** : 경제 뉴스와 관련된 비즈니스 로직 수행
- **AI Service** : LLM 챗봇과 차트 유사도에 관련된 비즈니스 로직 수행
- **Kafka Service** : SAGA (MSA의 트랜잭션 복구 패턴) 구조와 관련된 이벤트 처리 로직 수행
- **Redis Service** : 실시간 주가 정보와 회원의 Refresh Token(JWT) 저장 및 처리 로직 수행

### 오토 스케일링
- Deployment에서 Pod의 CPU 초기 사용량 및 오토 스케일링 시점을 기재합니다.
  
``` yaml
spec:
  containers:
  - name: server
    image: server
    resources:
      requests:
        cpu: "200m"
      limits:
        cpu: "500m"
```

- 지정해둔 CPU 사용량을 초과하면 Pod 수를 증가시켜 부하를 분산 시킵니다.

``` yaml
spec: 
  scaleTargetRef: 
    apiVersion: apps/v1 
    kind: Deployment 
    name: nginx-deployment 
  minReplicas: 1 # 최소 Pod 수 
  maxReplicas: 10 # 최대 Pod 수 
  metrics: 
  - type: Resource 
    resource: 
      name: cpu 
      target: 
        type: Utilization 
        averageUtilization: 50 # 평균 CPU 사용률 50%를 초과하면 스케일링
```
# 📚 프로젝트 산출물

## 1. 공기밥 서비스 (https://gonggibap.co.kr/)
![사이트](https://github.com/user-attachments/assets/aff4de95-00f1-4123-bd0f-ce552f179832)

## 2. 공기밥 익스텐션 (https://chromewebstore.google.com/detail/%EA%B3%B5%EA%B8%B0%EB%B0%A5-extension-%EB%A7%9B%EC%A7%91-%EA%B2%80%EC%83%89-%EC%84%9C%EB%B9%84%EC%8A%A4/poifnfdoponfeneednggfmdoabddncdk?hl=ko&utm_source=ext_sidebar)
![익스텐션](https://github.com/user-attachments/assets/de5f4979-0598-4dfe-a616-62b534431aa1)

## 3. ERD
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
