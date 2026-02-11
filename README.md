🔹 **Data Engineer**
🔹 관심 분야
  - **실시간 데이터 파이프라인** (Kafka, Apache Flink, Stream Processing)
  - **대규모 데이터 처리** (BigQuery, Spark, ETL/ELT)
  - **클라우드 데이터 인프라** (GCP, AWS, Data Warehouse 설계)
  - **머신러닝 파이프라인** (Feature Engineering, BigQuery ML, Vertex AI AutoML)

---

## 🏆 Career & Experience

**[Google Cloud X 천안과학산업진흥원 - GCP 기반 데이터/AI 엔지니어링]** – *(2025.12.08 ~ 2025.12.26)*
- BigQuery를 활용한 대용량 데이터 분석 (SQL)
- Vertex AI AutoML 기반 머신러닝 모델 개발
- 데이터 수집, 분석, AI 모델링, 시각화 전 과정 경험
- Google 엔지니어 멘토링

**[SK Shieldus Rookies - 지능형 애플리케이션 개발자 양성 과정]** – *(2024.12 ~ 2025.06)*
- 클라우드 기반 데이터 파이프라인 설계 및 미들웨어 활용
- Confluent Kafka + Apache Flink 기반 실시간 스트리밍 데이터 처리
- AWS EC2 분산 환경 구성 (11개 노드)
- 3회 미니 프로젝트 + 1회 실무 프로젝트 수행

---

## 🛠 Tech Stack

### **📊 Stream Processing & Message Queue**
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)  ![Apache Flink](https://img.shields.io/badge/Apache%20Flink-ED1C24?style=flat-square&logo=apache&logoColor=white)  ![Confluent](https://img.shields.io/badge/Confluent-311C87?style=flat-square&logo=confluent&logoColor=white)

### **☁️ Cloud Data & Analytics**
![Google BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)  ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)  ![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)  ![AWS RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)

### **🐍 Programming & Data Tools**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)  ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### **🔧 DevOps & Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)  ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)  ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🎯 Featured Projects

### **1. HANNOON - 실시간 프랜차이즈 매출 분석 플랫폼**
**SK Shieldus 부트캠프 최종 프로젝트** | 2025.03 ~ 2025.06

프랜차이즈 매장의 실시간 영수증 데이터를 수집, 처리, 분석하는 엔드-투-엔드 데이터 파이프라인

**🔧 기술 스택**
- **Message Queue**: Confluent Kafka (KRaft 모드, 11개 노드)
- **Stream Processing**: Apache Flink (3개 병렬 Job)
- **Data Format**: Avro + Schema Registry (40% 압축)
- **Backend**: Spring Boot Producer, Kafka Connect
- **Infrastructure**: AWS EC2 (12개 인스턴스)

**📊 주요 성과**
- ✅ 22시간+ 안정 실행 (Exactly-Once 보장)
- ✅ 실시간 매출 모니터링 (초 단위 업데이트)
- ✅ 이상 거래 탐지 (중복 결제 패턴)
- ✅ TOP 3 매장 실시간 랭킹

**🛠️ 핵심 역량**
- 분산 시스템 설계 & 디버깅
- Avro & Schema Registry를 통한 데이터 호환성 관리
- Kafka Ecosystem 실제 운영 경험
- 환경 설정 및 배포 프로세스

**📂 관련 레포지토리**
- 🔹 [purchase](https://github.com/Yongmin222/purchase) - Kafka Producer & 영수증 데이터 수집
- 🔹 [sales_total_realtime](https://github.com/Yongmin222/sales_total_realtime) - Flink 실시간 누적 매출
- 🔹 [duplicate-payment-detector](https://github.com/Yongmin222/duplicate-payment-detector) - Flink 중복 결제 탐지
- 🔹 [franchise-top-store](https://github.com/Yongmin222/franchise-top-store) - Flink TOP 3 매장 랭킹

**📄 팀 프로젝트 원본**
- [KFC-KafkaFriedCoders Organization](https://github.com/KFC-KafkaFriedCoders)

---

### **2. YouTube 영상 조회수 예측 모델 구축**
**Google Cloud 실무 프로젝트** | 2025.12 ~ 2025.12

YouTube Data API로 수집한 68,497개 영상 메타데이터 기반 조회수 예측 머신러닝 모델

**🔧 기술 스택**
- **데이터 수집**: Python, YouTube Data API v3
- **Data Warehouse**: Google BigQuery
- **데이터 분석**: SQL, BigQuery ML
- **ML 모델**: Vertex AI AutoML, Boosted Tree
- **배포**: Vertex AI Endpoint (REST API)

**📊 주요 성과**
- ✅ R² 성능: 0.28 → 0.80 (186% 향상)
- ✅ 17개 Feature Engineering (채널 파워, 콘텐츠 특성, 제목 키워드)
- ✅ Data Leakage 발견 & 해결 (좋아요/댓글 제외)
- ✅ 실제 서비스 가능한 API 배포

**💡 핵심 인사이트**
- 채널 파워(45%) > 콘텐츠 특성(25%) > 제목 키워드(15%)
- 대형 채널(100만 구독) vs 소형 채널(1만 구독) 간 45배 조회수 차이
- 키워드 최적화는 소형 채널에서만 약 9% 효과

**🛠️ 핵심 역량**
- EDA를 통한 데이터 인사이트 도출
- Feature Engineering & Data Preprocessing
- 머신러닝 모델 최적화 및 성능 평가
- 비즈니스 문제 정의 & 해결

---

## 📫 Contact & Credentials

📧 **Email**: gkdlfn579@gmail.com
💼 **LinkedIn**: [이용민 - Data Engineer](https://www.linkedin.com/)
🔗 **GitHub**: [@Yongmin222](https://github.com/Yongmin222)

### 🏅 Certifications
- **AWS Certified Cloud Practitioner** (2026.01.28)
- **Data Engineering 실무 교육** (SK Shieldus, Google Cloud, AWS)

<!-- ### 🎯 Problem Solving
[![백준 랭크](http://mazassumnida.wtf/api/v2/generate_badge?boj=gkdlfn579)](https://solved.ac/profile/gkdlfn579) -->
