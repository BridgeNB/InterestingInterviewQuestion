Http protocol is a very important concept for full stack developer. In this article, I will summary all critical points about http.

Http Features:

* Http builds upon TCP/IP protocol, default port is 80
* Http has no connection state.

Http Message:

* What is http message?
  * HTTP messages are how data is exchanged between a server and a client.

How http protocol transfer?

* Http protocol transfer by ACII in application layer, building upon TCP/IP protocol. Http request has three parts: state, request header, entity-body \#\#\#needs to search\#\#\#. A typical http request look like below

```html
<method> <request-URL> <version>
<header>

<entity-body>
```

* Method:
  * method: defines different way to interact with server. There are four basic methods: GET, POST, PUT, DELETE.
* URL
  * URL: \(Uniform resource locator\) - is a reference or an address to a resource on the Internet.
* Version:
* Header:
* Entity-body:

PS:

* Method + URL: GET, POST, PUT, DELETE a resource.

\#\#More about Methods\#\#

GET 

1. To obtain information safely and idempotently.
   1. Safe means GET can only be used to get information not modify. So GET method will not change information in database.
   2. idempotent means to the same URL, GET method should reply with same result.

   GET Request example

 





