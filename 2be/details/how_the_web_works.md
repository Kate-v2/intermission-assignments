## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
 * your computer checks the OS's cache for the IP address of the website root you want to go to. If it doesn't know it:
  *  the client (your computer) sends a request for the IP address of domain commonly known as www.example.com to a Resolving Name Server of the DNS (domain name system)
 * which queries a root name server 
 * which queries a Top Level Domain server (TLD) (if it doesn't have the IP cached). These serve domain roots.
 * which queries the Authoritative Name Servers (ANS) - which can provide the IP address. 
 * the RNS can return this to the OS
 * which passes it to the browser
 * which connects to the ip address


1.  What does HTTP stand for?
 * Hyper Test Transfer Protocol

1. 	What protocol does the World Wide Web use?
 * Transmission Control Protocol (TCP)

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
 * Internet Protocol

1. 	What does DNS stand for?
 * **A. Domain Name System**
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service



1. 	How are text domain names matched to their respective numeric IP addresses.
 * via DNS (and a series of queries to other servers)


1. 	What is the client?
  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * **C. The software which requests information from a server (browser)**
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to


1. 	What does URL stand for?
 * Universal Resource Locator

1. 	What are protocols
 * A. The standardization of IP addresses
 * B. The DNS standard method for data transfer
 * C.	The standardized network address system
 * D.	**The standardized method for transferring data or documents over a network**
 * E.	The standardized method for prioritizing data or document storage over a network


1. What does DNS stand for?
 * Domain Name System


1. what is the `www` portion of a url?
 * protocol identifier


1. What is The markup language used for all web documents?
 * HTML
 
1. What is the organization that monitors web technologies?
 * World Wide Web Consortium (W3C)

1. What is the Protocol for transferring web documents on the Internet?
 * ftp

1. What matches the domain names with numeric IP addresses?
 * DNS





