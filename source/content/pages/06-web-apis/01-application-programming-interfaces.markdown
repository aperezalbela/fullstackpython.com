title: Application Programming Interfaces
category: page
slug: application-programming-interfaces
sortorder: 0601
toc: True
sidebartitle: 6. Web APIs
meta: Web application programming interfaces (APIs) provide a machine-to-machine data transport mechanism. Learn more about web APIs at Full Stack Python.


# Application Programming Interfaces
Application programming interfaces (APIs) provide machine-readable
data transfer and signaling between applications.


## Why are APIs important?
HTML, CSS and JavaScript create human-readable webpages. However, those 
webpages are not easily consumable by other machines.

Numerous scraping programs and libraries exist to rip data out of HTML but 
it's simpler to consume data through APIs. For example, if you want the
content of a news article it's easier to get the content through an API than
to scrap the text out of the HTML.


## Key API concepts
There are several key concepts that get thrown around in the APIs world. It's
best to understand these ideas first before diving into the API literature.

* Representation State Transfer (REST)

* Webhooks

* JavaScript Object Notation (JSON) and Extensible Markup Language (XML)

* Endpoints


## Webhooks
A webhook is a user-defined HTTP callback to a URL that executes when a 
system condition is met. The call alerts the second system via a POST or GET
request and often passes data as well.

Webhooks are important because they enable two-way communication initiation 
for APIs. Webhook flexibility comes in from their definition by the API user
instead of the API itself.

For example, in the [Twilio API](https://www.twilio.com/api) when a text 
message is sent to a Twilio phone number Twilio sends an HTTP POST request 
webhook to the URL specified by the user. The URL is defined in a text box
on the number's page on Twilio as shown below.

<img src="/img/twilio-webhook-definition.jpg" width="100%" alt="Webhook definition in the Twilio API." class="technical-diagram" />


## API open source projects
* [Swagger](https://github.com/wordnik/swagger-core) is an open source project 
  written in Scala that defines a standard interface for RESTful APIs.


## API resources
* [Zapier](https://zapier.com/) has an
  [APIs 101](https://zapier.com/blog/apis-101/) free guide for what APIs 
  are, why they are valuable and how to use them properly. 

* [What RESTful actually means](https://codewords.recurse.com/issues/five/what-restful-actually-means)
  does a fantastic job of laying out the REST principles in plain language
  terms while giving some history on how they came to be.

* [What is a webhook?](http://sendgrid.com/blog/whats-webhook/) by 
  [Nick Quinlan](https://twitter.com/YayNickQ) is a plain English explanation
  for what webhooks are and why they are necessary in the API world.

* [Simplicity and Utility, or, Why SOAP Lost](http://keithba.net/simplicity-and-utility-or-why-soap-lost)
  provides context for why JSON-based web services are more common today than
  SOAP which was popular in the early 2000s.

* [API tools for every occasion](https://medium.com/@orliesaurus/api-tools-for-every-occasion-10-api-tools-released-in-2015-i-can-t-live-without-d5947d9ca9c3)
  provides a list of 10 tools that are really helpful when working with APIs
  that are new in 2015.


## APIs learning checklist
1. Learn the API concepts of machine-to-machine communication with JSON and 
   XML, endpoints and webhooks.

1. Integrate an API such as Twilio or Stripe into your web application. 
   Read the [API integration](/api-integration.html) section for more 
   information.

1. Use a framework to create an API for your own application. Learn about
   web API frameworks on the [API creation](/api-creation.html) page.

1. Expose your web application's API so other applications can consume data 
   you want to share.

