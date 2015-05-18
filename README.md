# gateway
An api gateway, acts as oauth2 authorization server, api throttling, api proxy.

## Request oauth2 access token (password flow).
```
POST https://localhost:3001/oauth/token HTTP/1.1
Host: localhost:3001
Accept: */*
Content-Type: application/x-www-form-urlencoded; charset=UTF-8

grant_type=password&client_id=123&client_secret=secret&username=bob&password=secret&scope=demo
```
