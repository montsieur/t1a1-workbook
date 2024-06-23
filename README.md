# Van Nguyen T1A1 Workbook

## Q1
### Identify and explain common and important components and concepts of web development markup languages	

#### What is a 'Markup' Language?

[**Markup languages**][1] is a set of instructions and rules that defines how content is laid out, presented and structured on a web page. This will control over elements on a user's page depending on how it is structured, formatting and how each element is specific and displayed or rendered on a specific web page *(Varagouli, 2021)*. 

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

3. [**Semantic Markup**][2] *(keyweo, n.d.)* - Used primarily within HTML, semantic markup is used to provide meanings to the content to improve accessibility and search engine optimization(SEO). It helps indicate and clearly describes the meaning of each element to both the browser and a developer. 

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

[**Packets**][3] basic units of data and is a term used to describe small segments of a larger message in networking *(Cloudflare, n.d.)*. The main feature of a packet is to send data over to a computer network such as the internet, by dividing/partitioning them into 'packets' and then recompiled by a computer or device that receives it. This method used is called [**Packet Switching**][4] which refers breaking down data, sending packets through multiple networks to it's final destination. The main benefit of this is this allows the ability to exchange and send packets to multiple computers *(Avi Networks, n.d.)* at the same time over the internet faster and more efficiently.

[3]: https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/ "Packets"

[4]: https://avinetworks.com/glossary/packet-switching/#:~:text=Packet%20switching%20is%20the%20transfer,packets%2C%20not%20in%20one%20piece. "Packet Switching"

#### IP Addresses

An [**Internet Protocol (IP)**][5] refers to a unique identification number *(Fortinet, 2024)* assigned to all devices connected to the internet. There are two different types of IP addresses:

- [**IPv4 (version 4)**][6] - is a protocol for use on packet-switched Link Layer networks introduced in 1981 by DARPA *(www.linksys.com, n.d.)*. It is used to identify and route data packets between devices on a network consisting of a network address and the host address. IPv4 are 32-bit integers represented by 4 numbers seperated by dots (.) in a range of 0-255 and is capable of 4.3 billion addresses *(B, 2019)*.

Below is an example of IP address generated for IPv4:
>189.123.123.90. 

- [**IPv6 (version 6)**][7] - is a protocol introduced in 1995 by Internet Engineering Task Force as the number of IPv4 addresses were exhausted. It is an improvement compared to IPv4 allowing complexity and efficiency through the enhancement of security by providing encryption, authenticity and reliability whilst being capable of having an infinite number of addresses. It is also provided better support for Mobile Devices, allowing faster and safer connecting between mobile devices than IPv4. IPv6 are 128-bits written as a group of 8 hexadecimal numbers separated by colon ( : ) *(B, 2019)*.

Below is an example of IP address generated for IPv6:
>fe80::d4a8:6435:d2d8:d9f3b11

[5]: https://www.fortinet.com/resources/cyberglossary/what-is-ip-address#:~:text=An%20Internet%20Protocol%20(IP)%20address,use%20the%20internet%20to%20communicate. "Internet Protocol"

[6]: https://www.linksys.com/support-article?articleNum=139604 "IPv4"

[7]: https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/ "IPv6"

#### Routers and Routing

A [**router**][8] is a network device(s) that connects multiple computer networks together either through a local network *(Testbook, n.d.)* or over the internet by directing and managing data packets between them through a cable or wirelessly (Wi-Fi) using TCP/IP models. As networks become increasingly complex, the potential routes between destinations also grow extensively.

[**Routing**][9] will provide security features such as firewalls, performs tasks to share from a single public IP address to multiple devices on a network and manages data traffic and enables the network to maximise its capacity and minimise congestion efficiently using various metrics such as:
- **Hop count** - specifies number of passes through devices such as a router, allowing a packet to move through the source.
- **Delay** - is the time taken by a router to process, queue and transmit data. The lower the value, the better the results.
- **Bandwidth** - this measures the capacity of the link between a router and a device. The higher the bandwidth, the stronger the link is between devices.
- **Load** - refers to the amount of resources/packets being passed through a network. Similar to a CPU, the more packets processed, the traffic load value will also increase that could affect the performance of the network.
- **Reliability** - measured depending on the link between devices and networks dynamically as a network can fail having downtime or may take longer to repair the link.
*(www.javatpoint.com, n.d.)*

