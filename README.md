# REST API Discovery with Liberty 

This sample contains a few ways of how to use Swagger documentation within Liberty. Application contains
two individual servlets. JAX-RS servlet is used to handle requests to a Tasks API, which allows user to create, view and delete Task objects. Second servlet is an extension of a HTTPServlet and is used to resond to requests for a Contacts API.
Contacts API lets you create, view and update Contact objects.

[TasksResource](/swagger-sample-application/src/main/java/net/wasdev/swaggersample/jaxrs/TasksResource.java) is a
JAX-RS resouce classs that uses both JAX-RS and Swagger annotations to document the API.

Documentation for HTTPServlet based API [ContactsServlet](/swagger-sample-application/src/main/java/net/wasdev/swaggersample/servlet/ContactsServlet.java)
is provided using Swagger stub file [swagger.json](/src/webapp/META-INF/stub/swagger.json)

## Getting Started

Browse the code to see what it does, or build and run it yourself:
* [Building and running on the command line](/docs/Using-cmd-line.md)
* [Building and running using Eclipse and WebSphere Development Tools (WDT)](/docs/Using-WDT.md)
* [Downloading WAS Liberty](/docs/Downloading-WAS-Liberty.md)

Once the server has been started, go to [https://localhost:9444/ibm/api/explorer/](https://localhost:9444/ibm/api/explorer/) to interact with the sample.


## Notice

© Copyright IBM Corporation 2016.

## License

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
````
