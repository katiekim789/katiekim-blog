---
layout: post
permalink: /how-to-setup-google-analytics-4/
title: '[GA4] Google Analytics 4 세팅하는 방법'
date: 2020-11-08 11:30:00 +09:00
feature: '/img/posts/07/posting_thumbnail.png'
background: '/img/posts/07/posting_background.png'
categories:
  - analytics
  - marketing
tags:
  - Marketing
  - Data Analytics
  - 마케팅
  - 데이터 분석
description: '새로 출시된 구글 애널리틱스4를 어떻게 세팅하는지에 대해 설명해드립니다.'
---
안녕하세요 성장중독 마케터K입니다.

지난 글에서 구글 애널리틱스4가 무엇인지 알아보았습니다.
(이 글이 무엇인지 궁금하다면 아래 링크로 GO GO!)
<br/>
[*** _Google Analytics 4(GA4)는 도대체 무엇인가?_](https://growth-mkt-k.kr/what-is-google-analytics-4/)


오늘은 GA4를 체험하기에 앞서 구글 애널리틱스 4 속성을 생성하는 방법에 대해서 알아보도록 하겠습니다.&#128522;


<br/>
## Google Analytics 4, 어떻게 세팅하면 되나요?

먼저, 구글 애널리틱스에 접속하여 왼쪽 하단에 '관리'를 클릭해주세요. 다행히도 구글은 기존 유니버셜 애널리틱스에 업그레이드하여 구글 애널리틱스 4 속성을 생성하는 옵션을 제공해주고 있습니다. 그럼 업그레이드 옵션을 클릭해보겠습니다.

![1](/img\posts\07\01_contents.png)

새로운 구글 애널리틱스 4 속성을 생성하라는 메시지가 표시됬을텐데요. 화면 상단에 써있는 것처럼 기존 유니버셜 애널리틱스는 그대로 두고 이 속성에 새로운 GA4 속성을 추가하는 형태로 업그레이드 된다고 보시면됩니다. (GA4 업그레이드 과정에서 기존 유니버셜 데이터가 사라질 염려 NO NO!)

![2](/img\posts\07\02_contents.png)

웹사이트에서 gtag.js 추적 코드가 추가되었다면, 웹 사이트에서 코드 변경할 필요없이 데이터 수집이 가능합니다. 저는 gtag.js가 추가되어있지 않기 때문에 이 옵션이 뜨지 않습니다. 그럼 ‘속성 만들기’를 클릭해주세요.

![3](/img\posts\07\03_contents.png)

짜짠! 새로운 구글 애널리틱스 4 속성이 생성된 것을 확인하실 수 있습니다.

![4](/img\posts\07\04_contents.png)

아직 잘 모르겠다구요? 그럼 왼쪽 하단에 ‘관리’를 클릭해보시겠어요? 어라? 보기 원래 유니버셜 애널리틱스에서는 계정 > 속성 > 보기가 있었는데 여기에는 보기가 없죠? 그렇다면 GA4가 제대로 생성되었다는 증거입니다. GA4에서는 보기가 사라졌거든요.

![5](/img\posts\07\05_contents.png)

속성을 선택하면 이렇게 2가지 속성을 확인할 수 있는데, UA-로 시작하는 속성이 기존 유니버셜 애널리틱스, 그리고 그냥 숫자로만 보여지는 속성이 GA4입니다. 그럼 이제 제대로 새로운 구글 애널리틱스 4 속성이 생성된 것을 확인하셨죠?

![6](/img\posts\07\06_contents.png)

새로운 구글 애널리틱스 4 속성이 생성된 것을 확인하실 수 있습니다. 그럼 이제 ‘관리’를 다시 선택하여 ‘데이터 스트림’을 클릭해주세요.

![7](/img\posts\07\07_contents.png)

<br>

---
&#128680; 여기서 잠깐! &#128680; <br> ※```데이터 스트림``` 이란? <br>
속성 안에 있는 계층구조로 고객 터치 포인트(ex, 앱, 웹사이트)에서 애널리틱스로의 데이터 흐름을 말합니다. Android 앱의 스트림, iOS 앱의 스트림, 웹사이트의 스트림 등 여러 데이터 스트림을 속성에 추가할 수 있습니다. (이전 유니버셜 애널리틱스는 ‘속성’ 안에 ‘보기’가 있는 구조) 스트림을 만들면 해당 속성에 대한 보고서는 스트림 생성일 이후부터 데이터가 쌓이는 구조이기 때문에 하루라도 빠르게 세팅하여 데이터를 모으는 것이 좋겠습니다.

---

<br>


데이터 스트림을 선택하면, 웹사이트에 대한 데이터 스트림이 자동으로 생성된 것을 확인하실 수 있습니다. ‘향상된 측정’이라고 적혀있는 박스 안에 ‘설정’을 누르면 안에 구성이 어떻게 되어있는지 자세히 확인 가능하신데요.

![8](/img\posts\07\08_contents.png)

구성하고 있는 아이콘을 살펴보면, 자동으로 측정되는 이벤트 리스트들이 나와있습니다.예를 들면, 페이지뷰, 스크롤 뎁스, 아웃바운드 클릭, 사이트 검색, 내장된 YouTube 비디오에 대한 engagement나 파일 다운로드 여부에 대한 이벤트들입니다. (이전 GA에서는 페이지뷰를 제외하고 전부 저희가 이벤트를 세팅했어야했는데 이제는 기본적인 이벤트들은 제공해준다는 점, 그리고 페이지뷰도 이벤트로 인식하여 데이터가 트래킹된다는 점이 이전 버전과의 차이점이라고 할 수 있습니다.)

![9](/img\posts\07\09_contents.png)


모든 작업을 자동으로 추적하게 하기 위해서는 모든 옵션을 그대로 두시고 저장하면 됩니다.
이제 데이터 스트림을 통해 웹 사이트에서 새로운 속성으로 데이터 수집을 시작하는데 필요한 모든 것을 세팅 완료했습니다.

데이터 스트림을 생성이 다 완료되었으면, 이제 오른쪽 상단에 있는 측정 id를 복사하여 구글태그매니저를 사용하여 웹사이트에 추가할 수 있습니다. 그 전에 밑에 ‘태그’ 옵션 2개를 한번 살펴보고 갈게요.

![10](/img\posts\07\10_contents.png)

이부분은 GA로 웹사이트 데이터를 받기 위해 웹사이트에 새 추적 태그를 추가하는 옵션인데요. 2가지 중 한가지를 현재 상황에 맞게 선택할 수 있습니다.
첫번째, “새로운 온페이지 태그 추가“ 에서는 현재 구글 애널리틱스를 사용하지 않는 경우에 사용하는 선택지 입니다. 구글 태그매니저를 사용하여 전체 사이트 태그(gtag.js)를 삽입해주시면 됩니다.

하지만 우리는 지금 기존 유니버셜 구글애널리틱스를 사용하고 있고, 이를 활용하여 GA4 속성을 생성하고 있는 중이기 때문에 두번째 옵션인 “기존 온페이지 태그 사용“를 활용하여
기존 태그를 새 GA4 속성에 연결하여 데이터를 수집할 수 있도록 해줄 것입니다. 그럼, 오른쪽 옵션을 클릭해주세요.

이제 G로 시작하는 측정ID를 카피한 다음 구글 태그매니저로 이동하도록 하겠습니다!  

---


이미 제 웹사이트에서는 구글 태그 매니저를 활용하여 기존 유니버설 애널리틱스로 데이터를 수집하고 있음으로 표준 구글 애널리틱스 속성, 컨테이너에 GA4 태그를 추가하도록 하겠습니다. 태그 이름을 GA4임을 구분할 수 있게 지정해주시고요. 태그 유형은 ‘Google 애널리틱스 : GA4 구성’로 택해주세요. 그 다음 아까 복사했던 ‘측정 ID’를 태그 구성에 붙여넣습니다. 태그에 대한 트리거는 웹사이트의 모든 페이지에서 태그가 실행되도록 ‘All Pages’를 택해준 다음, 저장 버튼을 누릅니다.


![11](/img\posts\07\11_contents.png)

이제 태그 제출을 눌러주세요!!  (그래야 tag 생성에 대한 변경사항을 웹사이트에 게시할 수 있습니다.) 여기까지 하셨다면, 이제 새로운 “앱 및 웹 구성” 태그가 생성된 것이고, 기존 유니버셜 구글 애널리틱스 태그를 가지고 있기 때문에, 기존 속성과 새로운 GA4 속성 모두에 데이터를 보낼 수 있게 되었습니다 (짝짝짝)

![12](/img\posts\07\12_contents.png)

그럼 웹사이트로 이동하여 페이지를 새로고침해볼까요? 그러면 새 태그가 트리거되고 새 속성에 데이터 수집이 시작됩니다. 데이터가 GA로 잘 수집되고 있는지 확인하기 위해 이제 GA로 다시 돌아가보겠습니다.


GA4에서 실시간 리포트 > 사용자 스냅샷을 클릭하면,

![13](/img\posts\07\13_contents.png)

이렇게 아래와 같이 데이터가 실시간으로 수집되는 것을 확인하실 수 있습니다.

![14](/img\posts\07\14_contents.png)

<br/>


오늘은 Google Analytics 4 속성을 세팅해보았는데요. 이전 유니버셜 애널리틱스와 GA4는 각각의 장점과 기능, 제공해주는 보고서 형태가 다르기 때문에 두 속성을 모두 세팅하여 우리 웹사이트에서 발생하는 여러 데이터를 다양한 각도로 살펴보고 비즈니스에 도움이 될만한 더 많은 인사이트를 얻어가시길 추천드립니다.

그럼 다음 시간에는 Google Analytics 4에 데이터 트래킹을 위한 이벤트를 세팅하는 방법에 대해 알아보도록 하겠습니다.


<br/>
