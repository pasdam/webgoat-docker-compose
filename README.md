# webgoat-docker-compose

docker-compose file with all the required components to play around with [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project).

## Run

To run the application:

```sh
docker-compose up -d
```

After that the apps will ba available at the following addresses:

* WebGoat: http://localhost:8080/WebGoat/login
* WebWold: http://localhost:9090/login
* ZapProxy: http://localhost:9091/zap/
