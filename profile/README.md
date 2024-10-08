# 🏡 집순이 집돌이의 건강 지킴이 서비스 🏋️‍♀️

## 📋 프로젝트 소개

### 🎯 목적

현대 사회에서 재택근무자, 집순이·집돌이, 은둔형 외톨이처럼 외출을 꺼리는 사람들이 신체 활동 부족으로 인해 비만율 증가와 건강 악화 문제를 겪고 있습니다.  
본 프로젝트는 이러한 문제를 해결하기 위해 간단한 실내 스트레칭을 제공하고, **YOLOv8 포즈 추정 모델**을 통해 실시간 자세 피드백을 제공합니다.  
사용자는 **웹 기반 서비스**를 통해 손쉽게 운동에 참여하며, 정확한 동작 수행으로 체력 증진을 도모할 수 있습니다.

### 🛠️ 설명

이 서비스는 실내에서 간단한 스트레칭을 수행하며, **인공지능 모델**이 사용자의 동작을 분석합니다.  
웹 환경에서 동작하여, 별도의 장비 없이 운동 동작의 정확성을 개선하고 효과를 극대화하는 데 중점을 둡니다.

차별점은, 실시간 코칭 대신 **영상 업로드 방식**을 채택해 사용자가 편안한 환경에서 큰 화면으로 동작 비교를 할 수 있습니다.  
또한, 홈트레이닝 프로그램 확장 가능성도 높아, **요가, 필라테스, 근력 운동** 등 다양한 프로그램에 적용할 수 있습니다.

---

## ⏳ 개발 기간

- **2024년 09월 ~ 2024년 11월** (약 3개월)

| 주차       | 주요 작업 내용                                   |
| ---------- | ----------------------------------------------- |
| 1~2주차    | 기획 및 요구사항 분석                            |
| 3~4주차    | 기술 조사 및 환경 세팅                           |
| 5~6주차    | 데이터 준비 및 모델 학습                         |
| 7~10주차   | 웹 서비스 개발 및 모델 통합                      |
| 11~13주차  | 테스트 및 성능 개선                              |
| 14주차     | 최종 배포 및 유지보수 계획 수립                  |
| 15주차     | 최종 발표 및 결과물 완성                         |

---

## 🖥️ 기술 스택


![image01](https://github.com/user-attachments/assets/a5b15113-7c72-428c-bf74-a95df32f2d7f)

- **프로그래밍 언어**: Python 🐍
- **모델 프레임워크**: PyTorch 🔥
- **서버 및 프론트엔드**: Streamlit 🌐
- **AI 모델**: YOLOv8 (포즈 추정) 🤖
- **학습 데이터**: AI허브 피트니스 자세 이미지 데이터 🏋️‍♂️
- **기타 라이브러리**: OpenPose 또는 PoseNet (포즈 추정), OpenCV (동영상 처리) 🎥
- **배포**: Streamlit Cloud ☁️

---

## 🧑‍🤝‍🧑 역할 안내

- **이서현** (팀장 / 프로젝트 매니저, 풀스택 개발자)
  - 프로젝트 기획 및 요구사항 분석
  - 프론트엔드 및 서버 개발
  - YOLOv8 모델을 연동하여 사용자의 자세 분석 기능 개발

- **박은빈** (팀원 / 데이터 엔지니어, AI 모델 개발자)
  - AI허브에서 피트니스 자세 이미지 데이터 수집 및 전처리
  - YOLOv8 모델 구축 및 학습
  - 모델 성능 최적화 및 파인튜닝

---

## 🌟 기대 효과 및 활용 분야

이 서비스는 집에 머무는 시간이 많은 사람들을 위한 맞춤형 운동 솔루션으로,  
**스트레칭을 통해 체력 증진 및 비만 예방**에 기여할 수 있습니다.  
또한, 요가, 필라테스, 근력 운동 등 다양한 프로그램으로 확장 가능하며,  
**정확한 자세 피드백**을 통해 운동 효과를 극대화할 수 있습니다.
