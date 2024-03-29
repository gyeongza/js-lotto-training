# 🚀 구현 기능 목록

<br />

> TDD 방법론에 따른 기능 구현 [테스트 코드 작성 - 기능 구현 - 테스트 - 커밋]
<br />

### 메인 로직

- (UI/입출력) 로또 구매 금액 입력 기능
- (UI/입출력) 구매한 로또번호 출력 기능
    - (Logic/생성) 랜덤 로또번호 생성 기능(오름차순 정렬)
- (UI/입출력) 당첨번호 입력 기능
- (UI/입출력) 보너스 번호 입력 기능
    - (Logic/비교) 구매한 번호 목록과 당첨번호 비교 기능 
- (UI/입출력) 당첨 통계 출력 기능 (당첨내역, 수익률)

### 에러 처리 [ERROR] / 테스트 케이스 작성

- (UI/입출력) 로또 금액 입력 에러
    - 숫자가 아닌 경우 예외 에러 처리
    - 천원 단위가 아닌 경우 에러 처리
- (UI/입출력) 당첨번호 입력 에러
    - 숫자가 아닌 경우 에러 처리
    - 개수가 올바르지 않은 경우 에러 처리
    - 숫자가 범위를 벗어난 경우 에러 처리
    - 중복된 숫자가 있는 경우 에러 처리
- (UI/입출력) 보너스 번호 입력 에러 
    - 숫자가 아닌 경우 에러 처리
    - 숫자가 범위를 벗어난 경우 에러 처리
    - 보너스 번호가 당첨번호에 포함될 경우 예외 처리

---