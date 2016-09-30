Presentations
=============

Descriptions and links to various presentations from Kevin Hakanson.

## Biography

[Kevin Hakanson][17] ([@hakanson][1]) is a Sr. Software Architect for Thomson Reuters where he is focused on highly scalable web applications, especially the JavaScript and security aspects. His background includes both .NET and Java, but he is most nostalgic about Lotus Notes. He has been developing professionally since 1994 and holds a Master’s degree in Software Engineering. When not staring at a computer screen, he is probably staring at another screen, either watching TV or playing video games with his family.

---
### Introduction to Speech Interfaces for Web Applications

Speaking with your computing device is becoming commonplace.  Most of us have used Apple's Siri, Google Now, Microsoft's Cortana, or Amazon's Alexa - but how can you speak with your web application?  The Web Speech API can enable a voice interface by adding both Speech Synthesis (Text to Speech) and Speech Recognition (Speech to Text) functionality.

This session will introduce the core concepts of Speech Synthesis and Speech Recognition.  We will evaluate the current browser support and review alternative options.  See the JavaScript code and UX design considerations required to add a speech interface to your web application.  Come hear if it's as easy as it sounds?

* Twin Cities Code Camp 20 (16 April 2016)
* MinneBar 11 (23 April 2016)
* Midwest JS (10-12 August 2016) ( [presentation][37] )
* Thomson Reuters Beyond the Edge - Ann Arbor (12 September 2016)

### Learning to Mod Minecraft: A Father/Daughter Retrospective

What do Minecraft and Blockly have in common? Minecraft is a popular, open world video game where players can build structures using digital blocks. Blockly is a open source visual programming language where students can build programs using blocks. LearnToMod combined these together to teach students how to modify Minecraft using either the Blockly visual editor or JavaScript.

This session will be the retrospective of an enthusiastic father teaching his hesitant daughter (who loves Minecraft) about programming. We started with Hour of Code and pair-programmed through LearnToMod’s video lessons. What did we create? How did we like it? What would we recommend to others? Come learn about our experience and ask questions.

* That Conference (10-12 August 2015) (with Audra Hakanson) ( [presentation][35], [video][36] )

### ng-owasp: OWASP Top 10 for AngularJS Applications

The OWASP Top 10 provides a list of the 10 most critical web application security risks.  How do these relate to AngularJS applications? What security vulnerabilities should developers be aware of beyond XSS and CSRF?

This session will review the OWASP Top 10 with a front-end development focus on HTML and JavaScript.  It will look at patterns to implement and others to consider avoiding.  We will also explore several built-in features of AngularJS that help secure your application.

* Thomson Reuters Beyond the Edge - Ann Arbor (17 September 2014)
* AngularMN Monthly Meetup (4 March 2015) ( [presentation][30], [video][31] )
* Twin Cities Code Camp 18 (25 April 2015)
* NDC Oslo (17-19 June 2015) ( [presentation][32], [video][33] )
* That Conference (10-12 August 2015) ( [presentation][34] )
* DevFestMN 2016 (6 February 2016)

### Securing TodoMVC Using the Web Cryptography API

The open source TodoMVC project implements a Todo application using popular JavaScript MV* frameworks. Some of the implementations add support for compile to JavaScript languages, module loaders and real time backends. This presentation will demonstrate a TodoMVC implementation which adds support for the forthcoming W3C Web Cryptography API, as well as review some key cryptographic concepts and definitions.

Instead of storing the Todo list as plaintext in localStorage, this "secure" TodoMVC implementation encrypts Todos using a password derived key. The PBKDF2 algorithm is used for the deriveBits operation, with getRandomValues generating a cryptographically random salt. The importKey method sets up usage of AES-CBC for both encrypt and decrypt operations. The final solution helps address item "A6-Sensitive Data Exposure" from the OWASP Top 10.

With the Web Cryptography API being a recommendation in 2014, any Q&A time will likely include browser implementations and limitations, and whether JavaScript cryptography adds any value.

* JavaScriptMN Monthly Meetup (28 August 2014)
* Thomson Reuters Eagan Technology Unconference (5 September 2014)
* jQuery Conference (12-13 September 2014) ( [presentation][26], [code][27], [demo][28], [video][29] )
* Twin Cities Code Camp 17 (4 October 2014)

### Make your own *Print & Play* card game using SVG and JavaScript 

Want to leverage your creativity, love of board games, and web platform experience to do something different?  Turn your imagination into a Print & Play card game using only a modern web browser, color printer and text editor.

This session will use the Scalable Vector Graphics (SVG) image format and JavaScript programming language to make a deck of cards for a simple game.  Creating a few cards in graphics software like Inkscape is one thing, but what about 50 or 100 cards?  What happens when you need to update them all?  That’s the value of generating your SVG using JavaScript.