[8]: https://testbook.com/articles/router#:~:text=Routers%20are%20vital%20networking%20devices,load%20balancing%2C%20and%20failover%20support. "Routers"

[9]: https://www.javatpoint.com/computer-network-routing#:~:text=The%20routing%20protocols%20use%20the,optimal%20path%20to%20the%20destination. "Routing"

####  Domains and DNS

[**Domains**][10] are web addresses consisting of a protrol, domain name and path. By giving a domain a unique [**Domain Name System (DNS)**][11], it functions as a home address allowing users to enter words into their browsers *(Allied Telesis, n.d.)* to access a website or a page from a website which is normally associated by a string of text with a numerical IP Address *(Fitzgerald, 2022)* that connects from a device to web servers, allowing ease of accessibility for users such as for example; https://www.google.com. 

Taking the example of Google, a domain name is typically broken down into two parts. The first being the Second-Level Domain (SLD) which comes before the extension correlating to the entity/name of a business and/or identity which is 'Google' and Top-Level Domain (TLD) which refers to the to extension of the website which is '.com'. *(Fitzgerald, 2022)*

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
*(Fortinet, 2021)*

This will allow reliable transferring of data communications such as emailing, texting, web browsing and file transfers between users *(Networking, n.d.)*.

[12]: https://www.noction.com/blog/tcp-transmission-control-protocol-congestion-control#:~:text=The%20main%20TCP%20features%20are,for%20creating%20multiple%20virtual%20connections. "TCP"

#### HTTP and HTTPS

[Hypertext Transfer Protocol (HTTP)][13] is used as a form of communication on the internet by transferring unencrypted data between a web server to a web browser(client) *(www.javatpoint.com, n.d.)*, and is operated above of the TCP layer. The main issue is due to the lack of encryption, data can be intercepted by a third-party.

[Hypertext Transfer Protocol Secure (HTTPS)][14] however differs. HTTPS is an extension to HTTP that allows secure encryption of data to be sent using Secure Sockets Layer (SSL) and Transport Layer Security (TLS) *(Shah, 2023)*. This is more commonly used now offering data integrity and security to transfer sensitive data such as credit card or other sensitive personal information between the client and the server.

[13]: https://www.javatpoint.com/http-vs-https "HTTP"

[14]: https://medium.com/@shahneel2409/http-and-https-protocol-features-a59db8dc4dc8 "HTTPS"

####  Web browsers

[Web Browsers][15] are applications to access websites on the World Wide Web (WWW) *(www.linkedin.com, n.d.)* using [protocols such as HTTP][16] *(GeeksforGeeks, 2023)*. Web browsers communicate by fetching data(request) from a web server and displays(renders) the web page in forms of media elements such as text, images and videos using CSS, Javascript, HTML and more to a user's display. It also provides integrated [developer tools][17] *(developer.mozilla.org, n.d.)*, allowing users to inspect and debug a web page, therefore making it possible to prevent errors and optimize performance of a web browser and/or web page. Google Chrome is the most commonly used browser followed by browsers such as Mozilla Firefox, Opera, Safari and more.

[15]: https://www.linkedin.com/pulse/how-does-web-server-communicate-application-pixipace-cy5vc/ "Web Browsers"

[16]: https://www.geeksforgeeks.org/functions-and-features-of-a-web-browser/ "Protocols using HTTP Web Browsers"

[17]: https://developer.mozilla.org/en-US/docs/Glossary/Developer_Tools "Developer Tools"

## Q4
### Describe the features of interpreters and compilers and how they are different.

#### Interpreters

An [**interpreter**][18] is a program that directly executes the instructions in a high-level programming language without having to convert it to machine code *(Toppr-guides, 2021)*. 

The difference with interpreters are:
- Executes a source of code directly one line at a time and will come to a halt if any error occurs with each statement, allowing an easier debugging process during compilation.
- Analyzing a source of code is generally quicker resulting in less time to compile but may take longer to execute as it the program will require to translate one line at a time.
- Programming languages or 'scripting languages' such as Python, Ruby and PHP uses interpreters. 

#### Compilers

