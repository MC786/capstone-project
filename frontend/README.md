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

**//jan**

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

### CSS
#### SASS
#### Stylus

### Javascript
#### Coffeescript

## Front End Frameworks

Frontend frameworks in general are files and folders which already contain samples of code. It depends on the framework, how much the template covers, how much you have to add by yourself and how much freddem is left for you own designs. As it is said in the beginning, nowadays there are a lot of different end-devices resulting in a matrix consisting out of lots of different operating systems, browsers and browser-version. Therefore coding websites gets very complex, as responsivensss is required.

The most famous frontend frameworks are React and Angular. React was developed by Facebook, Angular by Google. This is why they have a huge community and are widely known. 

React is a JavaScript Framework with a functional paradigm. Mostly it is used for UI. Its special features are DOM, One-Way-Data-Flow and the optional language JSX. 
DOM (Document Object Model) safes all elements in a tree-structure and calculates the position of every element. Every node is a HTML-element. All in all, it is an API, that enables JavaScript to access and change elements of the website.
One-way -data-flow means data can only flow "from the top to the bottom". The other way around only events triggered by the UI flow (e.g. clicking on a button). After that happens, the right position in the diagram is searched and from there on the lower elements get adjusted. An advantage is of one-way-data-flow is that it can be inserted in an already existing website and therefore no workflow is required and you have a lot of for your own ideas.  

Angular has all functions needed for Single-Page-Applications already integrated. It uses CSS and HTML but on top of that you have to learn TypeScript. Also you cannot just paste some functions in an already existing website, but you are working with Angular in a workflow. Angular is an object-oriented paradigm. Angular does not give you a lot of freedom for your own ideas.

A kind of simplified mixture out of React and Angular is the JavaScript framework Vue. It is combinable with HTML and CSS without any further language. It is a rather new framework and as it does not have a famous company-background as React or Angular, but still it is getting very popular at the moment. 
Vue is perfect for beginners, as besides JavaScript, HTML and CSS you do not have to learn a further language. The API is intentionally easy hold. So the aim of this framework is reaching an amazing result minimum effort. 

Another Framework is Foundation. It offers you a lot of predefined elements. They have both complete HTML-Templates and single components. They are also specified on mobile-first- and responsive-design. Anyways, foundation does not give the programmer a lot of freedom. The company ZURB developed the framework with the help of years of experience in consulting others on how to build a good website. Since 2011 it was published as an Open-Source-Project. 


**//nina**

## Designing in Front End
**//nico**


## Helpful Videos or Tutorials
- [What you need to know as a Front End Developer (02.2018)](https://www.youtube.com/watch?v=Xd7huBu39qk)
- [A Beginner's Guide to Front-End Development](https://www.upwork.com/hiring/development/beginners-guide-to-front-end-development/)

## Authors

| Name | E-Mail | Date of change |
|:-----|:-------|:---------------|
|Nina Erlacher|n.erlacher@web.de|20.03.2019|
|Jan Reinhards|jan.reinhards@web.de|20.03.2019|
|Nicolas Schlicht|schlicht.nicolas@gmail.com|20.03.2019|
|Christoph Teichmeister|christoph.teichmeister@gmail.com|20.03.2019|
