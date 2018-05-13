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

## Fetch the page, extract the content and process it.
you may need to extract a hash from the page. You may want to find a module like "Requests" in python, which allow you to make calls to webpages. Once you requested the page, you may need to write a regex in order to extract the hash from the page. Once you have extracted the hash, do the required processing and send it back like it says in the instruction!  

I do this in python, but any language can be used. Good luck and have fun!  

> Refer [Tools](Tools/tools.md)

> Refer [Tips](tips.md)
