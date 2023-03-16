<div align="center">
  <a href="https://www.onjeong-app.com/">
    <img src="https://onjeong-prod.s3.ap-northeast-2.amazonaws.com/profile/24c4b2d3-be1c-4bd8-8d95-79e7a66ce23eonjeong%20logo.png?s=200&v=4" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Onjeong-Project</h3>

  <p align="center">
    <a href="https://github.com/On-jeong"><strong>1. Explore the Organization</strong></a><br>
    <a href="https://github.com/On-jeong/Onjeong-front"><strong>2. Explore Front-end Repository</strong></a><br>
    <a href="https://github.com/On-jeong/Onjeong-back"><strong>3. Explore Back-end Repository</strong></a><br>
    <a href="https://www.onjeong-app.com/swagger-ui.html#"><strong>4. Explore API Documents</strong></a><br>    
    <a href="https://www.erdcloud.com/d/9JxX7unXDjeZN5XHC"><strong>5. Explore ERD</strong></a><br>    
    <br />
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
### Table of Contents
  <ol>
    <li><a href="#프로젝트-소개">프로젝트 소개</a></li>
    <li><a href="#프로젝트-목표">프로젝트 목표</a></li>
    <li><a href="#aws-public-cloud-architecture">AWS Public Cloud Architecture</a></li>
    <li><a href="#tech-stacks">Tech Stacks</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


### 프로젝트 소개

**온정**은 `Spring Boot`와 `React Native`를 기반으로 가족들과 같이 꽃을 키워나가며 소통하는 **가족커뮤니케이션 앱**을 구현한 프로젝트입니다. <br/><br/>

- 저희 서비스를 통해 가족 구성원들이 서로 소통하면서 아래와 같은 `여러 활동들`을 경험할 수 있습니다.
   - 가족 프로필 생성
   - 기념일 작성
   - 오늘의 기록 작성
   - 이주의 문답
   - 편지 보내기
- 이 다양한 활동을 통해 가족구성원들이 함께 꽃을 피워냄으로써 **가족애**를 키우는 것이 저희 서비스 목표입니다.

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


### 프로젝트 목표

- 역할을 분담하여 기획한 서비스를 **구현**하고 **배포**해봅니다.
   - 구현하는 과정에서 Front-end와 Back-end가 **협업**하는 과정을 이해합니다.
       - RESTful API를 직접 설계하고 API를 통한 HTTP 통신을 겪으며 협업 능력을 기릅니다.
       - 자신이 맡은 부분을 남에게 설명할 수 있는 의사소통 능력을 기릅니다.
   - 단순히 구현 후 끝나는 것이 아닌 **코드 리뷰**와 **피드백**을 통해 함께 성장합니다.
   - 기존의 코드를 지속적으로 개선하기 위해 **리팩토링**을 진행합니다.
- Spring Boot와 React Native를 기반으로 다양한 기술 스택을 **학습**하고 **적용**합니다.

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


### AWS Public Cloud Architecture
![image](https://onjeong-prod.s3.ap-northeast-2.amazonaws.com/git/%EC%98%A8%EC%A0%95+aws+%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C+%EA%B5%AC%EC%A1%B0_2.png)

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Tech Stacks
<table>
	<tr><th rowspan="5">⚛Front-end</th><td>Language</td><td>JavaScript</td></tr>
	<tr><td>Library</td><td>React Native</td></tr>
	<tr><td>State Container</td><td>react-query & Recoil</td></tr>
	<tr><td>Component</td><td>Styled-Components</td></tr>
	<tr><td>Asynchronous</td><td>Axios</td></tr>
	<tr><th rowspan="8">🌱Back-end</th><td>Language</td><td>Java 11</td></tr>
	<tr><td>Framework</td><td>Spring Boot 2.4.2</td></tr>
	<tr><td>ORM</td><td>Spring Data JPA</td></tr>
	<tr><td>Authorization</td><td>Spring Security, JWT, Firebase</td></tr>
	<tr><td>API Documentation</td><td>Swagger</td></tr>
	<tr><td>Database</td><td>MySQL, H2, Redis</td></tr>
	<tr><td>Test</td><td>JUnit5, Mockito</td></tr>
	<tr><td>DevOps</td><td>Docker, Jenkins, Github Action</td></tr>
	<tr><th rowspan="3">👩‍👩‍👧Collaboration</th><td>Api Test</td><td>Postman, Swagger</td></tr>
	<tr><td>Communication</td><td>Notion, Google Meet, Zoom Meet</td></tr>
	<tr><td>Version Control</td><td>Github</td></tr>
	<tr><th>⛏️AWS Public Cloud Service</th><td colspan="2">EC2, RDS, S3, Route 53, VPC, Internet gateway, NAT gateway, NLB, Certificate Manager </td></tr>
</table>

<p align="right">(<a href="#top">back to top</a>)</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/haeun-i">
        <img src="https://avatars.githubusercontent.com/u/76279010?v=4" width="110px;" alt=""/><br />
        <sub><b>김하은</b></sub></a><br />
        <sub><b>Back-end</b></sub></a><br />
        <a href="https://github.com/haeun-i" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/Junhui0u0">
        <img src="https://avatars.githubusercontent.com/u/71383600?v=4" width="110px;" alt=""/><br />
        <sub><b>박준희</b></sub></a><br />
        <sub><b>Back-end</b></sub></a><br />
        <a href="https://github.com/Junhui0u0" title="Code">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/hyeonjin25">
        <img src="https://avatars.githubusercontent.com/u/65444249?v=4" width="110px;" alt=""/><br />
        <sub><b>소현진</b></sub></a><br />
        <sub><b>Front-end</b></sub></a><br />  
        <a href="https://github.com/hyeonjin25" title="Code">💻</a>
    </td>
  </tr>
</table>  

<p align="right">(<a href="#top">back to top</a>)</p>


