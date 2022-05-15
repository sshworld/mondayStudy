# Git Commit Message 규칙

- 제목과 본문을 한 줄 띄워 분리하기

- 제목은 영문 기준 50자 이내로

- 제목 첫 글자를 대문자로

- 제목 끝에 . 금지

- 제목은 명령조로

- 본문은 영문 기준 72자마다 줄 바꾸기

- 본문은 어떻게보다 무엇을, 왜에 맞춰 작성하기

## Commit 유형 지정



- FEAT : 새로운 기능의 추가

- FIX : 버그 수정

- DOCS : 문서 수정

- STYLE : 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)

- REFACTOR : 코드 리팩토링

- TEST : 테스트 코트, 리팩토링 테스트 코드 추가

- CHORE : 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우), 그 외 자잘한 수정

## Commit Message 구조

    type(타입) : title(제목)

    body(본문, 생략 가능)

    Resolves : #issue, ...(해결한 이슈 , 생략 가능)

    See also : #issue, ...(참고 이슈, 생략 가능)

 

EX)

영문

[FEAT] : Add defense codes in ‘inputDecode()’ - Issue # 35

국문

[FEAT] : ‘inputDecode()’의 방어 코드 추가 - 이슈 # 35

## 출처

- https://meetup.toast.com/posts/106