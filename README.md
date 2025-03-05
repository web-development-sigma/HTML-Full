*****************************************************************************************************
-------------------------------------------Basics Of HTML--------------------------------------------
*****************************************************************************************************

# Tags in HTML

1. Self-Closing Tags
2. Pair Tags

* Self Closing Tags *
- <meta> tag : Description of html page is given i.e. metadata of the web page
- ##<link> tag : use to link different files and style sheets

Tags:

- <html>..</html> : A basic tag which structures the document as html file
- <head>..</head> : used to write content of the page head
- <title>..</title> : used to write a title to webpage.Used by search engines to search the website.
- <body>..</body> : Covers the main content of the webpage or html
-  headings : <h1>,<h2>,<h3>,<h4>,<h5>,<h6>
- <p></p> : Paragraph tag use to write text in the html Documents.
- <a></a> : Anchor tags hels to make links
- <br> : Break tag is used to break the line such that new text entered is appeared on next line

# Attributes:

- Attributes are the features of tags which gives addditional functionality to the tags.

- style : used to style the elements in the tag(inline css) 
- rel : used in link to give the relation of the file(ex. stylesheet)
- href : used to define a reference location that is to be used.
- target = _blank : used to open the page referenced in a new tab.



*****************************************************************************************************
---------------------------------------Image, List, Table--------------------------------------------
*****************************************************************************************************


# Images
- <img> : Tag used to insert image in the html page
- src : Basic attribute used to define path of the image 
- alt : Defines the purpose of the image in case of image failure or reload error



# Lists
-- UnOrdered Lists

    -Displays items using bullets
    - Written within <ul></ul> tag
    - type : disc,square,circle

-- Ordered Lists

    -Displays items using numbers
    - written within <ol></ol> tag 
    - type : A,1,i,I,a

- <li></li> : defines the list items
- type : an attribute defines style of bullets or numbers in the list

-- Definition Lists

    -organizes items into dictionary
    - written within <dl></dl>
    - <dt></dt> : Definition term works as a key
    - <dd></dd> : Definition definition works as value for the dt



# Tables
- <table></table> : used to create tables
- <th></th> : used to give table header
- <tr></tr> : used to define the table row
- <td></td> : used to give the cell data in the table

- rowspan : the element will take no. of rows mentioned to show data
- colspan : the element will take no. of columns mentioned to show data
- border : used to display the border with the mentioned width of border

- <caption>..</caption> : gives a title to the table
- <thead></thead> : gives a header
- <tfoot></tfoot> : gives a footer
- <tbody></tbody> : defines body of the table



*****************************************************************************************************
----------------------------------------------Forms--------------------------------------------------
*****************************************************************************************************


# Forms

- <form></form> : a html form is made in these tags
- action :  specifies the URL to which the form data should be sent
- method : get/post - defines how that data should be sent, typically either "GET" for retrieving data or "POST" for sending data

- <input> : used to give input to the form
- placeholder : Gives hints in the input
- type : Defines the input type (text/number/password/radio/checkbox/email)
- name : gives the name for input helps in parsing.

- <label></label> : used to label the input
- for : an attribute of label tag which is defined on the id of input

- <textarea></textarea> : used to give a dialogue box to enter brief text as input.
- rows/cols : an attribute defines the span on the box 

- <select></select> : provides a selection list with different options
- <option></option> : metions the options in the select tag

- required : for imp info that is to be inserted and required.
- autofocus : automatically focuses to the input on page load



*****************************************************************************************************
---------------------------------------Inline & Block Elements---------------------------------------
*****************************************************************************************************


