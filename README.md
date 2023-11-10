<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=100&section=header" />

<!-- 프로젝트에 대한 요약 설명 및 연계 서비스나 동작에 대한 설명을 작성합니다. -->
# 설명
> **Note**
>
> 
<br>
<br>

<!-- 프로젝트 개발 환경 구성 방법에 대한 설명과 실행 방법등 중요사항을 작성합니다. -->
# 개발 환경
| Tool | Version |
|-----|-----:|
| eclipse        | 2023-09        |
| gradle         | 7.6-bin        |
| java           | 1.7            |
| tomcat         | 10.1           |
| springboot     | 3.0.2          |
| mariadb        | 11.1.2         |
> **Important**
>
> 
<br>
<br>

<!-- 이용중인 개발툴에서 git을 내려받아 프로젝트를 구성하는 방법을 설명합니다.  -->
# 개발 설치 방법
1. git 정보 copy
2. eclipse > Import > Project from Git > Clone URI > next click
<br>
<br>

<!-- 웹페이지가 있는 서비스의 경우에 한하여 운영 환경별로 접근 링크를 작성하여 주고
화면이 없는 서비스의 경우 적용된 서버의 ip 목록을 작성하여 줍니다. -->
# 서버 링크
### Operational Temporary URL
> 관리자 URL : [http://xxx.zzzzzz.com:9000/](http://xxx.zzzzzz.com:9000/)  
> 대시보드 URL : [https://xxx.zzzzzz.com/auth](https://xxx.zzzzzz.com/auth)  
### Test URL
> 관리자 URL : [http://xxx.yyyyyy.org:9000/](http://xxx.yyyyyy.org:9000/)  
<br>
<br>

<!-- 소스를 서버에 배포하는 과정 또는 방법을 작성하여 줍니다. -->
# 배포 절차
1. build.gradle 파일에서 "task sync_export"의 from file에 war파일의 경로 수정  
befor : from file('C:/aaa/bbb/build/libs/project-0.0.1-SNAPSHOT.war')  
after : from file('D:/ccc/ddd/project/build/libs/project-0.0.1-SNAPSHOT.war')  
2. 이클립스의 gradle task 탭에서 custom > sync_export를 더블클릭
3. 바탕화면에 생성되는 ROOT.war 파일을 서버의 tomcat > webapps에 이동
4. 톰캣 재기동
<br>
<br>

<!-- 서비스 내용 관련 큰 틀에서 보안에 이슈가 없는 내용을 작성하여 줍니다. -->
# 참고사항
### 사용자 권한
| User | Permissions |
|:-----:|-----|
| 슈퍼관리자 | 시스템 관리자로 회원 등록 및 권한 설정 등의 시스템 운영 관리 |
| 관리자 | 일반사용자 및 업무를 관리 |
| 일반사용자 | 관리자와 소통을 위한 시스템 사용자 |
| 협력사용자 | 일반사용자의 화면을 모니터링하는 시스템 사용자 |

<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=100&section=footer" />
