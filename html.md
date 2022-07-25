# HTML

## BASICS OF HTML

## DEFINITION OF HTML
 
 **HYPERTEXT**
      : text(often with embeds such as images,too),that is organized in order to connect related items
 
 **MARKUP**
    : a style guide for typesetting anything to be printed in hardcopy or softcopy format
 
 **LANGUAGE**
     : a language that a computer system understands and uses to interpret commands



The **HYPERTEXT MARKUP LANGUAGE** or **HTML** is the standard *markup language* for documents designed to be displayed in a 'web browser'. 
It is assisted by technologies such as *Cascading Style Sheets*(css) and scripting languages such as *Java Script*.

**WEB BROWSERS** receive  HTML documents from a web server and render the documents into multimedia web pages. HTML describes the structure of the web page semantically 
and originally included cues for the appearence of the document.

**HTML ELEMENTS** are the building blocks of HTML pages.HTML provides a means to create structured documents by denoting structural semantics for texts such as
headings,paragraphs,lists,links,quotes and other items.HTML elements are delineated by tags,written using angle brackets.
Tags such as img and input directly introduce the content into the page.

HTML can embed programs written in a scripting language such as Java Script.Inclusion of CSS defines the look and layout of the content. The **WORLD WIDE WEB CONSORTIUM(W3C)**,former maintainer of the HTML and the current maintainer of CSS standards,has encouraged the use of CSS over explicit presentational HTML since 1997.
A form of HTML known as **HTML5**,is used to display video and audio,primarily using the **canvas** element,in collaboration with Java Script.


## HTML VERSIONS TIMELINE


| YEAR OF UPDATE  |    VERSION NAME     |
| --------------  | ----------------------------------|       
| NOVEMBER 24,1995| HTML 2.0 as RFC 1866              |
| JANUARY 14,1997 | HTML 3.2 as W3C recommendation    |
| DECEMBER 18,1997| HTML 4.0 as W3C recommendation    |
| APRIL 24,1998   | HTML 4.0 reissued with minor edits|
| DECEMBER 24,1999| HTML 4.01 as W3c recommendation   |
| OCTOBER 28,2014 | HTML 5 as W3C recommendation      |
| NOVEMBER 1,2016 | HTML 5.1 as W3C recommendation    |
| DECEMBER 14,2017| HTML 5.2 as W3C recommendation    |

## HTML ELEMENTS
>
>An **HTML ELEMENT** is defined by a start tag, some content and an end tag.
>The HTML element is everything from the start tag to the end tag:
>

![syntax html](https://user-images.githubusercontent.com/109893468/180767861-1fb9ec1d-4ed2-4793-a5ff-7a9389472281.png)


>##Example of HTML elements


![example html](https://user-images.githubusercontent.com/109893468/180767988-d80d41b9-677a-49fc-9dce-d03eb30c1cb7.png)



>**NESTED HTML ELEMENTS**
>
>
>HTML Elements can be nested that means that elements contain other elements.All HTML documents consists of nested HTML elements.Tags may also enclose further tag markup between the start and the end,including a mixture of tags and text.This indicates nested elements, as children of the parent element.The start tag may also include elemnt's *attributes* within the tag.


>##Example HTML document

![html example](https://user-images.githubusercontent.com/109893468/180769745-89357fa1-e18c-45e0-a331-2b92c6054975.png)


>The following example contains four html elements html,body,h1 and p.
>The **html** element is the root element that defines the whole html document.
>It has a start tag and a end tag.Then inside the html tag  there is a **body** element.

>The **body** element defines the document's body.Inside the body element there are two elements **h1** and **p**.

>The **h1** element defines a heading.It has a start tag and an end tag.
>The **p** element defines the paragraph.It has a start tag and an end tag as shown in the above example.

**EMPTY HTML ELEMENTS**


>HTML elements with no content are called as empty html elements.
>The **br** tag defines a line break,and is an empty element without a closing tag.Let's see the example of br tag.

![br example](https://user-images.githubusercontent.com/109893468/180772684-9ea603bc-66fd-4afb-ba16-b7788dfb7647.png)

## TYPES OF HTML

HTML can be divided into three categories:transitional,strict and frameset.These types apply to how HTML is used,not necessarily to the selection of tags.

1.Transitional
    
   **Transitional** is the most common type of HTML.It has a flexible syntax.Over the years,transitional html has been used without syntax restrictions,and browsers support a *best effort* approach to reading the tags.If tags are misspelled,the browsers do not correct the web developers' errors, and they display the content anyway.
    
2.Strict
           
   The **Strict type**  of HTML is meant to return rules into HTML and make it more reliable.This style of HTML is important on phones,where the processing power may be limited.A clean and error free code helps to load pages faster.

3. Frameset
           
      Finally, a **Frameset** allows web developers to create a patchwork of HTML documents where multiple documents can be connected into a single screen.This technique is often used to create a *menu system*.You click on menu item on the left screen, and only the right side of the screen re-loads.The menu stays in place.
           

**HTML ATTRIBUTES**
   
           Most of the *attributes* of the elements are name-value pairs, seperated by "=" and written within the start tag of an element after the element's name.The value may be enclosed in single or double quotes,although values consisting of certain characters can be left unquoted in HTML(but not XHTML).There are some *attributes* that affect the element simply by their presence in the start tag of the element,like the **ismap** attribute for the **img** element.
  There are several common attributes that may appear in many elements:
  
 - The **id** attribute provides a document-wide unique identifier for an element.Appended to the  URL of the page,it provides a globally unique identifier for the element,typically a sub-section of the page.
 - The **class** attribute provides a way of classifying similar elements.This can be used for semantic or presentation purposes.
 - An author may use the **style** attribute to assign presentational properties to a particular element.
 - The **title** attribute is used to attach subtextual explanation to an element.
 - The **lang** attribute identifies the natural language of the element's contents, which may be different from that of the rest of the document.
          
    
           