# Inline Elements
- Takes width fit to content i.e. as much it requires
- <a>: Anchor or hyperlink.
- <img>: Image.
- <span>: Generic inline container.
- <input>: Input field.
- <label>: Label for a form element.
- <strong>: Strong emphasis.
- <em>: Emphasized text.
- <br>: Line break.
- <code>: Code snippet.
- <b>: Bold text.
- <i>: Italic text.
- <u>: Underlined text.
- <small>: Smaller text.
- <sub>: Subscript.
- <sup>: Superscript.
- <mark>: Marked or highlighted text.
- <q>: Short inline quotation.
- <cite>: Citation.
- <kbd>: Keyboard input.
- <samp>: Sample output.
- <var>: Variable in a mathematical expression or programming context.
- <time>: Time.
- <abbr>: Abbreviation.
- <data>: Machine-readable translation of content.
- <acronym>: Acronym (Not supported in HTML5).


# Block Elements
- Takes full width of the screen by default
- <div>: A generic container for flow content.
- <p>: Paragraph.
- <h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Headings.
- <ul>: Unordered list.
- <ol>: Ordered list.
- <li>: List item.
- <form>: A section containing form controls.
- <table>: Table.
- <section>: A standalone section of a document.
- <header>: A container for introductory content or a set of navigational links.
- <footer>: Footer of a section or page.
- <nav>: A section of a page that contains navigation links.
- <article>: A self-contained composition in a document.
- <aside>: A section of a page that contains information indirectly related to the main content.
- <main>: The main content of a document.
- <fieldset>: A set of form controls grouped under a common name.
- <blockquote>: A block of text that is a quotation from another source.
- <pre>: Preformatted text.
- <canvas>: A container used to draw graphics via JavaScript.
- <dl>: Description list.
- <dt>: Term in a description list.
- <dd>: Description in a description list.
- <figure>: Any content that is referenced from the main content.
- <figcaption>: A caption for a <figure> element.
- <address>: Contact information for the author or owner of the document.
- <hr>: A thematic break or a horizontal rule.
- <tfoot>: Footer of a table.


*****************************************************************************************************
--------------------------------------------Id and Class---------------------------------------------
*****************************************************************************************************


- Id and class are attributes of the html elements/tags.
- Id is unique for each element where as class can be similar to different elements
- An element could have multiple class but only a single id 
- Id is used to uniquely identify the element
- Id is also used in linking elements in a website
- They are mostly used to ease styling the html documents and accessing the elements efficienttly


*****************************************************************************************************
----------------------------------------Video,Audio & Media------------------------------------------
*****************************************************************************************************

#Video

- <video></video> : used to insert the video element in the html
- src : here the source location/path is provided for the file
- controls : this attribute enables the controls to the users
- autoplay : this attribute starts the video directly
- loop : this attribute loops the video one played
- muted : this attribute mutes the video
- poster : gives a thumbnail to the video
- width and height

#Audio

- <audio></audio> : used to insert the audio element in the html
- src : here the source location/path is provided for the file
- controls : this attribute enables the controls to the users
- autoplay : this attribute starts the audio directly
- loop : this attribute loops the audio one played
- muted : this attribute mutes the audio
- preload : specify if and how the audio should be loaded (auto,metadata,none)

#svg

- <svg></svg> : It is a type of vectored media that can also be inserted in html.
- SVG files can also be called from image tag

# iframe
- <iframe></iframe> : used to import a webpage from otheer website into our webpage
- width and height


*****************************************************************************************************
-----------------------------------------Semantics tags----------------------------------------------
*****************************************************************************************************

#header : used to represent the top section of a web page
#footer : used to represent the footer of the web page
#nav : signifies a navigation menu in web page
#main : signifies the main content on web page
#article : indicates self contained piece of content
#figure : used for embedding images
#section : thematic grouping of content
#aside : used for sidebars
#time : used to represent time related imformation


*****************************************************************************************************
-----------------------------------------HTML Entities----------------------------------------------
*****************************************************************************************************

- &lt; : displays a less than symbol <
- &gt; : displays a greater than symbol >
- &amp; : for & symbol
- &copy; : ©
- &nbsp; : for a non breaking space
