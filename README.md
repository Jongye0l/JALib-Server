# JALib-Server
### Jongyeol Adofai Library Server
![Java](https://img.shields.io/badge/Lang-Java-c9c8e4.svg?&logo=openjdk)
![Intellij Idea](https://img.shields.io/badge/IDE-Intellij_Idea-c9c8e4.svg?&logo=intellijidea)

---
### 소개
* Spring Boot 기반의 **[JALib](https://github.com/Jongye0l/JALib)** 전용 백엔드 API 서버입니다.
---
### 주요 기능 및 특징
* **Spring Boot 기반 웹 서버:** JALib 클라이언트 및 관련 도구들과 통신하기 위한 안정적인 REST API 및 엔드포인트 제공
* **모드 관리 및 배포 지원:** `ModApplicatorController` 등을 통한 모드 데이터 전송 및 Windows 등 플랫폼별 안내 페이지 템플릿(Thymeleaf) 내장
* **바이너리/패킷 핸들링:** 사용자 정의 패킷 구조(`ByteArrayDataInput`, `ByteArrayDataOutput`)를 통한 효율적인 데이터 직렬화 및 예외 처리
* **현지화(Localization):** 다국어(한국어/영어) 요청 처리를 위한 시스템 지원
* **GZip 압축 지원:** 네트워크 대역폭 최적화를 위한 파일 압축 및 데이터 전송 최적화
---
### 기술 스택
* **Backend:** Java 17 / Spring Boot
* **Build Tool:** Gradle
* **Template Engine:** Thymeleaf (웹 안내 및 모드 적용 페이지 구성)
---
### 라이선스
이 프로젝트는 **BSD 3-Clause License**를 따릅니다. 자세한 내용은 [LICENSE](./LICENSE) 파일을 참고해 주세요.

---
### 개발 환경 Development environment
* Windows 11
* Intellij Idea 2026.1.3
* Oracle OpenJDK 21.0.7
* Java 17
---
### 테스트 환경 Test environment
* Windows 11
* Oracle OpenJDK 21.0.7
---
# [Join My Discord!](https://discord.jongyeol.kr)
