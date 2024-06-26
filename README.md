# Project :  Automatic macro email login

<br/>

## 프로젝트 소개

이번 프로젝트는, 프로그램을 실행시키면 **인터넷 브라우저(Chrome)** 가 실행되고 [다음](www.daun.net)으로 접속이 되어 자동 로그인을 한 후 현재 와 있는 메일을 볼수 있도록 자동화 시스템을 구축하는 것입니다.

<br/>

## 프로젝트 구조

첫번째로, JAVA의 키보드, 마우스 형태인(좌표) **ROBOT 라이브러리** 를 사용하여 원시적인 방법으로 구동시킵니다.
두번째로 UI Test 목적으로 나온 셀레니움 프레임워크를 사용하여 구동시킵니다.

<br/>

## Selenium

**셀레니움**은 브라우저 자동화, 크롤링과 관련된 라이브러리 입니다. 
보통 윈도우 익스플로러 같은 경우 **DOM** 이라는 것을 통해 제어하는데, **Chrome**이나 **Firefox** 같은 경우 웹드라이버를 따로 지원하여 **셀레니움**을 통해 제어가 가능합니다.

간단한 웹 접속, 스크롤 하는것 부터 웹사이트 로그인, 버튼 누르기, 특정 하이퍼링크 누르기 등의 기능으로 **크롤링(Crawling)** 이나 웹 **매크로(Macro)** 등 다양한 작업을 할 수 있습니다.

그 외에도 세분화 하는 경우엔 프록시 접속하기, 리캡차 넘어가기 등도 가능하다고 합니다.

<br/>

## 사용기술

- `JAVA`
- `Eclipes`
- `java-Selenium`
- `java-robot`

<br/>

## 리뷰

**코딩** 에 대해서 다른 측면으로 생각해 본 적이 있습니다.

간단한 **계산(연산)** 을 하려 하거나 간단한 **패턴(알고리즘)** 을 구하는 문제가 있을 때 저는 암산을 하거나 혹은 종이에 계산을 해 보았습니다.

30분 이면 그냥 제 머리로 즉석해서 해결이 되던 문제를 **코딩** 을 하여 해결을 하려 해보니 2시간은 넘게 걸린 것 같습니다.
정말 시간대비 효율도 떨어지고, 2시간이 지나서도 끝낸다는 보장이 없었습니다.

무식하게 **아날로그** 적인 방법으로 문제를 해결한 것을, **자동화** 하기 위해 프로그래밍 언어로 코딩을 해 보았더니 더욱 느릴 뿐이었습니다.

그런데 만약 이러한 문제를 5번을 반복하거나 혹은 매일 5번, 그리고 10번씩 반복하며 몇년이 지난다면,
혹은 이 **자동화** 시스템을 다른 사람도 이용한다면 이 **가치(효율)** 은 엄청날 것이라 자부합니다. 이 부분에서 저는 느끼는 바가 매우 컷습니다. 
 
 이 프로젝트를 하면서 느낀 것이 이와 같았습니다. 
 만약 제가 **E-mail** 을 **login** 해서 메일 갯수를 확인하는것은 고작 20초도 걸리지 않는데, 메크로라는 기법을 활용한다면 당장 원하는 값에 이르기 까지는 매우 비효율 적이지만, 이의 활용가치는 엄청 날 것이라는 겁니다.
 
 **매크로(Macro)** 란, 사용자가 정해놓은 일련의 과정, 패턴을 출력 하는 것을 뜻합니다.
 
 저는 **JAVA**의 내장 라이브러리 **ROBOT**을 통하여 원시적인 방법으로도 매크로를 실행시켜보고,
 그리고 더 나아가 진보적인 라이브러리인 **셀레니움(Selenium)** 을 통하여 브라우저를 **자동화** 하고 눈깜빡할 새에
 많은 작업을 끝내는 것을 보면서 **프로그래밍의 가치** 에 대해서 다시 한번 생각해 보게 만드는 프로젝트였습니다.
