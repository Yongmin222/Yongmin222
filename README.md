# 안녕하세요, 이용민입니다 👋

IT 분야로 전환한 비전공자로서, 대용량 데이터 파이프라인 설계와 분산 시스템 운영에 강점을 가진 데이터 엔지니어입니다.

🔹 **Data Engineer**  
🔹 관심 분야
- **실시간 데이터 파이프라인** (Kafka, Apache Flink, Stream Processing)
- **대규모 데이터 처리** (BigQuery, Spark, ETL/ELT)
- **클라우드 데이터 인프라** (GCP, AWS, Data Warehouse 설계)
- **머신러닝 파이프라인** (Feature Engineering, BigQuery ML, Vertex AI AutoML)

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
**SK Shieldus 부트캠프 최종 프로젝트** | 팀 3인 / 아키텍처 설계 · 인프라 · Kafka · Flink 담당 | 2025.03 ~ 2025.06

프랜차이즈 매장의 실시간 영수증 데이터를 수집, 처리, 분석하는 End-to-End 데이터 파이프라인

**🔧 기술 스택**
- **Message Queue**: Confluent Kafka (KRaft 모드, 11개 노드)
- **Stream Processing**: Apache Flink (3개 병렬 Job)
- **Data Format**: Avro + Schema Registry (JSON 대비 40% 압축)
- **Backend**: Spring Boot Producer, Kafka Connect
- **Infrastructure**: AWS EC2 (11개 인스턴스)

**📊 주요 성과**
- ✅ 22시간+ 무중단 안정 가동 (Exactly-Once 보장)
- ✅ 실시간 매출 모니터링 (초 단위 업데이트)
- ✅ 중복 결제 이상 거래 탐지 (CEP Pattern)
- ✅ TOP 3 매장 실시간 랭킹 (Sliding Window)
- ✅ 분산 환경 트러블슈팅 5건 직접 해결

**📂 관련 레포지토리**
- 🔹 [purchase](https://github.com/Yongmin222/purchase) - Kafka Producer & 영수증 데이터 수집
- 🔹 [sales_total_realtime](https://github.com/Yongmin222/sales_total_realtime) - Flink 실시간 누적 매출
- 🔹 [duplicate-payment-detector](https://github.com/Yongmin222/duplicate-payment-detector) - Flink 중복 결제 탐지
- 🔹 [franchise-top-store](https://github.com/Yongmin222/franchise-top-store) - Flink TOP 3 매장 랭킹
- 🔹 [KFC-KafkaFriedCoders](https://github.com/KFC-KafkaFriedCoders) - 팀 프로젝트 원본

📄 **[포트폴리오 상세 보기](https://drive.google.com/file/d/1HXL0rgfM0Z0XIELI4jh1m845yw6bXplS/view?usp=sharing)**

---

### **2. YouTube 영상 조회수 예측 모델 구축**
**Google Cloud 실무 프로젝트** | 2025.12

YouTube Data API로 수집한 68,497개 영상 메타데이터 기반 조회수 예측 ML 파이프라인

**🔧 기술 스택**
- **데이터 수집**: Python, YouTube Data API v3
- **Data Warehouse**: Google BigQuery
- **데이터 분석**: SQL, BigQuery ML
- **ML 모델**: Vertex AI AutoML, Boosted Tree
- **배포**: Vertex AI Endpoint (REST API)

**📊 주요 성과**
- ✅ R² 0.28 → 0.80 달성 (186% 향상)
- ✅ 원시 15개 컬럼 → 17개 Feature Engineering
- ✅ Data Leakage 직접 탐지 및 해결 (R² 0.95 → 0.74 → 0.80)
- ✅ Vertex AI Endpoint REST API 배포

**💡 핵심 인사이트**
- 채널 파워(45%) > 콘텐츠 특성(25%) > 제목 키워드(15%)
- 대형 채널(100만 구독) vs 소형 채널(1만 구독) 간 45배 조회수 차이
- 키워드 최적화는 소형 채널에서만 약 9% 효과

📄 **[포트폴리오 상세 보기](https://drive.google.com/file/d/1OGvtYk9S20cwHlCJA2am3N-sJt7NpNfG/view?usp=sharing)**

---

## 📫 Contact & Credentials

📧 **Email**: gkdlfn579@gmail.com  
🔗 **GitHub**: [@Yongmin222](https://github.com/Yongmin222)

### 🏅 Certifications
- **AWS Certified Cloud Practitioner** (2026.01.28)
