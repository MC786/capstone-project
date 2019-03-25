# Front-End Technologies

## What is Front End?
<h2 align="center">
  <p>
    <img alt="Front End vs Back End" src="data/FE vs BE.jpeg" width="300" />
  </p>
</h2>
<div align="justify">
In the context of web development, Front End Programming describes the process of designing what the customer sees when interacting with the programmers product. This means websites, app interfaces or even the screens on an ATM.
  
  Front End Programming draws the connection between the actions happening in the background and the graphical user interface. The referenced "actions in the background" are mostly part of Back End Programming, namely the logical coding, databases, hosting software, etc.
  
  In order to gather a general overview over needed skills for Front End Programming, coding languages and desing software should be studied. Coding languages mainly consist of HTML, CSS and Javascript and desing software could be Adobe Photoshop or Sketch.
 
 It is important to understand the role of browsers in todays World Wide Web.
  Web pages are built with HTML coding. The browsers role is to read given code and visualise it for the client. However, different browsers interpret HTML differently, which leads to problems with webpages being displayed differently throughout different browsers and different devices such as mobile phones.
</div>

**//chris**

## Languages used in Front End Programming
**//chris**

### HTML
<div align="justify">
HTML (Hypertext Markup Language) is considered as the base of the World Wide Web. It was developed by Tim Berners-Lee in 1990 and has been further developed since by the World Wide Web Consortium and the Web Hypertext Application Technology Working Group.


The purpose of a Markup Language is to structure text in documents so that it is syntactically differentiable.
Through the use of HTML, Front End programmers can structure text on their websites, but cant format it. HTML delivers information for the browsers how to work with the text that they should display and how exactly to display it. However, since there are many different browsers, every browser interprets HTML differently, which leads to websites sometimes looking differently on different browsers.
</div>

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>title of website</title>
    <!-- more information on head -->
    <!-- comments arent shown in browsers. -->
  </head>
  <body>
    <p>content of website</p>
  </body>
</html>
```
1) **Declaration of type of document**  
   States which definition of the type of document (DTD) is being used.  
2) **HTML-head**  
   Contains technical or documentary Informations. Usually arent visivble in browser window.  
3) **HTML-body**  
   Contains information which is interpreted and shown by the browser.
   
#### HTML5
<div align="justify">
After HTML, the World Wide Web Consortium and the Web Hypertext Application Technology Working Group focused on developing XML and XHTML, to enable developers to further design their webpages and add colour etc. However, XML turned out to be too complicated for a standard developer and was strongly disliked by the majority.

HTML5 was the first major update since 1999. It allowed developers to firstly implement and use video, images and audio files without the use of external plugins. If the user wanted to play videos or flash games from e.g. YouTube or Spielen.com, plugins like Java or Flash Player had to be installed.
  
HTML5 is also more tolerant concerning correct syntax. While still expecting correct syntax, it allows more syntactical errors than HTML did.
</div>

### CSS
<div align="justify">
CSS (Cascading Style Sheets) was developed by Hakon Lee in 1994.
  
HTML structures the text and CSS "stylises" the text. Code written in a .css file selects identifiers from HTML and assigns them specific attributes such as colour, background or font.
</div>

```CSS
<style>
  h1{
      color: red;
     }
 </style>
