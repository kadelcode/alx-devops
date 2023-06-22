Install and configure HAproxy on your ```lb-01``` server.

Requirements:

-	Configure HAproxy so that it send traffic to ```web-01``` and ```web-02```
-	Distribute requests using a roundrobin algorithm
-	Make sure that HAproxy can be managed via an init script
-	Make sure that your servers are configured with the right hostnames: ```[STUDENT_ID]-web-01``` and ```[STUDENT_ID]-web-02```. If not, follow this [tutorial](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/set-hostname.html).
-	For your answer file, write a Bash script that configures a new Ubuntu machine to respect above requirements
Example:
```
sylvain@ubuntu$ curl -Is 54.210.47.110
HTTP/1.1 200 OK
Server: nginx/1.4.6 (Ubuntu)
Date: Mon, 27 Feb 2017 06:12:17 GMT
Content-Type: text/html
Content-Length: 30
Last-Modified: Tue, 21 Feb 2017 07:21:32 GMT
Connection: keep-alive
ETag: "58abea7c-1e"
X-Served-By: 03-web-01
Accept-Ranges: bytes

sylvain@ubuntu$ curl -Is 54.210.47.110
HTTP/1.1 200 OK
Server: nginx/1.4.6 (Ubuntu)
Date: Mon, 27 Feb 2017 06:12:19 GMT
Content-Type: text/html
Content-Length: 612
Last-Modified: Tue, 04 Mar 2014 11:46:45 GMT
Connection: keep-alive
ETag: "5315bd25-264"
X-Served-By: 03-web-02
Accept-Ranges: bytes

sylvain@ubuntu$
```
