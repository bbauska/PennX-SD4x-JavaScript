# Web Programming Basics
Programming for the Web with JavaScript (PennX SD4x)
 
JavaScript is the programming language of the World Wide Web.
As a professional web software developer, you will not only need to know how to program in this simple yet powerful language, but you will need to understand the fundamentals of how data is exchanged on the World Wide Web (WWW) and what tools and frameworks are available to you for creating robust, interactive web applications.
This course, part of the CS Essentials for Software Development Professional Certificate series, provides an introduction to modern web development using JavaScript. In addition to exploring the basics of web page creation using HTML and CSS, you will learn advanced web page layout and responsive design tools such as Bootstrap. You will also learn how browsers represent a web page data using the Document Object Model (DOM) and how to develop dynamic, interactive web pages using JavaScript in the browser. Beyond fundamental JavaScript syntax and advanced language features such as callbacks, events, and asynchronous programming, you will work with jQuery, which provides functionality for simplified DOM manipulation and event handling.
This course will also introduce you to modern web frameworks and component-based libraries such as React.js for efficiently developing modular web page components, and D3.js for creating data-driven documents. We will also teach you how to represent and exchange data using JavaScript Object Notation (JSON), and how to access RESTful APIs on the web.
Server-side JavaScript is becoming more prevalent in the industry, with web frameworks such as Node.js and Express making it simple to create and deploy complex, data-driven web applications. This course will prepare you to use such frameworks and show you how to integrate them with NoSQL databases such as MongoDB.
Computer Science Essentials for Software Development Professional Certificate program (4 courses)
In the professional certificate program, you will learn essential computer science concepts for software development ranging from the fundamentals of object-oriented programming to using efficient algorithms to design high-quality software.
This program begins with the basic concepts of Java, one of the industry’s most commonly used programming languages, and progresses into best practices in modern software development to developing efficient algorithms using sophisticated data structures for complex computational tasks.
Finally, you will develop interactive and data-driven web apps using JavaScript.
Web Programming Basics
a)	Basics of the World Wide Web
b)	Developing Web Pages with HTML
I.	Using JavaScript to Create Dynamic, Data-Driven Web Pages
a)	JavaScript Basics
b)	Using JavaScript in Web Pages
II.	Client-Side Frameworks for Developing Modular Web Page Components
a)	Developing Web Applications with React
b)	Advanced Component Design for React
c)	Creating Data-Driven Web Content with D3.js
III.	Building Scalable Web Apps with Server-Side JavaScript
a)	Developing Web Applications with Node.js
b)	Databases and Web Applications

Syllubus
Course Overview
JavaScript is the programming language of the World Wide Web.
As a professional web software developer, you will not only need to know how to program in this simple yet powerful language, but you will need to understand the fundamentals of how data is exchanged on the World Wide Web (WWW) and what tools and frameworks are available to you for creating robust, interactive web applications.
This course, part of the CS Essentials for Software Development Professional Certificate series, provides an introduction to modern web development using JavaScript. In addition to exploring the basics of web page creation using HTML and CSS, you will learn advanced web page layout and responsive design tools such as Bootstrap. You will also learn how browsers represent a web page data using the Document Object Model (DOM) and how to develop dynamic, interactive web pages using JavaScript in the browser. Beyond fundamental JavaScript syntax and advanced language features such as callbacks, events, and asynchronous programming, you will work with jQuery, which provides functionality for simplified DOM manipulation and event handling.
This course will also introduce you to modern web frameworks and component-based libraries such as React for efficiently developing modular web page components, and D3.js for creating data-driven documents. We will also teach you how to represent and exchange data using JavaScript Object Notation (JSON), and how to access RESTful APIs on the web.
Server-side JavaScript is becoming more prevalent in the industry, with web frameworks such as Node.js and Express making it simple to create and deploy complex, data-driven web applications. This course will prepare you to use such frameworks and show you how to integrate them with NoSQL databases such as MongoDB.
Prerequisites
•	Basic knowledge of computer programming (variables, functions, control flow)
•	Knowledge of core data structures (arrays, lists, sets, trees)
Course Outline
•	Week 1 - Web Programming Basics: how web browsers and servers communicate using HTTP; creating static web content with HTML and CSS
•	Week 2 - Using JavaScript to Create Dynamic Web Pages: basics of the JavaScript programming language; accessing HTML elements from embedded JavaScript using the DOM and jQuery
•	Week 3 - Client-Side Frameworks for Developing Modular Web Page Components: component-based web app development using React; creating data-driven documents with D3.js
•	Week 4 - Building Scalable Web Apps with Server-Side JavaScript: generating dynamic content on the server using Node.js and Express; storing and retrieving data in MongoDB; developing an API for the web

I.	Web Programming Basics
This week we'll start with the basics of web programming by looking at how the worldwide web works.
We'll see how a browser communicates with a server using HTTP.
And we'll explore the fundamentals of webpage creation using HTML and CSS.
a)	Basics of the World Wide Web
You're watching this video, probably using some sort of web browser. 
In the browser, there's the video itself.
Maybe up at the top there's some images, off to the side is some text.
Maybe somewhere on the page you can click a link, click a button, and something else on the page will change, or you'll go to a different page.
How does all that work?
How does the content get from somewhere else to your computer?
What software is running?
And how can you as a software developer create that?
Those are things we're going to look at in this course.
It's the 21st century, you're watching this video.
You probably have some idea of what the Internet is.
 
But the internet is of course this global network of machines, some of them known as servers which have data or content that they make available to other machines.
Clients, which is where humans are using the machine to get data or maybe send data.
And then along the way there are devices, switches, routers, etc., which facilitate the transportation of data.
 
We can think of the Internet as a graph in the computer science sense of a graph.
There are nodes, which are the computers or devices that are in the graph.
And then the edges are the connections between them.
 
Here's a visualization of the Internet, or part of the Internet.
It looks like a graph it has a lot of nodes a lot of edges.
Down here in the bottom is sort of blown up.
You can see different computers that are on the Internet, that are connected to something in the middle here which is connected to other things.
And the point of the Internet is that it's a completely or fully connected graph.
Every node is connected through some number of edges to every other node.
 
Are the Internet and the World Wide Web the same thing?
We often use them interchangeably, and I will probably accidentally do it in this course.
But they're not actually the same thing.
The Internet is the network, is the hardware.
The World Wide Web we can think of as the software.
 
The World Wide Web is an application that is running on the network, on top of the Internet.
The Internet is providing the infrastructure that the World Wide Web is using that infrastructure to transfer transmit data.
So, what is the World Wide Web?
The World Wide Web is an application that runs on top of the Internet.
It combines various protocols to allow for communication and transfer of data between machines.
The web is composed of documents that are linked to each other.
Now, originally, the World Wide Web was designed to allow for this access to all these documents and to link them together.
And that we could get from one document to another using something known as the web browser.
 
I mentioned before that the Internet is a graph where the nodes are the devices and the edges are the physical connections between them.
The World Wide Web is also a graph that we can say is perhaps overlaid on top of the Internet.
Where now the nodes are the documents or the content or the resources.
And the edges are these virtual links between them where I can get from one to another, for instance, in this diagram at the bottom of this slide.
If I'm looking at this page on the Internet of this content or document on the Internet, I can follow these links to other pages or documents or contents and from here I can go up to here and here and so on, and now there's also a graph.
 
How do we identify or address content on the World Wide Web?
Generally speaking, every piece of content has what's known as a URI, or uniform resource identifier, that's just a unique address on the World Wide Web.
The URL, or uniform resource locator, is a type of URI, it's a type of address that specifies not only the location on the World Wide Web, but the protocol or the mechanism for accessing it.
 
Here's an example of a URL that we're, of course, very familiar with.
The first part of the URL is the protocol.
The protocol just explains the structure of communication between devices,
and we're going to look at this particular protocol http in a little more detail later in this lesson.
The next part is the host name.
The host name is the name of some computer that's on the World Wide Web.
Part of that is the domain name.
The domain name is a group of computers or a group of addresses that belong usually to some specific organization.
On that computer, on that host, somewhere on the World Wide Web, is the content, and that content is usually accessed via some file path.
And following that might be some parameters or some queries, some data that we want to send to the host that has that content before we get back that content.
 