A [**compiler**][19] reads an entire source code in one go and generates machine code for later execution by a computer's processor by converting human-readable code into instructions that a computer can understand and execute *(Built In, n.d.)*.

The difference with compilers are:
- Executes a source of code at one time, therefore shows all errors altogether resulting in debugging processes more difficult after compiling.
- A compiler typically runs faster because it translates an entire program at once but slower in analyzing and compiling as it generates more memory to run an entire source code at one time.
- Programming languages such as C, C++ and Java uses compilers.

[18]: https://www.toppr.com/guides/computer-science/computer-fundamentals/system-software/interpreter/#:~:text=An%20interpreter%20is%20a%20program,is%20to%20use%20a%20compiler. "Interpreters"

[19]: https://www.naukri.com/code360/library/characteristics-of-compiler "Compilers"

## Q5
### Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.	

The two most commonly used programming languages are [**Python**][21] and [**JavaScript**][22].

#### Python

Python is interpreted as a high-level programming language and one of the most popular forms of coding languages due to it's versatlity and user-friendly approach *(Gavrilova, 2023)*.

##### Benefits

- **Beginner Friendly** - the main reason for it's considered easy to learn is its simple syntax language, allowing users to easily read and understand which therefore allows developers to write and debug.
- **Versatility** - it can be used in a variety of applications from data analysis to machine learning depending on the developer's interest.
- **Community and Resources** - widely supported by the community that contributes to sharing many open-sourced libraries, forums, social media groups and frameworks. This is beneficial for those learning the language as they are able to gain knowledge and feedback from other developers.
- **Flexibility** - it's flexibility comes from having the ability to be integrated with other programming languages such as C++ and Java depending on the specific tasks needed for a project.
- **Prototype Friendly** - Being able to run and test a line(s) of code in real-time efficiently improve the debugging processes, improve or refine their source code.


##### Drawbacks

- **Slower than compiled languages** - because Python is an interpreted language, it will execute each line of code one at a time resulting in slower execution times especially when working on large databases or source codes.
- **Less Secure** - because Python is dynamically typed, it relates to the speed of which a program can run rather then the amount of time to compile resulting in vulnerabilities making it an easy target for hackers.
- **Poor multithreading** - with Global Interpreter Locks (GIL), this limits python to execute one thread at a time regardless of the amount of threads available and cannot be run in parallel, therefore affecting the performance.

[21]: https://serokell.io/blog/python-pros-and-cons "Python"

#### JavaScript

JavaScript is a widely used programming languaged primarly for it's versatility in creating interactive elements *(Anon, 2024)* within a website alongside with markup languages such as HTML and style languages such as CSS (Cascading Style Sheets).

##### Benefits

- **Speed and Efficiency** - has the ability to be executed on the client's side as the JavaScript code when a user accesses a website, it runs the code directly on their browser rather than relying on a server. This results in faster loading times and real-time dynamic responses.
- **Regular Updates** - receives updates by organizations such as the ECMA International (European Computer Manufacturers Association) and introducing new features and improvements to performances, constantly evolving and developing match with technological advancements.
- **Simplicity** - allows both front-end and back-end tasks to be executed within a single programming language. This allows the approach of a website to be unified by reducing the complexity and enhancing the efficiency when creating and maintaining a website.
- **Vast Resources** - JavaScript also benefits with a vast of libraries and frameworks such as React, Angular and Vue.js by offering pre-built components and structures for web development without starting from scratch.

##### Drawbacks

- **Vulnerabilities** - because JavaScript is implemented through various different browsers, it is exploited by using these differences to inject malicious code therefore compromising the security of the system. Furthermore, these unsolicited changes can come undetected from unauthorized access of data to manipulation of data which warrents vigilance.
- **Visibility** - as with it's vulnerabilities, this mostly is due to the visibility of code which is visible to everyone who has access to the webpage causing security risks and additionally, slows down the execution of the code itself.
- **Slow Execution** - JavaScript’s Document Object Manipulation (DOM) model depending on the performance of a network latency which will result in delays when loading a webpage especially if the code is not optimized correctly.
- **Dependancy** - disabling JavaScript or a flaw in the script for a webpage may cause the functionality of the webpage to cease or partially operate which will disrupt a user's experience.
- **Search Engine Optimization** - SEO has difficulties understanding and indexing JavaScript's content, affecting it's visibility during an online search, potentially reducing their reach with their intended audiences.

