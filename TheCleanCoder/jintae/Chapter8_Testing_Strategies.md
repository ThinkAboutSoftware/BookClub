<hr>

# 8.
# 테스트 전략
<hr>

## discussion

### Q. 
이번 챕터의 내용과는 동떨어지지만.. 읽으면서 궁금한 점이 있어 토론 내용으로 정했습니다!

- 자신이 겪어보지 않은 것들을 이해하거나 공감하는데엔 어떤 방법이 있을까요??

### A. 
- 저는 QA팀과 무언갈 해본 적이 없습니다. 여기 나오는 테스트들도 단위 테스트 말고는 해본적이 없구요.. 눈으로는 읽히는데 머리로는 상상이 잘 안되더군요. <br>
저같은 경우엔 실제로 경험을 해야 이해하는 편이였습니다. 


## Reviews
### QA는 오류를 찾지 못해야 한다

- 오류를 생각해 내는 것이 제일 어려운 일인 것 같아요.
    - 코드의 결점을 찾아 낼 수 있는 능력은  결국 경험 뿐이겠죠..?

#### QA는 같은 팀이다.

- 기획 단계에서도 QA와 같이 작업한다면 한결 수월할 것 같다는 생각을 해봅니다..

### 테스트 자동화 피라미드

#### 단위 테스트

- 제품 코드를 명세하려고 만드는 테스트.

#### 컴포넌트 테스트

- 인수테스트의 일종.
- 해당 업무규칙을 테스트한다.

#### 통합 테스트

- 여러 컴포넌트로 이루어진 큰 시스템에서만 의미가 있다!.
- 컴포넌트 묶음을 모아 묶음끼리 상호작용하는지 테스트한다.

#### 시스템 테스트

- 궁극적인 통합 테스트.
- 자주 돌리면 더 좋다!

#### 수동 탐색 테스트

- 가능한 많은 특이사항을 창의적으로 발견해내는 일이 목표다.

### 결론

- 테스트를 가능한 자주 실행해 시스템이 무결점 상태를 계속 유지하는지 확인해야 한다.