We can consider contents on the World Wide Web to fall into two categories.
One is the static content.
Static just means it does not change, that no matter who looks at it, no matter when they look at it, it always looks the same.
The technologies used to create static content are HTML and CSS, which we're going to see in the first part of this course.
Now the other type of content that we see on the World Wide Web is known as dynamic content.
Dynamic content is the content that changes as you're looking at it.
It could be generated based on who you are, it could be generated based on something that's happened, something that you've done within the application.
And the technology that's used for dynamic content is JavaScript which we'll see in weeks two, three, and four of this course.
 
Looking ahead at the next couple of lessons, we'll start to look at how does a browser request a web page or some resource on the World Wide Web?
What does it look like when it sends a request and what does it look like when the content comes back?
Once it's received, how does a web browser display it?
And then later in the course, how do you write your own programs to generate dynamic content in the browser?
•	Developing Web Pages with HTML
•	How a Web Browser Works
In the previous lesson, we introduced some basic concepts, the internet and the World Wide Web, and I mentioned the Uniform Resource Locator, or URL.  Which is the Unique address for some piece of content, some data, some resource on the World Wide Web.
I also mentioned that there is something known as the protocol, which is the structure of the content or communication between devices, and we'll start to look into that a little bit more in this lesson.
In the previous lesson, I showed a diagram of the internet, this completely connected graph of devices.
 
Here's a diagram of the World Wide Web.
Now remember, the World Wide Web is this application, the software running on the hardware that is the Internet, but it is also a graph.
The different pieces of content have links to each other that we can think of as edges in a graph.
In this particular diagram, Wikipedia is here at the center of the graph of the picture, and we can see there are links to to other pages and those have links to other pages or other websites as well.
How do we view content on the World Wide Web?
Well, in the old days, there were web browsers that were just text.
 
Here is an image of one now this image is a little more recent, but in the old days, let's say that 1980s, 1990s, we browsed the web using text browsers.
We could see the content, we could request content, we could link from one to the other.  It was just text.
Then somewhere in the early mid 1990s came one of the most popular graphical web browsers known as NCSA Mosaic.
 
Mosaic allowed you to not only go from one piece of web content, one page to another and see the content, but you could also for instance see images so that we could look at pictures of sleeping dogs.
 
Nowadays there are five popular web browsers; Chrome, Safari, Opera, Internet Explorer and Firefox.  What do I mean by web browser?  What exactly is that? 
 
Web browser is a piece of software that is used to access and display content that it finds on the world wide web, and let you navigate from one location, one document to another.
The browser contains three main components, and these are the three, I suppose, cornerstones of web content, and the three things we're going to look at in this course.
The first main component of the web browser is known as the 
1)	Rendering Engine.  The rendering engine is what decides what to display and how to display it within the web browser.  Thus, things like the presentation, the ordering of things, the content itself, and that uses technologies HTML and CSS, which we're going to see later in this week of the course. 
The next part of the browser is known as the 
2)	JavaScript Engine.  That’s the dynamic part.  That's the part that is running code in your browser on your computer, or on your device.  That's creating dynamic content, modifying content and that uses JavaScript, which we'll see in the second part of this course.
How does a web browser work?
 
The most important thing to understand for us as the web programmers or web developers is the protocol HTTP or Hypertext Transfer Protocol.
HTTP is how the web browser communicates with other devices, other computers, on the World Wide Web To request and transfer documents.
HTTP is a client server protocol.
There's some computer, which is known as the client.
Here, we have a little diagram of a laptop. It could be your mobile device. It could be your refrigerator. But, something that's on the world wide web. 
And, there's some server.  The server is generally some big computer that's Somewhere else, on the Internet, and they're connected of course by the Internet through various connections and devices along the way.
 
In HTTP the client initiates the conversation or the transfer of the data by sending what's known as an HTTP request, the server is out there listening for incoming request and the client sends the request saying Server, can you please give me some data?
The server then decides what to do with that request and sends back what's known as the HTTP response.
The HTTP response includes the content that the client requested, and then the client figures out what to do with that content.
HTTP is a plain-text, human-readable protocol that's used for exchanging data on the web.
 
What that means is that if you could open up your web browser and look at the data that's going back and forth, it's just text.
You would be able to read it.
HTTP is based on the client-server model.
The client sends a request, which is not only the content that its asking for, but also information about the client.
The server sends back the requested resource or content or page or data, but also information about the server itself.
If we could look at all of that content that's going back and forth between the server, and the client, the request, and the response we'd see something that looks like this.
 
Here at the top is the request.  The request is the client or the browser asking the server, can you please give me this information or this resource or this data.
All of this down here is the response.
Here is the headers of the response. This is information that the server is sending back about the server itself or about the data about the content And then down here is the content itself, the resource that was requested.
 
Let's look at more detail about an HTTP request.
 
The first line of the request is always a verb.  The verb tells the server what is the action that the client is hoping to perform.
It could be GET, which is saying please give me this resource.  I want to get this resource.
The verb can be head which is I just want the header information not any particular resource or post.  Which is to create a resource or create new content on the server.
Following the verb is the argument and the argument for instance in a get request which we'll see in just a second Is what is the name of the resource or content that's being requested.
On that first line on the HTTP request after the verb and the argument is always the protocol and these days generally the protocol is HTTP/1.1.
The client may send other information about itself, other information about the request book, that's the most important part.
Is the verb, the argument and the protocol.
 
Let's look at an example of an HTTP request in more detail.
The first line is always the request line. That includes the three important parts that I just mentioned.
The first thing in that line is the verb.
In this case, it's GET asking the server, please give me this resource.  I would like to get this resource.
The second thing is the argument or the identifier.
Here is some type of URI, some type of identifier that's the name of the resource or the page on the server.
And then last on this first line is the HTTP version.
Following that is some request headers.
It could be things like where is this client?
What is the type of web browser it's using, etc?
There's always a blank line after the headers, and then any other data that the client wants to send to the server as part of the request.
So, the server has received that HTTP request.  It knows the protocol.
It knows that they are talking HTTP one dot one, in this case, so it knows what is being requested.
And now it can handle that request and send back some sort of HTTP response.
 
The first line of an HTTP response always includes the protocol and the status code.
And there are different categories of status codes which could be just some information.
They're successfully giving you back the content, or successfully servicing the request.
It could redirect There can be types of errors  
 
The three most common error codes are 200 ok which indicates that the request was successful and I'm about to give you back the content that you've requested.
The one you're probably, everybody's familiar with is 404 which means not found.  That means that the server could not find the content that was requested.
And then one that we hope to never run into was 500, which is a server error. Which means there's some problem in the server, in the software, that's trying to handle that request.
 
Following that first line, which is the status code and the protocol, comes the header information, which is information about the server or about the response.
Then the blank line and then the body of the response which in the case of a gap request, would be the content of the resource of the page that was requested.
  
Here's an HTTP response example.  The first line is always the protocol, and then the status here is 200, okay.  Meaning that this request was successfully serviced.
Then we get the response headers which is just information about the server or about the content that's being sent back.
It has the date, it has the type of the server, it tells what is the content type, how many bytes are in the content, how many bytes are in the response.
There's always a blank line.
And then the body of the response, the requested resource, follows.
 
To summarize, we've looked at a web browser and
how a web browser works using a HTTP.
A HTTP is this plaint text human readable client server protocol
in which a client can request some resource.
And the server can send back a response with that resource.

Introduction to HTML
Last time we looked at how a web browser works.
 
How a web browser uses the HTTP protocol for
a client to send an HTTP request for some content or data on the World Wide Web.
And how the server uses HTTP to send back the response.
Now, often that response which includes the content or
data that's requested uses HTML.
 
So HTML or Hypertext Markup Language is a way of structuring content or
structuring data on the World Wide Web.
An HTML document consists of elements.
An element consists of tags generally followed by then some content and
what's known as the closing tag or end tag.
Here's an example of some HTML content.
It starts with a start tag, it's the content itself and
then there's some end tag.
 
So in this lesson, we'll start to look at HTML and we'll look at
the different types of tags and how they relate to what you see in the web browser.
 
