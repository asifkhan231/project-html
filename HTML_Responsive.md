<style>
    body{
        background-color:black;
        color:b;
        border:4px solid white;
        padding:5px;
        font-style:italic;
        

    }
    ul{
        font-size:15px;
    }
    h1{
        text-align:center;
    }
    /* img{ 
        max-width:300px;
        position:
        
    }
    #img2{

    }
    */
    
</style>
# HTML Responsive
- Responsive Web design is the approach that suggests that design and development should respond to the user’s behavior and environment based on screen size, platform and orientation.
- The practice consists of a mix of flexible grids and layouts, images and an intelligent use of CSS media queries.
- As the user switches from their laptop to iPad, the website should automatically switch to accommodate for resolution, image size and scripting abilities.<br>
***Example:***
![](https://www.w3schools.com/css/img_temp_band.jpg)
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_page)

&nbsp;

## 1. HTML &#60;meta> Settings
- To create a responsive website, add the following &#60;meta> tag to all your web pages.

>***Example***
>```html
><meta name="viewport" content="width=device-width, initial-scale=1.0">
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_viewport)

&nbsp;

- This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.

![](https://www.w3schools.com/css/img_viewport1.png)  ![](https://www.w3schools.com/css/img_viewport2.png)<br>
Without Meta settings.````````````````  &nbsp; With Meta setting

## 2.Responsive Image
- Responsive images are images that scale nicely to fit any browser size.
- If the CSS <mark>width</mark> property is set to 100%, the image will be responsive and scale up and down:

![](https://www.w3schools.com/html/img_girl.jpg)
>***Example***
>```html
><img src="img_girl.jpg" style="width:100%;">
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_image)


&nbsp;


**NOTE**=> If you are using 100% of width property then,  the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the <mark>max-width</mark> property instead.
- If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size:
![](https://www.w3schools.com/html/img_girl.jpg)

>***Example***
>```html
><img src="img_girl.jpg" style="max-width:100%;height:auto;">
>```
>[***try it yourself***]
&nbsp;

## 3.Responsive Text Size
- The text size can be set with a <mark>"vw"</mark> unit, which means the <ins>"viewport width"</ins>.

>***Example***
>```html
><h1 style="font-size:10vw">Hello World</h1>
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_text)

&nbsp;

## 4.Media queries
- In addition to resize text and images, it is also common to use media queries in responsive web pages.
- With media queries you can define completely different styles for different browser sizes.

>***Example***
>```html
><style>
>.left, .right {
>  float: left;
>  width: 20%; /* The width is 20%, by default */
>}
>
>.main {
>  float: left;
>  width: 60%; /* The width is 60%, by default */
>}
>
>/* Use a media query to add a breakpoint at 800px: */
>@media screen and (max-width: 800px) {
 > .left, .main, .right {
 >   width: 100%; /* The width is 100%, when the viewport >is 800px or smaller */
>  }
>}
></style>
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_media_query)

&nbsp;

## 5. W3.CSS Framwork
- W3.CSS is a modern CSS framework with support for desktop, tablet, and mobile design by default.
- W3.CSS is smaller and faster than similar CSS frameworks.
- W3.CSS is designed to be a high quality alternative to Bootstrap.
- W3.CSS is designed to be independent of jQuery or any other JavaScript library.
>***Example***
>```html
><!DOCTYPE html>
><html>
><meta name="viewport" content="width=device-width, initial-scale=1">
><link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
><body>
>
><div class="w3-container w3-green">
>  <h1>W3Schools Demo</h1>
>  <p>Resize this responsive page!</p>
></div>
>
><div class="w3-row-padding">
>  <div class="w3-third">
>    <h2>London</h2>
>    <p>London is the capital city of England.</p>
>    <p>It is the most populous city in the United Kingdom,
>    with a metropolitan area of over 13 million inhabitants.</p>
>  </div>
>
>  <div class="w3-third">
>    <h2>Paris</h2>
>    <p>Paris is the capital of France.</p>
>    <p>The Paris area is one of the largest population centers in Europe,
>    with more than 12 million inhabitants.</p>
>  </div>
>
>  <div class="w3-third">
>    <h2>Tokyo</h2>
>    <p>Tokyo is the capital of Japan.</p>
 >   <p>It is the center of the Greater Tokyo Area,
>    and the most populous metropolitan area in the world.></p>
>  </div>
></div>
>
></body>
></html>
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_w3css)

&nbsp;

## 6.Bootstrap
- Another popular CSS framework is Bootstrap. Bootstrap uses HTML, CSS and jQuery to make responsive web pages.

>***Example***
>```html
><!DOCTYPE html>
><html lang="en">
><head>
><title>Bootstrap Example</title>
><meta charset="utf-8">
><meta name="viewport" content="width=device-width, initial-scale=1">
><link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
><script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
><script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
></head>
><body>
>
><div class="container">
>  <div class="jumbotron">
>    <h1>My First Bootstrap Page</h1>
>  </div>
>  <div class="row">
>    <div class="col-sm-4">
 >     ...
>    </div>
>    <div class="col-sm-4">
>      ...
>    </div>
>    <div class="col-sm-4">
>    ...
>    </div>
>  </div>
></div>
>
></body>
></html>
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_bootstrap)