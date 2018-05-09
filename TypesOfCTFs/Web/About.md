# WEB
These type CTFs require the player to find the common vulnerabilities in the web technologies.

## For example
You might need to use **SQL injection** to read the *“secret_flag”* table of a database, use **directory traversal** to get a web server to serve you *“flag.txt”*, use **Cross-Site Scripting** to trick a simulated user to send you their password, or bypass some client-side checks implemented by obfuscated **javascript**


## For Post And Get and others
> GET is used to request data from a specified resource

> POST is used to send data to a server to create/update a resource

> HEAD method asks for a response identical to that of a GET request, but without the response body.

> The PUT method replaces all current representations of the target resource with the request payload.

> The DELETE method deletes the specified resource.

> The CONNECT method establishes a tunnel to the server identified by the target resource.

> The OPTIONS method is used to describe the communication options for the target resource.

> The TRACE method performs a message loop-back test along the path to the target resource.

> The PATCH method is used to apply partial modifications to a resource.

We can simply use *curl* or *nc* (just google it) or use tools such as **Postman** or **Burpsuite**.

## We divide the topic into sub-categories

> HTTP

> PHP

> SQL Injections