We will start with a blank screen, adding color and graphics elements like lines, shapes, text and images.  Learn about container elements and defining content for re-use.  Understand how units in the SVG coordinate system can transform our on-screen creation into an 8.5 by 11 inch printed page (or PDF). SVG examples will be both in their native XML format and created from JavaScript using Snap.svg, an open source library from Adobe designed for modern web browsers.

You will leave this session with a basic knowledge of SVG concepts, how to programmatically generate SVG using JavaScript, and how to make your SVG creation printer friendly.

* Twin Cities Code Camp 16 (5 April 2014) ( [code][21] )

### Scaling Agility from the Trenches

Let’s start a conference with a conversation. Instead of an opening talk, Twin Cities agile practitioners will share a fishbowl with coaches in a free-for-all discussion around the good the bad and the ugly of scaling agility instead of simply adding more process. Stop back for more details or stop in and enjoy the (fishbowl) madness.

* Agile Day Twin Cities 2013 (15 November 2013) ( panel participant; facilitated by David Hussman )
 
### Internationalize your JavaScript Application: Prepare for "the next billion" internet users.

Are you prepared for "the next billion" internet users, most of whom don't use English as their primary language?  This session will explore the globalization (internationalization and localization) of JavaScript based applications. It will look at the ECMAScript Internationalization API and popular open source projects like AngularJS, messageformat.js, jQuery Globalize and twitter-cldr-js.  Topics will include cultures/locales, character encoding, number formatting, date formatting, choice/plural formatting and translations.

* Thomson Reuters Eagan Technology Unconference (6 September 2013)  ( short [presentation][11] )
* Twin Cities Code Camp 15 (19 October 2013)  ( [presentation][14] )
* Iowa Code Camp 12 (2 November 2013)  ( [presentation][15], [video][16] )
* Google DevFest Twin Cities (8 February 2014) ( [presentation][19], [demo][20] )
* That Conference (11-13 August 2014) ( [presentation][23], [code][24], [demo][25] )
 
### A Humorous Comparison of Software Development with Star Wars: The Clone Wars
Lightning talk style presentation describing software development using references from Star Wars: The Clone Wars. ( [screencast][18] )

* Thomson Reuters Eagan Technology Unconference (6 September 2013)
* JavaScriptMN Monthly Meetup (26 September 2013)
* Iowa Code Camp 12 (2 November 2013)

### Developer's Guide to JavaScript and Web Cryptography

The increasing capabilities and performance of the web platform allow for more feature-rich user experiences. How can JavaScript based applications utilize information security and cryptography principles? This session will explore the current state of JavaScript and Web Cryptography. We will review some basic concepts and definitions, discuss the role of TLS/SSL, show some working examples that apply cryptography to real-world use cases and take a peek at the upcoming W3C WebCryptoAPI. Code samples will use CryptoJS in the browser and the Node.js Crypto module on the server.  An extended example will secure the popular TodoMVC project using PBKDF2 for key generation, HMAC for data integrity and AES for encryption.

* Twin Cities Code Camp 14 (27 April 2013) ( [presentation][7], [video][5], [demo][13] )
* JavaScriptMN Monthly Meetup (30 May 2013) ( [presentation][8] )
* Iowa Code Camp 11 (8 June 2013) ( [presentation][9] )
* Thomson Reuters Legal Market Dev Tech Forum Series (11 July 2013)
* Minnesota Developers Conference 2013 (26 September 2013) ( [presentation][10] )
* cf.Objective() 2014 (13-16 May 2014) ( [presentation][22] )

### HTTP Potpourri

Embracing HTTP is an important property of well constructed ReSTful and web apis. Every web developer is familiar with GET and POST, 200 and 404, Accept and Content-Type; but what about 207 and 413, OPTIONS and PROPFIND, Transfer-Encoding and X-File-Size? This session will be based on usage of various HTTP methods, headers and status codes drawn from the development of large scale, web applications. Examples will include raw HTTP, mixed in with JavaScript and ASP.NET MVC code.

* Twin Cities Code Camp 12 (14-15 April 2012) ( [presentation][6] )

### Implementing Messaging Patterns in JavaScript using the OpenAjax Hub

Is your web application a tightly coupled, DOM event handler mess?  Use techniques from the Enterprise Integration Patterns book to build better components.  Concepts including message, publish-subscribe channel, request-reply and message filter will be demonstrated in JavaScript (along with corresponding tests) using the OpenAjax Hub.

* Twin Cities Code Camp 11 (8-9 October 2011) ( [presentation][4], [code][12] )


---


#### BP101 Adding Lotus Sametime to Your Collaborative Commerce Web site

There are many statistics on the number of shopping carts being abandoned.  This session will show how to use Lotus Sametime to add real-time, online customer service to your Collaborative Commerce Web site.  A real-time intervention by a company representative can happen as a reaction to a customer request or a proactive response to a potential need.  These and other situations will be demonstrated.

* Lotusphere 2001 (14-18 January 2001)

#### BST108 eCommerce with Domino

