# java_spring
+ Web basics including HTTP, requests, responses, front-ends, and back-ends
+ Spring back-end applications in action
+ Testing APIs with the curl command-line tool

## GET Requests

### with Curl
```
curl localhost:4001/<filename>
```
OR

### with a Web Browser
```
http://localhost:4001/<filename>/
```

## POST Requests

### with Curl
```
curl -X POST -d "{\"name\":\"Pizza Hut\", \"line1\":\"123 Main St.\", \"city\":\"San Diego\", \"state\":\"CA\", \"zipCode\":\"90029\"}" -H "Content-Type: application/json" http://localhost:4001/<filename>/
```
OR

### with a Web Browser
```
http://localhost:4001/<filename>.html  -> submit
```
output
```
{"name":"Pizza Hut","line1":"123 Main St.","city":"San Diego","state":"CA","zipCode":"90029"}$
```
