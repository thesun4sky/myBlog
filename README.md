# MyBlog

이 프로젝트는 Spring Framework 기반의 프로젝트로 기본 게시판 기능을 구현하고있는 프로젝트 입니다.

## 디렉토리 구조
```bash
├── src                         # 소스 코드가 위치하는 디렉토리
│   ├── main                    # 메인 소스 코드가 위치하는 디렉토리
│   │   ├── java                # 자바 소스 코드가 위치하는 디렉토리
│   │   │   ├── comm.sparta.myblog  # 기본 패키지 이름
│   │   │   │   ├── controller  # 컨트롤러 클래스들이 위치하는 디렉토리
│   │   │   │   ├── dto         # DTO(Data Transfer Object) 클래스들이 위치하는 디렉토리
│   │   │   │   ├── entity      # 엔티티 클래스들이 위치하는 디렉토리
│   │   │   │   ├── repository  # 레포지토리 클래스들이 위치하는 디렉토리
│   │   │   │   ├── service     # 서비스 클래스들이 위치하는 디렉토리
│   │   │   │   └── MyBlogApplication.java  # 스프링 애플리케이션의 진입점인 메인 클래스
│   │   └── resources           # 리소스 파일들이 위치하는 디렉토리
│   │       └── static          # 리소스 중 정적인 파일들이 위치하는 디렉토리
│   │           └── index.html  # 첫 화면으로 출력할 HTML 코드
│   └── test                    # 테스트 소스 코드가 위치하는 디렉토리
├── build.gradle               # Gradle 빌드 스크립트 파일
├── settings.gradle            # Gradle 설정 파일
└── README.md                  # 프로젝트에 대한 설명이 담긴 마크다운 파일

``` 