In this session, you will learn the ins-and-outs of building an eCommerce site with Domino, and how you can build a site faster and easier with Domino than with other technologies.  We will explain how to set up customer registration, build a product catalog, and manage the shopping cart.  Tips on how to implement effective application security and get the best site performance will also be included.  Finally, this session will describe the different ways to integrate you eCommerce applications with existing ERP applications.

* Lotus Developers' Conference 1999 (20-23 June 1999)

[1]: https://twitter.com/hakanson
[2]: https://www.linkedin.com/in/kevinhakanson
[3]: http://stackoverflow.com/users/22514/kevin-hakanson
[4]: https://docs.google.com/presentation/d/1h95HJrrijsqNPvteAO4oo9NkcogfJWE4zS4MDUJJluo/pub?start=false&loop=false&delayms=3000
[5]: https://www.youtube.com/watch?v=iQ0PSR8xyGQ
[6]: https://docs.google.com/presentation/d/1hbUdAj1BrRVRgYK-_LR2cbG3M88HfFQwzhYFCxW-kqk/pub?start=false&loop=false&delayms=3000
[7]: https://docs.google.com/presentation/d/1Sx5ODjh_4lgfYgPNY3RqFzL4snvBbcGZ6byOn78K2ME/pub?start=false&loop=false&delayms=3000
[8]: https://docs.google.com/presentation/d/1ed8gcFiXtye9CTcbKkgoki8GM3Ix38Z00dcy_desKRE/pub?start=false&loop=false&delayms=3000
[9]: https://docs.google.com/presentation/d/1duucrW1Df5GgpzxUJp6RO-PminSYCDQKbSvHZYU4Uyw/pub?start=false&loop=false&delayms=3000
[10]: https://docs.google.com/presentation/d/1dpuhK96oyWndiiY9WLAFiEKFurIppv2mvS1WHVFbfqQ/pub?start=false&loop=false&delayms=3000
[11]: https://docs.google.com/presentation/d/18WgfvLWPFtaQaWcUS6LF4-NXFJX0dkEbFCqvG2k352I/pub?start=false&loop=false&delayms=3000
[12]: https://github.com/hakanson/tccc11
[13]: http://jswebcrypto.azurewebsites.net/demo.html#/
[14]: https://docs.google.com/presentation/d/1AbWHPOeNTL9w5nddBrRQ5f-3dJ1gp_JPtmHinLq9K80/pub?start=false&loop=false&delayms=3000
[15]: https://docs.google.com/presentation/d/1ZA8dp-SsXXqjKyFxsnVDrGcdoo0NaqE8dz-DCB8wA2M/pub?start=false&loop=false&delayms=3000
[16]: http://www.youtube.com/watch?v=h3p8cGOZ8CU
[17]: http://about.me/kevin.hakanson
[18]: http://youtu.be/nIS-XrNrv-0
[19]: https://docs.google.com/presentation/d/1MeQzuoyrPulLcyv_eOCoVrfHvs5tQATO0YLH2HyG-bg/pub?start=false&loop=false&delayms=3000
[20]: http://jsi18n.azurewebsites.net/demo.html
[21]: https://github.com/hakanson/tccc16
[22]: https://docs.google.com/presentation/d/1VC2yX5fEoXO2XTBpdGOMlZwFzuIu1A0PU2DpQ8fTxGs/pub?start=false&loop=false&delayms=3000
[23]: https://github.com/hakanson/jsi18n/blob/gh-pages/JavaScript%20Internationalization%20(That%20Conference).pdf
[24]: https://github.com/hakanson/jsi18n
[25]: http://hakanson.github.io/jsi18n/
[26]: https://docs.google.com/presentation/d/1lIMvkPXM2gsieAJ56aokX9QEKsEyTCHiHcJ8SjSU4DQ/pub?start=false&loop=false&delayms=3000
[27]: https://github.com/hakanson/todomvc-jquery-webcryptoapi
[28]: https://hakanson.github.io/todomvc-jquery-webcryptoapi/
[29]: http://youtu.be/kqwaZ-LzDag?list=PL-0yjdC10QYpmXI3l-PGK1od4kTWOjm_A
[30]: https://docs.google.com/presentation/d/1sXeJIMAUorz-EBEvxze2FTYWDqUTulaiR8XTo2C0_BA/pub?start=false&loop=false&delayms=3000
[31]: http://youtu.be/6uloYE87pkk
[32]: http://www.slideshare.net/kevinhakanson/ng-owasp-ndc
[33]: https://vimeo.com/131757758
[34]: https://docs.google.com/presentation/d/11dCU6lJ27R5RpuMDopMvkTzzcYmNAmv4CWzv4gYRxzs/pub?start=false&loop=false&delayms=3000
[35]: http://www.slideshare.net/kevinhakanson/learning-to-mod-minecraft-a-fatherdaughter-retrospective
[36]: https://youtu.be/InbVSEA8V0U
[37]: http://www.slideshare.net/kevinhakanson/introduction-to-speech-interfaces-for-web-applications