In the same way that HTTP is a plain text human readable protocol,
HTML is a plain text human readable language.
That means that you as a human can read HTML and see the content and
see the data and the structure of that content.
Now it's important to note that strictly speaking, HTML is a way of
structuring the data but does not decide or determine how to display it.
So HTML says here is the content, here is how
pieces of content relate to each other, but it doesn't say how to display it.
It's up to the web browser to choose how to display that content.
 
Here's an example of the hierarchical structure of HTML.
We'll see what these tags actually mean in a little bit later in this lesson, but
the point here is that the elements can be nested, that is that one
element can consist of other elements which consist of other elements and so on.
For example, here this first element is just kind of floating there,
this document type.
But the next element, the HTML element,
you can see has a start tag at the top here, and
an end tag at the bottom here, and in between, is the content.
Now in that content, the HTML content, we see the head and the body elements.
The head, up here, is going to be the header or information about the content.
And then here, the body is the content itself.
So, we can see that HTML consists of a head and a body.
And then we can dig down deeper and see this nesting or
this hierarchical structure even more.
For instance, the head contains a title, which is the title of the page, and so on.
So let's look at some of these important HTML tags, and understand what they do.
And then we'll see as we go along how you'll use them to create webpages.
 
So the first one is the doctype.
It's not actually a tag, but
rather tells the browser what type of version of HTML the content is.
Nowadays, HTML5 is the most popular type, and so
we would use this tag here <!DOCTYPE html>.
This declaration must be the first line of any HTML document,
because it tells the browser what type of version or standard of HTML it's using.
 
After the doc type comes the HTML element.
We can think of the HTML element as the root of our tree, if you will,
of the structured content, the hierarchical content.
In this case, we have DOCTYPE and then what follows it has to be html.
Everything else goes here, and then not html or
the html closing tag, the end of the html.
 
As we saw a little while ago,
HTML element consists of the head element and the body element.
The head element is not actually the content of the document, but
rather information about that document.
For instance, it might include the title of the page.
The title is what appears in the title bar at the top of your web browser.
There might be a link to other files that are going to be used within this page.
For instance CSS, which is a way of formatting the content,
which we'll see later in this part of the course.
Meta tags are used to provide additional information about the content or
about the web page.
For instance, keywords that can be used by a search engine.
And then lastly, if we want to have any dynamic content or
dynamic behavior in our HTML page we would use JavaScript and the script
tag allows us to link to JavaScript code that we'll see later in the course.
 
I said that the HTML element consists of the head element and the body element.
The body element includes all of the content to be displayed
within the web browser.
That might be images, it might be text, it might be links, etc.
So how are HTML and HTTP related?
In the previous lesson, we talked about HTTP as this protocol for
requesting content and sending back a response with that content.
So where does HTML fit in?
So when a browser makes a request for some document or some content or
some resource on the World Wide Web it sends as part of the HTTP request
the name of a file or some resource.
In this case /hello.html.
When the server handles that request and sends back a response the contents of that
file, the contents of that HTML file, are the response or
are part of the response, are the content, the body of the response.
 
Then when your browser gets back that plain text HTML, the structure of the content, the browser decides how to display it.
And here I'm using Google Chrome to display that very simple HTML page that just says Hello, World.
So, for the rest of this course if you want to follow along with what I'm doing and try these things on your own, I recommend that you use some sort of plain text editor.
 
So, we don't want to use any document editor that's going to introduce formatting, but something that just allows you to write plain text.
Once you have that ready, you can create a new file.
You can put your HTML in that file.
For instance, the HTML that we saw in this lesson.
Save the document, we'll call it hello.html.
 
And then open that file using your web browser.
Now I'm going to use Google Chrome in the rest of the course.
You can use Google Chrome or you can use any browser and
it will still show you, render the HTML.
Now one nice thing about all modern web browsers is that when you get the HTML
content and it's displayed in the browser you can actually see the HTML
in order to figure out how do things work.
 
So, in this case, I have my Hello, World page that I'm looking at with Chrome.
If I right-click or use the context menu, I can select View Page Source.
And then that will open up the source of the HTML.
So the browser is displaying that content, figuring out how to display it.
But it's also allowing me to see the code, if you will, the HTML, that's used to render that content.
So this is just a taste of getting started with developing web pages and
web applications, understanding HTML.
 
In the next lesson, we'll start to see more about HTML,
the different types of tags.
 
And then we'll later in this part of the course look at how we can affect
the appearance of the content in our HTML pages.

Basic HTML
 
In the previous lesson, we started to look at HTML, hyper text markup language.
This is the way that we structure the content that we're going to display on
the world wide web in a web browser.
And we saw four important HTML tags in the elements of an HTML page.
The first one specifies the version of HTML.
Then we have the root element of the entire document.
And then one for the header of the document.
And one for the body of the content in the document.
And using those four tags,
we were able to create a simple little HTML page that looks like this.
 
Now obviously we wanna get to a point where we're seeing very interactive HTML
pages with a lot of graphics, and content, and images, and so on.
But in this lesson, let's walk before we run, I suppose, and just get to changing
the appearance of some of the content and having more structure to our content.
 
So we'll start with one of the important HTML tags, which is the p tag standing for
paragraph.
We can use the p tag or
paragraph tag anywhere in the body of the HTML to delineate or
separate different paragraphs or ideas or different parts of the content.
So here's an HTML page or part of an HTML page.
 
We still have our DOCTYPE element at the top, we have the head, the body.
But within the body, we can have paragraph tags, start and end tag, for our paragraph
elements, and we can have many paragraph elements, of course, within the body.
 
Now it's important to remember, and I've mentioned before, the HTML specifies
the structure of the content, but not necessarily the way it will be displayed.
HTML was plain text but don't think that what you see in your text editor
will necessarily translate exactly the same way when rendered in HTML.
And here is an example of that.
 
In this case I have the words, this is some text.
I have a new line and a blank line here.
Then it says this is some more text, a new line and so on.
And we might think because we're used to using
document editors that are what you see is what you get.
That if we were to look at this in the web browser, it would look exactly like this.
But actually in the web browser, the web browser ignores the white space.
 
It ignores the break.
It ignores that blank line.
And this would all appear as one line of text.
So it's important to remember that HTML is being used for structuring the content,
but not necessarily deciding how it will be rendered or displayed.
 
In addition to the p tag, sometimes we wanna indicate that the HTML is not
just the content, but rather some sort of section header.
And in that case we use the h tag with a number from one through six
indicating what level or importance is that heading.
So h1, is the most important, that would be for
instance the title of the entire document.
And then there is h2, h3 down to h6 which is a very low level subheader.
Now the browser determines how to render h1 and h2 and so on, but
we would use this to tell the browser this is a section header and not just content.
Here in this example,
 
I am using h1 tag here to indicate that this is the most important header.
And then I would see down here, my browser,
which is Google Chrome, would render this in this particularly large bold font.
I can have a smaller subheader using the h3 tag, and Google Chrome
will use in a slightly larger than normal text but also bold font.
Now I've been saying that HTML is used for structuring the content and
to not necessarily affecting it's display, but sometimes we wanna tell the browser,
hey this is important text or important content and
we would like you to render it in a way that's different from regular text.
 
And two ways of doing that are using the b tag for bold and the i tag for italics.
We could also use the strong tag which is similar to the b tag,
it will render in bold.
But it just is to tell the browser that this is important semantically,
more important in terms of meaning and not simply show this in bold.
Likewise there's the tag for emphasis, I suppose,
which also will tell the browser to enter it in italics but to emphasize this text.
 
Previously, I showed the example where we have line breaks and empty lines in our
HTML content, but the browser ignored that and rendered it all as one line.
But if we want to tell the browser please put a new line here or
even put a horizontal line here, we can use the hr and br tags.
The hr tag is to indicate that there's some serious shift in the content, we're
separating different parts of the content, and that will render a horizontal line.
The br tag would be a line break, where we want to make sure that there's
just some white space between the different parts of the content.
 
So for example, here we see some HTML.
Here's how it's rendered.
The hr tag for horizontal rule I suppose, is this horizontal line.
The br is just this extra blank space and extra line break.
 
