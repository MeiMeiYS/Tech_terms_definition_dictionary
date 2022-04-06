
## A-
![Screen Shot 2022-03-25 at 1 55 18 PM](https://user-images.githubusercontent.com/86375959/161868920-69bc2ede-6e53-453a-bd80-1d163303dcc2.png)

### AWS (Amazon Web Services)
- Amazon Web Services (AWS) is the world's most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally.
- AWS fundamentals -> https://aws.amazon.com/getting-started/fundamentals-core-concepts/?nc1=h_ls

![VS Amplify](https://user-images.githubusercontent.com/86375959/161869055-359cc2e8-525d-4479-b7be-97760a41a8cc.png)

### AWS Amplify
- AWS Amplify is a set of purpose-built tools and features that lets frontend web and mobile developers quickly and easily build full-stack applications on AWS, with the flexibility to leverage the breadth of AWS services as your use cases evolve.

![Screen Shot 2022-03-25 at 2 30 49 PM](https://user-images.githubusercontent.com/86375959/161869237-c3ed61e5-ba40-438b-b35b-fa14d4f4a378.png)

### AWS AppSync
- AWS AppSync is a fully managed service that makes it easy to develop GraphQL APIs by handling the heavy lifting of securely connecting to data sources like AWS DynamoDB, Lambda, and more. Adding caches to improve performance, subscriptions to support real-time updates, and client-side data stores that keep off-line clients in sync are just as easy. Once deployed, AWS AppSync automatically scales your GraphQL API execution engine up and down to meet API request volumes.

![Screen Shot 2022-03-25 at 3 32 22 PM](https://user-images.githubusercontent.com/86375959/161869296-e3071f26-0465-4df7-a913-c8d9f733fcc7.png)

### AWS CloudFormation
- AWS CloudFormation lets you model, provision, and manage AWS and third-party resources by treating infrastructure as code.

![Screen Shot 2022-03-25 at 2 51 58 PM](https://user-images.githubusercontent.com/86375959/161869316-c3482f9c-2ce9-43cb-a718-2087701488a7.png)

### AWS Cognito
- Amazon Cognito handles user authentication and authorization for your web and mobile apps. With user pools, you can easily and securely add sign-up and sign-in functionality to your apps. With identity pools (federated identities), your apps can get temporary credentials that grant users access to specific AWS resources, whether the users are anonymous or are signed in.

### AWS DynamoDB
- Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data export tools.

### AWS Lambda
- AWS Lambda is a serverless, event-driven compute service that lets you run code for virtually any type of application or backend service without provisioning or managing servers. You can trigger Lambda from over 200 AWS services and software as a service (SaaS) applications, and only pay for what you use.
- AWS Lambda -> https://aws.amazon.com/lambda/

![Screen Shot 2022-03-25 at 2 27 03 PM](https://user-images.githubusercontent.com/86375959/161869439-672f3dec-7c49-44e5-af56-8f3938a662d2.png)

### Amazon API Gateway
- Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services. Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications. API Gateway supports containerized and serverless workloads, as well as web applications.
- Amazon API Gateway -> https://aws.amazon.com/api-gateway/

![API Gateway Works](https://user-images.githubusercontent.com/86375959/161869525-6d21ffdc-a7fd-4040-bc97-e30edc48db7e.png)

### Amazon S3 (Amazon Simple Storage Service)
- Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance.

## C-

### CRM (Customer relationship management)
- Customer relationship management (CRM) is a technology for managing all your company's relationships and interactions with customers and potential customers. The goal is simple: Improve business relationships to grow your business.

## D-

### DBMS(Database management system)
- A database management system (DBMS) that incorporates the relational-data model, normally including a Structured Query Language (SQL) application programming interface.

### Duck typing
- Duck Typing is a term commonly related to dynamically typed programming languages and polymorphism. The idea behind this principle is that the code itself does not care about whether an object is a duck, but instead it does only care about whether it quacks. 
- Duck typing in computer programming is an application of the duck test—"If it walks like a duck and it quacks like a duck, then it must be a duck"—to determine whether an object can be used for a particular purpose.
- With nominative typing, an object is of a given type if it is declared to be (or if a type's association with the object is inferred through mechanisms such as object inheritance). In duck typing, an object is of a given type if it has all methods and properties required by that type.[1][2] Duck typing can be viewed as a usage-based structural equivalence between a given object and the requirements of a type. See structural typing for a further explanation of structural type equivalence.

## F-

### Frames (The HTML Element)
- Frames allow a visual HTML browser window to be split into segments, each of which can show a different document. This can lower bandwidth use, as repeating parts of a layout can be used in one frame, while variable content is displayed in another.
- Sites like Facebook and Twitter use iframes to display content (plugins) on third party websites. Google AdSense uses iframes to display banners on third party websites.
- `<iframe>...</iframe>` An inline frame places another HTML document in a frame. Unlike an `<object />` element, an `<iframe>` can be the "target" frame for links defined by other elements, and it can be selected by the user agent as the focus for printing, viewing its source, and so on. The content of the element is used as alternative text to be displayed if the browser does not support inline frames.
- First introduced by Microsoft Internet Explorer in 1997, standardized in HTML 4.0 Transitional, allowed in HTML5.
 
## I-
  
### IDE (Integrated development environment)
- An integrated development environment (IDE) is software for building applications that combines common developer tools into a single graphical user interface (GUI). For example: VSCode.
  
## J-
  
### JWT (Json web token)
- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
- JWT introduction -> https://jwt.io/introduction
  
## L-
  
### Lerna
- Lerna is a tool for managing JavaScript projects with multiple packages.
- Splitting up large codebases into separate independently versioned packages is extremely useful for code sharing. However, making changes across many repositories is messy and difficult to track, and testing across repositories becomes complicated very quickly.
- To solve these (and many other) problems, some projects will organize their codebases into multi-package repositories (sometimes called monorepos). Projects like Babel, React, Angular, Ember, Meteor, Jest, and many others develop all of their packages within a single repository.
- Lerna is a tool that optimizes the workflow around managing multi-package repositories with git and npm.
- Lerna can also reduce the time and space requirements for numerous copies of packages in development and build environments - normally a downside of dividing a project into many separate NPM packages. See the hoist documentation for details.
- Lerna Documentation -> https://github.com/lerna/lerna
  
## M-
  
### Monorepo
- A monorepo is a version-controlled code repository that holds many projects. While these projects may be related, they are often logically independent and run by different teams.
- In version control systems, a monorepo is a software development strategy where code for many projects is stored in the same repository. This software engineering practice dates back to at least the early 2000s, when it was known as a 'shared codebase'.
  
![Many Repo](https://user-images.githubusercontent.com/86375959/161870025-804de03e-a342-421a-8c7f-707663d66275.png)

## N-
  
### NoSQL (not only SQL)
- When people use the term “NoSQL database,” they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.
- What is NoSQL -> https://www.mongodb.com/nosql-explained
  
## O-
  
### ORM (Object–relational mapping)
- Object–relational mapping (ORM, O/RM, and O/R mapping tool) in computer science is a programming technique for converting data between incompatible type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language.

## P-

### pagination
- Pagination, also known as paging, is the process of dividing a document into discrete pages, either electronic pages or printed pages.
- Electronic pages displayed on a web browser are often called web pages, regardless of whether they are accessed online via a web server on the World Wide Web, or stored locally offline. More accurately, such documents are named by the markup language that makes them displayable via a web browser, e.g. "HTML page" or "PHP page".
- With dynamic web pages, pagination is used for such things as displaying a limited number of results on search engine results pages, or showing a limited number of posts when viewing a forum thread.
- Pagination is used in some form in almost every web application to divide returned data and display it on multiple pages within one web page. Pagination also includes the logic of preparing and displaying the links to the various pages.
- Pagination can be handled client-side or server-side.
- Read more -> https://en.wikipedia.org/wiki/Pagination

### PWA (Progressive web application)
- A progressive web application (PWA), commonly known as a progressive web app, is a type of application software delivered through the web, built using common web technologies including HTML, CSS, JavaScript, and WebAssembly. It is intended to work on any platform that uses a standards-compliant browser, including both desktop and mobile devices.

### Pub/Sub Messaging
- Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic.
- A pub/sub model allows messages to be broadcasted asynchronously across multiple sections of the applications. The core component that facilitates this functionality is something called a Topic. The publisher will push messages to a Topic, and the Topic will instantly push the message to all the subscribers

![SUBSCRIBER](https://user-images.githubusercontent.com/86375959/161870496-66d46136-5465-4587-b888-6645eef6a80f.png)

## S-

### SaaS (Software as a service)
- Software as a service (or SaaS) is a way of delivering applications over the Internet—as a service. Instead of installing and maintaining software, you simply access it via the Internet, freeing yourself from complex software and hardware management.

### SSR (Server-side rendering)
- Server-side rendering (SSR) is an application’s ability to convert HTML files on the server into a fully rendered HTML page for the client. The web browser submits a request for information from the server, which instantly responds by sending a fully rendered page to the client.
- Server-side rendering refers to an application’s ability to display the web-page on the server rather than rendering it in the browser. When a website’s JavaScript is rendered on the website’s server, a fully rendered page is sent to the client and the client’s JavaScript bundle engages and enables the Single Page Application framework to operate.

### SDK (Software Development Kit)
- A software development kit (SDK) is a set of tools provided by the manufacturer of (usually) a hardware platform, operating system (OS), or programming language. For example: firebase.

### SQL (Structured Query Language)
- SQL stands for Structured Query Language. SQL lets you access and manipulate databases. SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987.
- SQL is the standard language for dealing with Relational Databases. SQL can be used to insert, search, update, and delete database records. SQL can do lots of other operations, including optimizing and maintenance of databases.

## T-

### Terraform 
- Terraform by HashiCorp, an AWS Partner Network (APN) Advanced Technology Partner and member of the AWS DevOps Competency, is an “infrastructure as code” tool similar to AWS CloudFormation that allows you to create, update, and version your Amazon Web Services (AWS) infrastructure.


  
  
  
  
  
