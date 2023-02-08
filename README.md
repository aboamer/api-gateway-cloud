# API gateway

#### Notes
- For some reason, **No enum constant javax.lang.model.element.Modifier.SEALED**
    error appear when I run the app while calling *response.getStatusCode()*
    without calling toString. (in ServerHttpResponse class)
- Api gateway has client load balancing by default.
- Zuul API Gateway but now is deprecated and Spring Cloud API Gateway is used.
- If you face error like **"java.net.UnknownHostException: failed to resolve...."**
then add below property in your student and address microservices.
*eureka.instance.hostname=localhost*