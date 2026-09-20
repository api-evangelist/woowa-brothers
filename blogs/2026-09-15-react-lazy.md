---
title: "집 나간 네트워크는 돌아왔는데 React.lazy는 왜 안 돌아올까"
url: "https://techblog.woowahan.com/27330/"
date: "2026-09-15"
author: "홍영민"
feed_url: "https://techblog.woowahan.com/feed/"
---
들어가며 파트너(업주)님이 영업 내내 주문을 받는 배민주문접수 웹뷰를 개발하던 중 QA 과정에서 네트워크 OFF -> ON으로 변경 후 다른 화면으로 이동 시 오류 화면이 노출된다는 티켓을 전달받았습니다. 원인을 파악해 보니 브라우저가 모듈 로드 실패를 기억하고 있었고, 이는 버그가 아니라 HTML 스펙에 명시된 동작이었습니다. 더 곤란한 것은 프런트엔드 빌드 도구인 Vite 공식 문서가 안내하는 해결책 중 […] The post 집 나간 네트워크는 돌아왔는데 React.lazy는 왜 안 돌아올까 first appeared on 우아한형제들 기술블로그 .