[22]: https://ellow.io/advantages-and-disadvantages-of-javascript/ "JavaScript"

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

**Reponse**:

Dear Alex,

I hope this message finds you well, and thank you for expressing your interest in developing a website for the Super Awesome Museum (SAM). I'm excited about the opportunity to assist and work with you to bring your visions to life.

From my understanding based on your request, the website will primarily be used to promote the museum effectively by offering essential information for visitors about the location of the museum and highlighting SAM's diverse collection of exhibits.

To ensure we are on the right track, what will be the SAM's main attraction and/or theme you would like to promote, and what is SAM's intended audience? This way, we can create a roadmap of ideas to effectively produce the website visually from a marketing point of view.

For the technical aspects of the website, I can certainly handle the entire process of building a website. This is a brief outline of what we can provide based on the information given:

1. **Home page**
We can create a visually appealing homepage that showcases featured exhibits and artefacts prominently to increase user engagement and create a good first impression to potential visitors.

2. **Visitor Information Page**
This will show clear navigation and information on how to reach SAM's address, including maps, directions, and parking details if applicable. This will ensure visitors can easily plan their trip to visit SAM.

3. **Contact and Interaction Page**
This is the contact page showing the museum's contact details, such as phone numbers and/or emails. This may include elements such as forms for visitors or potential visitors to send in their enquiries or feedback if you prefer this feature to be included.

To ensure this website is accessible to everyone, we will create a responsive website design that will be compatible with all devices, whether it is a computer, laptop, or mobile phone. In addition, we will create the website to implement the best search engine optimisation practices to ensure users are able to easily and visibly search SAM's website on browsers such as Google.

I'd love to schedule a meeting to discuss your project in more detail and answer any questions you may have. Please let me know your availability, and we can set up a time that works for you.

I look forward to your response and the opportunity to collaborate on this exciting project, and thank you for considering me for your website project.

Kind regards,

Van Nguyen, Web Developer<br>
+61 400 000 000<br>
www.portfolio.com<br>

## Q7
### Think back to a scenario or situation in your own software development projects or work. Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.

My only experience in a software engineering, was creating my first website portfolio at Coder Academy which was a very fun and educational project for someone like me who had no prior experience with web development whatsoever. What I would be reflecting specifically to this project would be the implementation and execution of visuals elements such as the use of images and semantic tags which is also a form of visual communication.

>*Gibbs Reflective Cycle (Mind Tools Content Team, 2022)*

#### Description

When I was planning my website visually, I knew I wanted to implement minimilism to my website so it's not too busy and overwhelming to a viewer's perspective. With a layout in mind after creating a wireframe, I spent many hours experimenting between CSS Flexbox and CSS Grid adding in visual elements such as a header, navigation, footer, text and imagery ensuring they wrapped the way I wanted to. Although I was unsuccessful after many attempts, I had to rethink my layout to ensure I'm able to execute it within my level of skill. In the end, even though it was not the layout I initially had in mind, I was able to produce a website that I have planned and executed gaining many experiences along the way.

#### Feeling

I attempted this project with a lot of optimism and positivity feeling I could do well at the beginning. However, after many failures, I had started to feel stressed and frustrated for not being able to get it correctly no matter how hard I try. It will escalate further when I had received a feeling of success after the completion of one element of the website and it will later break when working on the next element not long after. There was a lot of perseverance involved and after taking multiple breaks, I had to collect myself and rethink how I would approach the project and still produce a website that I am still satisfied with.

#### Evaluation

The positives I can take this project is having the ability to complete it. The moment I was able to go past the hurdle stopping me from progressing, it was a lot more smoother for the remaining of the project. Although I had taken a few shortcuts and because of that, the results wasn't exactly what I had initially planned and it was also not the correct way of executing which led to the project being evaluated lower than I would've hoped for such as using the wrong semantics for my navigation bar for my header. Additionally I was careless when submitting, seeing that some of my image elements were not visible from another's perspective but overall, I am still proud of myself for completing it.

#### Conclusion

