Write a Spring microservice/project that exposes the following HTTP methods.


PUT – no body it adds a message at the current timestamp - returns 200 OK

GET (int hour) – the number of messages in the last hours (hour is the parameter) with a degree of error in seconds - returns the nuber of messages in the last <<hour>> hours


For example, if we send a message at 04:01:01 and another at 05:01:02. if the current time is 06:01:02 and we want the number of messages in the last two hours then the result will be 1. So each second counts.


There will be two variants of this microservice. One that uses an embedded database another more optimal that uses only java collections.


Those two variants can be exposed under different paths (Two controllers)

We’re mostly interested in how the application is packaged, unit tested, and how spring/java/maven are used
  
  
The project should be placed somewhre on github or gitlab
