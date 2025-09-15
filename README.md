# Match-Point 🎾

> Java 객체 지향 프로그래밍(OOP) 학습을 위해 대한 테니스 협회에서 제공하는 공식 문서를 기반으로 한 스코어링 규칙 (2020 ver.) 을 구현한 콘솔 기반 테니스 스코어링 애플리케이션입니다.

## 🎬 실행 화면 (Screenshot)

## 🎯 프로젝트 소개 (About The Project)

이 프로젝트는 Java의 객체 지향 프로그래밍(OOP) 개념과 클린 코드 원칙을 실제 애플리케이션에 적용하며 체득하는 것을 목표로 하는 개인 프로젝트입니다. 요구사항 분석, 아키텍처 설계부터 구현, 테스트에 이르는 소프트웨어 개발의 전체 생명주기를 경험하며 실무 역량을 함양하는 데 중점을 둡니다.

## 🚀 주요 기능 (Key Features)

* **사용자 정의 경기 설정**: 3/5세트, 타이브레이크 여부, 선수 이름 등 커스텀 가능
* **실시간 스코어보드**: 매 득점마다 현재 점수와 서브권을 콘솔에 출력
* **정식 테니스 규칙 완벽 구현**: 듀스, 어드밴티지, 타이브레이크 등 ITF 규칙 기반 스코어링
* **경기 로그 파일 생성**: 경기 종료 후, 전체 경기 기록을 담은 텍스트 파일 자동 생성

## 🛠️ 기술 스택 (Tech Stack)

* Language: `Java 17`
* Build Tool: `Gradle`
* Testing: `JUnit 5`

## 🏁 시작하기 (Getting Started)

이 프로젝트를 로컬 환경에서 실행하는 방법입니다.

### **Prerequisites**

* Java (JDK 17 이상)
* Git

### **Installation & Run**

1.  레포지토리를 복제(Clone)합니다.
    ```sh
    git clone https://github.com/Yeji-Kim-Erica/match-point.git
    ```
2.  프로젝트 폴더로 이동합니다.
    ```sh
    cd match-point
    ```
3.  (추후 Gradle 설정 완료 시 빌드 및 실행 명령어 추가 예정)
    ```sh
    # 프로젝트 빌드
    ./gradlew build

    # 프로그램 실행
    ./gradlew run
    ```

## 🏛️ 아키텍처 (Architecture)

이 프로젝트는 역할과 책임 분리를 위해 **계층형 아키텍처(Layered Architecture)**를 적용했습니다.
* **View**: 사용자의 입출력을 담당합니다.
* **Controller**: 핵심 비즈니스 로직과 경기 흐름을 제어합니다.
* **Domain/Repository**: 데이터 객체와 파일 저장 로직을 담당합니다.

보다 자세한 설계 결정 과정은 `DESIGN.md` 파일을 참고해주세요.

## 📜 라이센스 (License)

이 프로젝트는 MIT 라이센스를 따릅니다. 자세한 내용은 `LICENSE` 파일을 참고해주세요.