From the experiences I've taken from this, it helped me understand what it's like to work on projects like this as this will be the norm once I enter the industry myself. With more research and practice, I will be able to attempt and complete a project like this with more confidence and speed. Although, I believe I would have been able to generate better results if I had better time management and control to research more rather than panicking and resorting to shortcuts. I may have not gotten the full satisfaction or result I wanted, but after reflecting, I now believe that failure is a normal and necessary step to learn and succeed. 

#### Action

If I had the chance to work on a similar project or create a portfolio website again, I would ensure to use all the resources available to me whether that will be through the internet or reach out to those nearest to me such as my lecturers. I will resort to better planning and learning more knowledge to be more efficient and optimise my time and methods to implement features I was not able to do before. In addition to further improving by learning JavaScript to add more interactive elements to my website.


## Q8
### A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

#### Action Plan

To attend more technology events and attempt domestic travel to attend events such as:
- Australian Computer Society Networking events
- Programmable (held once a year)
- Look out for meetups posted on Coder Academy Discord channels
- Using Linkedin to network with other developers and/or join events and groups relating to software engineering

The benefits of attending these networking and technology events are similar across each plan. It will provide me exposure to the industry and have opportunities to network and meet professionals within the IT industry. Being able to gain the knowledge of not only about software engineering but the professionals attending these events, I will be able to have a clearer understanding when listening to their panel or lectures which will improve my chances of learning and successfully networking with the relevant professionals which could potentially lead to an opportunity to join a tech company.

It is also important to network using social media platforms such as Linkedin to communicate through joining digital networks and applying for tech jobs on LinkedIn. At the same time, I will build on my portfolio and work on practicing my software engineering skills using websites such as LeetCode and other platforms and share it on my social media platforms.

With this in mind, I plan to allocate my time to this action plan within the next 12 months whilst learning all I can within Coder Academy. This way, I will gain the knowledge relevant to the industry whilst networking at these events by the time I finish the bootcamp and enter the tech industry as a result.

## Q9
### Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.	

[ChatGPT][24] is a free Language-Learning Model technology using artificial intelligence(AI), used to respond to user's queries with comprehensive, human-like responses. It uses deep learning techniques to process text and generate text prompts based on the patterns it learns and has received within it's network whilst easily adapting to a user's feedback when interacting *(Kanade, 2023)*.

In software development, it can be used a tool to help improve a developer's quality of life. The quality of life for a software developer is increased dramatically as it is a tool to help produce repetitive sources of code on their behalf, generate comprehensive documentation of code, simplifies the code, translate software interfaces, debugging extensive lines of codes quickly and have the ability to understand logic and structure *(GAMAGE, 2023)*. Overall, this improves efficiency, accuracy and performance. Because this is so accessible to the public, it is usable by user's who also have no prior knowledge looking to learn from this OpenAI learning model.

Although ChatGPT does improve a developer's quality of life, it still requires a level of human comprehension by the developer to understand the prompts and results given by ChatGPT. As it is not perfect, there will still be a degree of errors and lack of explanation which may not benefit a developer.

[24]: https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-chatgpt/ "ChatGPT"

## Q10
### Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.	

#### Legal Impacts

The main controversies in not just software development is plagarism and copyright as it stitches pieces of information learned from various internet sources, potentially infringing on intellectual property rights of third parties *(Ryan, 2023b)*. 

Another implication that will cause issues is the concern of data privacy and regulation. Because ChatGPT stores conversations as data in it's server's, it may lead to potential legal impacts if a user inputs confidential and/or sensitive information *(Ryan, 2023b)* which is later produced by the tool to another user. Even though user's are able to disable the chat history feature and request logs to be deleted, it is pointed out that deleting a chat does not erase information from the server as information *(O’Flaherty, n.d.)* received by ChatGPT goes through multiple forms of manipulation making it harder to erase.

Lastly, although ChatGPT does help improve a developer's quality of life, if the developer cannot comprehend the output sent by ChatGPT, it may lead to a degree of misunderstandings and errors whilst responses could also potentially contain discriminatory or inaccurate information, ultimately resulting in reputational damages *(Ryan, 2023b)*.

#### Ethical Impacts

Ethically, ChatGPT has issues alongside with the legal impacts that can result to implications such as:
- Biased and inaccurate information
- Privacy Violations
- Plagarism
- Copyright Infringements

