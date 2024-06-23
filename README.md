# Van Nguyen T1A1 Workbook

## Q1
### Identify and explain common and important components and concepts of web development markup languages	

#### What is a 'Markup' Language?

[**Markup languages**][1] is a set of instructions and rules that defines how content is laid out, presented and structured on a web page. This will control over elements on a user's page depending on how it is structured, formatting and how each element is specific and displayed or rendered on a specific web page. 

It is essential as it provides a standardized way to define elements, making it easier for computers and software applications to interpret and display correctly.

Example of popular Markup Languages include:
- **HyperText Markup Language (HTML5 or HTML)** - The most common and popular markup language used to create web pages with elements such as headings, paragraphs, images, links and more.

For example, below is a paragraph tag used in HTML to display text in a webpage:
>`<p> lorem ipsum </p>`


- **Extensible Markup Language(XML)** - Commonly used for storing and transporting data. The difference with XML is that it allows users to define their own customizable tag catering to the user's unique requirement.

For example, below uses unique naming conventions to describe a list of groceries
>`<groceries> <groceries>Chicken Thighs</groceries> </groceries>`

[1]: https://www.semrush.com/blog/markup-language/ "Markup Languages"

#### Components and Concepts of Web Development

The concept of a web development markup languages uses a set of structured tags and attributes to define each element and content within a web page which improves assessibility/search engine optimization(SEO), structural layout and content representation. Below are components that are commonly used in web development mark up languages.

1. **Tags** - Tags are used to define elements within a document. They are normally enclosed with angled brackets and as a pair of opening and closing tags. 

For example:

<h1>this is a HEADER</h1>

>This is a header that is wrapped around between an opening tag of `<h1>` and a closing tag of `</h1>`.

2. **Attributes** - Attributes are a set of additional values and information about an element. It is usually defined with an opening tag and consists of name and a value/target.

For example:

`<a href="https://www.thisisalink.com>Link</a>`
>This is an example of an attribute. `<a> </a>` is the tag and encased within it is the name of the link which is the hyperlink, pairing to = the value/target.

3. [**Semantic Markup**][2] - Used primarily within HTML, semantic markup is used to provide meanings to the content to improve accessibility and search engine optimization(SEO). It helps indicate and clearly describes the meaning of each element to both the browser and a developer. 

The main benefit of semantic markup is:

- **Search Engine Optimization**: by allowing a browser to access and easily understand the contents of a webpage from a header, main body and/or content which is primarily used for SEO principles and practices, assisting search engines to increase chances of a website's content to rank higher on the results page against the user's relevant keyword input.

- **Accessibility**: enabling users with disabilities to access and interact with your a web page. By having meaning to an element/content, it is easier for users and developers to understand and interpret what each component functionality and representation.

Example of Semantics:

`<nav> </nav>`
>Defines the content where the navigation list/menu will be located.
    
`<header> </header>`
>Defines a header for the webpage that contains a website logo, website name, navigation bar, etc. It is normally located at the top of the page
    
`<footer> </footer>`
>Defines a footer for the website that contains information such as contact information, copyright, website author details, etc. It is normally located at the bottom of the screen

[2]: https://www.keyweo.com/en/seo/glossary/semantic-tag/#:~:text=These%20semantic%20tags%20structure%20and,and%20their%20positioning%20is%20improved. "Semantic Markup"


## Q2
### Define the features of the following technologies that are essential in terms of the development of the internet:

 >- packets
 >- IP addresses (IPv4 and IPv6)
 >- routers and routing
 >- domains and DNS
>
>Explain how each technology has contributed to the development of the internet.

#### Packets

[**Packets**][3] basic units of data and is a term used to describe small segments of a larger message in networking. The main feature of a packet is to send data over to a computer network such as the internet, by dividing/partitioning them into 'packets' and then recompiled by a computer or device that receives it. This method used is called [**Packet Switching**][4] which refers breaking down data, sending packets through multiple networks to it's final destination. The main benefit of this is this allows the ability to exchange and send packets to multiple computers at the same time over the internet faster and more efficiently.

