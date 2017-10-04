simple-web-app
==============

Simple web application that demonstrates the use of the OpenID Connect client 
code and configuration.

Note: The default branch of this fork is `oda`. This branch contains 
configuration for [oda-idp]. So after cloning run 

    git checkout oda


Usage
-----

Requires [oda-idp] running on localhost:6088.

Ensure you have [Maven](https://maven.apache.org/download.cgi) installed. 
To start the web app, run

    mvn jetty:run 

Go to http://localhost:7070/simple-web-app/ and try logging in.

[oda-idp]: https://github.com/omahoito/oda-idp
