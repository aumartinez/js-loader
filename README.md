# js-loader
A simple JS loader

## JS loader script

A JS script that will implement a loading animation while a site with a lot of HTML content is loading

## How to implement

Add the call to the script next to the closing <code>&lt;/head&gt;</code> tag.

```html
    <script src="js/loader.js"></script>    
  </head>
  <body>
    <!-- A lot of content to be loaded -->
```
The loader will be called from the JS folder and will add a spinning wheel to the content, once the window.listener fires the load event it will call for the stop() function.

Here is a preview of the loader working:

![Screenshot](https://raw.githubusercontent.com/aumartinez/js-loader/master/img/screenshot.PNG)
