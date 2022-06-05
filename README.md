# crolling
mini project about crolling

OPEN API 문서 보는 방법

https://blogfiles.pstatic.net/MjAyMjA2MDRfMjYx/MDAxNjU0MzQ5MzQ1NTcz.AYUOH41cQItwQn2Rxzat6oMw3hI-eryvD2QlSM4LRY8g.DsPeUhsLVqTyBMV9YtaYXjVHFB1Kdy48oh__y76oXAIg.PNG.wjd3279/그림1.png?type=w2![image](https://user-images.githubusercontent.com/46236112/172041571-f4f53521-e713-416f-b6e0-357242ca4f54.png)

 
OPEN API: 제공처에서 backend를 만들어 놓고, 그 backend를 이용하는 방법을 제공
                   => backend 주소와 사용 규칙만 알면 backend 자원 사용 가능
                   
https://blogfiles.pstatic.net/MjAyMjA2MDRfMTUx/MDAxNjU0MzQ5MjcwNDkz.G2IY12h6LKPIjp31biadAe5PsWx1kH4nBwDhS73XVHYg.lf3XNOdYdTdZn2Se3PwYom_fkD9KiaheDBNz8gpS0Cwg.PNG.wjd3279/그림2.png?type=w2![image](https://user-images.githubusercontent.com/46236112/172041583-354fb04c-36b7-4cda-b057-68e697415428.png)


API guide
request
1. 주소 https://... -> (API 주소)
2. 전송 방식: GET
3. 보낼 것
   Query 검색어
   sort
   page
   ...


response
1. 형식: JSON
2. 응답 의미 설명
   collection
   thumbnail_url
   Image_url

요청 실패 시, status code나 response value를 통해 오류 코드를 보냄

================================================================================

REST API
: REST를 기반으로 만들어진 API

REST
:Representational State Transfer
HTTP URI(Uniform Resource Identifier)를 통해 자원 명시
-> HTTP Method(POST, GET, PUT, DELETE)를 통해 자원에 대한 CURD Operation 적용

API key
:특정 사용자만 알 수 있는 문자열
개발자 - API를 호출할 때 사용
서버 - 누가 API를 호출하는지 추적 가능

