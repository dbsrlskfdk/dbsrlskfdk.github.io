---
layout: post
title: [부스트캠프 AI Tech] KLUE Relation Extraction 대회 회고
subtitle: 부푼 꿈을 안고 시작한 6등의 회고
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
tags: [AI Tech, BoostCamp, NLP, Relation Extraction]
comments: true
---

## 대회기간
{: .box-note}
23.05.02 ~ 23.05.18

## 대회 Task 요약
- 데이터셋은 KLUE 데이터셋으로, 동일 문장 내에서 주어진 단어관의 관계를 예측(Classification)하는 Task
- Relation은 총 30개로, 한정적인 관계만이 주어짐.

## 대회 데이터셋 분포
### Numbers
| Source | Train | Dev | Test | Total |
| :----  | :---- | :--- | :--- | :--- |
| Wikipedia | 21620 | 3621 | 3452 | 28693 |
| Wikitree | 10672 | 4088 | 4249 | 19009 |
| Policy | 178 | 56 | 64 | 298 |
| Overall | 32470 | 7765 | 7766 | 48001|

### Class 별 분포
![KLUE Label](/assets/img/KLUE_label.JPG){: .mx-auto.d-block:}

