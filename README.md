UGE 36 -  Yones El Bana

Tirsdag - Fundamental network topics
Onsdag - Monitoring HTTP Headers 

1)
Vi fandt en keep-alive i vores http header
Keep-alive header holder forbindelsen oppe hele tiden.
2)
VI får redirect og r.html. redirects header er keep-alive og det samme med r.html.
Det sker ved goGet metoden.
3)
Den starter ved http og redirecter dig https.
Den forstår du skriver http, men sender dig til https.
4a) code 500
java.lang.ArithmeticException: / by zero
	Ups.processRequest(Ups.java:34)
	Ups.doGet(Ups.java:62)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:626)
	javax.servlet.http.HttpServlet.service(HttpServlet.java:733)
	org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:53)
Vi får 500 fordi der er fejl i koden og den ikke kan dividere med 0 som er en server error.

4b) code 404
Vi får 404 fordi prøver en path som vi ikke har oprettet en servlet til som er en client error.

6)
Getter viser det hele og post gemmer de ting du har hidden.


