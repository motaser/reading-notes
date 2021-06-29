# What is a REST API?

A REST API is an application programming interface that conforms to specific architectural constraints, like stateless communication and cacheable data. It is not a protocol or standard. While REST APIs can be accessed through a number of communication protocols, most commonly, they are called over HTTPS, so the guidelines below

**Identifying resources on the Web**

The target of an HTTP request is called a "resource", whose nature isn't defined further; it can be a document, a photo, or anything else. Each resource is identified by a Uniform Resource Identifier (URI) used throughout HTTP for identifying resources.


The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively.


![image](https://www.ltg.ed.ac.uk/~ht/WhatAreURIs/urr.png)

### 7 Rules for REST API URI Design

Rule #1: A trailing forward slash (/) should not be included in URIs
This is one the most important rules to follow as the last character within a URI’s path, a forward slash (/) adds no semantic value and may cause confusion. REST API’s should not expect a trailing slash and should not include them in the links that they provide to clients.

**_Rule #2_**   : Forward slash separator (/) must be used to indicate a hierarchical relationship
The forward slash (/) character is used in the path portion of the URI to indicate a hierarchical relationship between resources.

**_Rule #3_**: Hyphens (-) should be used to improve the readability of URIs
To make your URIs easy for people to scan and interpret, use the hyphen (-) character to improve the readability of names in long path segments. Anywhere you would use a space or hyphen in English, you should use a hyphen in a URI.

**_Rule #4_**: Underscores (_) should not be used in URIs
Text viewer applications (browsers, editors, etc.) often underline URIs to provide a visual cue that they are clickable. Depending on the application’s font, the underscore (_) character can either get partially obscured or completely hidden by this underlining.

**_Rule #5_**: Lowercase letters should be preferred in URI paths
When convenient, lowercase letters are preferred in URI paths since capital letters can sometimes cause problems. RFC 3986 defines URIs as case-sensitive except for the scheme and host components.

**_Rule #6_**: File extensions should not be included in URIs
On the Web, the period (.) character is commonly used to separate the file name and extension portions of a URI.

**_Rule #7_**: Should the endpoint name be singular or plural?
The keep-it-simple rule applies here. Although your inner-grammatician will tell you it's wrong to describe a single instance of a resource using a plural, the pragmatic answer is to keep the URI format consistent and always use a plural.


REST vs GraphQL APIs, the Good, the Bad, the Ugly
Since being introduced by Facebook, GraphQL has taken the API world by storm as an alternative to REST APIs. GraphQL fixes many problems that API developers and users have found with RESTful architecture. However, it also introduces a new set of challenges which need to be evaluated. Because GraphQL is not simply a evolutionary replacement for REST, this post will deep dive into the pros and cons of each and when GraphQL makes sense for your application.

