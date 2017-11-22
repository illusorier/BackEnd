First you set up a basic build script.

You can use any build system you like when building apps with Spring.

Create a resource representation class. 

In Spring's approach to building RESTful web services, HTTP requests are handled by a controller.

These components are easily identified by the `@RestController` annotation.

以下代码省略了package和import:

        @RestController
        public class GreetingController {
        
            private static final String template = "Hello, %s!";
            private final AtomicLong counter = new AtomicLong();
        
            @RequestMapping("/greeting")
            public Greeting greeting(@RequestParam(value="name", defaultValue="World") String name) {
                return new Greeting(counter.incrementAndGet(),
                                    String.format(template, name));
            }
        }
        
The `@RequestMapping` annotation ensures that HTTP requests to `/greeting` are mapped to the `greeting()` method.
        
> The above example does not specify `GET` vs. `PUT`, `POST`, and so forth, because `@RequestMapping` maps all HTTP operators by default. Use `@RequestMapping(method=GET)` to narrow this mapping.