ChatGPT does not have the capabilities to provide citations for it's sources *(Ryan, 2023a)*. Since it is trained through various sources, multiple accounts of information may contain biases by a user resulting in false or inaccurate information to be outputted by the tool, ruining it's credibility. One main unethical practices with ChatGPT involves user's to generate content and information and passing it off as their own. Even though ChatGPT uses the methods of paraphrasing and modification to sources of information, it is not completely free of plagarism as it fails to use any citations in it's documentation *(Lee, 2023)*. But there has been debates of using ChatGPT to elevate academic writing as long as a student or user are transparent with the use of tools such as ChatGPT *(Perkins, 2023)*.

## Q11
### Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

#### Soft Skills

Soft skills generally refers to a personal trait or ability of an individual that often cannot be taught with on-the-job training methods. Those with exceptional soft skills manage to negotiate higher salaries *(Eilers, 2023)* and find themselves landing positions within a tech company easier than someone with lesser soft skills. Examples of soft skills include:

- **Communication** - being able to convey technical and complicated concepts to those without prior technical knowledge.
- **Time Management** - keeping track and able to work multiple projects and managing tasks at one time while being able to work efficiently meeting expectations such as deadlines.
- **Problem-solving skills** - providing innovative solutions, overcoming through any obstacle that prevents you from completing a project.

#### Hard skills

Hard skills refers to skills learnt through education of hands-on experiences which is measurable through practical exercises *(S. Gillis, n.d.)*. Examples of hard skills within software development include:

- **Programming Languages**: it is crucial to have knowledge in programming languages such as Python, JavaScript, C#, etc. This will allow developers to to create a body of source for a computer or device to execute depending on the project.
- **Testing & Debugging** *(Codemotion, 2023)*: being able to speedily and accurately indentify and resolve cold is an integral process within the software development industry.
- **Version control systems** *(Eilers, 2023)*: usage of a software tool that allows a developer to keep record of various different versions of a particular code and/or file that another developer is working on.

## Q12
### Explain multiple roles or job positions that would be found in a medium-sized software development company.	

#### Software Developer

Software developers are found in almost every industry that as technology is always evolving and used for everyday tasks. They generally utlize a range of tools and specialize in creating and designing software and/or applications by using different programming language codes such as Python, JavaScript, C++ and more. This can include maintaining the functionality of networks and devices through code and often engage with clients to understand the requirements and processes behind them *(devry.edu, n.d.)*. 

#### Project Manager

They provide leadership and technical expertise to their team of software developers, overseeing the development process of a project *(Ovcharenko, 2022)*. During the development process, project managers manage their team and assist them to design, execute, monitor and complete the work required to ensure satisfactory results for their clients. Some skills required for this position may include *(Motiso, n.d.)*:

- **Organisational Skills** - Builds a detailed plan outlining for projects which may include budgeting, personnel and resources to prevent any risks and potential problems.
- **Relationship Management** - whether through clients or their own team, they are able to either provide viable feedback, communicate goals and resolving conflict.

#### UI/UX Designer

UI/UX Designer (User Interface/User Experience) are responsible for designing the accessibility of a user's interface and experience on applications, software, website or device that a person interacts with *(Coursera, n.d.)*. Their tasks involves gathering data and conducting research *(Coursera, 2023)* on how a user will interact with their product whether it is the visual interface of a website menu or graphical layout. By doing so, they are able to design and create wireframes to demonstrate how their product will function visually and methodically or to improve on an existing product to further enhance a user's experience. 

#### Full-Stack Developer

A Full-Stack Developer is defined by developers that have expertise in both Front-End and Back-End development *(SEEK, n.d.)*. Generally referred to as Web Developers, but their skills can be applied for other types of software development as they are proficient in most programming languages. Front-End development works on user interfaces of any website and/or application that a client or viewer can see and interact with using languages such as HTML, CSS and JavaScript. While Back-End Development refers to the server-side and databases of a website and/or application that is generally never touched by the end-user *(SEEK, n.d.)* using program languages such as Python, Java and Ruby.

## References

Allied Telesis. (n.d.). Domain Name System (DNS) Feature Overview and Configuration Guide. [online] Available at: https://www.alliedtelesis.com/us/en/documents/domain-name-system-feature-overview-and-configuration-guide#:~:text=DNS%20translates%20meaningful%20domain%20names.

