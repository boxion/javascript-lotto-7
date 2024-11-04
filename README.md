# javascript-lotto-precourse

기능
1. 로또 번호 발행
  - 숫자 범위: 1~45
  - 번호 개수: 6개 (중복되지 않음)
  - 구입 금액: 사용자가 입력한 금액에 따라 로또 발행 수량 결정
  - 로또 한 장 가격: 1,000원
2. 당첨 번호 추첨
  - 당첨 번호: 중복되지 않는 6개 숫자
  - 보너스 번호: 중복되지 않는 1개 숫자
3. 당첨 기준 및 금액
  - 1등: 6개 번호 일치 - 2,000,000,000원
  - 2등: 5개 번호 + 보너스 번호 일치 - 30,000,000원
  - 3등: 5개 번호 일치 - 1,500,000원
  - 4등: 4개 번호 일치 - 50,000원
  - 5등: 3개 번호 일치 - 5,000원
4. 사용자 입력 및 출력
  - 로또 구입 금액: 입력받고, 1,000원 단위로 나누어 떨어지지 않을 경우 에러 처리
  - 당첨 번호: 사용자로부터 입력받음
  - 보너스 번호: 사용자로부터 입력받음
  - 당첨 내역 및 수익률: 구매한 로또 번호와 당첨 번호를 비교하여 출력
5. 에러 처리
  - 잘못된 입력 시 "[ERROR]"로 시작하는 메시지를 출력하고 재입력 요구
  - 예: 번호가 1~45 범위에 속하지 않거나, 구입 금액이 1,000원 단위가 아닐 경우
6. 프로그램 종료
  - 사용자 입력을 통해 로또 게임을 종료함
