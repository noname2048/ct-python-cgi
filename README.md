# ct-python-cgi

- cgi는 CGI, FastCGI, WSGI, ASGI 등의 발전을 이뤘다.
- apache(java), tomcat(java), nginx(c) 와 같은 web-server 가http 요청을 먼저 받는다
- 이를 python 과 같은 언어로 서버를 구동하기 위해서 둘간의 인터페이스가 필요하다.
- CGI 1.1는 RFC 3875로 첫 표준화를 이룬다.

# 동기
- 인터페이스가 어떻게 구성되어있는지 궁금하다.
- os로 부터 ngxin가 요청을 어떻게 이어 받는지도 궁금하지만, 구현해본 사람이 별로 없을 것 같다.
- 생활코딩으로부터 cgi 구현체를 확인하고 이를 따라해 봄으로써 인터페이스를 이해하고, 
- 출력할 수 있는 방법이 있다고 한다면 출력해본다.

