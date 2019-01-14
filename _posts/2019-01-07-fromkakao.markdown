---
layout: post
title:  "What I learned from Kakao arena project"
date:   2019-01-08 0:00:00
author: jjung
categories: [from mistakes, machine learning]
tags: [deeplearning, kakao]
---

관련 링크 : [카카오 아레나](https://arena.kakao.com/c/1), [개발코드](https://github.com/jjunghub/shopnet)

#### 쇼핑몰 상품정보(이미지벡터, 상품텍스트정보)로 부터 대분류, 중분류, 소분류, 세부분류의 4가지 카테고리의 각 분류로 분류해내는 미션

배운것
* 꼭 하나의 명확한 측정지표를 정의하고 판단기준으로 삼을 것
* 거창한 모델 하나를 완성하려 하기보다 작은것부터 키워나가며 단계별로 확인작업을 거칠 것
(한 뭉치 후 확인하지말고, 변화를 줬을 때 하나씩 정리해 나갈것 => 뇌피셜 노노, dev데이터에 돌려 score꼭 확인)
* 변화가 있을 때 모델의 기록을 커밋으로 남겨 각 case마다 언제나 되돌릴 수 있는 환경을 만들고 진행할 것
* 모델크기와 데이터에 대한 감각 필요 (특히, LSTM, embedding의 경우 데이터 사이즈와 학습량에 대한 감이 없음)
* 터미널에서 바로 실행하기보다 실행코드를 코드파일에 정의하여 흔적을 남길 것

