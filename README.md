Follow these instructions exactly for pretty much everything:

The Javascript goes at the bottom of your page. Do not make a separate .js file like you would a style.css file. Things will get way too fucking confusing. These parts should be marked by <script></script> brackets.

If you are going to put .css on every single page you create, make sure it is at the top. You can also create a separate .css file for certain pages or batches of pages if you would like to try and keep things more organized. As long as you put <link rel="stylesheet" href="style.css">  in the <head> of your HTML. It will look something like this:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Page</title>

    <link rel="stylesheet" href="path to style.css goes here">
</head>

<body>
    <h1>Hello world</h1>
</body>
</html>

Make sure that you have the path setup right. For example, if you want a stylesheet to only effect the pages in a folder called "blogs". The files in this folder will be named "blog_page1.html", "blog_page2.html" or whatever the fuck. Within this folder, <link rel="stylesheet" href="style.css"> will work if you name your stylesheet file "style.css", but if you don't want to copy paste this style into another folder, you can change it to <link rel="stylesheet" href="blogs/style.css">.

I hope that makes sense.

I highly recommend you keep style.css files for each page or batch of pages so that things don't end up cluttery and fucky to edit later. I'm not going to hold your hand through every single process, but I'm going to assume that anyone screwing around with HTML and stuff for any reason has some decent understanding on how important copying and pasting is. Save your work as you go, have multiple drafts, keep snippets of code you need in other .txt files to use, blah blah blah. I will do some more n00b level instructions on setting up paths in a separate file which you will see somewhere over there in the sidebar.

Coords or coordinates are used for mapping images. This is a CSS positioning system. It can be used for creating clickable areas or areas that display videos and images. I don't expect you to map your own coords, but you will have to copy and past them in your CSS or in the jscript at times. These numbers will look like "201,34,567,1923" and things like that. Do not fuck with these numbers.

Everything should be pretty straight forward, it's literally just copying and pasting shit where it goes.
