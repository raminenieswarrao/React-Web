**URL: React.Development.JS**

The URL https://unpkg.com/react@17/umd/react.development.js points to the development version of React v17, hosted on the unpkg content delivery network (CDN). 
This file is in the UMD (Universal Module Definition) format, which means it can be used in various JavaScript module systems such as CommonJS, and AMD, and as a global variable in the browser.

**URL: React-DOM.Development.JS**

The URL https://unpkg.com/react-dom@17/umd/react-dom.development.js points to the development version of ReactDOM v17, hosted on the unpkg content delivery network (CDN). 
ReactDOM is a package that provides DOM-specific methods that can be used at the top level of a web app to enable an efficient way of managing the DOM.

**Date: 7/31/2024** 

HTML <body> Tag:

The <body> tag defines the body of the HTML document. It contains all the content that is displayed on the web page.
<div id="root"></div>:

This <div> element is a container where the React application will be rendered. The id="root" attribute allows React to target this specific element for rendering.
<h1>Getting Started with React</h1>:

This is a standard HTML heading element that displays the text "Getting Started with React". It is included directly in the HTML and will be rendered by the browser as part of the initial page load.
<script type="text/javascript">...</script>:

This <script> tag contains JavaScript code. The type="text/javascript" attribute specifies the scripting language used.

React and ReactDOM
Inside the script tag, the following JavaScript code is used to render a React component:

javascript
Copy code
ReactDOM.render(
    React.createElement("h1", null, "Getting Started with React. Used the Javascript"),
    document.getElementById("root")
);
Explanation
ReactDOM.render:

This method is used to render React elements into the DOM. It takes two arguments: the React element to render and the DOM element to render it into.
React.createElement("h1", null, "Getting Started with React. Used the Javascript"):

React.createElement is a method used to create a React element. In this case, it creates an h1 element with no props (null) and the text content "Getting Started with React. Used the Javascript".
Arguments:
"h1": The type of element to create.
null: The props to pass to the element (none in this case).
"Getting Started with React. Used the Javascript": The children (content) of the element.
document.getElementById("root"):



This method returns the DOM element with the id root. It is used as the container for rendering the React element created above.
