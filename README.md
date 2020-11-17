# Holy bible

![alttext](undraw_welcome_cats_thqn.svg "Welcome!")

## What is DNS?

![alttext](undraw_Domain_names_re_0uun.svg "DNS")

>The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

- How does DNS work?
    - The process of DNS resolution involves converting a hostname (such as www.example.com) into a computer-friendly IP address (such as 192.168.1.1). An IP address is given to each device on the Internet, and that address is necessary to find the appropriate Internet device - like a street address is used to find a particular home. When a user wants to load a webpage, a translation must occur between what a user types into their web browser (example.com) and the machine-friendly address necessary to locate the example.com webpage.



## What is HTTP?
![alttext](undraw_server_q2pb.svg)
> The Hypertext Transfer Protocol (HTTP) is the foundation of the World Wide Web

- Is used to load web pages using hypertext links. HTTP is an application layer protocol designed to transfer information between networked devices and runs on top of other layers of the network protocol stack.
- A typical flow over HTTP involves a client machine making a request to a server, which then sends a response message.

## HTTP Methods
> Sometimes referred to as an HTTP verb

 - indicates the action that the HTTP request expects from the queried server.
    - Two of the most common HTTP methods are ‘GET’ and ‘POST’
    - A ‘GET’ request expects information back in return (usually in the form of a website), while a ‘POST’ request typically indicates that the client is submitting information to the web server
    
    
    
    
    
## What is CORS?
>CORS (cross-origin resource sharing)

 - A request for a resource (like an image or a font) outside of the origin is known as a cross-origin request.
    - Unlike same-origin, navigating to "https://www.ejemplo.com/hola.html" from URL1 could be allowed with CORS. Allowing cross-origin requests is helpful, as many websites today load resources from different places on the Internet (stylesheets, scripts, images, and more).
    - Cross-origin requests, however, mean that servers must implement ways to handle requests from origins outside of their own. CORS allows servers to specify who (i.e., which origins) can access the assets on the server, among many other things.


## What is RESTful?
>RESTful web services
 - RESTful are built to work best on the Web. Representational State Transfer (REST) is an architectural style that specifies constraints, such as the uniform interface, that if applied to a web service induce desirable properties, such as performance, scalability, and modifiability, that enable services to work best on the Web. In the REST architectural style, data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs), typically links on the Web. The resources are acted upon by using a set of simple, well-defined operations
    
## What is a middleware?
>Middleware is software that lies between an operating system and the applications running on it.
- Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications. It’s sometimes called plumbing, as it connects two applications together so data and databases can be easily passed between the “pipe.”

## What is NPM, NVM and YARN?
>NPM short for Node Package Manager

- npm is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js.
-  It consists of a command line client, also called npm, and an online database of public and paid-for private packages, called the npm registry. 

>NVM short for Node Version Manager
- nvm is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL.
>YARN
- YARN is a package manager for JavaScript.
- It reads from the package.json file, so it should work on any project that's already using npm. It's pretty speedy too. It took about 12 seconds.
 - With npm, it took almost two minutes. It puts its dependencies in Node modules, just like npm, so all your tooling should work the same.

## JSON
>JavaScript Objet Notation
- Its a Data Representation Format
- Commonly used for APIs and Configs
- Its used becouse its extremely lightweight to send back and forth and its easy to read/write
>JSON Types
- JSON supports almost any datatype such as:

    - Strings ("Hello World, "John", "J")
    - Numbers ("10", "1.5", "-30", "1.2e10")
    - Booleans (True or False)
    - Null (Essentialy stands for nothing)
    - Arrays [1,2,3; "Hello","World"]
    - Objects {"key": "value"} {"age": 24}

> JSON Web Token
- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
- This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

## Deploy a project
> The key to success for every enterprise project is a well-thought-out plan. One of the biggest mistakes that most teams make is having practices in place that lead to last-minute scrambling. 



 - - -


### Microservices
> A variant of the service-oriented architecture (SOA) structural style
- Microservice architecture, arranges an application as a collection of loosely coupled services. In a microservices architecture, services are fine-grained and the protocols are lightweight. 

### Regular expressions
   - A regular expression is a sequence of characters that define a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

### Minification
 - Minification is the process of removing all unnecessary characters from the source code of interpreted programming languages or markup languages without changing its functionality.

>    - In JavaScript:
>        - var array = [];
> for (var i = 0; i < 20; i++) {
>  array[i] = i;
>}
>
>>            this can be replace by:
>        - for(var a=[i=0];i<20;a[i]=i++);

### Ternary operator
- The ternary operator is an operator that exists in some programming languages, which takes three operands rather than the typical one or two that most operators use. It provides a way to shorten a simple if else block.

### Logical operators
- The concept of logical operators is simple. They allow a program to make a decision based on multiple conditions. Each operand is considered a condition that can be evaluated to a true or false value.

# Version control system
> What is a “version control System”?
- Version control systems are a category of software tools that helps record changes to files by keeping a track of modifications done to the code.

> What is GIT?
 - **Git** is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

> What is GitHub?
 - **GitHub** is a code hosting platform for version control and collaboration.
 It lets you and others work together on projects from anywhere.

> What is GitLab?
- Similar to GitHub, GitLab is a repository manager which lets teams collaborate on code. Written in Ruby and Go, GitLab offers some similar features for issue tracking and project management as GitHub.
   - One of the big differences between GitLab and GitHub is the built-in Continuous Integration/Delivery of GitLab.

> GitFlow
- **GitFlow** is a branching model for Git, created by Vincent Driessen. It has attracted a lot of attention because it is very well suited to collaboration and scaling the development team.

> Branching
- Branching, is the duplication of an object under version control (such as a source code file or a directory tree) so that modifications can occur in parallel along multiple branches.
   - For an easy way to understand this a branch in Git is just a named reference to a commit, yep that's it.
   
> POO Basics

> Recursión

> Markdown

> Agile methodologies

    > What is KANBAN?

    > What is SCRUM??

## Best practices


> Design patterns

> Testing (With Jest) and code quality

   > SOLID

   > Codeparing

   > Linter (With ESLint)

   > Documentation (With JSDoc and PlantUML)

> When should you use GET, POST, DELETE, PUT, etc… methods?

> When should you return an HTTP code 200, 201, 300, etc.. 

## Useful technologies
   >  Contentful

   >  Express

   >  Koa

   >  Redux

   >  React
   
   >  Vue.js

## Databases
   >  Relational DB

   >  Non relational DB

   >  SQL

> MongoDB

> CRUD operations

  > CouchDB

>  Redis

## Node JS / JS Theory

>     V8 engine

>     Event loop

>     Modules, require, import/export

>     Node eventemitter

>     Streams and buffers

>     JS Data types

### Handling errors

> Try catch

> console.log

> etc

### Callback hell

> Promises

> Async await

### HOF
> Arrow function

> map

### reduce

> Why use them

> When use them

> etc

### POO
> Garbage collector

> Constructor/destructor

> new operator

### Object methods
> this

> keys

> etc

### Classes
> Array methods

> push

> pop

> etc

### JSON Methods
> stringify 

> parse

### SCOPE
> var

> let

> const

> Ecmascript

### Prototype
> Api

> ApiGateway

> Backends for frontends

> Destructors




### Bibliography
    https://javascript.info/
    https://eloquentjavascript.net/
    https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/get-started/README.md
    https://github.com/bevacqua/es6
    https://jgthms.com/javascript-in-14-minutes/
    https://learnxinyminutes.com/docs/javascript/
    https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9 

    https://undraw.co/
    https://pages.github.com/
    https://www.markdownguide.org/cheat-sheet/
    
    Images format SVG

