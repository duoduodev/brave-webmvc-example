## WebMVC 2.5 Example

### spring-webmvc-servlet.xml

`spring-webmvc-servlet.xml` is indirectly read due to spring references
in web.xml. This setups the app and tracing of it.

*   brave.webmvc.Frontend and Backend : Rest controllers with no tracing configuration
*   brave.spring.beans.TracingFactoryBean : This helps configure tracing, notably Log4J 1.2 integration


