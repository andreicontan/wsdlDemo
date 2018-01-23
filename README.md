# wsdlDemo

Curl requests:
$ curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws

Unix optional:
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws | xmllint --format
