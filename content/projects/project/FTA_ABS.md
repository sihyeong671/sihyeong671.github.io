---
title: "Segment & Classify for Treponema pallidum"
link: ""
image: "/images/seegene.jpeg"
description: "foundation model을 활용한 매독균 Segment 및 분류 알고리즘 개발"
featured: true
tags: ["PyTroch Lightning", "Segmentation", "Classification"]
fact: ""
weight: 97
sitemap: 
    priority : 0.8
---

**매독균 분류 프로젝트**
- PyTorch Lightning을 이용해 모델 학습 코드 구현
- Confusion matrix 시각화 및 Metric logging
- OpenCV 이용한 전처리 (Contrast Enhancement, Sharpening)
- SegGPT모델 사용한 자동 Segment 파이프라인 구축
- resize의 영향 줄이기 위해 원본 이미지 split하여 예측하고 이를 평균내어 결과 예측에 사용
- 원본 이미지와 segment mask의 overlay 픽셀의 intensity값의 분포 파악하여 연관성 확인
- noramlized intensity histogram distribution을 model의 fc layer에 concat하여 모델 구조 변형 및 약간의 성능 개선