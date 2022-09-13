##201
[Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
Computers connected to the internet are called clients and servers
* Clients are the typical web user's internet-connected devices 
* Servers are computers that store webpages, sites, or apps

1. The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
3. If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
4. The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

[Website Design](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
start with a sketch
next, choose assests : such as theme, text, colors

Comments: 
Comments are snippets of text that can be added along with code. The browser ignores text marked as comments. You can write comments in JavaScript just as you can in CSS:

/*
Everything in between is a comment.
*/
Copy to Clipboard
If your comment contains no line breaks, it's an option to put it behind two slashes like this:

// This is a comment

1. Compose a short poem describing how HTTP sends data between computers.
A client makes a request
TCP is established
HTTP GET request to server
TCP closes

2. Describe how HTML, CSS, and JS files are "parsed" in the browser.
Parsing is the process of reading HTML content and constructing a DOM tree
from it. Hence the process is also called DOM parsing and the program that
does that is called the DOM parser.

3. How can you find images to add to a Website?
Use the img tag <img>, then you need to specify 4 attributes:
Src - location of the image/path/site;
Alt - the alternate text/written description;
Width - width of the image;
Height - height of the image;

4. How do you create a String vs a Number in JavaScript?
A string is characters wrapped in quotes // numbers have no quotes, stand
alone

5. What is a Variable and why are they important in JavaScript?
A variable is a named container used for storing values. Car/let/const
the value contained inside a variable can be any JavaScript data type,
including a number, string, or object.
A commonly accepted practice is to use const as much as possible, and let in
the case of loops and reassignment. Generally, var can be avoided outside of
working on legacy code.


1. What is an HTML attribute?
HTML attributes are special words used inside the opening tag to control the
element's behavior. HTML attributes are a modifier of an HTML element type.
A space between it and the element name. (For an element with more than one
attribute, the attributes should be separated by spaces too.)
The attribute name, followed by an equal sign.
An attribute value, wrapped with opening and closing quote marks.

2. Describe the Anatomy of an HTMl element.
* The opening tag: This consists of the name of the element (in this
example, p for paragraph), wrapped in opening and closing angle brackets.
This opening tag marks where the element begins or starts to take effect. In
this example, it precedes the start of the paragraph text.
* The content: This is the content of the element. In this example, it is
the paragraph text.
* The closing tag: This is the same as the opening tag, except that it
includes a forward slash before the element name. This marks where the
element ends. Failing to include a closing tag is a common beginner error
that can produce peculiar results.

3. What is the Difference between <article> and <section> element tags?
The <section> tag defines a section in a document. The <article> tag
specifies independent, self-contained content.
The section tag defines sections in a document, such as chapters, headers,
footers, or any other sections of the document.
The article tag specifies independent, self-contained content.
An article should make sense on its own and it should be possible to
distribute it independently from the rest of the site.

Potential sources for the article element:
Forum post
Blog post
News story
Comment

4. What Elements does a "typical" website include?
Header // Navigation Bar // Main Content // Sidebar // Footer

5. How does metadata influence Search Engine Optimization?
Using metadata boosts your SEO efforts because it's written in the search
engine's language. This helps search engines better understand the topic of
your webpages and content. It also helps them display more relevant results
to searchers.

6. How is the <meta> HTML tag used when specifying metadata?
Meta tags always go inside the <head> element, and are typically used to
specify character set, page description, keywords, author of the document,
and viewport settings.

charset          character_set                 Specifies the character
encoding for the HTML document
content         text                                  Specifies the value
associated with the http-equiv or name attribute
http-equiv    content-security-policy         Provides an HTTP header for
the information/value of the content attribute
                      content-type
                      default-style
                      refresh   
name           application-name                      Specifies a name for
the metadata
                     author
                     description
                     generator
                     keywords
                     viewport   


1. What is the first step to designing a Website?
project ideation - ask some questions
to have a vision of what you want and how to get there

2. What is the most important question to answer when designing a Website?
* What exactly do I want to accomplish?
* How will a website help me reach my goals?
* What needs to be done, and in what order, to reach my goals?


1. Why should you use an <h1> element over a <span> element to display a top
level heading?
Span has no semantic value; therefore it has no extra benefits - By default,
most browser's user agent stylesheet will style an <h1> with a large font
size to make it look like a heading
An span is an inline element
An h1 is a block element
An inline element cannot contain a block element

2. What are the benefits of using semantic tags in our HTML?
- Search engines will consider its contents as important keywords to
influence the page's search rankings (see SEO)
- Screen readers can use it as a signpost to help visually impaired users
navigate a page
- Finding blocks of meaningful code is significantly easier than searching
through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming



1. Describe 2 things that require JavaScript in the Browser?
Any complex feature - interactive content, animated graphics, content
updates

2. How can you add JavaScript to an HTML document?
Adding the <script> element   -- can be internal or external OR inline


[What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
