### 단위 테스트 정의
- 작은 코드 조각을 검증하고,
- 빠르게 수행하고, 
- 격리된 방식으로 처리하는 자동화 테스트

#### 단위 테스트의 고전파와 런던파
- 고전파 : 모든 의존성 같이 테스트
- 런던파 : 테스트 대상 시스템을 협력자에게 격리 (mock 사용)

### 좋은 테스트 4대 특성
- 회귀 방지(거짓 음성)
- 리팩터링 내성(거짓 양성)
  - SUT가 수행한 단계가 아니라(세부사항) SUT가 만든 최종 결과를 검증해야 한다(요구조건) 
- 빠른 피드백
- 유지보수성

### 블랙박스테스트 / 화이트박스 테스트
- 블랙박스 테스트 : 내부 구조를 몰라도 시스템의 기능을 검사할 수 있는 소프트웨어 테스트 방법 (명세와 요구사항)
- 화이트박스 테스트 : 애플리케이션의 내부 작업을 검증하는 테스트 방식 (소스 코드에서 파생)
 
- 테스트를 작성할 때는 블랙박스 테스트. 테스트를 분석할 때는 화이트박스 테스트

### 목과 스텁
- 목은 외부로 나가는 상호 작용을 모방하고 검사하는데 도움이 된다.
- 스텁은 내부로 들어오는 상호 작용을 모방하는 데 도움이 된다.
