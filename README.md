## 로또 미션 저장소
### Effective Swift
NEXTSTEP with yagom-academy

### 기능 요구 사항
- 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환합니다 (예: "" => 0, "1,2" => 3, "1,2,3" => 6, "1,2:3" => 6)
- 문자열 계산기에 숫자 이외의 값 또는 음수를 전달하는 경우 Error를 throw 합니다.

### 이번 프로젝트 진행 Flow
1. 구현 기능 목록 작성
2. 해당 기능 목록을 토대로 테스트 케이스 작성
3. 테스트 케이스를 토대로 실패하는 기능 먼저 구현
4. 실패를 확인하고 최대한 빠르게 우선 성공하는 기능 구현
5. 리팩토링
6. 1...5 반복

### 구현 기능 목록

- 문자열 입력
    - 문자열 입력 유효성 검사
    - 쉼표 또는 콜론을 구분자로 나눈 배열 반환하는 메서드
- 문자열 계산
    - 문자열 계산기 유효성 검사