Anon, (2024). Advantages and Disadvantages of Javascript - ellow.io. [online] Available at: https://ellow.io/advantages-and-disadvantages-of-javascript/.

Avi Networks (n.d.). What is Packet Switching? Definition & FAQs. [online] Avi Networks. Available at: https://avinetworks.com/glossary/packet-switching/#:~:text=Packet%20switching%20is%20the%20transfer.

B, S. (2019). Differences between IPv4 and IPv6 - GeeksforGeeks. [online] GeeksforGeeks. Available at: https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/.

Built In. (n.d.). Compiler vs. Interpreter in Programming. [online] Available at: https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter#:~:text=A%20compiler%20translates%20code%20written [Accessed 23 Jun. 2024].

Cloudflare. (n.d.). What is a packet? | Network packet definition. [online] Available at: https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/.

Codemotion (2023). Trending Hard Skills and Soft Skills In Software Development. [online] Codemotion Magazine. Available at: https://www.codemotion.com/magazine/it-careers/trending-hard-skills-and-soft-skills-in-software-development/.

Coursera (2023). What Does a UX Designer Do? [Updated 2021]. [online] Coursera. Available at: https://www.coursera.org/articles/what-does-a-ux-designer-do.

Coursera. (n.d.). What Is a User Interface (UI) Designer? [Updated 2022]. [online] Available at: https://www.coursera.org/articles/what-is-a-user-interface-ui-designer-guide.

developer.mozilla.org. (n.d.). Developer Tools - MDN Web Docs Glossary: Definitions of Web-related terms | MDN. [online] Available at: https://developer.mozilla.org/en-US/docs/Glossary/Developer_Tools.

devry.edu. (n.d.). What Does a Software Developer Do | DeVry University. [online] Available at: https://www.devry.edu/blog/what-does-a-software-developer-do.html#:~:text=interact%20with%20computers.-.

Eilers, C. (2023). Software Engineering: Hard vs. Soft Skills - ALX Africa. [online] www.alxafrica.com. Available at: https://www.alxafrica.com/software-engineering-hard-vs-soft-skills/#:~:text=Hard%20skills%20software%20engineers%20learn%20include%3A%20programming%20languages%20like%20Python [Accessed 23 Jun. 2024].

Fitzgerald, A. (2022). The Plain-English Guide to Domains & Domain Names. [online] blog.hubspot.com. Available at: https://blog.hubspot.com/website/what-is-a-domain.

Fortinet (2021). What is TCP/IP and How does it work? [online] Fortinet. Available at: https://www.fortinet.com/resources/cyberglossary/tcp-ip.

Fortinet (2024). What is an IP Address? How it works? How to Locate it? [online] Fortinet. Available at: https://www.fortinet.com/resources/cyberglossary/what-is-ip-address#:~:text=An%20Internet%20Protocol%20(IP)%20address.

GAMAGE, D. (2023). 7 Ways ChatGPT Can Help Developers | .cult by Honeypot. [online] cult.honeypot.io. Available at: https://cult.honeypot.io/reads/how-can-chatgpt-help-developers/.

Gavrilova, Y. (2023). Pros and Cons of Python. [online] Pros and Cons of Python. Available at: https://serokell.io/blog/python-pros-and-cons.

GeeksforGeeks. (2023). Functions and Features of a Web Browser. [online] Available at: https://www.geeksforgeeks.org/functions-and-features-of-a-web-browser/.

Kanade, V. (2023). ChatGPT Characteristics, Uses, and Alternatives | Spiceworks. [online] Spiceworks. Available at: https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-chatgpt/.

keyweo (n.d.). Semantic tag : definition, interests and structure. [online] Keyweo. Available at: https://www.keyweo.com/en/seo/glossary/semantic-tag/#:~:text=These%20semantic%20tags%20structure%20and [Accessed 23 Jun. 2024].

Lee, B. (2023). Is ChatGPT plagiarism free? [online] www.hotcoursesabroad.com. Available at: https://www.hotcoursesabroad.com/study-abroad-info/once-you-arrive/is-chatgpt-plagiarism-free/#:~:text=If%20you%20define%20plagiarism%20as.

