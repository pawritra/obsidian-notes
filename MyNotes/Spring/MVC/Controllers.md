Basically you can use 2 types of controllers,

@RestController
@Controller

Both are implementations of @Component class. Thus, on using this annotation these endpoints will automatically be added to the Spring Application.

@Controller - 
It is used for building MVC application with every endpoint either redirecting or return a View component. You have to return one of the following in this case.

@RestController
It on the other hand returns a JSON Body. It is a combination of @Controller and @ResponseBody.