Two more tags to talk about that are somewhat related, but are going to be
used later in the course when we're affecting the appearance of the content.
One is the div tag.
The div tag gives us some more structure within the body that says
that this part of the content goes together.
It's a way of organizing the content.
And as we'll see later, it's a way of applying visual elements in styling and
formatting, are two parts of the contents.
 
Related to the div tag, is the span tag.
The span tag says, here's some text, some content that we were
going to eventually apply some formatting or styling to.
It's usually a smaller part of content than the div tag,
which can be a much bigger part of the content.
 
Last within our HTML, we can also have comments.
Comments are things that are not rendered in the browser, but
are perhaps notes to ourselves or to other people who are viewing our HTML.
Or we can temporarily remove parts of the HTML.
In this part, we're listing people's names.
But this particular name here is commented out.
It would not appear when it's rendered in the HTML browser.
 
Now you may note that all of these HTML tags start with the < symbol,
end with the > symbol.
We noted that also that's when we had the line break or
the entire blank line that the browser ignored it.
So how can we address these perhaps special characters?
In HTML, we can insert special characters using
the ampersand then the particular name and semicolon notation.
For example, as we see here in this slide,   for non breaking space,
followed by semicolon, puts in extra white space.
Ordinarily, the browser will take any amount of white space and
condense it down to a single white space.
Single space between, for instance, words.
But if we want more space or
more space between paragraphs, we can use the nbsp tag.
If we want to have a less than or greater than we can use < for
less than character, > for greater than character.
Now you might say, well wait, we started this by saying that less than
was the special thing and so now we have a way of showing less than.
But what about & because now & is something that's being used in
a special way.
So if we want to use &, it's “&” then “amp;” for the non-breaking space.
 
And there are lots of other HTML entities, special characters, copyright,
registration, the Euro character, the pound sterling character.
We can insert any of these using the different HTML special entities.
 
Last, here's a big HTML page with all the things we've seen
in this particular lesson.
We start with the DOCTYPE element which says what version of HTML we're using.
We have the HTML element which is the root of our structure.
Within the HTML element, there's the head, which includes the title,
and in this case a meta information.
The HTML element in addition to containing the head element
contains the body element.
The body element in this case has some headers, h1 and h3 headers.
We see the paragraph tag with the p tag used to indicate
here are some content that's separate from the rest of the content.
Here is a horizontal rule that we'll give us this horizontal line in the content.
We have the <div> tag which is going to say,
here is some chuck of content to which we may apply styling and formatting later.
And we have the span tag which is similar to the div tag but
is used for a smaller piece of content.
 
When I look at this in Google Chrome, this is what I see.
So far in the course the past couple of lessons we've seen HTML.
HTML is a plain text human readable language for indicating
the structure of the content that we're seeing on the worldwide web, and
we started to look at the different tags that we can use to organize that content.
Coming up we'll see more tags, but also start to look at how can we affect
the appearance of the content in our web browsers?
 

HTML Formatting and Attributes
In the past two lessons we've been looking at HTML, a way of structuring or
organizing the content of our Web pages.
We saw the HTML pages or HTML documents consist of elements and
those elements are delineated or indicated using tags.
 
Here are the important HTML tags that we saw in the previous lesson.
 
Using those HTML tags we were able to create a web page that looks like this when viewed in Google Chrome.
Now for the most part it's Google Chrome or any web browser that's deciding on the appearance of the content.
We're giving some indication to the browser that this should bold, this should be italics, but for the most part, the browser decides how things should appear.
In this lesson we'll start to talk about how we as the programmer, we as the developer of the html page, can tell the browser this is how we want this content to appear.
 
We're going to do that using what's known as HTML Attributes.
Every HTML element or tag, can have additional information provided as attributes which come in name/value pairs.
The name specifies some sort of property of the element, and then the value is the value of that property.
 
In this example at the bottom of this slide, we have the p tag, or paragraph tag
and we can specify some named attributes and then it's equal to some value.
 
The first attribute we'll look at is known as the title attribute.
The title is not the title of the page which you've seen previously, but
rather the title of that element.
And we would be able to see that title when we hover of mouse over that element
and we would see the tooltip gives the name.
For instance, in this case if I have an h1, a level one header and
I give it the title Welcome, when I mouse over or
hover over that I would see the tooltip that says welcome.
 
Before affecting the appearance we're going to use the style attribute.
 
The style attribute lets us as the creator of the HTML page, tell the browser
this is how I want you to render or this is how I want that HTML content to appear.
And there are different key value pairs that we can use within the style attribute
that specify the visual appearance of the content.
As a very simple example,
 
I have an h1 piece of content which would in Google Chrome be rendered like this.
It's a little bit bigger than normal text and it's bold.
But I can use the style attribute within the h1 tag to tell it
I want the content to appear as red and
I also want it to be transformed.so the first letter of every word is capitalized.
So you see here, I have the style attribute within the h1 tag, and I
have this key value pair color:red, which tells it ,I want the texts to appear red.
There's a semicolon because I'm about to give it another key value
pair which is text transform capitalize,
which tells the browser transform this text, which is here.
And rather than rendering it as it is, in normal h1,
capitalize the first letter of each word.
And what we would see in Google Chrome is content that looks like this.
 
It's still the same font size as h1 usually would be but now it's red and
now the first letter of every word is capitalized.


Some of the other properties of the style attribute that we can use,
include the background color.
Ordinarily, a browser will choose some background color, usually white or
maybe a gray or something like that.
But we can say we want the color to be yellow, or red,
or whatever behind this particular text.
We can specify the font that's used.
The browser will generally choose some sorta font, but for instance we may
want a sans serif font, like verdana, we may want a fixed width font,
like courier, and we tell the browser this is the font to use to show this text.
We can choose the font size.
The font size can be specified in the number of pixels high.
It can be using some other measurement metric like inches.
Or we can say what percentage should it be compared to what it ordinarily would be.
If it's ordinarily 12 point font and
we say 200% then, of course, it would be rendered in 24 point font.
And then if we want to shift the text, align the text,
we can use the text align property of the style attribute to say whether it should
be centered, left justified right justified etc.
 
So here's an example where I'm using the span tag.
In the span tag, I've mentioned previously that we have a little bit
of text in this case the word world, to which we want to apply some formatting.
In this case, we're going to apply the style attribute.
We're going to say that the color of this text should be white,
the background's color should be green.
We're going to use the Verdana font which is Sans-Serif font, and
we're gonna make it twice as big as usual, font size of 200%.
 
And in Google Chrome this is how that would be rendered.
Let's see another similar example then start to talk about
some of the things we would wanna do as HTML developers or web developers,
web programmers, to simplify this a little bit.
In this particular case I have a paragraph with a Content.
1 is an odd number and then I have another paragraph with 2 as an even number.
And you can see that I'm using the style attribute of that first paragraph
to specify the color as blue, that's the color of the text.
In the second paragraph, I'm using the style attribute
to specify the color is white and the background-color is now blue.
 
In Google Chrome it would look like this with 1 is an odd number being blue and
white background and 2 is an even number being white on a blue background.
Now what if I wanted to add more paragraphs and alternate between
blue on a white background for odd, and white on a blue background for even.
Well, I can copy and paste and then I can change 2 to 4 and 1 to 3 and
what I see is something like this.
Now I'm using color blue for the odd number and
color white, background color blue for the even number.
And now I can do this for 5, and 6, and so on and so forth.
And sure, this all works totally fine.
But what happens if I now want to change the color of the odd numbers to green?
Well, I would have to go in each of these places where I've specified blue,
I would have to change that to green each place.
Likewise if I wanted to change the background color for
the even numbers, for instance from blue to green, I would have to go and
change that on every single place.
And that's sort of seems repetitive and
maybe there is a more graceful way where I would only have to change it in one place
and not have to change it every single place.
 