Mind Tools Content Team (2022). Gibbs Reflective Cycle. [online] www.mindtools.com. Available at: https://www.mindtools.com/ano9qiu/gibbs-reflective-cycle.

Motiso, D. (n.d.). What’s a Project Manager in Software and What Do They Do? https://www.indeed.com/career-advice/finding-a-job/project-manager-in-software.

Networking. (n.d.). What is Transmission Control Protocol (TCP)? | Definition from TechTarget. [online] Available at: https://www.techtarget.com/searchnetworking/definition/TCP#:~:text=One%20of%20the%20main%20functions.

Noction (2018). TCP (Transmission Control Protocol) Congestion Control. [online] Noction. Available at: https://www.noction.com/blog/tcp-transmission-control-protocol-congestion-control#:~:text=The%20main%20TCP%20features%20are.

O’Flaherty, K. (n.d.). ChatGPT-4o Is Wildly Capable, But It Could Be A Privacy Nightmare. [online] Forbes. Available at: https://www.forbes.com/sites/kateoflahertyuk/2024/05/17/chatgpt-4o-is-wildly-capable-but-it-could-be-a-privacy-nightmare/.

Ovcharenko, S. (2022). 10 Key Roles in Software Development Team & Their Responsibilities. [online] Alcor BPO. Available at: https://alcor-bpo.com/10-key-roles-in-a-software-development-team-who-is-responsible-for-what/.

Perkins, M. (2023). Academic integrity considerations of AI Large Language Models in the post-pandemic era: ChatGPT and beyond. Journal of University Teaching and Learning Practice, 20(2).

Ryan, E. (2023a). Ethical Implications of ChatGPT. [online] Scribbr. Available at: https://www.scribbr.com/ai-tools/chatgpt-ethics/.

Ryan, E. (2023b). What Are the Legal Implications of ChatGPT? [online] Scribbr. Available at: https://www.scribbr.com/ai-tools/legal-implications-chatgpt/.

S. Gillis, A. (n.d.). What is hard skills? - Definition from WhatIs.com. [online] SearchCIO. Available at: https://www.techtarget.com/searchcio/definition/hard-skills#:~:text=Hard%20skills%20are%20specific%20abilities.

SEEK. (n.d.). How to become a Full Stack Developer - Salary, Qualifications, Skills & Reviews. [online] Available at: https://www.seek.com.au/career-advice/role/full-stack-developer.

Shah, N. (2023). HTTP and HTTPS Protocol Features 🚀. [online] Medium. Available at: https://medium.com/@shahneel2409/http-and-https-protocol-features-a59db8dc4dc8.

Testbook. (n.d.). Router: Understanding Uses, Features, Types, Benefits. Protocols. [online] Available at: https://testbook.com/articles/router#:~:text=Routers%20are%20vital%20networking%20devices.

Toppr-guides. (2021). What is an Interpreter? Types, Differences, Advantages & Disadvantages. [online] Available at: https://www.toppr.com/guides/computer-science/computer-fundamentals/system-software/interpreter/#:~:text=An%20interpreter%20is%20a%20program.

Varagouli, E. (2021). What Each Markup Language Is Used For. [online] Semrush Blog. Available at: https://www.semrush.com/blog/markup-language/.

www.javatpoint.com. (n.d.). HTTP vs HTTPS - javatpoint. [online] Available at: https://www.javatpoint.com/http-vs-https.

www.javatpoint.com. (n.d.). What is Routing? Definition and Types in Computer Network - javatpoint. [online] Available at: https://www.javatpoint.com/computer-network-routing#:~:text=The%20routing%20protocols%20use%20the [Accessed 23 Jun. 2024].

www.linkedin.com. (n.d.). How does a web server communicate with an application server? [online] Available at: https://www.linkedin.com/pulse/how-does-web-server-communicate-application-pixipace-cy5vc/ [Accessed 23 Jun. 2024].

www.linksys.com. (n.d.). Differences between IPv4 and IPv6. [online] Available at: https://www.linksys.com/support-article?articleNum=139604.

www.naukri.com (2024). Code 360 by Coding Ninjas. [online] Naukri.com. Available at: https://www.naukri.com/code360/library/characteristics-of-compiler.