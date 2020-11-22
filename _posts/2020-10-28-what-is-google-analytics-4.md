---
layout: post
permalink: /what-is-google-analytics-4/
title: '[GA4] Google Analytics 4(GA4)는 도대체 무엇인가?'
date: 2020-10-28 11:30:00 +09:00
feature: '/img/posts/06/posting_thumbnail.jpg'
background: '/img/posts/06/posting_background.jpg'
categories:
  - analytics
  - marketing
tags:
  - Marketing
  - Data Analytics
  - 마케팅
  - 데이터 분석
description: '새로 출시된 GA4가 기존 구글 유니버셜 애널리틱스와 어떻게 다르고, 마케터에게 어떤 영향을 끼치는지에 대한 글'
---
안녕하세요 성장중독 마케터K입니다.

10월 14일 구글에서 새로운 Google Analytics 4를 출시함에 따라, 전세계 마케터들의 이목이 쏠렸는데요. 도대체 기존 구글 애널리틱스와 어떤 차이가 있고, 이것이 마케터들에게 어떤 영향을 끼치길래 다들 이토록 관심을 가지는 것인지 한번 알아보도록 하겠습니다 :)

<br/>
## 1. Google Analytics 4, 왜 주목해야하는가?

2019년에 베타 버전으로 출시한 구글 애널리틱스 ‘앱+웹’ 속성을 사용해보신 분들은 어느 정도 차이점을 인지하고 계시겠지만, 정식 출시된 Google Analytics 4에는 이전 버전(Universal Analytics 속성)과 매우 다른 여러 기능들이 포함되어 있습니다. 유니버셜 애널리틱스와의 GA4의 차이점을 크게 구분하면 4가지로 요약할 수 있습니다.

<br/>
1) 앱과 웹에서 일어나는 고객 행동을 하나의 툴에서 교차 분석 가능
(과거에는 웹사이트를 측정하는 유니버설 애널리틱스와 모바일 앱 활동을 측정하는 Firebase용 Google 애널리틱스, 이렇게 각각의 속성들이 따로 존재하여 교차기기 간에 분석이 어려웠습니다.)

2) 세션 중심이 아닌 유저와 이벤트 중심으로 데이터 모델 변경

3) 크롬 쿠키 정책 변경 및 개인 정보 보호 정책 준수에 따라 서드파티 쿠키에 대한 최근 브라우저들의 보안 정책에 영향을 덜 받을 수 있도록 쿠키 의존도가 줄어든 이용자 식별 방식

4) 구글 BigQuery를 사용하여 raw data를 누구나 저장하여 사용 가능(예전엔 구글 360 유료버전에서만 사용 가능했지만 이젠 무료로 가능!)


<br/>
## 2. Google Analytics 4의 주요 특징

그렇다면 Google Analytics 4가 기존 구글 애널리틱스와 어떤 차이가 있을까요? 다음은 기본보다 더욱 더 강화된 GA4의 5가지 특징에 대해서 알아보겠습니다.

<br/>
#### 1) 머신러닝을 사용하여 트렌드에 관한 인사이트를 마케터에게 제공

머신러닝을 활용하여 기존 데이터를 기반으로 사이트 트래픽 또는 사용자의 행동을 예측하여 데이터 인사이트를 알려줍니다. 예를 들어, 새로운 고객의 요구로 인해 수요가 증가하고 있는 제품이 무엇인지 알 수 있는데요. 이를 통해, 한정된 마케팅 예산으로 어떤 곳에 효율적으로 투자할 수 있는지 결정을 내리는데 도움을 줄 수 있을 것으로 보여집니다.

<br/>
#### 2) 고객 중심 데이터 측정

마케터들은 앞으로 고객들이 주로 어디서 유입되고, 어디서 전환되는지 고객의 전체 라이프 사이클을 잘 이해하고 있어야합니다. 왜냐면 우리의 고객이 웹의 광고를 보고 웹사이트로 유입되어 둘러보다가 마지막에 앱을 통해 제품을 구매할 수도 있기 때문입니다. GA4는 기기/페이지/세그먼트의 각각 개별 메트릭만 측정하는 것이 아니라 유저의 전체 여정을 완벽하게 측정하는데 좀더 초점을 맞추고 있기 때문에

<br/>
#### 3) 구글애즈와의 긴밀한 통합

이제 GA4에서는 웹 및 다른 소스(ex. 앱) 간의 상호작용을 측정하기 때문에 보다 더 정확한 구글 애널리틱스 데이터를 기반으로 구글애즈에 맞춤 잠재고객 생성이 가능해지며, 구글 매체에서 더 정확한 전환 트래킹이 가능해집니다.

<br/>
#### 4) “데이터 스트림” 기능 제공
기존 Universal Analytics 속성에서 제공하는 보기 및 세그먼트 대신 “데이터 스트림” 기능을 제공합니다. 따라서 GA4에서는 “보기” 레벨 섹션이 없습니다. 기존 유니버셜 애널리틱스에서는 세 가지 레벨(계정, 속성, 보기)가 있었지만 GA4에서는 계정 및 속성 레벨만 있습니다.


<br/>
#### 5) 이벤트 추적 방식 변경
기존 Analytics의 "이벤트 추적"에는 수정된 Analytics 코드 또는 gtag.js 스크립트가 필요했지만 Google Analytics 4는 UI 내에서 기본적인 이벤트를 자동으로 추적할 수 있습니다. GA4의 데이터 스트림 세부정보를 보면 스크롤 뎁스, 이탈클릭, 페이지 조회, 사이트 내 검색, 동영상 조회, 파일 다운로드 등을 자동 수집할 것인지 체크하는 영역이 있는데, 이 부분에 체크를 하게되면 해당 이벤트는 맞춤 이벤트로 세팅하지 않아도 측정 가능해집니다. (즉, 위에 자동 수집 이벤트를 제외한 나머지 이벤트는 맞춤 이벤트로 세팅하여 추적해야한다는 것을 의미합니다.)

<br/>
이렇게 정리해놓고 보니 마케터 입장에서 기존 유니버셜 구글애널리틱스보다 강력해진 기능들이 많아보이는데요! 다음 글에서는 GA4로 직접 업데이트해보면서 GA4의 보고서가 어떻게 달라졌는지, GA4를 어떻게 활용해야하는지를 알아보도록 할게요!



<br/>
##### 참고자료 :

- [https://www.blog.google/products/marketingplatform/analytics/new_google_analytics/](https://www.blog.google/products/marketingplatform/analytics/new_google_analytics/)
- [https://developers.google.com/analytics/devguides/collection/ga4/events](https://developers.google.com/analytics/devguides/collection/ga4/events)
- [https://www.searchenginejournal.com/new-google-analytics/384049/#close](https://www.searchenginejournal.com/new-google-analytics/384049/#close)
- [https://louder.com.au/2020/10/15/google-analytics-4-launches/](https://louder.com.au/2020/10/15/google-analytics-4-launches/)
- [https://raddinteractive.com/what-is-the-new-google-analytics-4/](https://raddinteractive.com/what-is-the-new-google-analytics-4/)

<br/>