[3]: https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/ "Packets"

[4]: https://avinetworks.com/glossary/packet-switching/#:~:text=Packet%20switching%20is%20the%20transfer,packets%2C%20not%20in%20one%20piece. "Packet Switching"

#### IP Addresses

An [**Internet Protocol (IP)**][5] refers to a unique identification number assigned to all devices connected to the internet. There are two different types of IP addresses:

- [**IPv4 (version 4)**][6] - is a protocol for use on packet-switched Link Layer networks introduced in 1981 by DARPA. It is used to identify and route data packets between devices on a network consisting of a network address and the host address. IPv4 are 32-bit integers represented by 4 numbers seperated by dots (.) in a range of 0-255 and is capable of 4.3 billion addresses.

Below is an example of IP address generated for IPv4:
>189.123.123.90. 

- [**IPv6 (version 6)**][7] - is a protocol introduced in 1995 by Internet Engineering Task Force as the number of IPv4 addresses were exhausted. It is an improvement compared to IPv4 allowing complexity and efficiency through the enhancement of security by providing encryption, authenticity and reliability whilst being capable of having an infinite number of addresses. It is also provided better support for Mobile Devices, allowing faster and safer connecting between mobile devices than IPv4. IPv6 are 128-bits written as a group of 8 hexadecimal numbers separated by colon (:).

Below is an example of IP address generated for IPv6:
>fe80::d4a8:6435:d2d8:d9f3b11

[5]: https://www.fortinet.com/resources/cyberglossary/what-is-ip-address#:~:text=An%20Internet%20Protocol%20(IP)%20address,use%20the%20internet%20to%20communicate. "Internet Protocol"

[6]: https://www.linksys.com/support-article?articleNum=139604 "IPv4"

[7]: https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/ "IPv6"

#### Routers and Routing

A [**router**][8] is a network device(s) that connects multiple computer networks together either through a local network or over the internet by directing and managing data packets between them through a cable or wirelessly (Wi-Fi) using TCP/IP models. As networks become increasingly complex, the potential routes between destinations also grow extensively.

[**Routing**][9] will provide security features such as firewalls, performs tasks to share from a single public IP address to multiple devices on a network and manages data traffic and enables the network to maximise its capacity and minimise congestion efficiently using various metrics such as:
- **Hop count** - specifies number of passes through devices such as a router, allowing a packet to move through the source.
- **Delay** - is the time taken by a router to process, queue and transmit data. The lower the value, the better the results.
- **Bandwidth** - this measures the capacity of the link between a router and a device. The higher the bandwidth, the stronger the link is between devices.
- **Load** - refers to the amount of resources/packets being passed through a network. Similar to a CPU, the more packets processed, the traffic load value will also increase that could affect the performance of the network.
- **Reliability** - measured depending on the link between devices and networks dynamically as a network can fail having downtime or may take longer to repair the link.

[8]: https://testbook.com/articles/router#:~:text=Routers%20are%20vital%20networking%20devices,load%20balancing%2C%20and%20failover%20support. "Routers"

[9]: https://www.javatpoint.com/computer-network-routing#:~:text=The%20routing%20protocols%20use%20the,optimal%20path%20to%20the%20destination. "Routing"

####  Domains and DNS

[**Domains**][10] are web addresses consisting of a protrol, domain name and path. By giving a domain a unique [**Domain Name System (DNS)**][11], it functions as a home address allowing users to enter words into their browsers to access a website or a page from a website which is normally associated by a string of text with a numerical IP Address that connects from a device to web servers, allowing ease of accessibility for users such as for example; https://www.google.com. 

Taking the example of Google, a domain name is typically broken down into two parts. The first being the Second-Level Domain (SLD) which comes before the extension correlating to the entity/name of a business and/or identity which is 'Google' and Top-Level Domain (TLD) which refers to the to extension of the website which is '.com'.

