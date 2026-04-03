
2026-03-26 12:00
  
Status: #u-developed #source 

Tags: [[networking concepts]]

Reference Link: [What do client side and server side mean? | Client side vs. server side](https://www.cloudflare.com/learning/serverless/glossary/client-side-vs-server-side/)

## Citations/Sources

####  What is the client-server model? | Paragraph 1, Line 1-2

	Quote: "Much of the internet is based on the client-server model. In this model, user devices communicate via a network with centrally located servers to get the data they need, instead of communicating with each other."

The internet is an endless web of clients and servers, whereby the client is the end-device operated by a user that requests services or information from a well-kept, reliable server. End-devices, or clients--while they are capable of sharing resources or offering services--aren't necessarily designed for providing a service 24/7. 

####  What is the client-server model? | Paragraph 1, Line 1-2

	Quote: "The client-server model is used because servers are typically more powerful and more reliable than user devices. They also are constantly maintained and kept in controlled environments to make sure they're always on and available."

Servers are specifically designed to offer services and even pool hardware resources from other servers together to offer efficiency, power, and redundancy or allow for fail-over techniques. But, more importantly, the internet (a.k.a internetwork) is only possible if there is a central hub of servers that is always available and able to route packets--or your requests--to its destination and back.

For example, every person must have a plan with their internet service provider (ISP) in order to have access to the broader internet. When a packet is destined for a network that does not exist in the client's local area network (LAN), it will shoot out straight to the gateway, and go to one of your ISP's edge routers, which has its own sets of services that ensures the packet gets to where it needs to go.

####  What is the client-server model? | Paragraph 3, Line 1

	Quote: "Servers can serve multiple client devices at once, and each client device sends requests to multiple servers in the course of accessing and browsing the Internet."

The role of a client and server can be delineated specifically by its particular role at the time. In this case, the client can reach out to multiple servers and request resources at a time, whereas servers can serve multiple clients at a time. 

####  What does client side mean? | Paragraph 1, Line 1

	Quote: "In web development, 'client side' refers to everything in a web application that is displayed or takes place on the client (end user device)."

Client side refers to where processes take place. In the case of a web browser, the process will take place on the client's web browser.

When a client enters their web browser--like Google Chrome, for example--the client will send out a **DNS** request to a **DNS Server** to resolve the domain name, "www.google.com," into an IP address. Once the DNS server returns an IP address, then the client will request browser information/content from the returned IP address, which will be retrieved from the **web server** that hosts the website associated with that IP address.

The web server will provide content that will be drawn onto the client's web browser like text/characters, photos/illustrations, UI, and behavioral components summoned by JavaScript.

Now for the important part: The client will take that 'front-end' information--which refers to the types of processes that will take place on the an application--and interpret it to enable the end-user to interact with certain elements on the web browser to potentially make more requests.

####  What does client side mean? | Paragraph 3, Line 1

	Quote: "...HTML, CSS, and JavaScript that dictate how the Netflix main page appears to the user are interpreted by the browser on the client side."

Most client-server models have moved from hosting dynamic web-pages on the server side to hosting some of the processes on the client side.

For example, HTML, CSS, and JavaScript are the main aspects of a static website, where HTML is responsible for providing the content and formatting information to the browser, CSS deals with the styling of the website, and JavaScript handles all of the dynamic behavior and interactivity on that website (animations, drop-down menus, etc.)

These kinda of websites are also able to respond to certain events, like a user hovering their mouse over a button; The button may increase in size, change color, while slightly moving adjacent buttons away to make room for the newly-increased size. However, this is something that is *only* visible to the client.

####  What does server side mean? | Paragraph 1

	Quote: "Much like with client side, 'server side' means everything that happens on the server, instead of on the client. In the past, nearly all business logic ran on the server side, and this included rendering dynamic webpages, interacting with databases, identity authentication, and push notifications."

When talking about the server side, that is explicitly concerned with what is happening on the "backend," or the processes that take place on the server. What is unique about servers is that you can use any type of logic or programming language to that support the processes running on that server without worrying about the client; A client using an application is more sensitive to the information it receives since the kind of information that can be interpreted is application-dependent. **JavaScript is universally accepted, however.**

Another consideration to make is that the more dependent the client-side is on the server, the more latency that can introduce. Like it was mentioned before, most businesses ran all their logic on the server side, meaning all requests had to travel from the client all the way to the server and back, every time.
## Summary

The internet is mainly predicated on a client-server model, where servers offer services, and the clients request those services. This is to conduce an inter-networking environment where there is some form of centrality, reliability, and efficiency; Clients, or end-devices, aren't designed to have high availability and offer lots of services. Some terms like client-side and server-side are used to describe where certain processes run, and draw a clear line between what the role of a client and a server is. Some examples of a client may be a computer requesting a webpage, and the server would be the computing device(s) that offer/serve that webpage.

## Key Takeaways

- A client requests resources, information, or services
- A server offers high availability, efficiency, and reliable offerings of resources, information, or services.
- Client-sided refers to the processes that run on the client, i.e. drawing content on a webpage.
- Server-sided refers to the processes that run on the server, i.e. rendering dynamic webpages, interacting w/ databases, identity authentication, etc. 