```
<div align="justify">

</div>

#### SASS
<div align="justify">
Sass is a preprocessor for CSS and simplyfies the work with CSS, especially related to big stylesheets. It was designed by Hampton Catlin and developed by Natalie Weizenbaum in 2007. With the use of Sass, it is possible to declare variables and to work with them. This is helpful in big stylesheets to keep those values consistent. Moreover Sass lets you use features that do not exist in CSS yet like nesting, mixins, inheritance and other. A mixin lets you make groups of CSS declarations that you want to reuse throughout your site. You can even pass in values to make your mixin more flexible. 
</div>

#### Stylus
<div align="justify">
Stylus is a preprocessor for CSS and its goal is to make the work with CSS more efficiently. A characteristic of Stylus is its simple syntax. You do not need curly brackets, colons or semicolons. 
In Stylus it is possible to declare Variables and to use Nested Rules and Mixins like in Sass. Stylus convinces through its simple structur and the compability with JavaScript.
</div>

### Javascript

#### Description
<div align="justify">
JavaScript, often abbreviated as JS, is a dynamic and high-level programming language. It was created by Brendan Eich in 1995 during his time at Netscape Communications. Prior to this Netscape Communications partnered with Sun Microsystems to include their static programming language Java, because Netscape decided that the scripting language they want to create would complement Java, and to break the Microsoft monopoly for user adoption of Web technologies and platforms. JavaScript was called LiveScript when it got first released in September 1995 but it was renamed JavaScript in December 1995.
JavaScript was is the first client-side language and changed the world through the way to build the side of the site the user sees and interacts with. Before it, there were static HTML sites with no interactivity. 
Beside HTML and CSS, JavaScript is the most ubiquitous client-side language. If HTML dictates the content of a page, and CSS dictates the look and feel, JavaScript dictates the behavior of a page. JavaScript complements HTML and CSS due to changing content on the page and the way things look when a user interacts with it.
JavaScript is embedded right into the HTML of a page between <script> tags. An alternative way is to link an external JavaScript file, which is helpful if multiple pages are sharing the same chunks of code. 
Moreover JavaScript is a weakly-typed language, which means that JavaScript has not strict typing rules. It is object-oriented (prototype-based) and event-driven. 
To standardize JavaScript to foster multiple independent implementations, ECMAScript was created in 1997. ECMAScript is a scripting-language specification, which is standardized by ECMA International.
While JavaScript is a client-side language, some of its most powerful features involve asynchronous interaction with a remote server, which means that JavaScript is able to communicate with the server in the background without interrupting the user interaction taking place in the foreground.
With the Use of JavaScript it is possible to build a dynamic website, which is characterized by rollover effects and dropdown menus. Moreover new content and data can be loaded without reloading the page and animating page elements such as fading, resizing and relocating can be integrated. Playing audio and video and validating input from Web forms are other enhancements due to the use of JavaScript. In addition, browser compatibility issues can be repaired. 
</div>

#### Advantages
<div align="justify">
JavaScript is client-side and due to this it is very fast because it can be run immediately within the client-side browser. Moreover being client-side reduces the demand on the website server. Some JavaScript applications can even run without connecting back to a web server, which means they will work in a browser with or without an internet connection. 
Another Advantage of JavaScript is the simplicity. It is easy to learn and to implement compared to other languages. JavaScript enjoys a high popularity because it is used everywhere in the web. 
Through JavaScript it is possible to create a rich interface to a website, for example with drag and drop components or a slider.
</div>

#### Disadvantages
<div align="justify">
The client-side Security is not completely guaranteed, because the code executes on the users computer and in some cases it can be exploited for malicious purposes. This is a reason why some people choose to disable JavaScript.
Moreover JavaScript can be interpreted differently by different browsers, if no tool like JQuery, which handles all cross-browser inconsistencies and provides a consistent interface, is used.
</div>

#### Compilers
<div align="justify">
JavaScript can be compiled from code written in different languages through compilers like CoffeeScript and TypeScript.
</div>

##### Coffeescript
<div align="justify">
CoffeeScript is a language that compiles into JavaScript. It enables to write the code easier and up to 30% less coding lines. The code compiles into the equivalent JavaScript without interpretation at runtime. If the code is valid in JavaScript, it is valid in CoffeeScript.
Moreover CoffeeScript provides a more clearly syntax and it is more understandable than JavaScript. An Example of the difference is an automized declaration of the variables and optional brackets.
</div>

##### TypeScript
<div align="justify">
TypeScript is a typed superset of JavaScript that compiles to plain JavaScript and it is Open Source. TypeScript runs on every browser, in Node.js or in any JavaScript engine that supports ECMAScript 3 or newer. It offers classes, modules, and interfaces to help you build robust components. If the code is valid in JavaScript, it is valid in TypeScript.
</div>

#### Sources and Links
https://sass-lang.com/guide
https://de.wikipedia.org/wiki/Sass_(Stylesheet-Sprache)
https://we-code-it.de/2017/09/07/sass-less-less-sass-oder-doch-stylus/
https://en.wikipedia.org/wiki/Stylus_(stylesheet_language)
https://de.wikibooks.org/wiki/Websiteentwicklung:_JavaScript:_Einleitung
https://guide.freecodecamp.org/javascript/advantages-and-disadvantages-of-javascript/
https://www.frontend-gmbh.de/frontend/javascript/
https://www.upwork.com/hiring/development/what-is-javascript/
https://www.bigcommerce.com/ecommerce-answers/what-javascript-and-why-it-important/
https://coffeescript.org/#introduction
https://www.typescriptlang.org/


## Front End Frameworks
<div align="justify">
Frontend frameworks in general are files and folders which already contain samples of code. It depends on the framework, how much the template covers, how much you have to add by yourself and how much freddem is left for you own designs. As it is said in the beginning, nowadays there are a lot of different end-devices resulting in a matrix consisting out of lots of different operating systems, browsers and browser-version. Therefore coding websites gets very complex, as responsivensss is required.

The most famous frontend frameworks are React and Angular. React was developed by Facebook, Angular by Google. This is why they have a huge community and are widely known. 

React is a JavaScript Framework with a functional paradigm. Mostly it is used for UI. Its special features are DOM, One-Way-Data-Flow and the optional language JSX. 
DOM (Document Object Model) safes all elements in a tree-structure and calculates the position of every element. Every node is a HTML-element. All in all, it is an API, that enables JavaScript to access and change elements of the website.
One-way -data-flow means data can only flow "from the top to the bottom". The other way around only events triggered by the UI flow (e.g. clicking on a button). After that happens, the right position in the diagram is searched and from there on the lower elements get adjusted. An advantage is of one-way-data-flow is that it can be inserted in an already existing website and therefore no workflow is required and you have a lot of for your own ideas.  

Angular has all functions needed for Single-Page-Applications already integrated. It uses CSS and HTML but on top of that you have to learn TypeScript. Also you cannot just paste some functions in an already existing website, but you are working with Angular in a workflow. Angular is an object-oriented paradigm. Angular does not give you a lot of freedom for your own ideas.

A kind of simplified mixture out of React and Angular is the JavaScript framework Vue. It is combinable with HTML and CSS without any further language. It is a rather new framework and as it does not have a famous company-background as React or Angular, but still it is getting very popular at the moment. 
Vue is perfect for beginners, as besides JavaScript, HTML and CSS you do not have to learn a further language. The API is intentionally easy hold. So the aim of this framework is reaching an amazing result minimum effort. 

Another Framework is Foundation. It offers you a lot of predefined elements. They have both complete HTML-Templates and single components. They are also specified on mobile-first- and responsive-design. Anyways, foundation does not give the programmer a lot of freedom. The company ZURB developed the framework with the help of years of experience in consulting others on how to build a good website. Since 2011 it was published as an Open-Source-Project. 
</div>

## Designing in Front End
<div align="justify">
Designing Front End takes a big part of Front End development, since it influences the user highly. Most of today's strategies are build around UCDs (user-centered designs) and user experience is one of the biggest challenges. If the user is satisfied, the economy around it the product functions.
A big part to work on is responsiveness, as today's websites and web-applications need to scale well on every device with their own resolution. "Responsive design" is a term by Ethan Marcotte (2010) which describes the ability to respond on the technical requirements. Basic principles are: fluid grids (the arrangement transforms based on screen width and length), media queries (which control when to switch arrangements) and flexibility (flexible images and media scale based on their container).
</div>


There are best practices to meet the expections a user has:
* user focused design research (what does our user want?)
* reuse common design patterns (they work, don't reinvent the wheel!)
* consistency (design-wise and content-wise, use the same appearance and the same terminology!)
* communication (communicate with the user if something's changed, if they don't see progress, they get frustrated!)

These are just the main examples, to get a full overview visit this [site](https://www.uxpin.com/studio/blog/guide-design-consistency-best-practices-ui-ux-designers/).


## Helpful Videos or Tutorials
- [What you need to know as a Front End Developer (02.2018)](https://www.youtube.com/watch?v=Xd7huBu39qk)
- [A Beginner's Guide to Front-End Development](https://www.upwork.com/hiring/development/beginners-guide-to-front-end-development/)
- [Best Practices UI/UX](https://www.uxpin.com/studio/blog/guide-design-consistency-best-practices-ui-ux-designers/)

## Authors

| Name | E-Mail | Date of change |
|:-----|:-------|:---------------|
|Nina Erlacher|n.erlacher@web.de|23.03.2019|
|Jan Reinhards|jan.reinhards@web.de|23.03.2019|
|Nicolas Schlicht|schlicht.nicolas@gmail.com|25.03.2019|
|Christoph Teichmeister|christoph.teichmeister@gmail.com|25.03.2019|
