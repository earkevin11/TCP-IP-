# TCP-IP Networking

# What is the main purpose of a network?
- To share information and resources with one another

# What are protocols?
- Networks work correctly because the various devices and software follow the rules (protocols).
- Protocols are a set of logical rules that devices must follow to communicate.

# What is a Networking model?
- Networking model defines rules about how each part of the network should work, as well as how the parts should work together so that the entire network functions correctly

# What is the purpose of a networking model?
- Networking models define a structure and different categories (layers) of standards and protocols.
- Think networking models as a set of architectural plans for building a house.
- To build a house, there are framers, electricians, bricklayers, painters, and more.
- One could build a house without the blueprint but the blueprint would ensure that the house would not collapse plus it would have hidden spaces to accomdate the plumbing, electrical, gas, and more.

# TCP / IP rules are used today
- TCP/IP became the common choice and OSI fell away

# Corporate networks are known as enterprise networks 
- Smaller networks at home, when used for business purposes are known as small office/home office (SOHO) networks

# TCP/IP Networking Model 
- This model allows us all to take a computer (or cellpgone) out of the box, plug in all the right cables, turn it on, and connect to and use the network. 
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/172253551-07aeba04-0e2e-4080-9974-9fc325efe99f.png" height="50%" width="50%" alt="TCP/IP Model"/>
  
<p/>

# TCP/IP Application Layer
- This layer's protocols provide services to the application software running on a computer
- The application layer doesn't define the application itself, but it defines services that applications need.
- For example, application protocol HTTP defines how web browsers can pull the contents of a web page from a web server.
- Most popular TCP/IP application today is the web browser

# How does the HTTP work?
- To make a request for a web page and return the contents of the web page, the applications use the HTTP.
- The web browser application and web server application - use a TCP/IP application

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/172429199-d9165f4b-cc28-48e0-a68c-431445942424.png" height="85%" width="85%" alt="TCP/IP Model"/>
  
<p/>

# Note: Full version of most web addresses - aka Uniform Resource Locators (URL) - begins with the letters HTTP, which means that HTTP is used to transfer the web pages.


# HTTP GET Request, HTTP Reply, and One Data-Only Message
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/172447553-afad7652-1719-417a-b47c-2391503a3baf.png" height="6%" width="65%" alt="TCP/IP Model"/>
  
<p/>



# TCP/IP Transport Layer
- Two most commonly used Transport Layer protocols are the Tranmission Control Protocol (TCP)
- AND the User Diagram Protocol (UDP)
- Transport Layer protocols provide servuces to the application protocols that reside one layer higher in the TCP/IP model


# How does a Transport Layer protocol provide a service to a higher-layer protocol?
- TCP: Error Recovery


# TCP Error Recovery Basics
- To understand and appreciate Transport layer protocols, you have to think about the layer above the transport layer, the application layer.
- Each layer provides a service to the layer above it, like the error-recovery service provided to the application layer protocols by TCP.
- To recover from errors, TCP uses the concept of acknowledgements. 

<p align="center">
  
<img src="" height="6%" width="65%" alt="TCP/IP Model"/>
  
<p/>