[10]: https://blog.hubspot.com/website/what-is-a-domain "Domains"

[11]: https://www.alliedtelesis.com/us/en/documents/domain-name-system-feature-overview-and-configuration-guide#:~:text=DNS%20translates%20meaningful%20domain%20names,remember%20than%20an%20IP%20address "DNS"

## Q3
### Define the features of the following technologies that are essential in terms of the development of the internet:

 >- TCP
 >- HTTP and HTTPS
 >- web browsers (requests, rendering and developer tools)
>
>Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

#### TCP

[Transmission Control Protocol (TCP)][12] is a protocol designed to control the transferring of data using applications and devices to exchange forms of communication. TCP is a standardized procedure for information to be communicated because of features such as:

- **Connection Management** - Initializes a connection between the sender and receiver a reliable, secure communication link.
- **Reliability** - allows reliable peer to peer (P2P) transfers and retransmission to ensure data is transferred correctly.
- **Flow Control** - Prevents overflow of data sent to a recipient at one time which is usually requested by the receiver to the sender.
- **Congestion Control** - Similar to the Flow Control, it ensures the transfer of data from the sender does not overflow the servers of the receiver's network.

This will allow reliable transferring of data communications such as emailing, texting, web browsing and file transfers between users.

[12]: https://www.noction.com/blog/tcp-transmission-control-protocol-congestion-control#:~:text=The%20main%20TCP%20features%20are,for%20creating%20multiple%20virtual%20connections. "TCP"

#### HTTP and HTTPS

[Hypertext Transfer Protocol (HTTP)][14] is used as a form of communication on the internet by transferring unencrypted data between a web server to a web browser(client), and is operated above of the TCP layer. The main issue is due to the lack of encryption, data can be intercepted by a third-party.

[Hypertext Transfer Protocol Secure (HTTPS)][15] however differs. HTTPS is an extension to HTTP that allows secure encryption of data to be sent using Secure Sockets Layer (SSL) and Transport Layer Security (TLS). This is more commonly used now offering data integrity and security to transfer sensitive data such as credit card or other sensitive personal information between the client and the server.

[14]: https://www.javatpoint.com/http-vs-https "HTTP"

[15]: https://medium.com/@shahneel2409/http-and-https-protocol-features-a59db8dc4dc8 "HTTPS"

####  Web browsers

[Web Browsers][16] are applications to access websites on the World Wide Web (WWW) using [protocols such as HTTP][17]. Web browsers communicate by fetching data(request) from a web server and displays(renders) the web page in forms of media elements such as text, images and videos using CSS, Javascript, HTML and more to a user's display. It also provides integrated [developer tools][18], allowing users to inspect and debug a web page, therefore making it possible to prevent errors and optimize performance of a web browser and/or web page. Google Chrome is the most commonly used browser followed by browsers such as Mozilla Firefox, Opera, Safari and more.

[16]: https://www.linkedin.com/pulse/how-does-web-server-communicate-application-pixipace-cy5vc/ "Web Browsers"

[17]: https://www.geeksforgeeks.org/functions-and-features-of-a-web-browser/ "Protocols using HTTP Web Browsers"

[18]: https://developer.mozilla.org/en-US/docs/Glossary/Developer_Tools "Developer Tools"

## Q4
### Describe the features of interpreters and compilers and how they are different.	    

https://seprotec.com/blog/10-important-qualities-an-interpreter-must-possess/

https://www.naukri.com/code360/library/characteristics-of-compiler

https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter#:~:text=A%20compiler%20translates%20code%20written,when%20the%20program%20is%20running.

## Q5
### Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.	

#### Python

https://aws.amazon.com/what-is/python/

#### JavaScript

https://www.computerscience.org/bootcamps/guides/javascript-uses/#:~:text=JavaScript%20is%20a%20programming%20language,user%2Dfriendly%20and%20interactive%20websites.