And so in that case, we're going to use two other important attributes
of an HTML tag or element, which are id and class.
The id attribute lets us give a unique identifier to that HTML element,
the HTML tag withing the HTML page.
That we can then use to apply, for instance, formatting and appearance.
Class is a collection of elements that can belong to a class that lets us say, apply
this formatting or apply this appearance to all elements that are in this class.
So, the difference between id and
class is that id is unique to a specific element In the HTML page.
However, a class can include many elements,
and element can say I'm in this particular class.
So how would we do this for our even odd blue white example?
Well, rather than having every other paragraph the odd paragraphs
specifying the color blue.
I will put them into a class called odd,,
that is the attribute is called class and its value will be odd, which I've made up.
Likewise, I will take my even paragraphs and rather than having
this long style attribute specification, I will put them into the even class.
Now at this point if I put the odd ones into the odd class and
the even ones into the even class, and then I try to render the page,
the page would say I'm sorry I don't know what odd and even are.
So I need to tell it what odd and even are.  Class = .odd & class = .even within style of head.
 
Which I'm going to do in the header of my HTML,
the head section of the HTML using the style tag.
So at the bottom I have the body and as you can see in the body I have
the odd paragraphs are in the odd class, the even paragraphs are in the even class.
Within the head of the HTML page I'm using the style tag.
The style tag says that what's between the tags,
what's in this element is not html content to be rendered but
rather styling or formatting information about that html content.
The first thing we see is this specification
of the odd class should be color: blue.
How do I have know, or how did I specify that it's the odd class?
Well obviously it's the name odd here, but
also the period before odd indicates that this is a class name.
And we'll see examples later where it's either an element name or an ID name.
In this case, .odd or period odd says that
I'm specifying the appearance of every element that is in the odd class.
Which are these odd paragraphs down here.
Likewise, I have .even that says that this is specifying the appearance
of elements that are in the even class, which are these ones down here, of course.
And I'm saying that in the even class, this style of any element
that's in the even class, is to have the color white and the background color blue.
Now when the web browser renders this HTML, it'll apply the odd formatting
to elements in the odd class and the even formatting to elements in the even class.
Why did we do this?
Well, it saved a little bit of HTML.
But remember, the motivation was what if I want to change
the color of the odd text from blue to green.
Previously, before we saw the style tag, we'd have to do that in three places.
Now I only have to do it in one place.
I only have to change it here.
Where if I anything in the odd class to be green instead of blue,
I just change it in one place.
Likewise, if I want anything in the even class to have a green background instead
of a blue background, I don't have to go find every even paragraph,
I just have to change it in one place.
And that change that will applied then to anything in that class.
 
To summarize, we've been looking at HTML and using it to organize the structure of
the content, but now we're starting to see how we can affect the appearance.
Appearance of the content.
We can use the style attribute to specify for instance the color,
the background color, the size, the type of fonts of any text within element.
And we can use the class to apply styling to many elements in our html page.
 

Introduction to CSS
In the previous lesson, we saw how we can affect the appearance of the HTML elements using attributes.
One of the attributes is style.
 
Style let's us specifically say, we wanna use this particular font size,
color, background color, etc.
We can also use the class attribute.
The class attribute lets us put elements into a class, and
then apply a styling to all the elements in that class.
 
Here's another example of plain HTML.
It's some memorable quotes from movies.
Most of the appearance is just the default appearance,
as decided by the Google Chrome browser.
Maybe there are some things that are specifically,
we decided on the appearance, for instance, we say, this is the header, and
so we know it will be bold and a little bit bigger.
Here is a link to another page,
its blue and underscored or underlined, we'll see links later.
Previously we saw how to make text italics or text italicized.
Other than that, everything is just the default appearance.
 
Here's what we could refer to as stylish, or stylized HTML.
Here we are able to specify different font sizes, things are bold,
things are indented differently.
And we're gonna see how we can accomplish something like this,
using what's known as CSS.
 
CSS is Cascading Style Sheets.
It's a formal language for specifying the appearance of HTML elements.
And CSS has a standard specification,
defined by the World Wide Web Consortium, or W3C.
 
Why do we have CSS, well keep in mind, the HTML in theory,
specifies the structure of the content, what information there is, how
different things relate to each other, but not so much the appearance of the content.
CSS is another language,
so it allows us to specify the appearance of the elements in the HTML page.
So how does CSS work?
 
In a previous lesson, we looked at HTTP, and we said that in HTTP,
what comes back as an HTTP response is HTML.
When the web browser gets the HTML,
it starts to try to render all of the elements, but it also looks for the CSS.
Now the CSS, Casgating Style Sheets, can be in the HTML page, or
they can be in a separate page in a separate file.
If it is in a separate file, the web browser will make another HTTP request to
get that separate file, that CSS file, and then we'll get that in the HTTP response.
When the browser has downloaded or received all of the HTML and
CSS that it needs, now it's ready to start rendering the page.
 
For element that's in the HTML, the browser will see if there's some CSS
to apply to it, again, different fonts, colors, etc.
 
If there's no specific CSS for that element, then it'll just use the default.
In theory, we would only have one CSS styling applicable to every element.
If there are more than one different types of stylings, for instance,
a particular element that's in multiple classes, or it's in a specific class.
But we also decide to style it some other way for
some other reason, there are various rules on how those would get resolved.
But for our purposes, we'll just say that every
HTML element in our page will only have one styling applied.
 
There are three ways that we can use CSS in our HTML pages.
Two of them we've already seen without knowing that it was CSS.
The first one is what we will call inline, which is within the elements,
within the HTML tag, will specify that style as an attribute.
The second one,
which we saw at the end of the previous lesson, is what we can call internal.
We have a style element in the head of the HTML, and
we can apply different stylings to different classes.
And then third, as I mentioned, we can have an external css file that is
linked from out HTML page, and that will be downloaded separately as a separate
HTTP request and response, and then applied to our page.
 
Let's review the first way, which is the inline CSS, as a style attribute.
When we are doing inline CSS,
within the element tag, we have within the tag for the element,
we specify the style attribute with the styling that we want to apply.
 
In this particular case, we are saying that for this particular element for
this this particular tag, we want it to appear red.
So in that case, we would see it still, h1, still a little bit bigger font,
still bold, but in this case red instead of the default which is black.
Let's quickly talk about what is good and bad about inline CSS.
Clearly, it's very easy to use, if it's only want to do something once.
There's just this one specific HTML tag that I want to be red, for instance.
It's very easy to do that.
However, we saw at the end of the last lesson, if I had a lot of
tags that I want to apply this styling to, it's not so good for that.
 
And one problem also,
is that we're mixing together the HTML and the CSS all in one place.
Not even in just one file, but in one place in that one element.
We're specifying the structure, but we're also specifying the appearance.
Maybe those should be separated.
 
The second way of getting CSS into our HTML pages is what we can call
internal CSS, using the Style tag.
As we saw at the end of the last lesson,
we can put a style tag in the header of the HTML, and then we can
specify the different appearance of different elements in our HTML page.
For instance, in this case,
within the head of our HTML, we have the style tag, style elements.
And we're going to say that anything that's h1,
anything that's a level 1 header, will be red and will be capitalized,
we'll capitalize the first letter of each word.
Now in the bottom of our HTML page, within the body,
anytime there's an h1 tag, it's going to apply this CSS,
this rule to any h1, and so this will as before, appear red.
Note that in this case, it would apply this formatting red and
transforming the first letter of each word to be capital with every h one.
Every level one header in our webpage, and not just this one particular one.
It's worth reviewing at this point the CSS syntax.
At the start of this lesson, I pointed out that CSS is a language, and
CSS has to follow the specific structure.
 
The first thing is known as the Selector.
The Selector specifies to what
sorts of elements do we want to apply this formatting.
After the selector we have the curly braces, and
within the curly braces, we have property value pairs.
The property is the type of appearance, and
the value is the specific value, the specific thing there.
And with semicolons, and we can have many of them within the same selector.
 
So using the style tag, style elements, the internal CSS,
allows us to separate the content, which is in the body of the HTML page,
from the appearance, which is in the head of the HTML page.
It's certainly easy to use, to apply some styling to all the elements in the page.
It's perhaps only good if there are only certain stylings that we want to apply.
The disadvantage is, that if we have lots and lots and lots of styling to apply, but
the head of our HTML page might get really,
really big, compared to the body of the HTML page.
And another problem is that we can't use that styling in other HTML pages,
without copying and pasting it, which is, of course, not desirable.
 
