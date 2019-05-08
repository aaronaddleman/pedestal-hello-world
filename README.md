# pedestal hello world

Following the tutorial for building a pedestal based website.

# start server

- boot repl
- (require 'hello)
- (hello/start)

# call server

```
curl -i http://127.0.0.1:8890/greet
HTTP/1.1 200 OK
Date: Wed, 08 May 2019 04:15:14 GMT
Strict-Transport-Security: max-age=31536000; includeSubdomains
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
X-XSS-Protection: 1; mode=block
Content-Type: text/plain
Transfer-Encoding: chunked
Server: Jetty(9.3.8.v20160314)

Hello, world!% 
```
