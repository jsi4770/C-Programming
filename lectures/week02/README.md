## 📌 Week 02 - C 프로그램의 구성

### 핵심 내용

- C 프로그램은 다음 요소로 구성됨
  - 헤더 파일
  - main() 함수
  - 변수 선언
  - 실행문

- 전처리기 지시문
  - `#include <stdio.h>`
  - 라이브러리 포함 역할

- main() 함수
  - 프로그램의 시작점
  - 실행 흐름의 중심

- 문법 요소
  - 세미콜론(;) → 문장 종료
  - 주석 → 코드 설명

---

### 핵심 흐름

C 프로그램 기본 구조:

```c
#include <stdio.h>

int main(void) {
    printf("Hello World");
    return 0;
}
