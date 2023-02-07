# Choi Yoon Sun | 최윤선 포트폴리오

***'코딩은 무엇이지?'*** 라는 의문의 시작으로<br>
***Python, Flask, Django, DRF, Docker, NGINX, Gunicorn, AWS를 통한 배포*** 에 대한 배움과<br>
호텔리어 출신으로 다정하고 빠른 눈치로 인해 팀원들의 멘탈케어 하는 방장의 역활 <br>
등 끊임없이 성장하고 배우는걸 좋아하는 백엔드 주니어 개발자 최윤선입니다! <br>

## 📱Contact
- 이메일: bristol9128@naver.com
- 블로그: https://azalea-keep-in-mind.tistory.com/
- Github: https://github.com/yoonsun9128

---

## 📂 My Project
### 1. ThumBook
- 목적

        1. yes24에 등록된 책 데이터를 크롤링하여 정보 소개
        2. 다른 유저의 평점에 기반하여 사용자 선택에 따른 책 추천
        3. 게시글을 통해 책 리뷰를 소통하는 웹서비스
        4. 마지막 캠프 기간동안 배운 CRUD 과정을 다시 되돌아 보기 위한 서비스

- 프로젝트 일정 : 22.12.02 ~ 22.12.28 (4주)
- 배포 사이트 :  https://www.thumbookfe.ml/
- Git Link : <a href="https://github.com/yoonsun9128/Book_Space">프로젝트 내용</a>

- 팀 프로젝트
    - 팀구성 : 5명
    
- 나의 활동

        1. 데이터베이스 모델링
        2. yes24 책 정보 beautifurSoup을 이용하여 크롤링한 데이터 모음
        3. 평점을 기준으로 한 추천 시스템
        4. 회원가입 및 로그인 시 시리얼라이즈 validate를 통한 유효성 검사
        5. 원하는 책이 없을 경우 모델이 생성하며 게시물 작성가능하게 끔 설정
        5. 비밀번호 재설정(django에서 기본적으로 제공하는 PasswordResetView 사용)
        6. 회원 정보 수정시 비밀번호 확인 후 가능하게 끔 설정(check_password)
        7. Q를 사용한 검색 기능
        8. 테스트 코드 작성 중
        
- 사용 기술
    - 백엔드
        - Python | Django | Django REST framework | Djnago Rest framework simple-jwt | SMTP
    - 프론트 엔드
        - Javascript | HTML | CSS
    - DB
        - Sqlite3 | PostgreSQL | AWS S3
    - 배포
        - Docker | AWS EC2 | AWS Route53 | Gunicorn | Nginx | cloudFront
- 노션 링크 : <a href="https://bitter-trunk-e9a.notion.site/A1-c8728c9326d147d3b8dae30a8eba570c">트러블 슈팅 및 사용자 피드백 모음</a>
- 회고 및 느낀점
    - 프로그램을 만들때는 코드를 활용적으로 작성하는것도 중요하지만, 사용자가 이용했을시 불편한 점이 없도록 만드는게 중요하다는 생각이 들었다.
    - 처음으로 배포하는 과정을 지켜보며, 로컬 환경과 배포 환경이 서로가 다른 부분을 확인하고 동일하게 맞춰줘야하는 부분을 체크해가며 시도해야겠다는 생각이 들었다.
    - 테스트 코드를 미리 작성했다라면, 배포 후 받을 피드백을 줄일 수 있지 않을까 하며, 테스트 코드의 중요성을 다시 한번 깨달았다.
    
- 시연 연상 : <a href = "https://www.youtube.com/watch?v=DP8B0_Z7l-w">시연영상</a>

### 2. 텔레토비 인쇄소

- 목적

        1. Djnago의 기본 user model이 아닌, custom user model 사용
        2. 유화 제작 인공지능 기술(NST)을 사용하여 이미지의 스타일을 변환하여 게시글을 생성
        2. 게시글, 댓글 생성한 SNS 서비스
        
- 프로젝트 일정 : 22.11.22 ~ 22.11.28 (1주)
- Git Link : <a href="https://github.com/yoonsun9128/teletubbies_print_BE">프로젝트 내용</a>
- 팀 프로젝트
    - 역할 : 팀장
    - 팀구성 : 5명
    
- 나의 활동

        1. 머신러닝 이용한 유화제작 시스템
            -> 사용자가 합치고 싶은 사진을 업로드 하면 output_image로 두 사진이 섞인 이미지 보여주기
        2. 좋아요 기능
        
- 사용 기술
    - 백엔드
        - Python | Django | Django REST framework | Djnago Rest framework simple-jwt
    - 프론트 엔드
        - Javascript | HTML | CSS
    - 머신러닝
        - OpenCV | Tensorflow
    - DB
        - Sqlite3
- 회고 및 느낀점
    - 데이터베이스 설계에 대한 중요성을 알았다. 원래 목적은 포토카드를 만들어주는 사이트를 만들고 싶었으나, 모델간의 관계를 잘 이해하고 있지 않아 하루만에 다시 DB를 설계해야하는 아쉬움이 남은 프로젝트이다.



