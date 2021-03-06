Annotations:

1, @SpringBootApplication
This is the base annotation that will be added on main class by default after a Spring Boot project is created. 
It can be seen as a collection of the following three annotations: @Configuration、@EnableAutoConfiguration、@ComponentScan .

2, The @RestController annotation tells Spring that this code describes an endpoint that should be made available over the web. The @GetMapping(“/hello”) tells Spring to use our hello() method to answer requests that get sent to the http://localhost:8080/hello address. Finally, the @RequestParam is telling Spring to expect a name value in the request, but if it’s not there, it will use the word “World” by default.