## Q6
### A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.	

>The client’s email is as follows:
>
>Hello there!
>
>My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artefacts, objects, and paraphernalia about all sorts of things from all over the world.
>
>I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum.
>
>We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum.
>
>We don’t know much about this website stuff - does this sound like something that you can do? 
>
>Looking forward to hearing from you,
>
>Alex
>
>Director
>
>Super Awesome Museum  

## Q7
#### Think back to a scenario or situation in your own software development projects or work. Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.



## Q8
#### A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.



## Q9
#### Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.	



## Q10
#### Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.	



## Q11
### Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

>- soft skills
>- hard skills

## Q12
### Explain multiple roles or job positions that would be found in a medium-sized software development company.	



## References
1. **Markup Languages**: https://www.semrush.com/blog/markup-language/
2. **Semantic Markup**: https://www.keyweo.com/en/seo/glossary/semantic-tag/#:~:text=These%20semantic%20tags%20structure%20and,and%20their%20positioning%20is%20improved.
3. **Packets**: https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/
4. **Packet Switching**: https://avinetworks.com/glossary/packet-switching/#:~:text=Packet%20switching%20is%20the%20transfer,packets%2C%20not%20in%20one%20piece.
5. **Internet Protocol**: https://www.fortinet.com/resources/cyberglossary/what-is-ip-address#:~:text=An%20Internet%20Protocol%20(IP)%20address,use%20the%20internet%20to%20communicate.
6. **IPv4**: https://www.linksys.com/support-article?articleNum=139604
7. **IPv6**: https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/
8. **Routers**: https://testbook.com/articles/router#:~:text=Routers%20are%20vital%20networking%20devices,load%20balancing%2C%20and%20failover%20support.
9. **Routing**: https://www.javatpoint.com/computer-network-routing#:~:text=The%20routing%20protocols%20use%20the,optimal%20path%20to%20the%20destination.
10. **Domains**: https://blog.hubspot.com/website/what-is-a-domain
11. **DNS**: https://www.alliedtelesis.com/us/en/documents/domain-name-system-feature-overview-and-configuration-guide#:~:text=DNS%20translates%20meaningful%20domain%20names,remember%20than%20an%20IP%20address
12. **TCP**: 
    - https://www.noction.com/blog/tcp-transmission-control-protocol-congestion-control#:~:text=The%20main%20TCP%20features%20are,for%20creating%20multiple%20virtual%20connections. 
    - https://www.fortinet.com/resources/cyberglossary/tcp-ip

    - https://www.techtarget.com/searchnetworking/definition/TCP#:~:text=One%20of%20the%20main%20functions,browsing%20wouldn't%20be%20possible. 
13. **HTTP**: https://www.javatpoint.com/http-vs-https
14. **HTTPS**: https://medium.com/@shahneel2409/http-and-https-protocol-features-a59db8dc4dc8
15. **Web Browsers**: https://www.linkedin.com/pulse/how-does-web-server-communicate-application-pixipace-cy5vc/
16. **Web Browser Protocols using HTTP**: https://www.geeksforgeeks.org/functions-and-features-of-a-web-browser/
17. **Developer Tools**: https://developer.mozilla.org/en-US/docs/Glossary/Developer_Tools
18. **Interpreters**: https://seprotec.com/blog/10-important-qualities-an-interpreter-must-possess/
19. **Compilers**: https://www.naukri.com/code360/library/characteristics-of-compiler
20. **Interpreters vs Compilers**: https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter#:~:text=A%20compiler%20translates%20code%20written,when%20the%20program%20is%20running.
21. **Python**: https://aws.amazon.com/what-is/python/
22. **JavaScript**: https://www.computerscience.org/bootcamps/guides/javascript-uses/#:~:text=JavaScript%20is%20a%20programming%20language,user%2Dfriendly%20and%20interactive%20websites.
