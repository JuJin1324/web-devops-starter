# web-devops-starter
Web 운영 관련 기초 지식 정리

## IaaS, PaaS, SaaS
* [참조링크](https://wodonggun.github.io/wodonggun.github.io/study/IaaS,-PaaS,-SaaS.html)

## Inbound / Outbound
* Inbound = ingress : 서버를 기준으로 외부 클라이언트에서 요청이 서버로 들어올 때 허용할 클라이언트의 IP 지정  
* Outbound = egress : 서버를 기준으로 트래픽을 밖으로 내보낼 때 허용할 IP 지정  
* 해당 서버가 **Stateful**하다 : Inbound의 정책을 그대로 기억하고 있어서 요청에 대한 응답을 내보낼 때 Outbound를 따로 지정해주지 않아도 요청한 IP로 응답을 내보내준다.
* 해당 서버가 **Stateless**하다 : Inbound의 정책을 기억하지 않고 요청에 대한 응답을 내보낼 시 Outbound 정책을 거쳐서 내보내기 때문에 요청한 클라이언트의 IP가 Inbound 뿐만 아니라 Outbound 정책에도 허용되어 있어야 한다.
* 참조링크: [방화벽 인바운드 아웃바운드 개념](https://m.blog.naver.com/PostView.nhn?blogId=blogpyh&logNo=220731762459&proxyReferer=https:%2F%2Fwww.google.com%2F)


## 마이크로서비스 아키텍처
* [마이크로서비스 아키텍처. 그것이 뭣이 중헌디?](http://guruble.com/%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%84%9C%EB%B9%84%EC%8A%A4microservice-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%EA%B7%B8%EA%B2%83%EC%9D%B4-%EB%AD%A3%EC%9D%B4-%EC%A4%91%ED%97%8C%EB%94%94/)
* [MSA 제대로 이해하기 -(1) MSA의 기본 개념](https://velog.io/@tedigom/MSA-%EC%A0%9C%EB%8C%80%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-1-MSA%EC%9D%98-%EA%B8%B0%EB%B3%B8-%EA%B0%9C%EB%85%90-3sk28yrv0e)
* [MSA 제대로 이해하기 -(2) 아키텍처 개요](https://velog.io/@tedigom/MSA-%EC%A0%9C%EB%8C%80%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-2-MSA-Outer-Architecure)
* [MSA 제대로 이해하기 -(3)API Gateway](https://velog.io/@tedigom/MSA-%EC%A0%9C%EB%8C%80%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-3API-Gateway-nvk2kf0zbj)

## Authentication(인증)과 Authorization(인가)의 차이
> **Authentication**: 유저가 누구인지 확인하는 절차(A라고 하며 접근하는 사람이 진짜 A인지 확인하는 절차)   
> **Authorization**: 어떠한 유저가 특정 자원에 접근하려 할때, 그에대한 접근 권한이 있는지 확인하는 절차

## Proxy
* [포워드 프록시(forward proxy) 리버스 프록시(reverse proxy) 의 차이](https://www.lesstif.com/system-admin/forward-proxy-reverse-proxy-21430345.html)

## Web Server
* [WSGI, WAS, CGI 이해](https://brownbears.tistory.com/350)
* [웹 서버 소프트웨어 Apache와 NginX 비교](https://cntechsystems.tistory.com/24)

## 이벤트 드리븐 아키텍쳐(Event Driven Architecture EDA)
* [요즘-제일-핫하다는-이벤트-드리븐-누구냐-넌](https://news.samsung.com/kr/%EC%9A%94%EC%A6%98-%EC%A0%9C%EC%9D%BC-%ED%95%AB%ED%95%98%EB%8B%A4%EB%8A%94-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%93%9C%EB%A6%AC%EB%B8%90-%EB%88%84%EA%B5%AC%EB%83%90-%EB%84%8C)
* [[프로그래밍 패러다임]이벤트 기반 프로그래밍(Event-based programming)](https://kamang-it.tistory.com/entry/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D-%ED%8C%A8%EB%9F%AC%EB%8B%A4%EC%9E%84%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EA%B8%B0%EB%B0%98-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8DEvent-based-programming)

## Docker
* [공식 사이트](https://www.docker.com/)
* [초보를 위한 도커 안내서 - 도커란 무엇인가?](https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html)

## Kubernetes
* [쿠버네티스란 무엇인가?](https://kubernetes.io/ko/docs/concepts/overview/what-is-kubernetes/)

## 메세지큐
* [참조링크](https://12bme.tistory.com/176)

## Kafka
* [공식 사이트](https://kafka.apache.org/)
* [참조링크](https://taetaetae.github.io/2017/11/02/what-is-kafka/)

## Reactive 프로그래밍

## TCP/IP

## HTTP
* [Http 통신과 Socket 통신 차이](https://mangkyu.tistory.com/48)
* [Http 프로토콜이란](https://gmlwjd9405.github.io/2019/04/17/what-is-http-protocol.html)

## 동기 / 비동기
* [참조링크](https://tech.peoplefund.co.kr/2017/08/02/non-blocking-asynchronous-concurrency.html)   
* [참조링크](https://leeph.tistory.com/24)

## three-tier architectures
* [3 Tier Architecture(3계층 구조)](http://blog.naver.com/PostView.nhn?blogId=limoremo&logNo=220073573980)   

## 가상화기술
* [가상화 기술이란?](https://selfish-developer.com/entry/%EA%B0%80%EC%83%81%ED%99%94-%EA%B8%B0%EC%88%A0%EC%9D%B4%EB%9E%80?category=825819)   
* [가상화 기술의 유형](https://selfish-developer.com/entry/%EA%B0%80%EC%83%81%ED%99%94-%EA%B8%B0%EC%88%A0%EC%9D%98-%EC%9C%A0%ED%98%95?category=825819)   
* [가상화기술 Type2](https://selfish-developer.com/entry/%EA%B0%80%EC%83%81%ED%99%94%EA%B8%B0%EC%88%A0-Type2?category=825819)   
* [가상화기술 Type1](https://selfish-developer.com/entry/%EA%B0%80%EC%83%81%ED%99%94-%EA%B8%B0%EC%88%A0-Type1?category=825819)   
* [1. Xen Project 소개](https://selfish-developer.com/entry/1-Xen-Project-%EC%86%8C%EA%B0%9C?category=825819)  

## CDN (Contents Delivery Network)
* [CDN(Contents Delivery Network) 이란?](https://goddaehee.tistory.com/173)   

## CIDR, Subnet mask
* [[네트워크 기초 지식] IP, CIDR 표기법, 서브넷 마스크](https://cjwoov.tistory.com/27)   

## CORS policy
자바스크립트에서 자바스크립트 파일의 도메인과 다른 도메인의 웹페이지 접근 혹은 다른 도메인의 API 호출 시 CORS policy...어쩌고 Error가 나타나게된다.
CORS가 무엇인지 다음의 링크를 참조하자.
* [Cross Origin Resource Sharing - CORS](https://homoefficio.github.io/2015/07/21/Cross-Origin-Resource-Sharing/)

## Protocol
* RDP(3389): 원격 데스크톱 프로토콜(Remote Desktop Protocol, 줄여서 RDP)은 마이크로소프트사가 개발한 사유 프로토콜로, 다른 컴퓨터에 그래픽 사용자 인터페이스를 제공하는 프로토콜이다.
