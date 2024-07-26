# 도서 관리 시스템 

## 프로젝트 개요
도서관에서 책과 회원을 관리하기 위한 간단한 콘솔 애플리케이션입니다.<br>
이 프로그램을 통해 도서를 추가, 삭제, 검색, 대출 및 반납할 수 있으며, 회원을 관리하고, 도서 리뷰를 작성하고, 카테고리별 도서 통계를 볼 수 있습니다.<br>
이 시스템은 도서관 관리의 효율성을 높이고, 사용자에게 직관적인 인터페이스를 제공합니다.


## 주요 기능
- **도서 추가, 삭제, 검색**
- **도서 목록 보기**
- **도서 대출 및 반납**
- **회원 추가 및 삭제**
- **도서 정보 수정**
- **카테고리별 도서 검색**
- **도서 리뷰 작성**
- **카테고리별 도서 통계 보기**

## 사용 방법
1. **프로젝트 클론 및 빌드**
    ```sh
   git clone <your-repo-url>
   cd <your-repo-directory>
3. **프로젝트 실행**
- **IDE (IntelliJ, Eclipse 등)에서 LibraryManagementSystem 클래스를 실행합니다.**
- **커맨드 라인에서 다음 명령어로 실행합니다**
  ```sh
  javac LibraryManagementSystem.java
  java LibraryManagementSystem
5. **기능 사용**
- **실행 후, 메뉴에서 원하는 기능을 선택합니다.**
- **각 기능에 필요한 정보를 입력합니다.**

## 기술 스택
- **프로그래밍 언어: Java**
- **컬렉션 프레임워크: ArrayList, HashMap**
- **스트림 API: Java Stream API를 사용하여 도서 검색 및 통계 처리**
## 리뷰 포인트
- **객체 지향 프로그래밍: 클래스 간의 책임 분리 및 협력**
- **컬렉션 및 스트림 사용: 데이터 관리 및 처리의 효율성**
- **유저 인터페이스: 콘솔을 통한 사용자와의 상호작용**
## 부족한 점
- **데이터 영속성: 현재 메모리 내에서만 데이터가 관리되며, 프로그램 종료 시 데이터가 사라짐**
- **예외 처리: 사용자 입력 오류 및 기타 예외 상황에 대한 처리 미흡**
- **확장성: 기능 추가 및 변경 시 구조적 변경이 필요할 수 있음**
## 히스토리
# 버전 1.0 (2024-07-25)
- **도서 관리**: 도서 등록, 수정, 삭제 및 조회 기능
- **회원 관리**: 회원 등록, 수정, 삭제 및 조회 기능
- **대여 관리**: 도서 대여 및 반납 기능

# 버전 1.1 (미정)
- **데이터베이스 연동**: 데이터베이스를 통한 데이터 저장 및 조회 기능 추가 예정
- **예외 처리 강화**: 안정성을 높이기 위한 예외 처리 로직 강화 예정
- **GUI 지원**: 사용자 친화적인 그래픽 사용자 인터페이스(GUI) 기능 추가 고려 중
