# HTML Boilerplate

## Introduction

Boilerplate is the basic structure HTML documents have

## Creating an HTML File

To create a new HTML file you sould use the extension .html like index.html that will have the homepage of the website

## Doctype

The doctype tells the browser what version of HTML should use to render the document.

This is a HTML4 version Doctype
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

## HTML Element

After declare the Doctype we need to provide an <html> element known as the root element

```
<!DOCTYPE html>
<html lang="en">
</html>
```

lang specifies the language of the text content

## Head Element

The <head> element is where we put our meta-information about the webpage. Inside it we should not use any html element that displays content.

## The Charset Meta Element

It is used for the charset encoding of the webpage

```
<meta charset="utf-8">
```
It is important because it ensures that the webpage will display special symbols and characters from different languages.

## Title Element

This element is used to give a webpage human readable title which is displayed in our webpage browser tab.

```
<title>My Nice Website</title>
```

If we don't include a title element, the browser will use the file name as the default

## Body Element

This element `<body>` is where the content of the website is displayed

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Cool Website</title>
    </head>
    <body>
        <h1>Hello World!</h1>
    </body>
</html>
```