Which leads us to the third approach to including CSS in our HTML pages,
which is the external CSS.
In this case, we put CSS in a separate file, and then we link it, or
include it in our HTML page, using a tag in the head of the HTML file.
So here we have movies.HTML, and within the head, We have a link element.
The link element tells the browser go get this other file, link to this other file
in particular, it's saying, go get this file movie-styles.css.
What will happen in this case, is that the browser, upon seeing this link element,
will make another HTTP request from movie-styles.css.
We'll get an htb response now, containing the contents of that file,
movie-styles.CSS, which we see over here as our CSS file,
including the selector and the property value pairs.
Here we see, as we saw in the previous example,
that we're going to apply this styling to all H1 elements.
So for instance, over here, we have the h1 elements.
And when we render the page, when the browser renders the page,
it will apply this styling to all h1 elements.
And so, the header, in this case again, would be red.
So now we have managed to separate the content and
presentation, not just from the body and the head, but
in completely separate files, in an HTML file, and in a CSS file.
And we can, of course, use this CSS file in many different HTML pages.
We could also use many CSS files in one HTML page,
if we had different stylings in the different files.
Of course, when we start to create more files,
there's more files to work with, more files to keep track of.
 
But generally the advantages of separating the content, the HTML,
and the presentation in the CSS, outweighs these disadvantages.
In CSS, remember I said, we have the selectors and
then the property value pairs.
 
There are three types of selectors.
One is the element selector, as we saw on the previous example.
And the element selector, the selector is the HTML tag or the hl element.
It has applied this Styling, in this case red, to all h1 elements in the page.
 
Now one that we saw at the end of the last lesson was the class selector.
The class selector always starts with a period to indicate the name of the class,
and then the name of the class.
If we had a class called address, and
then we had HTML elements that were in that class, using the class attribute,
then it would apply this styling to every HTML element that's in that class.
 
And last, we haven't seen an example like this yet, but
when we have an ID, that's starting with the hashtag or the pound sign,
that applies the styling to one specific, distinct, unique element in the HTML page.
It bears repeating, that the ID has to be unique or distinct within the HTML page.
You can only have one element with that particular ID, and
this will apply the styling to that element.
 
To summarize, we started to look at Cascading Style Sheets,
a way of affecting the appearance of our HTML elements,
perhaps in a separate file that's linked or included from our HTML file.
We're going to be seeing CSS a lot in subsequent lessons in this part of
the course, and especially in the next couple of weeks of the course, where we're
going to dynamically change the appearance of the HTML elements using CSS.


HTML Lists and Forms
In the previous lessons,
we've been looking at how to affect the appearance of HTML elements using CSS.
In this lesson, we'll go back to plain HTML and
talk about some of the other tags that are available to us, starting with lists.
 
In HTML, we can create lists of elements or of items that are ordered or unordered.
In an ordered list we use the ol tag, for ordered list.
An ordered list, when the browser renders it, it will put, in this case,
numbers in front of each list element, or list item.
We indicate that it's an ordered list using the ol tag, and
then each item in the list is surrounded with li and the not li, or closing li tag.
In an unordered list there are no numbers in front of each element,
just some sort of icon, for instance in this case, the bullet.
The unordered list uses the ul tag.
But again, each element in the list has the li and close li tag.
In an unordered list, we can use the style attribute
to affect the appearance of the type of bullet that's used in front of each item.
For instance, here I have ul for unordered list.
 
And then I have the style attribute specifying that the list-style-type is
a circle.
Now rather than the filled in bullets, the black bullets,
this will just be the empty circle.
And there are different types of list styles that we can use.
There's the disc, which is the default one, the filled in bullet.
The circle, which is the empty circle, a square, or we can just have none at all.
In the same way that we can apply style attributes to an unordered list,
we can also apply style attributes to an ordered list.
Here we use the type attribute, and we specify the type of number or
letter that will appear in front of each list item.
By default it will use numbers like 1, 2, 3, 4, 5.
 
Here by using type="A" what we'll get is A, B, C, D, etc.,
in front of each item in the list.
And there are a variety of different types that we can use in an unordered list,
uppercase letters, lowercase letters, roman numerals, etc.
We can of course have a list within a list.
We can have, in this case, an ordered list within an unordered list.
 
In this case, we'll have an unordered list on the outside.
We'll specify the list-style-type to be circle.
And then on the inside we'll have an ordered list using A, B, C,
D in front of each element, and it would appear like this.
The next thing I wanna look at is forms.
 
Forms are an important part of any HTML page,
especially when we're trying to get information from the user.
 
We're gonna use a form element or a form tag in our HTML page and
put all the form items within those tags.
Each item or input has a different type and
we're going to look at the different types of types within the next few slides here.
 
We can use the type attribute for
each input to indicate what type of input it is.
And that will let us do some checking later on when we wanna make sure, for
instance, that a value is legal.
 
So going back to our example here, let’s start with these at the top.
These are the traditional inputs where the user needs to type something.
 
The first one that's Full Name is the text type, that's just any sort of input
text that will appear as a single input text field in the browser.
Following that we can have an email type, which will expect to have a valid email address.
We can have the password type, which will instead of showing in the browser what they're actually typing, will show some kind of bullet or asterisk to hide what they are typing.
And last, we can have a date input type, which allows us to, for instance, specify the format of the date, in this case month, day, year, or we can use other formats as well.
Now if we go back to our form, we see the next form element or input is this slider.
 
In HTML we call this a range input or the range type.
This allows the user to slide back and forth and choose different values.
And here we're specifying that the minimum value is 1950, the maximum value is 2020.
Next, we have an often confused or two often confused types which are radio buttons and checkboxes.
 
These ones here indicated in the slide are radio buttons.
The radio button appears as a circle that we can click.
 
But a radio button means that we can only choose one out of some group.
So, these are type radio.
But these three options all have the same name.
This means that they're grouped together and the user can only choose one of these three.
If they chose one and then clicked on another then it would unselect the first one that they chose.
Each element or each radio button has a different value that we can use later on when we want see what they selected.
But they can only choose one of these three.
Below that are checkboxes.
 
Checkboxes are similar but we can choose more than one.
So here the type is checkbox.
They all have the same name, which indicates that they all go together, but
they have different values, of course, but we can choose more than one.

 
Here we see the color picker or the color chooser, the input type is color.
And when we click that button what we would see is the color chooser.
Different browsers show the color chooser or color picker differently, here's what it looks like in Google Chrome.
 
When we want the user to be able to upload a file, we have the input type="file".
And they can click the button, for instance, if it reads Choose File, they'll choose a local file and then the No file chosen will automatically be changed to the file name when they indicate the file to upload.
Last, we have buttons.
 
We're going to be using buttons a lot, especially in the second part of this course when we're doing JavaScript.
Here we see two different types of buttons, the first one is the Submit button.
When we say type="submit", that means when the user clicks it to take the action of the form.
The action of the form, for instance, might be choosing a new page or loading a new page.
It might be running some code.
We'll see examples of that later.
Here we have the reset type.
A Reset is a button that will clear all of the fields, set them back to their defaults when the user clicks it.
 
There are lots of other input types that we didn't see in this lesson.
The most common ones are the type="text", where the user can type something, and buttons, as we'll see later on.
 
To summarize, in this lesson we looked at HTML lists, which allow us to organize information in an unordered list or an ordered list.
And we looked at forms, which allow us to get information from the user.

HTML Links, Images & Tables
When I introduced the idea of the web browser, I mentioned that back in the old days, web browsers just showed the text.
 
Here's an example of one called Lynx.
Lynx was a text-based web browser.
You could, of course, click on links or follow links, choose a link using a cursor, but there were no images.
 
Later on, and certainly now, web browsers allow us to see images, for instance here's a photo of a women cycling.
How do we get images into our HTML pages?
 
We do that using the image or img tag.
The img tag tells a web browser to show an image in that particular spot.
Now the image is not really in the HTML page, remember HTML is just plain text.
Rather it's a link.
It tells the browser to go get that image.
And we'll talk about where it gets it in a little bit.
The image has two required attributes, one is the source or src.
That's the location of the image.
And the other is alt or A-L-T, that's the alternative or alternate, I should say, text.
That's what should appear as the image description for instance if the image could not be loaded.
It's also used for instance for screen readers which are going to read the text.
We can also specify the height and width of the image and we can specify the title of the image which is the text that will appear when the user hovers over it with the mouse.
 
