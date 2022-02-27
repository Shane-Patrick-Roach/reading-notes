# WRRC and Java



## Key Concepts

---

## HTTP

- This protocol is used to transmit and recieve web pages, as well as server workings and scripting technologies.

- A web server just a computer program that listens for requests from browsers and then execute them.

- These requests and responses are issued in a special language called HTTP, which is short for Hyper Text Transfer Protocol. This only defines what the browser and web server say to each othe, not how they communicate.

## What happens when I follow I a link?

1. Parsing the URL
2. Sending the request.
3. The server response.

## What is an IPA?

- For the layman, an IPA is an Internet Protocol Address, which is a numeric identifier for a computer, server, or other resource connected to a TCP/IP network.
- This is a server that serves a collection of hostnames and their correlated IP's.
- If the request or response is greater than the size of a single packet, the browser uses a TCP request instead. UDP is a lightweight protocol that optimizes for speed, with the tradeoff being that it offers no guarentees in terms of delivery or order.
- It is well suited for use-cases where error-checking can be outside the network interface and packet-loss is prefereable to delayed delivery.

## What is HTTP?

- **Hyper test Transfer Protocol** is an application layer protocol that generally assumes use of TCP as its transport-layer protocol.

## What is TCP?

- Transmission Control Protocol
- TCP ensures delivery and ordered data transmission.
- This is done very simply, using whats known as a sequence number for every byte sent.



## Things I want to Know More About

---


### Review of Crud

- Create
- Read
- Update
- Delete




## Reference/Citations

---


- [HTTP Review](https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-)
- [Simple Response Cycle](https://www.baeldung.com/java-http-request)
