# YOLOv9-PCB
> KCC 2024_YOLOv9 기반의 PCB (인쇄 회로 기판) 결함 탐지 및 분류

#### 📖 개요
본 프로젝트는 YOLOv9 모델을 활용하여 **인쇄 회로 기판(PCB)** 의 결함을 실시간으로 탐지하고 분류하는 시스템을 개발합니다. **Programmable Gradient Information (PGI)** 와 Generalized Efficient Layer Aggregation Network (GELAN) 같은 최신 기술을 적용하여 높은 정확도와 연산 효율성을 구현하였습니다.

#### 📌 주요 내용
- 모델: YOLOv9, GELAN-c
- 데이터셋: 약 10,000장의 PCB 이미지
- 주요 결함 유형: missing hole, mouse bite, open circuit, short, spur, spurious copper
- 데이터셋 출처: Roboflow
- 기술:
  - PGI: 정보 손실 최소화를 통한 성능 향상
  - GELAN: 효율적인 네트워크 구조로 경량 모델에서도 높은 성능 유지
- 성과:
  - YOLOv9: PCB 결함 탐지에서 가장 높은 정확도를 기록
  - GELAN-c: 복잡한 PCB 이미지에서도 정보 손실을 최소화
#### 🛠️ 활용 사례
- 전자기기 제조: PCB 품질 검사 및 불량 탐지
- 스마트팩토리: 제조 과정 모니터링 및 자동화 품질 관리
- 산업 현장: 실시간 결함 탐지를 통한 생산 효율성 향상

#### ✔︎ 결과  
<img src="https://github.com/user-attachments/assets/88c5a9be-9368-4326-8332-4cf6376cccb3" width="500" height="500">

