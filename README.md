SpringRESTFulWebService , followed as just in Spring.io using GGTS
=======================

This guide walks you through the process of creating a "hello world" RESTful web service with Spring.

What you’ll build ?

You’ll build a service that will accept HTTP GET requests at:

http://localhost:8080/greeting

and respond with a JSON representation of a greeting:

{"id":1,"content":"Hello, World!"}

You can customize the greeting with an optional name parameter in the query string:

http://localhost:8080/greeting?name=User
The name parameter value overrides the default value of "World" and is reflected in the response:

{"id":1,"content":"Hello, User!"}
What you’ll need

My Choice:

About 15 minutes
GGTS
JDK 7
Gradle 2.0x
