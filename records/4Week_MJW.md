## Title: [4Week] 문재원

## 미션 요구사항 분석 & 체크리스트

---
## 필수미션
1. 네이버 클라우드 플랫폼을 통한 배포


2. 내가 받은 호감리스트(/usr/likeablePerson/toList)에서 성별 필터링기능 구현

## 선택미션
1. 젠킨스를 통해 리포지터리의 main 브랜치에 커밋 이벤트가 발생하면 자동으로 배포가 진행되도록 구현


2. 내가 받은 호감리스트(/usr/likeablePerson/toList)에서 호감사유 필터링기능 구현


3. 내가 받은 호감리스트(/usr/likeablePerson/toList)에서 정렬기능 구현

---

## 체크리스트
- 네이버 클라우드 플랫폼 [X]
- 성별 필터링 기능 [O]
- 호감 사유 필터링 기능 [O]
- 정렬 기능 [X]
---
## **[접근 방법]**
필수미션 성별 필터링 기능은 InstaMemberBase에 선언된 gender 객체를 이용해서
성별을 필터링 하는 방법을 구현했다.

선택미션 호감사유 필터링 기능은 LikeablePerson에 선언된 attractiveTypeCode 객체를
Controller에 불러올 때 Controller에 선언된 attractiveTypeCode는 String 형식이여서
정수형으로 변환하는 Integer.parseInt를 사용하여 변환하고 기능을 구현하였다.


---

## **[특이사항]**
여전히 클라우드 플랫폼은 구현하지 못한 상태이다.

정렬 기능은 이번에 구현에 실패하였으나, 계속 구현 시도를 할 예정이다.