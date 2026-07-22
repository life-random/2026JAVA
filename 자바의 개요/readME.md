# ☕ Java 기초 정리

![Java Logo](https://github.com/user-attachments/assets/fea3331f-5452-4ecb-a063-7efe8028e710)

## 1. Java란?

자바(Java)는 1995년 '썬 마이크로시스템즈(Sun Microsystems)'의 **제임스 고슬링(James Gosling)** 팀에서 임베디드 시스템을 위해 개발한 **객체지향 프로그래밍 언어(OOP)**입니다. 현재는 오라클(Oracle)에 인수되어 관리 및 배포되고 있습니다.

---

## 2. 객체지향 프로그래밍 (OOP)

자바는 대표적인 **객체지향 언어**입니다.

* **절차지향과의 차이점:** 코드를 순차적으로 실행하는 절차지향 언어와 달리, 독립된 단위인 **'객체(Object)'**들을 만들고 이들의 상호작용을 통해 프로그램을 구성합니다.
* **OOP의 4가지 주요 특징:**
  1. **추상화 (Abstraction)**
  2. **캡슐화 (Encapsulation)**
  3. **상속 (Inheritance)**
  4. **다형성 (Polymorphism)**

---

## 3. Java의 가장 큰 특징: JVM

자바의 가장 큰 강점은 **JVM(Java Virtual Machine, 자바 가상 머신)**을 사용한다는 점입니다.

* **운영체제(OS) 독립성:** "Write Once, Run Anywhere (한 번 작성하면 어디서든 실행된다)"라는 슬로건처럼, JVM 덕분에 개발자는 OS(Windows, macOS, Linux 등) 종류에 구애받지 않고 프로그램을 실행시킬 수 있습니다.

---

## 4. 통합 개발 환경 (IDE)

자바 프로젝트를 효율적으로 개발하기 위해 **통합 개발 환경(IDE, Integrated Development Environment)**을 사용합니다.

* **IntelliJ IDEA:** 현재 자바 개발에서 가장 보편적이고 강력한 기능을 제공하는 표준 IDE ([공식 사이트](https://www.jetbrains.com/idea/))
* **Eclipse:** 오랜 기간 사용되어 온 전통적이고 안정적인 IDE ([공식 사이트]([https://www.jetbrains.com/idea/](https://www.eclipse.org/downloads/))
* **VS Code:** 가볍고 다양한 언어 플러그인을 지원하는 범용 코드 에디터 ([공식 사이트]([[https://www.jetbrains.com/idea/](https://www.eclipse.org/downloads/](https://code.visualstudio.com/))

> 🔗 **Amazon Corretto (OpenJDK):** [Amazon Corretto 다운로드](https://aws.amazon.com/ko/corretto/)

---

## 5. 💡 오늘 요약: JDK vs JRE vs JVM

| 구분 | 개념 | 역할 |
| :--- | :--- | :--- |
| **JDK** | Java Development Kit | **개발 도구** (JRE + 컴파일러 `javac` 포함) |
| **JRE** | Java Runtime Environment | **실행 환경** (JVM + 자바 라이브러리 파일) |
| **JVM** | Java Virtual Machine | 자바 바이트코드(`.class`)를 읽어 해당 OS가 이해할 수 있는 **기계어로 변환 후 실행** |

> **포함 관계:** `JDK` ⊃ `JRE` ⊃ `JVM`
