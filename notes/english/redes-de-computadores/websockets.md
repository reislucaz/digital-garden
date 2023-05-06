# WebSockets protocol: Innovating your projects with efficiently live communication.

## Presentation
Hello, my name is Lucas Reis, I am 19 years old and a Software Engineering student at UNIEvangélica de Goiás, Brazil. To understand this article, it is recommended that you have some knowledge about [Network Protocols](https://www.comptia.org/content/guides/what-is-a-network-protocol) and [how Web works at background.](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works#:~:text=The%20browser%20sends%20an%20HTTP,internet%20connection%20using%20TCP%2FIP.)

I am here to introduce you to a powerful network protocol that can enhance your projects - [WebSockets](https://www.rfc-editor.org/rfc/rfc6455).

## What is WebSockets?
WebSocket is, at its core, an application protocol, similar to HTTP or FTP. The main difference is that in these other protocols, communication ends after a request-response interaction, while in WebSockets, the communication persists until one of the sides closes the channel. See the diagram below:

![WebSockets message diagram](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wuu84bwu8wh0whh3hogj.png)

## Origin
This protocol is built on top of TCP/IP, just like HTTP, but it can also be used in conjunction with HTTP to establish an initial connection between the client and server. Its origins can be traced back to December 2011, when the web was transitioning to Web 2.0, the web of interactions. With this protocol, it has been possible to create real-time applications such as web chats, video games, and more.

## Handshake HTTP Sample
![Screenshot from RFC 6455](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/d1zdse3jakiq21sycnms.png)

## What can this be helpful?
WebSockets can be extremely useful in certain situations where you need persistent and bidirectional real-time communication. In such contexts, it can be the best way to create an application that meets these requirements.

## Application Sample
**1. Webchat**
_You can use WebSockets to easily develop a real-time web chat!_

**2. Tracker**
_A Tracker can be developed using WebSockets to communicate in real-time between the front-end that sends coordinates to the back-end every 5 seconds or something similar._

**3. Notifications**
_You can use WebSockets to communicate with the client that they have a new update without the need to reload the page or retrieve a specific endpoint with new notifications._

**4. Video Games**
_Video Games can be developed using WebSockets as a Framework! It can enable instant communication between players and the server on the web without losing packets or causing lag._

## The end!
This protocol is a great way to innovate your projects and show your friends that you know how to use TCP/IP to its full potential without sacrificing network performance! You are welcome to make suggestions for this article or correct any errors. =D

## References
- [RFC 6455](https://www.rfc-editor.org/rfc/rfc6455)
