# gateway
[![Build Status](https://drone.io/github.com/api-gateway/gateway/status.png)](https://drone.io/github.com/api-gateway/gateway/latest)

An api gateway, acts as oauth2 authorization server, api throttling, api proxy.

## Request oauth2 access token (password flow).
```
POST https://api-gateway.herokuapp.com/oauth/token HTTP/1.1
Accept: */*
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Host: api-gateway.herokuapp.com

grant_type=password&client_id=123&client_secret=secret&username=bob&password=secret&scope=demo
```
