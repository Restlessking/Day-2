Differences between Document and Window Objects:-

    In this article, we will see the Document object & Window object and Key Characteristics of the Document & window Object along with knowing their implementation & the differences between them.

Document Object:-

    => The document object represents a web page that is loaded in the browser. By accessing the document object, 
    
    => we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. 
    
    => The document object can be accessed with a window.document or just document.

Key Characteristics of the Document Object:-

    DOM Structure:-
    
    The document object provides a hierarchical representation of the HTML elements on a webpage, allowing developers to navigate, modify, and manipulate the content dynamically.

    Methods:- 
    
    The document object offers methods like getElementById(), getElementsByClassName(), and querySelector(), enabling developers to select specific elements based on their IDs, classes, or other attributes.

    Properties:- 
    
    Properties such as document.title, document.URL, and document.body provide information about the document's title, URL, and body, respectively.

    Content Manipulation:-
    
    Through the document object, you can dynamically create, modify, or delete elements, attributes, and text content on a webpage.

Syntax:-

    document.propertyname;

Window Object:-

    => The window object is the topmost object of the DOM hierarchy. 
    
    => It represents a browser window or frame that displays the contents of the webpage.
     
    => Whenever a window appears on the screen to display the contents of the document, the window object is created. 

Key Characteristics of the Window Object:-

    Global Scope:-
    
    The window object serves as the global scope in JavaScript, meaning variables and functions declared without the var, let, or const keyword become properties of the window object.

    Browser Information:-
    
    The window object offers properties like window.innerWidth, window.innerHeight, and window.navigator to provide information about the browser's dimensions, navigator object, and other related details.

    Navigation:-
    
    Methods such as window.open(), window.close(), and window.location allow developers to control browser navigation, open new windows or tabs, and manipulate the current URL.

    Timers:-
    
    The window object provides functions like setTimeout(), setInterval(), and clearTimeout() to manage time-based operations and execute code asynchronously.

Syntax:-

    window.propertyname;

Difference between document and window:-

Document:-

    => It represents any HTML document or web page that is loaded in the browser.

    => It is loaded inside the window.

    => It is the object of window property.

    => All the tags, elements with attributes in HTML are part of the document.

    => We can access the document from a window using the window. document

    => The document is part of BOM (browser object model) and dom (Document object model)

    => Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title

Window:-

    => It represents a browser window or frame that displays the contents of the webpage.  

    => It is the very first object that is loaded in the browser.

    => It is the object of the browser.

    => Global objects, functions, and variables of JavaScript are members of the window object.

    => We can access the window from the window only. i.e. window.window

    => The window is part of BOM, not DOM.

    => Properties of the window object cannot be accessed by the document object.