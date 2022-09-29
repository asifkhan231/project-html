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

</style>
# HTML Computer Code
- The computer has a unique formatting and text style for displaying the messages related to codes.
- The &#60;code> tag is used to display the computer code on the website. There are number of elements available to mark up computer code using HTML.
## 1.&#60;code> Tag
- The &#60;code> tag in HTML is used to define the piece of computer code. During the creation of web pages sometimes there is a need to display computer programming code. 
>***Synetex***
>```html
><code>code........</code>
>```

>***Example***
>```html
><pre>
><code>
>#include<stdio.h>
>int main() {
>	printf("Hello Geeks");
>}
></code>
></pre>
>```
***output***<br>
![](https://media.geeksforgeeks.org/wp-content/uploads/code1-1.png)

&nbsp;

## 2.The &#60;kbd> Element
- It is a phrase tag and used to define the keyboard input. The text between the &#60;kbd> tag represents similar text should be typed on the keyboard.
- The text enclosed by &#60;kbd> tag is typically displayed in the browser’s default mono-space font.
- It is possible to achieve richer effect with CSS.

>***Example***
>```html
><p>Save the document by pressing <kbd>Ctrl + S</kbd></p>
>```
>[***try it yourself***](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_kbd)

>***Another Example***
>```html
><!DOCTYPE html>
><html>
>	<head>
>		<title>The kbd tag</title>
>		<style>
>			body {
>				text-align:center;
>			}
>		</style>
>	</head>
>	<body>
>		<div class = "gfg">GeeksforGeeks</div>
>		<kbd>A computer</kbd>
>		<kbd>science</kbd>
>		<kbd>portal</kbd>
>	</body>
></html>					
>```
***output***<br>
![](https://media.geeksforgeeks.org/wp-content/uploads/kbd.png)

&nbsp;

## 3.HTML &#60;samp> Element
- It is a phrase tag and used to define the sample output text from a computer program. The HTML Sample Element is used to enclose inline text which represents sample (or quoted) output from a computer program.

>***Example***
>```html
><p>Message from my computer:</p>
><p><samp>File not found.<br>Press F1 to continue</samp></p>
>```
>[try it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_samp)

&nbsp;

## 4.&#60;var>
- It is a phrase tag and used to specify the variable in a mathematical equation or in a computer program. The content of this tag is displayed in the italic format in most of the browsers.

>***Example***
>```html
><!DOCTYPE html>
><html>
>	<head>
>		<title>var tag</title>
>	</head>
>	<style>
>		body {
>			text-align:center;
>		}
>		.gfg {
>			font-size:40px;
>			font-weight:bold;
>			color:green;
>		}
>		.geeks {
>			font-size:25px;
>			font-weight:bold;
>		}
>	</style>
>	<body>
>		<div class ="gfg">GeeksForGeeks</div>
>		<div class = "geeks"><var> Tag</div>
>		<var>GeeksforGeeks Variable</var>
>	</body>
></html>					
>```


&nbsp;

>***Example***
>```
><p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>
>```
>[try it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_var)

&nbsp;