At the bottom, here's an example of how we would have an image in our HTML page.
We'd open up with the image tag.
We'd specify the source, the name of the image.
And then alt's what we call the alt text.
The alternate text is a description of the image that would be shown in the page if,
for some reason, the image could not be loaded.
Now I mentioned we have to specify the location of the image and
there are two ways of specifying the location of the image.
One is the absolute path and the other is the relative path.
The absolute path is a URL that could be accessed on its own.
It is the full path, it is its distinct, unique address on the World Wide Web.
And in this case we're using the absolute path by specifying
the entire URL including the protocol http etc., etc.
However, if the image that we want to display in the HTML page
is somewhere, for instance, near the HTML page like on the same computer,
we can use what's known as the relative path.
 
Here, for instance, we see that we have some file structure.
We have our index.html page, and maybe there are two of these images,
one in the same folder or directory, another in a subfolder or subdirectory.
 
We can, instead of using the absolute path including http, etc., etc., we can just say that it's the same directory, but a different file using the relative path.
We could also say it's relative to the location of this HTML page.
In this case, it's in the photo subdirectory or subfolder.
And then this is the name of the file.
 
Now core or key to the entire idea of the World Wide Web, is that from one page you can link or go or traverse or surf.
I guess no one says surf any more.
You can surf to another page.
We do that using the <a> tag or anchor tag.
Now the <a> tag, the anchor tag, has a lot of uses in an HTML page.
But the most common one is when we're linking to another page or another resource on the Web.
The <a> tag has an href attribute, which is the location to which we should jump or navigate when the link is clicked.
We can also have a target which says whether we should open a new window or new tab, for instance, when the user clicks that link.
When we're following a link and specifying it using the <a> tag, we can use an absolute path or a relative path.
And then we specify in the HTML, the link or in some cases the image that needs to be clicked in order to follow that link.
 
In this case, we start with the <a> tag or the anchor tag.
Then we specify the href, the location to which we should navigate if the user clicks on this link.
We have the target, in this case meaning just show the content in this web browser itself.
Here is the text that, as you've seen in many web browsers I'm sure, is the clickable link.
And then we end the HTML element using the not a or the /a tag.

Sometimes we can use an a tag or an a element, an anchor element, to link not just to another webpage but somewhere specifically within that webpage.
Or even specifically within the page itself, and we call those using bookmarks.
We can do that using the id attribute for any element in the HTML page.
 
For instance, let's say I have some level three header and I want the user to be able to click a link that scrolls the webpage to that particular part of the page, rather than starting at the top of the page.
I can specify its id, in this case health.
 
And then I create links that will go to that part of the page.
If it's within the same page I can have a href=#health.
And this is a link when the user clicks on this link it will scroll to that part of the page.
 
If I wanna have a bookmark to a spot in a different page,
I can have the name of that page then hash mark or pound, and then the name of the id of the element to which to scroll when we open that page.
Lastly, we'll look at tables.
 
In the previous lesson we talked about lists.
Lists were a way of organizing information.
Tables give us even more structure.
We can use the table tag to say this is the start and end of our table.
In this case we're specifying the border which is the width of the border between elements and the table.
 
A table consists of rows, each row of the table starts and ends with the <tr> tag for table row.
There are two different types of rows.
 
One row, which we can call the header, uses the <th> tag for table header to indicate the content that goes into that row.
It doesn't have to be the first row of the table, though that would usually make the most sense.
Here we see that the browser by default is rendering it in bold, indicating that it's the header of the table.
 
The <td> tag is the table data, that's just for a regular table cell, a regular row within our table.
Here we see the text rendered just as normal text.
 
Just like every other HTML element, the table has attributes that we can use to affect its appearance.
We saw border in the previous example.
That's the border that will appear around the table.
We can specify for the border the width in pixels.
We can specify whether it's a solid or a dotted line border, we can specify the color etc.
 
The padding is the space between the cell content and the borders.
So if we have some text and we have a lot of padding then the borders will move farther and farther away from that text.
We can specify the alignment of the text within any cell or an entire row.
 
And then the border spacing is affected by this border spacing property, which is the space between the different cells.
Now in that previous example, we had a three by three grid, or table.
Sometimes we want a cell to span multiple rows or multiple columns.
We can use the <rowspan> attribute to say that this particular cell should go across, for instance, in this case, two rows.
 
So we see here that it starts on one row but then would go down to the next.
Well if there's <rowspan> then there must be column-span or <colspan>.
This would say to let this table data cell go across multiple columns.
 
To summarize, we've seen the last three HTML tags that we're going to look at in this course.
 
We have the <img> tag for including images in our HTML pages.
We have the <a> or anchor tag for creating links, and the <table> tag for further organizing our data.

Responsive Web Design With Bootstrap
This week we've been looking at HTML and CSS for
structuring the content in our web pages and for affecting its appearance.
And we've seen some examples of HTML pages and
what they look like when rendered in a browser like Google Chrome.
But it's important to remember, as a professional software developer,
that the users of the web page, the people who are viewing your web page,
may be doing so on different types of devices.
 
Sometime in late 2016, the usage on the mobile, and handheld, and tablet devices started to exceed usage from desktop devices, laptops, PC's, etc.
This means that not only are people looking at your web pages on smaller devices, but of course on a variety of different types of devices, which raises challenges when it comes to designing the page.
 
Here we see, perhaps, a traditional web design.
At the top, we have what they call a carousel of data.
Here are some charts at the bottom here.
 
And if we have a web page that looks like this, and we look at it on a phone or a tablet, by default the browser will try, and the mobile device will try, to crush everything into the little space that it has, which can warp or affect the appearance of things.
For instance, now these charts seem to be crushed together.
 
What we want is something known as responsive web design.
In responsive web design, the web page realizes that the browser on which it's being viewed might be smaller or bigger, and fills in the space accordingly.
So Responsive Web Design is an approach to designing the web pages, or creating a web pages, that we think about the different types of devices and how the page would look when rendered in different types of browsers.
How do we achieve RWD, or Responsive Web Design?
Well, we could try to write different CSS for different types of browsers.
In CSS we can detect the browser type.
And then we could say on certain browsers and certain devices, we'd have different spacing different sizes.
But that can certainly be lots and lots and lots and lots of CSS.
And every time a new device, or a new size device, comes out we'd have to go back and modify our CSS.
 

 

 
What we want instead is automatic responsive web design, to use tools that do this automatically for us.
And one such tool is known as Bootstrap.
Bootstrap is an open source, front end development framework that's produced and maintained by Twitter.
And it lets us create responsive web pages and applications just by using CSS.
 
Key to understanding how to use Bootstrap is understanding what they call the grid system.
In Bootstrap, all elements in the page are arranged into a grid.
And depending on the size of the web browser or the size of the device, it will rearrange those grid elements.
 
So here's a quick way of starting to use Bootstrap.
We begin with a basic HTML page, just like any other HTML page that we would write.
 
To include Bootstrap in our project, we would include these following tags in the head section of our HTML page.
We would specify the CSS style sheet that we're going to use.
And then we would specify these two JavaScript libraries.
We'll, of course, look at JavaScript later in this course.
But for now, we'll just use the JavaScript that Bootstrap makes available to us on the web.
In this particular slide, I'm showing the most recent versions of Bootstrap.
But you should go to the getbootstrap.com website in order to get what's more updated.
 
Next, in the head section of our HTML page, we specify this meta tag named viewport.
And all this does is tell the web browser to figure out the width of the device or the browser, and then use that when figuring out how to arrange the elements in the Bootstrap grid.
 
Last, we can apply Bootstrap formatting to all the elements in our HTML by using a div in the container class.
Container is a class in the Bootstrap CSS that has the different formatting rules.
And we would create a div and put our content into that div.
That allows Bootstrap to figure out how to change the appearance of the content in our page.
If we create the default Bootstrap Hello, World page, it would look something like this.
 
And if we were to resize, it would resize accordingly.
 
In the Bootstrap grid system, all the content is organized into rows which, of course, are just horizontal groups of columns.
And Bootstrap will figure out how to arrange those depending on the device and the size of the window.
 
