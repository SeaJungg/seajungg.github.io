---
layout: post
title: "Node js 모듈화 어떻게 진행하고 왜 진행할까?"
category: inProgress
---

### 현상 파악
- 소스별로 코드 길이가 너무 길어지고 있다.
- 간단한 반영인데 반영절차가 복잡하다(재시작 등)


### 문제 정의
- 난 솔직히 문제 아니라고 생각함 (긴 게 왜 문제? 여러 개인게 더 문제 아님?)


### 도입한 내용
- node:vm 을 가져와서 '파일 전처리' 같은 비즈니스 로직에 밀착되어 있는 단순 작업들은 그 안에서 돌리도록 처리.

### 솔직히 뭐가 좋은지 모르겠음. 모듈화가 아직은 오버테크놀로지인지?