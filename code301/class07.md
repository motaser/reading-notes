#  API ( Application Programming Interface) 

API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you're using an API.

![image](https://nitrocdn.com/GuYcnotRkcKfJXshTEEKnCZTOtUwxDnm/assets/static/optimized/rev-13aab04/wp-content/uploads/2020/01/rest.png)
 
 Those URLs tell the browser that there's a concept, somewhere. A browser can then go ask for a specific representation of the concept. Specifically, the browser asks for the web page representation of the concept.


 **GET, POST, PUT, PATCH, and DELETE are the five most common HTTP methods for retrieving from and sending data to a server.**

 * ### The GET method

The GET method is used to retrieve data from the server. This is a read-only method, so it has no risk of mutating or corrupting the data. For example, if we call the get method on our API, we’ll get back a list of all to-dos.


* ### The POST method

The POST method sends data to the server and creates a new resource. The resource it creates is subordinate to some other parent resource. When a new resource is POSTed to the parent, the API service will automatically associate the new resource by assigning it an ID (new resource URI). In short, this method is used to create a new data entry.

* ### The PUT method

The PUT method is most often used to update an existing resource. If you want to update a specific resource (which comes with a specific URI), you can call the PUT method to that resource URI with the request body containing the complete new version of the resource you are trying to update.


* ### The PATCH method

The PATCH method is very similar to the PUT method because it also modifies an existing resource. The difference is that for the PUT method, the request body contains the complete new version, whereas for the PATCH method, the request body only needs to contain the specific changes to the resource, specifically a set of instructions describing how that resource should be changed, and the API service will create a new version according to that instruction.

* ### The DELETE method
The DELETE method is used to delete a resource specified by its URI.

## *-Conclusion-*
Anyone looking to build a complete application must know how to query a database. Almost all applications would require you to fetch and store data from a database. These request methods are more than enough for a fully functional application. Javascript’s new Fetch API is extremely simple to use. Whether you’ve worked with APIs before, it is easy to pick up or adapt to. Nonetheless, the fundamental understanding of each of these requests would well equip you to be adaptable to other kinds of HTTP request methods.