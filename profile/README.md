![하트](https://github.com/silverCareer/.github/assets/84756243/b8e7c37c-cc8f-40e8-b9e5-c8c081bfeb82)# SilverCareer 

<p align="center"><img src="https://github.com/silverCareer/.github/assets/84756243/9190517a-bc37-4cdd-810b-b4f8acca051b" alt="로고" width="200px"></p>

<br>

> **디지털 하나로 1기 교육과정 3차 프로젝트**<br>
> **개발기간:** 2023.07.07 ~ 2023.08.30</p>

<br>

## 📽️ 시현 주소
> 

<br>

## 🖥️ 배포 주소
> https://www.silvercareer.shop/

<br>

## 🙋🏻‍♀️ 구성원
<table>
    <tr>
        <td align="center">곽동현</td>
        <td align="center">백연정</td>
        <td align="center">성창호</td>
        <td align="center">정재헌</td>
        <td align="center">한성훈</td>
    </tr>
  <tr>
        <td align="center"><a href="https://github.com/alivejuicy">@alivejuicy</a></td>
        <td align="center"><a href="https://github.com/baek0402">@baek0402</a></td>
        <td align="center"><a href="https://github.com/kylesung0520">@kylesung0520</a></td>
        <td align="center"><a href="https://github.com/drdd1120">@drdd1120</a></td>
        <td align="center"><a href="https://github.com/seonghunhan">@seonghunhan</a></td>
    </tr>
    <tr>
        <td align="center"><span> <img width="160px" src="https://github.com/silverCareer/.github/assets/84756243/077401f6-6932-477a-9cb5-bb6b43652689" ></span></td>
        <td align="center"><span> <img width="160px" src="https://github.com/silverCareer/.github/assets/84756243/151bfc38-cba9-40f8-8626-e02cb54037ce" ></span></td>
        <td align="center"><span> <img width="160px" src="https://github.com/silverCareer/.github/assets/84756243/e9e8311c-c6f6-4b1a-a93a-082a3629416a" ></span></td>
        <td align="center"><span> <img width="160px" src="https://github.com/silverCareer/.github/assets/84756243/171be7f2-4751-471f-98bb-c273bd672f11" ></span></td>
        <td align="center"><span> <img width="160px" src="https://github.com/silverCareer/.github/assets/84756243/bd0b3ad7-5feb-487e-bbfb-5c0140cc0835" ></span></td>
    </tr>
    <tr>
        <td>
            <ul>
                <li>백엔드</li>
                <li>JWT, Redis</li>
            </ul>
        </td>
      <td>
            <ul>
                <li>프론트엔드</li>
                <li>메인화면, 상품 관</li>
            </ul>
      </td>
      <td>
          <ul>
              <li>백엔드</li>
              <li>Jenkins, </li>
          </ul>
      </td>
      <td>
          <ul>
              <li>백엔드</li>
              <li>api</li>
          </ul>
      </td>
      <td>
          <ul>
              <li>프론트엔드</li>
              <li></li>
          </ul>
      </td>      
    </tr>
  
</table>

<br>

## 💡 프로젝트 소개
"SilverCareer"은 경력이 있고, 능력이있는 60세 이상의 중장년층들이 멘토가 되어 노하우를 판매하는 서비스입니다. <br>

- 은행 업무의 핵심인 여신으로 범위를 좁혔습니다.
- 행원 및 관리자들이 보다 편하게 ERP 시스템을 다룰 수 있도록 간결한 UI/UX로 사용성 부분을 개선하고자 하였습니다
- 여신상품 등록, 검색, 대출심사, 가입, 대출상환까지 여신 업무 전반에 대한 시스템을 개발하였습니다.
- 고객관리, 직원관리, 수신관리 등 기본적인 내용도 포함하였습니다.

<br>

## 📂 폴더 구조
```
├── README.md
├── .classpath 
├── pull_request_template.md
├── src/main
│   ├── SQL                            # 대출상환 자동화 프로시져 
│   ├── java
│   │   ├── Controller                 # 사용자 요청 처리 및 응답 
│   │   ├── DAO                        # 데이터베이스에 접근하는 Data Access Object 
│   │   ├── DTO                        # Data Transfer Object
│   │   ├── Filter                     # 문자 인코딩 
│   │   ├── Service                    # 비즈니스 로직 
│   │   └── util                       # 유틸리티 클래스 
│   ├── webapp 
│   │   ├── META-INF
│   │   ├── WEB-INF 
│   │   │     ├── components           # 팝업 관련 코드들 
│   │   │     ├── key                  # DB 접근 키
│   │   │     ├── view                 # Client가 접근하지 못하도록 보안 강화 
│   │   ├── css			       # css 스타일시트 파일 
│   │   ├── js			       # Java Script 파일 
│   │   ├── public		       # 이미지, 폰트 파일들
└────── └── index.jsp 
```
<br>


## ☁️ 시스템 아키텍쳐
![image](https://github.com/silverCareer/.github/assets/84756243/da3e2a0c-1904-4a5e-ba66-68795f2929b4)

<br>

## ⚙️ 기술 스택
### Environment
#### Front-end
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![Git](https://img.shields.io/badge/git-F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white)
### Communication
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Google Meet](https://img.shields.io/badge/Google%20Meet-00897B?style=for-the-badge&logo=google-meet&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
### Front-End
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
### Back-End
![JSP](https://img.shields.io/badge/JSP-000000.svg?style=for-the-badge&logo=jsp&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)

<br>

## ✏️ 기능 리스트
### 로그인
1. 행원/관리자 기능
2. 3분 로그인 세션 기능

### 메인 화면
고객, 직원, 여신, 수신 분류
1. 고객 검색 및 등록
- 고객 상세 정보 확인 가능
- (관리자) 고객 정보 수정 가능 
2. 직원 검색
3. 지점 검색
4. 여신 상품 검색
- 여신 상품 상세 정보 확인 가능
- (관리자) 여신 상품 수정 및 삭제 가능
5. 여신 상품 가입 내역 검색
- 고객 별 상환 내역 확인 가능
6. (관리자) 여신 상품 등록
7. 여신 상품 가입 
8. 계좌 검색
- 계좌별 입출금 내역 확인 가능
9. 계좌 생성

<br>

## ⚒️ 기술적 고려 사항
### PRG 패턴
1.  새로고침 이슈
    - Form 제출 이후 새로고침 시 중복으로 제출되는 이슈가 발생했다.
    - PRG 패턴을 도입하여 GET 방식으로 리다이렉션 시킴으로써 이슈를 해결했다.
### 보안
1.  세션
    - 보안성을 위해 쿠키 대신 세션을 도입했다.
    - 세션 Time-out을 3분으로 설정했고 시간이 지나면 자동으로 로그아웃 시킨다.
2.  암호화 및 해싱
    - 비밀번호를 SHA-256으로 해싱해서 DB에 저장했다.
    - 주민등록번호와 계좌번호는 AES-256으로 양방향 암호화해서 DB에 저장했다.
3.  SSL/TLS
    - SSL For Free에서 인증서 발급 받아 HTTPS 통신을 사용했다.
### DB Modeling
1.  파티셔닝
    - 입출금내역은 하루에 최소 수백만 건 이상 발생하고 1년이면 수십억 건이 쌓이기 때문에, 빠른 검색을 위해 시간을 기준으로 transaction_date 칼럼에 대해 파티셔닝을 도입했다.
    - MySQL 특성상 파티셔닝을 하려면 외래키 제약 조건이 없어야 한다. 계좌 ID, a_id에 대한 기존의 제약 조건을 해제했고, 이로 인해 발생하는 무결성 문제는 입출금 시 DB의 트랜잭션 기능을 사용하여 해결했다.
    - 하지만 외래키 제약 조건을 해제하면 인덱스도 해제되기 때문에 오히려 검색 속도가 더 저하된다. 이를 해결하기 위해 a_id에 대한 인덱스를 다시 설정했다.
2.  인덱스
    - users 테이블은 실제로 수천만명의 고객 정보가 등록되어 있기 때문에 빠른 검색을 위해 주민등록번호에 인덱스를 설정했다.
    - accounts 테이블에서도 마찬가지로 계좌번호에 인덱스를 설정했다.
    - 주민등록번호와 계좌번호를 AES-256으로 암호화하여 저장한 뒤에 인덱스를 설정하여 보안 문제를 최소화했다.
3.  프로시져
    - 대출상환이 자동으로 이루어지도록 이벤트 스케줄러와 프로시져를 활용하여 기능을 구현했다.
    - 9시에 그 날 상환이 이루어져야 하는 계좌 목록을 따로 테이블로 구성한다.
    - 10시부터 11시 40분까지 30분 간격으로 계좌를 체크하여 상환금보다 잔액이 크다면 출금을 수행한다.
    - 자정에 마지막으로 계좌를 체크하고 여전히 잔액이 상환금보다 작다면 연체를 기록한다.
