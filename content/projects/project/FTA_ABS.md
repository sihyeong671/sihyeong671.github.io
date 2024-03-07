---
title: "Segment & Classify for Treponema pallidum"
link: ""
image: "/images/seegene.jpeg"
description: "foundation model을 활용한 매독균 Segment 및 분류 알고리즘 개발"
featured: true
tags: ["PyTroch Lightning", "Segmentation", "Classification"]
fact: ""
weight: 99
sitemap: 
    priority : 0.8
---

**매독균 분류 프로젝트**
- PyTorch Lightning을 이용해 모델 학습 코드 구현
- Confusion matrix 시각화 및 Metric logging
- 너무 큰 이미지가 resize에 많은 영향을 받는 것으로 파악하여 image split해서 예측하고 그 평균으로 전체 이미지를 분류 하도록 프로그래밍
- OpenCV를 이용한 전처리 및 SegGPT를 활용한 자동 Segment 파이프라인 구축
- 전문가가 분류할 때 Intensity를 하나의 요소로 보는 것을 파악하여 밝기 데이터 분포를 파악
- 밝기 분포를 model의 condition으로 추가하여 모델 구조 변형 및 약간의 성능 개선