# Spring Boot based web appliaction to dump information from request

This is a simple spring boot web application that receives requests and dumps their information (cookies/headers). It's pretty usefull to be used to test SSO Proxy or any Proxy, to see that changes that were made to the request.

You can compile it as a .war file and execute it. The port is defined at 8080 with context.path at '/'.