In this example, we're going to see the same content more or less rendered with Bootstrap and without Bootstrap.
At the top of my HTML here, I am gonna use Bootstrap.
I'll create a <div> that's in the container class.
Remember, if you're going to use Bootstrap, you have to have the <div> in the class container, and put your content into there.
Within that container, I will create a single row.
Now, this isn't the same as a row in a table, but rather a row in the Bootstrap grid system.
 
Within the row, I will have more divs, which are in different classes depending on how much of that row I want them to take up.
We can think of the row as having a width of 12.
And in this case, I'm saying that each column within the row takes up 4, that's what the 4 here specifies, 4 of the 12.
But I can perhaps take half or more than half, and so on, by specifying different column widths.
Now, at the bottom of my page,
I have a traditional table that we saw in the previous lesson.
The table will not automatically resize.
But as we saw at the beginning of this lesson, when we make the web browser smaller, the content will get crushed together.
 
Here's how that HTML page looks when rendered in Google Chrome, more or less full screen.
So we can see, they look very similar.
This is one row of the Bootstrap grid system.
And this, of course, is just one row of our traditional HTML table.
 
But when I start to move the browser, and make the browser smaller, you can see what happened now is that Bootstrap figured out that this content, we can't fit all of the content in that one row.
So rather than trying to have it all in one row, it'll start putting things underneath each other.
However, my HTML table is going to keep getting smaller and smaller as I make the window smaller.
 
Now, I've made the window so small that the Bootstrap content appears here in the same way, now stacked on top of each other.
 
But now the HTML in the table is starting to use multiple rows because I'm making the cells so small.
If I wanna see what my HTML page looks like on different devices, I can use tools, for instance, in Google Chrome, to render it on different devices and see how it would respond to different device sizes.

Here's the same page that we saw in the previous example.
If I right-click, or get the context menu, I can then go to Inspect in Google Chrome.
 
And that'll open a window like this, which shows me the HTML and the rendered HTML at the same time.
By default, it showing me my responsive web page, the regular Google Chrome browser.
But here I can change to, for instance, iPhone 5, and Google Chrome will show me what it looks like on iPhone 5.
Now, of course, it's just figuring out the dimensions of the iPhone 5 browser.
But we can see in this case that my Bootstrap content does get stacked on iPhone 5.
 
But my table is getting crushed here.
If I want to choose a different device, I can, for instance, choose iPad.
And then I can see what happens when I rotate the iPad using the rotate button.
And now I can see what it would look like in that particular browser.
We're not going to do too much more with Bootstrap in this lesson.
I do recommend, if you're interested in this, that you look at the Bootstrap website.
And probably, through looking at the Bootstrap website, especially their examples, you'll see lots of things that you would like to try or include in your HTML pages, as well.
Fortunately, every browser allows you to inspect or see the HTML source.
And you can get an idea of how the elements in the Bootstrap examples are put there.
For instance, here in the example's page for Bootstrap, I see the different buttons.
 
And maybe in my webpage, I want this sort of button, this big blue button with the grey border around it.
I can right-click, or get the context menu.
I can choose Inspect.
And that will open up in Google Chrome the Inspect window.
And I can see that it's highlighted here, and here I'll circle it.
It tells me that this element that I like is a button.
It's in type button.
And it's in these three Bootstrap classes, the btn for button.
Btn-large for a large button, and btn-primary for what they call the primary button, which is the blue.
So I can use those classes in my HTML page to get a button that looks exactly the same as that one.
That's it for Week 1 of this course.
 
We started off by looking at HTTP, the protocol that's used on the worldwide web for transferring data.
We saw HTML for allowing us to specify the structure of our web content, and CSS for allowing us to specify its appearance.
In this lesson, we looked at responsive web design using libraries, for instance Bootstrap, to automatically resize our page and make it look nice on different types of devices.
In the next part of the course, we'll start looking at JavaScript.
JavaScript the third important technology in web programming that allows us to create dynamic content within our HTML pages.

Introduction to Week 2
Starting this week, we'll be looking at JavaScript, one of the world's most popular programming languages.
We'll start with the core features of the language and then we'll see how we can use JavaScript to access HTML elements and create dynamic web content.


Introduction to JavaScript
Last week we started looking at two of the key technologies for web development, HTML and CSS.
HTML allows us to specify the structure of the content in our web page and
CSS allows us to specify its appearance using style attributes.
However, both HTML and CSS only allow for static content.
That is, when the web browser renders them, they don't change regardless of what happens within the context of that web page.
 
So this week we'll start looking at how do we create dynamic content in the web page and we're going to start looking at the programming language JavaScript.
 
JavaScript was developed in the mid 1990s when the web browsers started to take off.
It is clear that there needed to be some way of rendering dynamic content in the browser.
JavaScript was originally called LiveScript because the Java programming language was becoming so popular the name was changed and it stuck.
Now JavaScript is one of the most popular programming languages in the world as you surely know which is why you're taking this class perhaps.
And it runs on just about every browser and on many types of devices.
 
There are three ways that we can develop in JavaScript.
We're mostly going be using one of these ways.
But we look at some of the others later on in the course.
The first way is embedding the JavaScript directly in the HTML using script tags and script elements or using a link to an external .js for JavaScript file.
Now, we've seen the link tag before for CSS.
This would allow us to link our HTML page to a JavaScript file.
We're mostly going to be using the script tags to be put the JavaScript directly into the HTML.
The second way of developing in JavaScript is to use what's known as the REPL, R-E-P-L.
That stands for read, evaluate, print, loop.
It allows us to write a line of code, evaluate it, write another line of code, evaluate, and so on.
In browsers such as Chrome, have a console, that allow us to write some JavaScript and then see the output.
Third, you could write JavaScript into a .js file and run it in a stand-alone runtime environment or execution environment such as Node.js, which we'll see in the fourth week of this course.
 
Here's a very, very simple JavaScript page.
We will of course be spending the next couple of lessons on JavaScript.
But it's a standard HTML page And within the body of the HTML, we see a script element or the script tags.
This tells the browser that what is here between the script tags is not
HTML to be rendered, but rather JavaScript to be executed and then the output should be rendered in the HTML page.
The first thing we see is this line here document.write The current day and time is document is a global variable a variable we can access anywhere in HTML page that means this HTML document.
Write as you can imagine is going to let us write content to it and here we have a string that says The current date and time is.
On the next line we declare a variable called time, we create a date which is going to represent the current date and time and then we use the document.write right function again.
We pass it the variable time.
And this will print or write the current date and time within the web browser.
The details of this example aren't as important as just showing that we can include the JavaScript in the HTML page using the script tag.
 
This is what my page would look like in Google Chrome.
It's just regular HTML.
We see the parts that I wrote in HTML.
This part and here is the generated part from the JavaScript and then we have all of this, which is the current date and time.
If we look here at the timestamp, around 5:32 PM, when I reload the page, the next time I reloaded the page I see the new time now 5:34 PM.
 
Let's look ahead at what we're going to see in the next few weeks on JavaScript.
In the remainder of this week, we'll look at JavaScript basics and then we'll see how we can use JavaScript to access the HTML elements and give us dynamic content.
Next week we're going to see client side frameworks, those are JavaScript frameworks that we can use within the browser.
And in week four, we'll use server-side frameworks that's JavaScript frameworks that we can use running on a HTTP server.
Before I wrap up this lesson, I'll just point out that in these examples, I'm using a particular version of JavaScript with a particular web browser on a particular operating system.
You may see slight differences depending on, for instance, which version of JavaScript you're using or which web browser.
 
But we'll try to stick to standard JavaScript so that everything will be the same.

JavaScript Variables


Abcdefghijklmnopqrstuvwxyz1234567890


xxyyyzzzz


xxyyyzzzz


xxyyyzzzz


xxyyyzzzz


xxyyyzzzz



II.	Using JavaScript to Create Dynamic, Data-Drive Web Pages


a)	JavaScript Basics



b)	Using JavaScript in Web Pages

III.	Client-Side Frameworks for Developing Modular Web Page Components
b)	Developing Web Applications with React



c)	Advanced Component Design for React


d)	Creating Data-Driven Web Content with D3.js


IV.	Building Scalable Web Apps with Server-Side JavaScript
a)	Developing Web Applications with Node.js



b)	Databases and Web Applications


