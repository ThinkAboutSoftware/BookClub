# ch 5 TDD
- TDD는 잘돌아간다 받아들여라
- 작성한 코드가 전부 잘돌아가는지 알지 못하면 프로라 할 수 있는가?
- 변경할 때마다 테스트
- TDD 원칙
    - 실패한 단위 테스트를 만들기 전에 제품코드를 만들지 않는다
    - 컴파일이 안되거나 실패한 단위 테스트가 있으면 더 이상의 단위 테스트를 만들지 않는다
    - 실패한 단위 테스트를 통과하는 이상의 제품 코드는 만들지 않는다.
    - 30초 길이 유지
- 혜택
    - 확신
    - 결함 주입 비율
    - 용기 : 변경에 대한 두려움이 사라진다 => 가장 좋은 점이라고 생각함
    - 문서화 
    - 설계 : 테스트를 먼저 만들기 위해 좋은 설계를 고민한다 => 필요한 부분이다!
        - 의존성이 낮은 좋은 설계를 만드는 힘
    - 프로다운 선택
- 질문 : 해로운 점?

해야지 해야지 언제해
회사가 원하는 걸 개발해서 회사의 비즈니스가 먼저냐, 개발자의 원칙이 먼저냐 의문이 들 때가 있다.
당장 눈앞에 보이는 무언갈 만드는게 중요한 경우가 다반사다.
아래와 같이 연습으로 눈감고도 TDD를 하는 경지가 아니면 사실 어렵다.
회사와 비즈니스가 존재하니 개발을 하지, 장인들이 모여 경지에 도달하고자 하는게 개발이 아니기 떄문에..