# HTML Boilerplate Code Explained

![computer screen with javascript](/public/html-boilerplate.avif)

This guide will provide a detailed explanation of a standard HTML boilerplate code. This is the foundation for most web pages and understanding each part will help you get started in web development.

## What is HTML?

> HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).
>
> Reference:
> [MDN Web Docs | HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

## HTML Boilerplate

Here is a basic example of an HTML boilerplate:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="css/style.css" />
    <script defer src="js/app.js"></script>
  </head>
  <body></body>
</html>
```

### Let's Break It Down

1.  ### **`<!DOCTYPE html>`**:

     -  This declaration defines the document type and version of HTML. Here, it specifies HTML5, the latest standard.

2.  ### **`<html lang="en">`**:

    - `<html>`: This is the root element that wraps all the content on the entire page. Any tag that is created will be inside of this overarching parent element

    - `lang="en"`: This attribute helps define the language of your document.

3.  ### **`<head>`**:

    - This element contains meta-information about the document that is not displayed on the web page itself.

    - **`<meta charset="UTF-8" />`**:

    > UTF-8 (UCS Transformation Format 8) is the World Wide Web's most common character encoding. Each character is represented by one to four bytes. UTF-8 is backward-compatible with ASCII and can represent any standard Unicode character.
    >
    > Reference:
    > [MDN Web Docs | UTF-8](https://developer.mozilla.org/en-US/docs/Glossary/UTF-8)

    - **`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`**: This helps control the page's dimensions and scaling to fit different device screens (responsive design).

    - **`<title>Document</title>`**: Sets the title of the document, which is seen in the browser's title bar or tab.

4.  ### **`<link rel="stylesheet" type="text/css" href="css/style.css" />`**:

    - Links a CSS file for styling the HTML content. It's stored in a `css` folder and named `style.css`. This ensures your styles appear on your page if you do not insert style tags or inline-css in your html body.

5.  ### **`<script defer src="js/app.js"></script>`**:

    - Links a JavaScript file that adds interactivity to the page. The `defer` attribute ensures that the script is executed only after the HTML document has been fully parsed. Alternatively, you can just place your Javascript file at the end of your body tag if you do not wish to use `defer`.

6.  ### **`<body>`**:
    - This element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, etc., that are displayed on the web page.

> **Tip**: A shortcut to generate HTML boiler plate code is to type an exclaimation point in your html file and then press enter. This will generate the basic boilerplate we discussed, except it will not contain the `<script>` tag for the Javascript or the `<link>` tag for the css

For more detailed information on each HTML element and attribute, you can check out the [MDN Web Docs | HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).
