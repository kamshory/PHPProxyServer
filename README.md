# PHP Proxy Server

Sometimes we need to create a proxy server because we are limited by something that causes us to not be able to access a website address directly from a machine. This proxy server will forward all requests received to the destination server.

As an example:
The web server that you are heading to uses port 94 while your application uses shared hosting and cannot access port 94 using cURL because of the settings made by the hosting provider.

You require a proxy server to allow access from your application to port 94 via port 80.

All you have to do is create a proxy server that guarantees access to port 94. This proxy server will receive a request from your application and then forward the request to port 94.
