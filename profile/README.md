<div align="center">
  
<img width="100" height="100" alt="logo" src="https://github.com/user-attachments/assets/b1c194bb-48e1-4328-8612-a2e22295a8ef" />

### AI 기반 부트캠프 비교·추천 서비스, SOFTWARE CAMPUS

[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?logo=github-actions)](https://github.com/features/actions)
[![ArgoCD](https://img.shields.io/badge/GitOps-ArgoCD-EF7B4D?logo=argo)](https://argoproj.github.io/cd/)
[![AWS EKS](https://img.shields.io/badge/Infrastructure-AWS%20EKS-FF9900?logo=amazon-aws)](https://aws.amazon.com/eks/)

[🌐 서비스 바로가기](https://www.softwarecampus.co.kr) | [📖 API 문서](#) | [📊 모니터링](#)

</div>

---

## 📋 목차

- [프로젝트 소개](#-프로젝트-소개)
- [서비스 미리보기](#-서비스-미리보기)
- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [시스템 아키텍처](#-시스템-아키텍처)
- [팀 소개](#-팀-소개)

---

## 🎯 프로젝트 소개

### 배경

**문제 인식**: 소프트웨어 개발 교육시장의 지속적 성장에도 불구하고 교육과정 정보 불충분

**시장 현황**
- SW 개발 교육시장 2028년 1,200조 예상 (2배 성장)
- 국내 에듀테크 2025년 10조원 규모
- 국가 예산 배정 증가 (2021년 2,224억 → 2025년 4,781억)

### 솔루션

**AI 기반 분석**을 통해 개인의 목표와 역량에 가장 적합한 IT 부트캠프를 추천·비교하는 커리어 의사결정 지원 서비스

### 핵심 가치

- 🎓 **신뢰성**: 수료증 OCR 자동 검증 + 광고성 후기 제한
- ⚙️ **편의성**: AI 비교·추천 서비스 + 부트캠프 과정 정보 종합 비교
- 🔍 **투명성**: 커리큘럼 정보 일원화 + 기술 스택, 학습 범위, 기간, 난이도 제공

---

## 📸 서비스 미리보기

### 메인 화면
<p align="center">
  <img width="1512" height="823" alt="SCR-20260118-tdrp" src="https://github.com/user-attachments/assets/1003bb79-7598-4383-af9b-144856fb369c" />

</p>

### 핵심 기능


| 부트캠프 비교 | AI 맞춤 추천 | 관리자 대시보드 |
|:---:|:---:|:---:|
| ![비교](docs/images/compare.png) | ![AI](docs/images/ai.png) | ![dashboard](docs/images/ai.png) |
| 장바구니 기반 비교 | 개인 맞춤형 추천 | 다양한 통계 제공 |

---

## ✨ 주요 기능

### 1️⃣ 실제 수료생의 생생한 후기
- 수료증 OCR 자동 검증으로 **허위 후기 원천 차단**
- 검증된 후기만 제공 → 신뢰성 확보

### 2️⃣ 각기 다른 커리큘럼 통일
- 커리큘럼 법주화, 용어 통일, 산재된 커리큘럼 통합
- **장바구니 기반 비교 페이지**로 편의성 강화

### 3️⃣ AI 개인 맞춤 추천 서비스
- 법주화된 커리큘럼 속 선택의 자유
- AI를 통한 개인 맞춤형 추천
- **장바구니 담기** → **비교 필요?** → **AI 추천 선택**

### 4️⃣ 교육 관리 편의성
- 수강자 모집을 위한 기능 지원
- 간편한 자료입력을 통한 요점 가능

---

## 🛠 기술 스택

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge)
![OAuth2](https://img.shields.io/badge/OAuth2-000000?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

### AI
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white)

### Infrastructure
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![AWS EKS](https://img.shields.io/badge/AWS_EKS-FF9900?style=for-the-badge&logo=amazon-eks&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![AWS Route53](https://img.shields.io/badge/Route53-8C4FFF?style=for-the-badge&logo=amazon-route53&logoColor=white)
![AWS ALB](https://img.shields.io/badge/AWS_ALB-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS ACM](https://img.shields.io/badge/AWS_ACM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Ingress](https://img.shields.io/badge/Ingress-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Load Balancer](https://img.shields.io/badge/Load_Balancer-2496ED?style=for-the-badge)

### CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

### Observability
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=for-the-badge)
![Tempo](https://img.shields.io/badge/Tempo-F46800?style=for-the-badge)

---

## 🏗 시스템 아키텍처


### 애플리케이션 아키텍처

<img width="3271" height="1618" alt="AA" src="https://github.com/user-attachments/assets/903caeb9-7f55-4684-ae7a-f76946a7a89c" />

### 클라우드 인프라 아키텍처

<img width="3644" height="1377" alt="IA" src="https://github.com/user-attachments/assets/4c98a95a-2664-4be4-841b-9840d7a01397" />


### CI/CD 파이프라인

<img width="3834" height="902" alt="CICD" src="https://github.com/user-attachments/assets/bee053ce-7e67-464c-b55d-38f62e3bed9b" />


### 모니터링 아키텍처

OpenTelemetry 기반 통합 관측 시스템

- Application·Redis에서 발생하는 **트레이스와 로그**는 OpenTelemetry Java Agent/Collector로 수집
- **메트릭**은 Prometheus가 직접 스크래핑
- 수집된 데이터는 Prometheus·Tempo·Loki에 저장되며, Grafana에서 단일 화면으로 모니터링

<img width="3088" height="1206" alt="Monitoring" src="https://github.com/user-attachments/assets/df058cfb-d777-4c04-be8d-72e91b4e8777" />

---

## 👥 팀 소개

| <img src="https://github.com/minji-yoon.png" width="100"/> | <img src="https://github.com/zionge2k.png" width="100"/> | <img src="https://github.com/kkkwp.png" width="100"/> | <img src="https://github.com/kyeonghwi.png" width="100"/> | <img src="https://github.com/Me1onMusk.png" width="100"/> |
|:---:|:---:|:---:|:---:|:---:|
| [윤민지](https://github.com/minji-yoon) | [이성](https://github.com/zionge2k) | [정채윤](https://github.com/kkkwp) | [박경휘](https://github.com/kyeonghwi) | [김태영](https://github.com/Me1onMusk) |
| 팀 리더<br>데브옵스 엔지니어<br>인프라 엔지니어 | 백엔드 개발<br>DBA<br>문서화 담당 | PL(프로젝트 리더)<br>백엔드 개발<br>인프라 엔지니어 | 프론트엔드 개발<br>백엔드 개발<br>DBA | 프론트엔드 개발 |        
---

## 📞 문의

프로젝트에 대한 문의사항이 있으시면 [swcampus1127@gmail.com](mailto:swcampus1127@gmail.com)로 연락주세요.

---

<div align="center">

**Software Campus** - AI 기반 부트캠프 비교·추천 서비스

Made with ❤️ by Software Campus Team

</div>
