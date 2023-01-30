---
description: >-
  Networks and protocols are fundamental concepts in computer science and
  telecommunications that describe the rules and methods for communication
  between devices and systems
---

# Networks & Protocols

Networks and protocols are fundamental concepts in computer science and telecommunications that describe the rules and methods for communication between devices and systems. They form the backbone of the internet and other global networks, and are used to transmit data, voice, and video across the world.

## **History**

* In the 1960s, the US Department of Defense (DoD) developed the first packet-switching networks, which allowed for efficient data transfer between computers.
* In the 1970s, the development of the Transmission Control Protocol (TCP) and Internet Protocol (IP) formed the foundation of the internet as we know it today.
* In the 1980s, the development of the Domain Name System (DNS) and File Transfer Protocol (FTP) further enhanced the functionality of the internet.
* In the 1990s, the World Wide Web (WWW) and the development of the Hypertext Transfer Protocol (HTTP) revolutionized the way we access and share information online.
* In recent years, the proliferation of cloud computing and the Internet of Things (IoT) has led to the development of new protocols and technologies, such as the MQTT and CoAP, designed to support low-power, low-bandwidth devices.

## Relevant people

* Vint Cerf and Bob Kahn are known as the "fathers of the internet" for their work on the development of TCP and IP.
* Tim Berners-Lee developed the World Wide Web and the HTTP protocol.
* Paul Mockapetris developed the Domain Name System (DNS).
* Phil Zimmermann developed the Pretty Good Privacy (PGP) encryption protocol.

## **Protocols**

### **Transmission Control Protocol (TCP)**

* TCP is a connection-oriented protocol that guarantees the delivery of data packets in the correct order.
* It also provides flow control and error correction mechanisms to ensure that data is transferred reliably.
* TCP works by establishing a virtual connection between two devices before any data is transferred, and then breaking the data into small packets, called segments, which are sent and reassembled at the destination.
* The main algorithm used in TCP is the Transmission Control Protocol Congestion Avoidance Algorithm (TCP-CA) which controls the rate at which a device sends data to prevent network congestion.

### **Internet Protocol (IP)**

* IP is a connectionless protocol that routes packets of data based on their IP addresses.
* It does not guarantee the delivery of data packets or their order.
* IP works by dividing data into small packets called datagrams, which are sent independently and reassembled at the destination.
* IP does not provide any mechanism for error checking or correction, which is why it is often used in conjunction with TCP or other transport layer protocols.

### **Domain Name System (DNS)**

* DNS is a hierarchical naming system that translates domain names (such as [www.example.com](http://www.example.com/)) into IP addresses.
* It allows for easy human-readable access to websites and other online resources, rather than having to remember and enter IP addresses.
* DNS works by resolving domain names to IP addresses through a system of DNS servers, which are organized in a hierarchical structure.
* One of the most common algorithms used in DNS is the caching algorithm which help to reduce the latency of DNS resolution.

### **File Transfer Protocol (FTP)**

* FTP is a standard protocol for transferring files between computers on a network.
* FTP allows for the transfer of files and directories, as well as the ability to manage file permissions and access control.
* FTP uses two separate connections, one for control and one for data transfer, and requires a separate login for the server.

### **Hypertext Transfer Protocol (HTTP)**

* HTTP is a protocol used for transferring data over the internet (e.g. sending a request for a webpage from your browser to a server).
* HTTP is the foundation of the World Wide Web, and allows for the transfer of hypertext documents (such as HTML, XML, and JSON) between web browsers and servers.
* HTTP uses a request-response model, where the client sends a request to the server, and the server responds with the requested data.

### **Simple Object Access Protocol (SOAP)**

* SOAP is a protocol used for exchanging structured data between applications over a network.
* SOAP uses XML as its message format, and can be carried over a variety of lower-level protocols, including HTTP and SMTP.
* SOAP is typically used for web services and other remote procedure call (RPC) systems, and often includes built-in error handling.

### **Representational State Transfer (REST)**

* REST is a set of architectural principles for creating web services.
* RESTful web services use HTTP methods (such as GET, POST, PUT, and DELETE) to interact with resources.
* REST is typically used for simple CRUD (create, read, update, delete) operations and is often used in conjunction with JSON.

### **MQTT and CoAP**

* MQTT and CoAP are protocols designed to support low-power, low-bandwidth devices in IoT networks.
* MQTT is a lightweight publish-subscribe messaging protocol, while CoAP is a RESTful protocol for resource-constrained devices.
* Both MQTT and CoAP are designed to minimize the amount of data transmitted, and to minimize the power consumption of devices.

## Cloud computing

In cloud computing, networks and protocols are used to communicate between the various components of the system, such as between the client and the server, and between different microservices. The use of standard protocols allows for interoperability between different systems and vendors, making it easier to share data and resources.

For example, the HTTP protocol is commonly used to access cloud-based services and applications, such as web-based email or storage services. The HTTP protocol allows the client (e.g. web browser) to send requests to the server (e.g. email or storage service), and the server to send responses back to the client. This is done using standard HTTP methods, such as GET, POST, PUT, and DELETE.

Another example is the use of the Simple Object Access Protocol (SOAP) and Representational State Transfer (REST) protocols to interact with web services and APIs in cloud computing. SOAP is an XML-based protocol that uses HTTP for transport and is commonly used for enterprise-level applications. REST is an architectural style that uses HTTP methods (such as GET, POST, PUT, and DELETE) to interact with resources. Both SOAP and REST are widely used in cloud computing to provide access to various services and applications.

In addition to standard protocols, cloud computing also makes use of various security protocols, such as Secure Sockets Layer (SSL) and Transport Layer Security (TLS) to encrypt data in transit, and Secure Shell (SSH) to provide secure remote access to servers. Algorithm such as RSA, AES, and SHA are also used in cloud computing to secure data at rest and secure communication.

## Conclusion

Networks and protocols are the foundation of communication between devices and systems, they are used to transmit data, voice, and video across the world. Examples of protocols include HTTP, SOAP, REST, MQTT, and CoAP. In cloud computing, these protocols are used to communicate between the various components of the system, allowing for interoperability and ease of integration between different systems and vendors. Security protocols and algorithms are also used to ensure the confidentiality, integrity, and authenticity of data in the cloud.
