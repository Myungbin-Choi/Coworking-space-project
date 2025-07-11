# 공유 오피스 체험 신청자 유료 전환 예측 모델링 프로젝트
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>


## 프로젝트 개요
### 분석 목적
공유오피스 비즈니스 지표의 추이를 예측하고 서비스 개선을 위한 인사이트 제시
- 공유오피스의 3일 무료 체험 데이터를 기반으로 사용자의 방문 및 출입 패턴을 분석한다
- 머신러닝 기반 결제 전환 예측 모델을 통해 유료 전환 가능성을 예측한다


### 활용 데이터
공유 오피스 3일 체험 신청자 로그 데이터 
- 주요 컬럼 : 유저 ID, 신청일시, 방문일, 입퇴실 시각, 출입 시각, 결제 여부, 지점 면적 등
![dataandfeature](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/dataandfeature.png)


### 수행 역할
- pandas, matplotlib, seaborn을 활용한 데이터 분석 및 시각화
- 머신러닝 모델 선정 및 모델 학습
---

## 분석 과정 
![modeling_step1](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step1.png)
![modeling_step2](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step2.png)
![modeling_step3](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step3.png)
![modeling_step4](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step4.png)
![modeling_step5](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step5.png)
![modeling_step6](https://github.com/Myungbin-Choi/Coworking-space-project/blob/main/images/modeling_step6.png)

---

## directory structure
```bash
├── README.md                          <- 프로젝트 요약 설명
├── coworking_space.ipynb              <- 분석 통합 파일 (preview 용)
├── coworking_space.py                 <- 분석 통합 파일 (code 공유용)
├── 공유오피스_유료전환_예측_요약포트폴리오.pdf  <- 프로젝트 2page 요약 파일
├── 공유오피스_유료전환_예측_포트폴리오.pdf     <- 프로젝트 보고서 요약 파일
├── images                             <- 주요 이미지 파일
│   ├── dataandfeature.png       
│   ├── modeling_step1.png      
│   ├── modeling_step2.png   
│   └── modeling_step3.png            
│   └── modeling_step4.png
│   └── modeling_step5.png                   
│   └── modeling_step6.png                   
                   
```
