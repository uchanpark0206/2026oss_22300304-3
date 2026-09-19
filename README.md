


#Service Topic : 제작한 CRUD Frontend Service 주제 도서를 관리하고 수정하고 수정된 데이터를 다시 집어넣는 서비스를 만들기

Data Fields : 6개 이상의 데이터 Field와 각 항목 설명

1.번호(id) 표에서 번호를 출력하기 위해 
사용

2.도서명():도서의 이름을 넣기 위한 항목 

3.저자():도서의 저자를 넣기위한 항목 

4.출판사()출판사를 넣기 위한 항목

5.연도 출판 연도를 넣기위한 항목

6.ibs ibs번호를 넣기 위한 항목

7.카테고리 카테고리를 넣기위한 항목

List Page : index.html에서 표시한 Field 4개 이상
번호,
도서명,
저자, 
카테고리

Validation : add.html과 edit.html에 적용한 Validation 조건 4개 이상

1.if문을 통해 만약 도서명과 저자 그리고 출판자를 입력 하지 않을 경우 flase로 
만듬
2.저자를 입력 하지 않을 경우 flase로 
만듬

3.출판자를 입력 하지 않을 경우 flase로 
만듬

4.출판연도가 1900~2024년도 사이가 아니라면 flase로처리함

RWD  : Desktop과 Mobile 환경을 어떻게 구성했는지 설명:

데스크탑에서는 header부분이 붉은색이 나오도록 만들고 모바일상태이면 폰트사이즈를 줄이고 haeder부분의 색도 갈색으로 바끔

Bootstrap : 사용한 Bootstrap Component 또는 Class
:
text-center ,Buttons ,Tables ,Flexbox ,CDN 등

Problem & Solution : 개발 중 발생한 문제와 해결 방법

:개발중 자바스크립트에 대해 전혀 몰라서 힘들었지만 재미나이를 통해 물어보며 많은것을 배움


Reflection : 새롭게 알게 된 점 또는 궁금한 점

:js에서 일반 코딩처럼 연결되지 않은 복수의 html에서 어떻게 대이터를 선언하고 선언된 데이터를 사용하늕 몰랐으나 로컬스토리지에 넣어서 그걸 사용할떄 다시 빼서 사용하는 식으로 작동한다는 사실을 알게됨.

 *rem단위 찾아보기!!! =>>기본 픽셀 단위인 16px에 곱해지는 수 /사용하는 이유는 기본 폰트사이즈를 즐리면 자동으로 폰트에 적용시키기 위해서 사용

 궁금한점:왜 이제껏 git push는 닥 html에서 각각해야 됐는데 이번 과제에서 한번 push하니까 다른 html에서 다 푸쉬가 되는가?
 그리고 버셀에서 그냥 비짓으로 들어가면 css적용이 안되는 이유가 뭘까?

<!--
수업중 필기 내용
반응형 웹(rwd/responsive web)
디스플레이의 크기에 따라 다르게 보이는 웹
 구성요소
 
 fluid grid
 고정 픽셀대신 %나 fr단위 사용

 flexinle images
 이미지가 부모요소

 *inline 과 block의 차이 이해할 것!!!

 media Queries
 특정 조건에 따라 css 스타일 적용
orientation
min-width
max-width
hover,pointer
(위치가 중요/모바일의 경우css의 가장 마지막에 적용해야함)
 
 *rem단위 찾아보기!!! =>>기본 픽셀 단위인 16px에 곱해지는 수 /사용하는 이유는 기본 폰트사이즈를 즐리면 자동으로 폰트에 적용시키기 위해서 사용

 css framework
 자주 사용하는 css스타일과 ui컴포넌트를 미리 정의한 도수
 대표적
 bootstrap,tailwind,css bulma
 
 bootstrap사용법
 
 1)cdn(content delivery network):풀주소를 가지고 와서 사용/소도 빠름

 2)doenload

 3)

 절대패스/상대패스
 절대패스(루트기준['/'=루트라고 부름]) 상대패스(지금 내 위치 기준[''..''=부모 '.'=현재])
 

 -->

