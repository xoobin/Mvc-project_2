1.HTTP 통신이란?
HTTP는 애플리케이션 계층에서 동작하는 하이퍼 텍스트 전송 프로토콜로, 
하이퍼 링크를 사용하여 인터넷에서 페이지를 로드하는 데 사용된다.
클라이언트-서버 시스템에서의 작업이 일반적이며, 
HTTP 요청에는 HTTP 버전 유형, URL, HTTP 메서드, HTTP 요청 헤더 및 본문 등이 포함된다. 



2.브라우저에 URL을 입력 요청 후 서버에서 응답하는 과정?
HTTP 통신 과정에서 클라이언트 측에서 HTTP 요청 헤더를 통해 서버 측으로 URL 입력을 요청하면
브라우저는 해당 URL의 DNS를 통해 서버의 IP 주소를 조회한 뒤 HTTP 또는 HTTPS 요청을 생성하여 서버로 전송한다.
이때 클라이언트가 서버에게 바라는 요청의 유형을 'HTTP 메서드' 라고 하는데, 대표적으로 GET,POST 등이 있으며 이는 HTTP 요청의 구조 중 '요청 시작 줄' 에 포함된다.
요청을 받은 서버는 클라이언트에게 HTTP 응답을 보내는데, 이때 HTTP 상태코드, HTTP 응답 헤더 등이 함께 전송된다.
HTTP 상태코드는 요청이 성공적으로완료되었는지에 대한 여부를 나타내는 세자릿수 코드로,
코드 뒷자리가 2로 시작한다면 HTTP 요청이 성공적으로 이루어졌음을 알 수 있고, 4 또는 5로 시작한다면 클라이언트 혹은 서버 문제로 인해 오류가 발생하여 요청에 실패했다는 의미로 적절한 조치를 취해야 한다.


