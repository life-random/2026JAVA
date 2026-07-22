# 01. 자바 기초 및 Hello World 출력

자바 개발 환경 설정 후 가장 처음 작성해보는 basic 출력 실습 코드입니다.

---

## 1. 실습 코드 (`HelloWorld.java`)

```java
package ch01;

/**
 * 여러줄 주석
 * ctrl + alt + L <-- 코드 정렬 단축키 (IntelliJ)
 * 프로그래밍 세상과의 첫 인사
 * 화면에 문자열 Hello World를 출력하기
 */
public class HelloWorld {
    // <-- 한줄 주석 (컴파일러가 무시하는 영역입니다)
    public static void main(String[] args) {
        System.out.println("Hello, World"); // 명령의 끝은 ;(세미콜론)으로 알려준다.
        System.out.println(""); // 출력 후 다음 줄로 넘어가는 역할을 합니다(Line feed)
        
        // 화면에 숫자 0부터 9까지 출력하기
        System.out.println(0); // ctrl + d (해당 줄 복사)
        System.out.println(1);
        System.out.println(2);
        System.out.println(3);
        System.out.println(4);
        System.out.println(5);
        System.out.println(6);
        System.out.println(7);
        System.out.println(8);
        System.out.println(9);

    } // end of main

} // end of class
```
## 2. 핵심 개념 정리

### 1) 실행 흐름 (`main` 메서드)
* 기본적으로 코드가 실행되기 위해서는 **`main` 메서드 내부의 코드**가 실행되어야 합니다.
* **예외:** `main` 메서드 내부에서 다른 클래스나 외부/내부의 메서드, 객체를 호출하여 연계하여 실행하는 경우가 있습니다.

### 2) 콘솔 출력 (`System.out.println()`)
* 화면에 값을 출력하고 **자동으로 줄바꿈(Line Feed)**을 수행합니다.
* 괄호 `()` 안에 상수, 변수, 리터럴 등을 넣어 출력할 수 있습니다.
  * **문자열 (String):** 반드시 큰따옴표(`" "`)로 감싸야 합니다. (예: `"Hello World"`)
  * **단일 문자 (char):** 작은따옴표(`' '`)로 감쌉니다. (예: `'A'`)
  * **숫자 및 변수:** 따옴표 없이 그대로 입력합니다. (예: `123`, `x`)

---

## 3. 유용한 IntelliJ 단축키

| 단축키 | 기능 |
| :--- | :--- |
| `Ctrl` + `Alt` + `L` | **코드 자동 정렬** (포맷팅) |
| `Ctrl` + `D` | **현재 줄 복사**하여 바로 아랫줄에 붙여넣기 |
| `Ctrl` + `/` | **한 줄 주석** 생성 및 해제 (`//`) |
