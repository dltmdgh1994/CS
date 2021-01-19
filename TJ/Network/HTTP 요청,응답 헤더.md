# HTTP 요청,응답 


## Request Header


### - 요청 헤더는 HTTP 요청 메시지 내에서만 나타나며, 가장 방대


1) HOST - 요청하는 호스트에 대한 호스트명 및 포트 번호

2) USER_Agent -클라이언트 소프트웨어(브라우저 및 OS) 명칭과 버전 정보

3) Cookie -서버에 의해 Set-Cookie로 설정된 클라이언트의 쿠키 정보

4) Refere -바로 직전에 머물렀던 웹 링크 주소
          -CSRF 공격을 막기 위한 Referer 검증에 사용
          
5) Authorization -인증 토큰 (JWT/Bearer)을 서버로 보낼 때 사용

6) Origin  -POST 요청을 보낼 시, 요청이 어느 주소에서 시작되었는지 표시
           -요청을 보낸 주소와 받는 주소가 다르면 CORS 에러 발생
           
           
           

## Response Header


1) Server - 서버 소프트웨어 정보
2) Set-Cookie - 서버 측에서 클라이언트에게 부여하는 쿠키 정보

3) Expires - 리소스 캐시 만료 일시

4) Allow - 해당 엔티티에 대해 서버 측에서 지원 가능한 HTTP 메소드의 리스트

5) Access-Control-Allow-Origin - CORS 요청을 허용하는 도메인           
           
