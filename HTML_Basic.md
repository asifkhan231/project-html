<style>
   body{
   background-color:gray;
   color:black
   }
</style>
# 1. HTML
- HTML stands for **hyper text markup language** .
- It use to create web pages.
- HTML tell the browser what to show and how show.
- It describe the structure of a web page.

### Simple Syntex
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
   ```

### Example Explaination

- &#60;!DOCTYPE html&#62; ==> It defines that this is a HTML document.<br>
- &#60;Html&#62; ==> This Element is a root Element of this HTML document.<br>
- &#60;Head&#62; ==> Head contain meta information off HTML page.<br>
- &#60;Title&#62; ==> Title element gives title to the web page.<br>
- &#60;Body&#62; ==> Body element defines the document's body, and is    a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.<br>
- &#60;h1&#62; ==> It defines larg heading.<br>
- &#60;p>  ==> it indicates to the paragraph.<br>

&nbsp;

# 2. HTML Basic Examples
 ## Document
   All HTML documents must start with a document type declaration: &#60;!DOCTYPE html>.<br>

The HTML document itself begins with &#60;html> and ends with &#60;/html>.<br>

The visible part of the HTML document is between &#60;body> and &#60;/body>.<br>

> ***Example***
>```html
><!DOCTYPE html>
><html>
><body>
>
><h1>My First Heading</h1>
><p>My first paragraph.</p>
>
></body>
></html>
>```
>
>### [[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_document "Example Code")
&nbsp;

## The &#60;!DOCTYPE html>  Declaration
- The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.<br>
- It must only appear once, at the top of the page.

> &#60;!DOCTYPE html>

&nbsp;

## HTML Headings
- Headings in HTML define from &#60;h1> to &#60;h6> according to thier importance.<br>
- &#60;h1> is the most important heading and &#60;h6> is the least important heading.<br>
&nbsp;
>***Example***
>```html
><h1>This is heading 1</h1>
><h2>This is heading 2</h2>
><h3>This is heading 3</h3> 
>```
>
>### [[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_headings "Example Code").

&nbsp;
 ## HTML Paragraphs
 - Paragraphs in HTML defines by &#60;p>.<br>
 >***Example***
 >```html
 ><p>This is a paragraph.</p>
 ><p>This is another paragraph.</p>
 >```
 >[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic_paragraphs "Example Code")

&nbsp;
 ##  HTML Links
 - HTML links defines by  &#60;a>.<br>
 - ***href*** attribute contain the url of any link.
 >***Example***
 >```html
 > <a href="https://www.w3schools.com">This is a link</a>
 >```
 >.
 

 &nbsp;

 ## HTML Images
 - HTML images defines by &#60;img> element.<br>
 -  ___src___ attribute conatins the derictory of image.
 - We can give style to our image like size width heigth etc. by Style attribute.
 >***Example*** 
 >```html
 >  <img src="/img/font.jpg" alt="font" >
 >```
>.
&nbsp;

# 3. HTML Elements
- __An HTML Element define with a start tag (<>), the content and with end tag(>).__
- Example:-
     - <tag_name>content goes here...</tag_name>

>Example
>```html
>  <p>This  is First Paragraph.</p>
>  <h1>This is First heading.</h1>
> <h2>This is second heading.</h2>
> <br>
>```
>.

## Nested HTML Element 
- HTML elements can be nested (this means that elements can contain other elements).

- All HTML documents consist of nested HTML elements.

- The following example contains four HTML elements (&#60;html>, &#60;body>, &#60;h1> and &#60;p>,&#60;strong>):

>***Example***
>```html
> <!DOCTYPE html>
> <html>
>  <head>
>    <title>Document</title>
>  </head>
>   <body>
>   <h1>HEADING 1</h1>
>     <p>This is <strong>Paragraph</strong> No. 1</p>
>  </body>
> </html>
>```
>.

## Empty HTML Element 
- Element that does not have an end tag is know as Empty Element.
>***Example***
>```html
><br/>
><hr/>
>```
>.

&nbsp;

# 4. HTML Attribute

- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"

>***Example***
>```html
><p style="color:gray;">This will written in gray color.</p>
>```
>.

&nbsp;

## The href Attribute
- The hyper link tag &#60;a> contain ***href*** Attribute. Andd this attribute contain URl of Any web page the link goes to.
>***Example***
>```html
><a href="https://www.instagram.com/_asifkhann_/">
>```
>[Asif khan](https://www.instagram.com/_asifkhann_/ "Asif khan's Instagram Account")  

&nbsp;

## The src Attributes
- src attribute mainly use in &#60;img> element to Show the directory of the image.
>***Example***
>```html
><img src="/img/font1.jpg">
>```
>.

- There are types of url in src attribute:
   1. Absolute url:- Link of a &nbsp;**External Image** that took from another website.Example:- https://wallpapers.com/wallpapers/black-and-white-office-desk-desktop-i5qgtxi9v4hw81fv.html?embed=true.

   2.Relative url:- Links to an &nbsp;image that is hosted within the website.Example:- /img/font1.jpg.

&nbsp;
   ## The width and height Attributes
   - The &#60;img> tag should also contain width and height attribute , which decides the width and height of image.
   >***Example***
   >```html
   > <img src="/img/font.jpg" width="400px" height="500px">
   >```
   >.

&nbsp;

## The alt Attribute
 - The alt attribute gives a alternat name or text of image, and this is aslo something that &#60;img> tag should have.

 >***Example***
 >```html
 > <img src="/img/avengers.jpg" alt="avengers">
 >```
 >.

 &nbsp;

 ## The style Attribute
 - Style attribute specifies the style of img , text, paragraph , heading etc. (such as color, font, size, font-style etc.)
> ***Example***
> ```html
><p style="color:blue; font-size:5px">this paragraph will be written in blue color.</p>
>```
>.

&nbsp;
## The title Attribute
- This attribute gives additional information about the element.
>***Example***
>```html
><p title="this is a important paragraph">The first paragraph.</p>
>```
>.


&nbsp;

# 5. Headings
- HTML headings are titles or subtitles that you want to display on a webpage.
- HTML headings defines by &#60;h1> to &#60;h6>,the most important heading defines by &#60;h1> and the least important heading defines by &#60;h6>.
- Each HTML heading have their own size by defualt.
>***Example*** 
>```html
><h1>Heading 1</h1>
><h2>Heading 2</h2>
><h3>Heading 3</h3>
><h4>Heading 4</h4>
><h5>Heading 5</h5>
><h6>Heading 6</h6>
>```
>.

&nbsp;

## Heading style
- we can add style on html headings(such as color , boldness, highlighting etc.).

>***Example***
>```html
><h1 style="color:gray; font-style:italic; font-size:10px;">
>```
>.

&nbsp;

# 6. Paragraphs
- A paragraph always starts on a new line, and is usually a block of text.
- A html paragraph defines by &#60;p>. 
>***Example*** 
>```html
><p>Hello, This is first HTML paragraph.</p>
><p>And This is second paragraph.</p>
>```
>.

&nbsp;

## HTML display
- It's difficult to know, how html paragraph will be dispayed . Coz HTML will Autometically remove Extra space and extra lines from paragraps.
- you cannot change the display by adding extra spaces or extra lines in your HTML code.
>***Example***
>```html
><p>
>This paragraph
>contains a lot of lines
>in the source code,
>but the browser
>ignores it.
></p>
>
><p>
>This paragraph
>contains         a lot of spaces
>in the source         code,
>but the        browser
>ignores it.
></p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_paragraphs2 )

&nbsp;

## The &#60;pre> Element
- The html &#60;pre> element stands for preformatted text.
- The content inside the &#60;pre> element will display in the same format in which you write the content in element.
>***Example***
>```html
><pre>
>  My Bonnie lies over the ocean.
>
>  My Bonnie lies over the sea.
>
>  My Bonnie lies over the ocean.
>
>  Oh, bring back my Bonnie to me.
></pre> 
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_pre)

&nbsp;

# 7. HTML style
-  The style is a html attribute which is  use to add style to an Element,(such as color,size, font,etc.).
>***Example***
>### <font color="red"> I am Red. </font>
>
>### <font color="blue">I am Blue.</font>
>
>## **I am Big**
&nbsp;
>### code
>```html
><p style="color:red">I am Red.</p>
><p style="color:blue">I am Blue</p>
><p style="font-size:50px">I am Big.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_intro)

&nbsp;

## Background Color
- Background color  property is used to manage the color of background.
- 
>***Example***
>```html
><body>
>
><h1 style="background-color:powderblue;">This is a heading</h1>
><p style="background-color:tomato;">This is a paragraph.</p>
>
></body>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_background-color2)

&nbsp;
## Text color
- HTML text color property is used to style the text with different colors.
>***Example***
>```html
><h1 style="color:blue;">This is a heading</h1>
><p style="color:red;">This is a paragraph.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_color)

&nbsp;
## Font And Text-Size
- The CSS font-family property defines the font to be used for an HTML element:
- The text size property defines the size the text.
>***Example***
>```html
><h1 style="font-family:verdana;">This is a heading</h1>
><p style="font-family:courier;">This is a paragraph.</p>
>
>
><h1 style="font-size:300%;">This is a heading</h1>
><p style="font-size:160%;">This is a paragraph.</p>
>
>```
>[Font-family code](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_font-family)<br/>
>[Text size code](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_font-size)

&nbsp;
## Text Alignment
- Text alignment property defines the horizontel alignment of text.
>***Example***
>```html
><h1 style="text-align:center;">Centered Heading</h1>
><p style="text-align:center;">Centered paragraph.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_styles_text-align)

&nbsp;

# 8. HTML Text formatting
- The text formatting property allows HTML to format text in defferent shape and size.
>***Example***
>
> *This text is itelic.*<br>
> **This text is bold.**<br>
> ***This text is bold itelic.***<br>
> This is <sub>subcript</sub> and  this is <sup>supercript</sup>.

&nbsp;

## HTML Formatting Elements
- &#60;b> - Bold text
- &#60;strong> - Important text
- &#60;i> - Italic text
- &#60;em> - Emphasized text
- &#60;mark> - Marked text
- &#60;small> - Smaller text
- &#60;del> - Deleted text
- &#60;ins> - Inserted text
- &#60;sub> - Subscript text
- &#60;sup> - Superscript text

>***Example*** 
>```html
><b>This text is bold</b>
><strong>This text is important!</strong>
><i>This text is italic</i>
><em>This text is emphasized</em>
><small>This is some smaller text.</small>
><p>Do not forget to buy <mark>milk</mark> today.</p>
><p>My favorite color is <del>blue</del> red.</p>
><p>My favorite color is <del>blue</del> ><ins>red</ins>.</p>
><p>This is <sub>subscripted</sub> text.</p>
><p>This is <sup>superscripted</sup> text.</p>
>```
>.

&nbsp;

# 9.HTML Quotation and Citation Elements

## The &#60;Blockquote>
- The HTML &#60;blockquote> element is used to define the section that is quoted from another source.<br>
- Browsers usually indent &#60;blockquote> elements.
>***Example*** 
>```html
><p>Here is a quote from WWF's website:</p>
><blockquote cite="http://www.worldwildlife.org/who/index.html">
>For 50 years, WWF has been protecting the future of nature.
>he world's leading conservation organization,
>WWF works in 100 countries and is supported by
>1.2 million members in the United States and
>close to 5 million globally.
></blockquote>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_blockquote)

&nbsp;

## HTML &#60;q> Element
- HTML &#60;q> is used to quote the small section.(like this "section").
>***Example***
>```html
><p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_q)

## HTML &#60;abbr>
- HTML &#60;abbr> element is stands for abbreviation.
- it show the abbreviation or acronym of any word like;HTML, CSS, WHO, MR.,dr.etc
use title attribute to add information.
>***Example***
>```html
><p>The <abbr title="World Health Organization">WHO</abbr> was fonded in 1948.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_abbr)

&nbsp;

## HTML &#60;address> Element
- The HTML <address> tag defines the contact information for the author/owner of a document or an article.

- The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

- The text in the <address> element usually renders in italic, and browsers will always add a line break before and after the <address> element.
>***Example***
>```html
><address>
>Written by John Doe.<br>
>Visit us at:<br>
>Example.com<br>
>Box 564, Disneyland<br>
>USA
></address>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_address)

&nbsp;

## HTML &#60;cite> Element
- HTML &#60;cite> element defines the title fo the any book , poem, song, painting, movie etc.
- A person's name does not include in this element.
>***Example***
>```html
><p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_cite)

&nbsp;

## HTML &#60;bdo> Element
- &#60; bdo> element stands for Bi-directional override.
- It just override the direction.
>***Example*** 
>```html
><bdo dir=""rtl>This will be written in right to left direction.</bdo>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_bdo)

&nbsp;

# 10.HTML Comments
- HTML comments help us to understand the html code , they  are not displayed in the browser.
- We can write a comment by following this syntex
    - &#60;!-- comments -->
>***Example***
>```html
><!-- This is a comment -->
>
><p>This is a paragraph.</p>
>
><!-- Remember to add more information here -->    
>```
>.

&nbsp;

# 11. Color
- Colors in any html element can be appy by just thier name or , by RGB , HEX, HSL
- any color you can use by just it's name.
  - like :-
  <pre>
        - <h3 style="background-color:tomato; width:60px; margin:6px; padding: 5px; text-align:center;">Tomato</h3>  <h3 style="background-color:blue; width:60px; margin:6px; padding: 5px;text-align:center;">Blue</h3> <h3 style="background-color:cyan; width:60px; margin:6px; padding: 5px;text-align:center;">Cyan</h3> <h3 style="background-color:gray; width:60px; margin:6px; padding: 5px;text-align:center;">Gray</h3> <h3 style="background-color:dodgerblue; width:100px; margin:6px; padding: 5px;text-align:center;">Dodgerblue</h3> <h3 style="background-color:slateblue; width:100px; margin:6px; padding: 5px;text-align:center;">Slateblue</h3>   <h3 style="background-color:mediumseagreen; width:140px; margin:6px; padding: 5px;text-align:center;">MediumSeaGreen</h3>   <h3 style="background-color:yellow; width:100px; margin:6px; padding: 5px;text-align:center;">Yellow</h3> 
        etc</pre>

&nbsp;

## Background-Color
- You can set any background color for html element.<br>
Example:-
  <h4 style="background-color:purple; text-align:center;">Hello World!</h4>       
  <h4 style="background-color:lightgray; color:black; text-align:center;font-size:20px">he CSS font-family property defines the font to be used for an HTML element. The text size property defines the size the text.</h4>  

&nbsp;
>### Exaample
  >```html
  ><h1 style="background-color:DodgerBlue;">Hello World</h1>
  ><p style="background-color:Tomato;">Lorem ipsum...</p>
  >```
  >[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_color_background)

  &nbsp;

  ## Text Color
  - You can add any color to your text either by it's name or by it's color code.
  - #### __Example__
      <font color="orange">this text is written in Orange color.</font><br>
      <font color="lightblue">This is wrritten in Light blue color.</font>

>***Example***
>```html
><h1 style="color:Tomato;">Hello World</h1>
><p style="color:DodgerBlue;">Lorem ipsum...</p>
><p style="color:MediumSeaGreen;">Ut wisi enim...</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_color_text)

&nbsp;

## Border Color
- You can set color of borders.
- __Example__
   <h3 style="border: 3px solid darkgreen; text-align:center;">Dark Green</h3>
   <p style="border:5px solid darkred; text-align:center;">Dark Red</p>

>***Example***
>```html
><h1 style="border:2px solid Tomato;">Hello World</h1>
><h1 style="border:2px solid DodgerBlue;">Hello World</h1>
><h1 style="border:2px solid Violet;">Hello World</h1>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_color_border)

&nbsp;

 ## i.**RGB(Red, Green, Blue)**
 - RGB is a type of color code, We can use mix values of Red, Green and blue to use diffenet color.
 - Each value of (Red, Green , Blue) define intensity of color, we can set by value between  0-255 each(255, 255, 255), This means that there are 256 x 256 x 256 = 16777216 possible colors!
-  for example , rgb(255, 0, 0) is red color value , coz red gets highest value (255)where other two green and blue get (0,0) each.
- Like this, to display white color just set all rgb value high, rgb(255, 255, 255).
#***Example***:-
```html
 <p style="color:rgb(255,255,255);">This text is in white color.</p>
 <p style="color:rgb(0,0,0);">This text is in black color.</p>
 ```
 #### Output:-
 <p style="color:rgb(255,255,255);font-size:30px;">This text is in white color.</p>
 <p style="color:rgb(0,0,0); font-size:30px;">This text is in black color.</p>

> 📝 Note: [To see rgb color code list Click here](https://www.rapidtables.com/web/color/RGB_Color.html)

## ii. HEX
- HEX stands for hexadecimal number codes, HEX code is written like this  #rrggbb where rr is red , gg is green and bb is blue .HEX code is between 00 to ff.
- For example:- #ff0000 is red , coz rr is set to it's highest value ff and other two get 00 each.
- #00ff00 is green, coz gg is set to it's highest value ff and  other two set to 00.
- #0000ff is blue, coz bb is set to it's highest value and other two is set to 00 each.
- To display white color just set all color values high :- #ffffff.
- to display black color just set all color values to low :- #000000.
***Example:-***
```html
<h4 style="background-color:#ffffff; text-align:center; width:150px;padding:10px">White</h4>
<h4 style="background-color:#000000; text-align:center; width:150px;padding:10px">Black</h4>
<h4 style="background-color:#6a5acd; text-align:center; width:150px;padding:10px">violet</h4>
<h4 style="background-color:#ee82ee; text-align:center; width:150px;padding:10px">lightpink</h4>
<h4 style="background-color:#0000ff; text-align:center;width:150px;padding:10px">Darkblue</h4>
```
***output:-***
<h4 style="background-color:#ffffff; text-align:center; width:150px;padding:10px">White</h4>
<h4 style="background-color:#000000; text-align:center; width:150px;padding:10px">Black</h4>
<h4 style="background-color:#6a5acd; text-align:center; width:150px;padding:10px">violet</h4>
<h4 style="background-color:#ee82ee; text-align:center; width:150px;padding:10px">lightpink</h4>
<h4 style="background-color:#0000ff; text-align:center;width:150px;padding:10px">Darkblue</h4>

> 📝 Note: [To see hex color code list Click here](https://www.color-hex.com/)

&nbsp;

## iii.HSL
- HSL stands for Hue Saturation Lightness,
- HSL value will be denoted like this hsl(hue, saturation, lightness)
- Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

- Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color.

- Lightness is also a percentage value. 0% is black, and 100% is white.

***Example:-***
```html
<h3 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h3>
<h3 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h3>
<h3 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h3>
<h3 style="backgound-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h3>
<h3 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h3>
<h3 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h3>
```
***Output:-***
<h3 style="background-color:hsl(0, 100%, 50%);text-align:center; width:180px;padding:10px">hsl(0, 100%, 50%)</h3>
<h3 style="background-color:hsl(240, 100%, 50%);text-align:center; width:180px;padding:10px">hsl(240, 100%, 50%)</h3>
<h3 style="background-color:hsl(147, 50%, 47%);text-align:center; width:180px;padding:10px">hsl(147, 50%, 47%)</h3>
<h3 style="background-color:hsl(300, 76%, 72%);text-align:center; width:180px;padding:10px">hsl(300, 76%, 72%)</h3>
<h3 style="background-color:hsl(39, 100%, 50%);text-align:center; width:180px;padding:10px">hsl(39, 100%, 50%)</h3>
<h3 style="background-color:hsl(248, 53%, 58%);text-align:center; width:180px;padding:10px">hsl(248, 53%, 58%)</h3>

>[to see HSL color code list click here](https://www.december.com/html/spec/colorhsl.html)

&nbsp;

# 12.CSS
- CSS stands for **Cascading Style Sheet**.
- It is used to format layout of multiple web pages all at time.
- Css saves time and lot of work.
- With css we can control font-style, color, background-color, imgaes, border and many more.<br/>
***Example***
```html
<!DOCTYPE html>
<html>
<head>
<Style>
body{
   background-color:"cyan";
}
h1{
   background-color:"lightgreen";
   text-align:"center";
}
p{
   color:#"ee82ee";
   font-size="15px";

}
</style>
</head>
<body>
   <h1>Hello World!</h1>
   <p>Hello guys, This is Asif Khan And I'm from Nagour Rajasthan. Currently I'm pursuing my B.Tech degree in Computer Science.</p>
</body>
</html>
```
***Output***
<pre style="background-color:cyan;">
   <h1 style="background-color:lightgreen;
   text-align:center;">Hello World!</h1>
   <p style="color:green;
   font-size:30px;">Hello guys, This is Asif Khan And I'm from Nagour Rajasthan. Currently I'm pursuing my B.Tech degree in Computer Science.</p>
</pre>

&nbsp;

-Thier is three ways to use Css.
 1. Internal:- using style element inside the head part of the html code.
 2. Extarnal:- Using style element by creating a css file and linking it to the html file.
 3. Inline :- Using style element inside the element like (&#60;p>, &#60;h>etc).

 -The most common way to add CSS, is to keep the styles in external CSS files. 

 &nbsp;

 ## 1. Inline CSS
 - An inline CSS is used to apply a unique style to a single HTML element.

- An inline CSS uses the style attribute of an HTML element.

___Example___
>```
><h1 style="color:blue;">A Blue Heading</h1>
>
><p style="color:red;">A red paragraph.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_css_inline)

&nbsp;

## 2.Internal CSS
- An internal CSS is used to define a style for a single HTML page.

- An internal CSS is defined in the &#60;head> section of an HTML page, within a &#60;style> element.

>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><style>
>body {background-color: powderblue;}
>h1   {color: blue;}
>p    {color: red;}
></style>
></head>
><body>
>
><h1>This is a heading</h1>
><p>This is a paragraph.</p>
>
></body>
></html>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_css_internal)

&nbsp;

## 3.External CSS
- An external style sheet is used to define the style for many HTML pages.

- To use an external style sheet, add a link to it in the <head> section of each HTML page.
>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
>  <link rel="stylesheet" href="stylesheet.css">
></head>
><body>
>
><h1>This is a heading</h1>
><p>This is a paragraph.</p>
>
></body>
></html>
>```
**NOTE** => The external style sheet can be written in any text editor. The file must not contain any HTML code, and must be saved with a .css extension.

>stylesheet.css
>```css
>body {
>  background-color: powderblue;
>}
>h1 {
> color: blue;
>}
>p {
>  color: red;
>} 
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_css_external)

&nbsp;

==> Now you can use any kind of style for your element with css.(such as color, font-size, background-color, border, margin, padding, font-family.etc.)

&nbsp;

# 13.HTML Links
- HTML links are hyperlinks.

- You can click on a link and jump to another document.

- When you move the mouse over a link, the mouse arrow will turn into a little hand. 

- The HTML &#60;a> tag defines a hyperlink.
>***Syntex***
>```html
><a href="url">link text</a>
>```
- The most important attribute of the &#60;a> element is the href attribute, which indicates the link's destination.

>***Example***
>```html
><a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_w3schools)

&nbsp;

**NOTE**==>By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red

&nbsp;

## The Target attribute
- The target attribute defines where to open the linked file.
- The target attribute can have one of the following values:

    - _self - Default. Opens the document in the same window/tab as it was clicked
    - _blank - Opens the document in a new window or tab
    - _parent - Opens the document in the parent frame
    - _top - Opens the document in the full body of the window

    >***Example***
    >```html
    ><a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
    >```
    >[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_target)

&nbsp;

## Relative And Absolute links
- Absolute URL's => It is full web address of any different web page including (https://www.). 
- Relative URL's => It  is address of local web page or a web page which come into the same website.(without https://www.).

>***Example***
>```html
><h2>Absolute URLs</h2>
><p><a href="https://www.w3.org/">W3C</a></p>
><p><a href="https://www.google.com/">Google</a></p>>
>
><h2>Relative URLs</h2>
><p><a href="html_images.asp">HTML Images</a></p>
><p><a href="/css/default.asp">CSS Tutorial</a></p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links)

&nbsp;

## Email Address

- You can link  your email address by using <ins>Mailto:</ins> property inside the href attribute.

>***Example***
>```html
><a href="mailto:someone@example.com">Send email</a>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_email)

&nbsp;

## Button as a link
- You can a button as a link ,  when ever  you click the button it will shift you to the linked page or file.
- thier is some javascript tricks that you have add on it.
>***Example***
>```html
><button onclick="document.location='default.asp'">HTML Tutorial</button>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_button_element)

&nbsp;

## Link Color
By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red

you can change link state color,with css
>***Example***
>```html
><style>
>a:link {
>  color: green;
>  background-color: transparent;
>  text-decoration: none;
>}
>
>a:visited {
>  color: pink;
>  background-color: transparent;
>  text-decoration: none;
>}
>
>a:hover {
>  color: red;
>  background-color: transparent;
>  text-decoration: underline;
>}
>
>a:active {
>  color: yellow;
>  background-color: transparent;
>  text-decoration: underline;
>}
></style>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_colors)

&nbsp;

## Link Button's style
- The link button can also be styled like when we move our mouse no it we will change its color.

>***Example***
>```html
><style>
>a:link, a:visited {
>  background-color: #f44336;
>  color: white;
>  padding: 15px 25px;
>  text-align: center;
>  text-decoration: none;
> display: inline-block;
>}
>
>a:hover, a:active {
>  background-color: red;
>}
></style>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_button)

&nbsp;

## HTML Bookmark
- Bookmarks can be useful if a web page is very long.

- To create a bookmark - first create the bookmark, then add a link to it.

- When the link is clicked, the page will scroll down or up to the location with the bookmark.

- First , use id attribute to creat a bookmark.
>***Example***
>```html
><h2 id="C4">Chapter 4</h2>
>```

then, Add a link to the bookmark with in the same page.
>```
><a href="#C4">Jump to Chapter 4</a>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_links_bookmark)

&nbsp;

# 14.HTML Tables
- HTML tables allow web developers to arrange data into rows and columns.
- A HTML table contains table header, table cells inside rows and  columns.
 
 >***Example***
 >```html
 ><table>
 > <tr>
 >   <th>Name</th>
 >   <th>City</th>
 >   <th>College</th>
 > </tr>
 > <tr>
 >   <td>Asif Khan</td>
 >   <td>Bikaner</td>
 >  <td>UCET</td>
 ></tr>
 > <tr>
 >   <td>Ayush Pathak</td>
 >   <td>Baliya</td>
 >  <td>UCET</td>
 ></tr>
 > <tr>
 >   <td>Anish Saini</td>
 >   <td>Baggar</td>
 >  <td>UCET</td>
 ></tr>
 ></table>
 >```

 ***OUTPUT***
| Name            | city          |college   |
| :---------      | :-----:       |   -----: |
|Asif Khan        | Bikaner       |UCET      |
|Ayush Pathak     | Baliya        |UCET      |
|Anish Sini       | Baggar        |UCET      |

&nbsp;

### All tag explanation
1. &#60;tr> - tr  stands for table rows , by &#60;tr> creat table rows.
2. &#60;td> - td stands for table  data, td tag defines table cells.
3. &#60;th>- th stands for table headers, sometimes you want your cells to be table header cells. 

> ***Example***
>```html
><table>
>  <tr>
>    <th>Person 1</th>
>    <th>Person 2</th>
>    <th>Person 3</th>
>  </tr>
>  <tr>
>    <td>Emil</td>
>    <td>Tobias</td>
>   <td>Linus</td>
>  </tr>
>  <tr>
>    <td>16</td>
>    <td>14</td>
>    <td>10</td>
 > </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table6)

&nbsp;

## 1.Table Border
- We can add diffenet style and shape to the table border.(by css)
- To add a border, use the CSS border property on table, th, and td elements:
>***Example***
>```css
>table, th, td {
>  border: 1px solid black;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_border)

&nbsp;

## 2.Collapsed Table Border
 - To avoid having double borders like in the example above, set the CSS border-collapse property to collapse.

- This will make the borders collapse into a single border:

>***Example***
>```css
>table, th, td {
>  border: 1px solid black;
>  border-collapse: collapse;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_collapse)

&nbsp;

## 3. Table background-color
- If you set a background color of each cell, and give the border a white color (the same as the document background), you get the impression of an invisible border:
>***Example***
>```css
>table, th, td {
>  border: 1px solid white;
>  border-collapse: collapse;
>}
>th, td {
>  background-color: #96D4D4;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_border_style)

&nbsp;

## 4.Round Table Border
- With the border-radius property, the borders get rounded corners.
>***Example***
>```
>table, th, td {
>  border: 1px solid black;
>  border-radius: 10px;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_border_round1)

&nbsp;

## 5.Type of borders
dotted     
dashed     
solid     
double     
groove     
ridge     
inset     
outset     
none     
hidden

&nbsp;

## 6. Table Size
- HTML tables can have different sizes for each column, row or the entire table.
- Use the style attribute with the width or height properties to specify the size of a table, row or column.

>***Example*** For  Table Row Size
>```html
><table style="width:100%">
>  <tr>
>    <th>Firstname</th>
>    <th>Lastname</th>
>    <th>Age</th>
>  </tr>
>  <tr style="height:200px">
>    <td>Jill</td>
>    <td>Smith</td>
>    <td>50</td>
>  </tr>
>  <tr>
>    <td>Eve</td>
>    <td>Jackson</td>
>    <td>94</td>
>  </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_row_height)

&nbsp;

>***Example*** For Table Column Size
>```html
><table style="width:100%">
>  <tr>
>    <th style="width:70%">Firstname</th>
>    <th>Lastname</th>
>    <th>Age</th>
>  </tr>
>  <tr>
>    <td>Jill</td>
>    <td>Smith</td>
>    <td>50</td>
>  </tr>
>  <tr>
>    <td>Eve</td>
>    <td>Jackson</td>
>    <td>94</td>
>  </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_column_width)

&nbsp;

## 7.HTML Table Header
- HTML tables can have headers for each column or row, or for many columns/rows.
- Table headers are defined with <mark>th</mark> elements. Each <mark>th</mark> element represents a table cell.
>***Example***
>```
><table>
>  <tr>
>    <th>Firstname</th>
>    <th>Lastname</th>
>    <th>Age</th>
>  </tr>
>  <tr>
>    <td>Jill</td>
>   <td>Smith</td>
>    <td>50</td>
>  </tr>
>  <tr>
>    <td>Eve</td>
>    <td>Jackson</td>
>    <td>94</td>
>  </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_th)

&nbsp;

### Vertical Table Heading
- To use the first column as table headers, define the first cell in each row as a &#60;th> element:
>***Example***
>```
><table>
>  <tr>
>    <th>Firstname</th>
>    <td>Jill</td>
>    <td>Eve</td>
>  </tr>
>  <tr>
>    <th>Lastname</th>
>    <td>Smith</td>
>    <td>Jackson</td>
>  </tr>
>  <tr>
>    <th>Age</th>
>    <td>94</td>
>    <td>50</td>
>  </tr>
></table>
>```
>[try it yoursef](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_th_vertical)

&nbsp;

### Header Alignment
- We can use align property of style attribute , To align our header where ever we want.
>***Example***
>~~~css
>th {
>  text-align: left;
>}
>~~~
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_th_align)

&nbsp;

### Table Caption
- we can add caption for the html table.
- for caption we use &#60;caption> element.
>***Exapmle***
>```html
><table style="width:100%">
>  <caption>Monthly savings</caption>
>  <tr>
>    <th>Month</th>
>    <th>Savings</th>
>  </tr>
>  <tr>
>    <td>January</td>
>    <td>$100</td>
>  </tr>
>  <tr>
>    <td>February</td>
>    <td>$50</td>
>  </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_tables2)

&nbsp;

## 8. HTML Table Padding & Cell spacing
- HTML tables can adjust the padding inside the cells, and also the space between the cells.

### Cell Padding
- Cell padding is the space between the cell edges and the cell content.
- By default the padding is set to 0.
- To add padding on table cells, use the CSS padding property.

>***Example***
>```css
>th, td {
>  padding: 15px;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_cellpadding)

&nbsp;

- To add padding only above the content, use the padding-top property.

- And the others sides with the padding-bottom, padding-left, and padding-right properties:

>***Example***
>```
>th, td {
>  padding-top: 10px;
>  padding-bottom: 20px;
>  padding-left: 30px;
>  padding-right: 40px;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_cellpadding2)

&nbsp;

### Table Cell Spacing
- Cell spacing is the space between each cell.
- By default the space is set to 2 pixels.
- To change the space between table cells, use the CSS border-spacing property on the table element:

>***Example***
>```
>table {
>  border-spacing: 30px;
>}
>```
>[try it youself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_border-spacing)
&nbsp;

## 9.HTML Table Colspan & Rowspan
- HTML tables can have cells that span over multiple rows and/or columns.

### Colspan
- To make a cell span over multiple columns, use the colspan attribute:
>***Example***
>```html
><table>
>  <tr>
>    <th colspan="2">Name</th>
>    <th>Age</th>
>  </tr>
>  <tr>
>    <td>Jill</td>
>    <td>Smith</td>
>    <td>43</td>
>  </tr>
>  <tr>
>    <td>Eve</td>
>    <td>Jackson</td>
>    <td>57</td>
>  </tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_colspan2)

&nbsp;

### Rowspan
- To make a cell span over multiple rows, use the rowspan attribute:
>***Example***
>```html
><table>
>  <tr>
>    <th>Name</th>
>    <td>Jill</td>
>  </tr>
>  <tr>
>    <th rowspan="2">Phone</th>
>    <td>555-1234</td>
>  </tr>
>  <tr>
>    <td>555-8745</td>
></tr>
></table>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_rowspan2)

&nbsp;

## 10.Table Styling
 
 ### Zebra Strips
 - If you add a background color on every other table row, you will get a nice zebra stripes effect.

- To style every other table row element, use the :nth-child(even) selector like this:

>***Example***
>```css
>tr:nth-child(even) {
>  background-color: #D6EEEE;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_zebra)


**NOTE**==> <mark>If you use (odd) instead of (even), the styling will occur on row 1,3,5 etc. instead of 2,4,6 etc.</mark>
&nbsp;

### Vertical Zebra Strips
- To make vertical zebra stripes, style every other column, instead of every other row.
- Set the :nth-child(even) for table data elements like this:

>***Example***
>```css
> td:nth-child(even) , th:nth-child(even) {
>  background-color: #D6EEEE;
>}
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_zebra_vertical)

&nbsp;

### Combine Zebra Strrips
- You can combine the vertical and horizontal zebra strips together.
- If you use a transparent color you will get an overlapping effect.
- Use an rgba() color to specify the transparency of the color:
>***Example***
>```
>tr:nth-child(even) {
>  background-color: rgba(150, 212, 212, 0.4);
>}
>
>th:nth-child(even),td:nth-child(even) {
>  background-color: rgba(150, 212, 212, 0.4);
>}
>```
>[try it youself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_zebra_combine)

&nbsp;

### Horizontal Divider
- If you specify borders only at the bottom of each table row, you will have a table with horizontal dividers.

- Add the border-bottom property to all tr elements to get horizontal dividers:
>***Example***
>```css
>tr {
> border-bottom: 1px solid #ddd;
>}
>```
>[try it youself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_border_divider2)

&nbsp;

### Hoverable Table
- Use the :hover selector on tr to highlight table rows on mouse over:
>***Example***
>```css
>tr:hover {background-color: #D6EEEE;}
>```
>[try it youself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_hover)

&nbsp;

## 11.Table colgroup
- The &#60;colgroup> element is used to style specific columns of a table.

### Row Colgroup
- If you want to style the two first columns of a table, use the &#60;colgroup> and &#60;col> elements
- The &#60;colgroup> element should be used as a container for the column specifications.
- Each group is specified with a &#60;col> element.
- The span attribute specifies how many columns that get the style.
- The style attribute specifies the style to give the columns.
>***Example***
>```html
><table>
>  <colgroup>
>   <col span="2" style="background-color: #D6EEEE">
>  </colgroup>
>  <tr>
>    <th>MON</th>
>    <th>TUE</th>
>    <th>WED</th>
>    <th>THU</th>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_colgroup1)

&nbsp;

**Note**==> <mark> The &#60;colgroup> tag must be a child of a &#60;table> element and should be placed before any other table elements, like &#60;thead>, &#60;tr>, &#60;td> etc., but after the &#60;caption> element, if present.</mark>

&nbsp;

### Multiple Col Elements
- If you want to style more columns with different styles, use more &#60;col> elements inside the &#60;colgroup>.
>***Example***
>```html
><table>
>  <colgroup>
>    <col span="2" style="background-color: #D6EEEE">
>    <col span="3" style="background-color: pink">
>  </colgroup>
>  <tr>
>    <th>MON</th>
>    <th>TUE</th>
>    <th>WED</th>
>    <th>THU</th>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_colgroup2)

&nbsp;

### Empty Colgroups
- If you want to style columns in the middle of a table, insert a "empty" &#60;col> element (with no styles) for the columns before.

>***Example***
>```html
><table>
>  <colgroup>
>    <col span="3">
>    <col span="2" style="background-color: pink">
>  </colgroup>
>  <tr>
>    <th>MON</th>
>    <th>TUE</th>
>    <th>WED</th>
>    <th>THU</th>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_colgroup3)
 

&nbsp;

### Hide Columns
-  You can hide columns with the visibility: collapse property:

>***Example***
>```
><table>
>  <colgroup>
>    <col span="2">
>    <col span="3" style="visibility: collapse">
>  </colgroup>
>  <tr>
>    <th>MON</th>
>    <th>TUE</th>
>    <th>WED</th>
>    <th>THU</th>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_table_colgroup4)

&nbsp;

# 15. HTML List

- HTML allow developer to creat list of the data item.
***Example***

 Ordered List:-
1. first item                  
2. second item
3. third item
4. fourth item

 Under-ordered List:-
- first item                  
- second item
- third item
- fourth item

## 1.Unordered List 
- An unordered list starts with the &#60;ul> tag. Each list item starts with the &#60;li> tag.

- The list items will be marked with bullets (small black circles) by default:

>***Example***
>```html
><ul>
>  <li>Coffee</li>
>  <li>Tea</li>
>  <li>Milk</li>
></ul>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_unordered2)

&nbsp;

### Horizontal List
- HTML lists can be styled in many different ways with CSS.
- One popular way is to style a list horizontally, to create a navigation menu:

>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><style>
>ul {
>  list-style-type: none;
>  margin: 0;
>  padding: 0;
>  overflow: hidden;
>  background-color: #333333;
>}
>
>li {
>  float: left;
>}
>
>li a {
>  display: block;
>  color: white;
>  text-align: center;
>  padding: 16px;
>  text-decoration: none;
>}
>
>li a:hover {
>  background-color: #111111;
>}
></style>
></head>
><body>
>
><ul>
>  <li><a href="#home">Home</a></li>
>  <li><a href="#news">News</a></li>
>  <li><a href="#contact">Contact</a></li>
>  <li><a href="#about">About</a></li>
></ul>
>
></body>
></html>
>```
>[try it yoursself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_menu)

&nbsp;

**NOTE** => The CSS <mark>list-style-type</mark> property is used to define the style of the list item marker. It can have one of the following values:

disc   ==>	Sets the list item marker to a bullet (default)<br/>
circle ==>	Sets the list item marker to a circle<br/>
square ==>	Sets the list item marker to a square<br/>
none	 ==>  The list items will not be marked<br/>

>***Example***
>```html
><ul style="list-style-type:circle;">
>  <li>Coffee</li>
>  <li>Tea</li>
>  <li>Milk</li>
></ul>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_unordered_circle)

Change the value of bullet style and try more.

&nbsp;

## 2.Order List

- An ordered list starts with the &#60;ol> tag. Each list item starts with the &#60;li> tag.

- The list items will be marked with numbers by default:

>***Example***
>```html
><ol>
>  <li>Coffee</li>
>  <li>Tea</li>
>  <li>Milk</li>
></ol>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_ordered2)

&nbsp;

### Centrol List Counting
- By default, an ordered list will start counting from 1. If you want to start counting from a specified number, you can use the start attribute:

>***Example***
>```html
><ol start="50">
>  <li>Coffee</li>
>  <li>Tea</li>
>  <li>Milk</li>
></ol>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_start)

&nbsp;

**NOTE** => The type attribute of the &#60;ol> tag, defines the type of the list item marker:
- type="1"  ==>	The list items will be numbered with numbers (default)
- type="A" ==>	The list items will be numbered with uppercase letters
- type="a" ==> 	The list items will be numbered with lowercase letters
- type="I" ==>	The list items will be numbered with uppercase roman numbers
- type="i"	==>  The list items will be numbered with lowercase roman numbers.

>***Example***
>```html
><ol type="A">
>  <li>Coffee</li>
>  <li>Tea</li>
>  <li>Milk</li>
></ol>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_ordered_ucase)

Change the value of bullet style and try more.

&nbsp;

## 3.Description List
- A description list is a list of terms, with a description of each term.
- The &#60;dl> tag defines the description list, the &#60;dt> tag defines the term (name), and the &#60;dd> tag describes each term:
>***Example***
>```html
><dl>
>  <dt>Coffee</dt>
>  <dd>- black hot drink</dd>
>  <dt>Milk</dt>
>  <dd>- white cold drink</dd>
></dl>
>```
>[try it youself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_description)

&nbsp;

# 16.HTML Block And Inline Element
- Every HTML element has a default display value, depending on what type of element it is.
- There are two display values:
    - block 
    - inline.

&nbsp;

## 1.Block Level Element
- A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.
- A block-level element always takes up the full width available (stretches out to the left and right as far as it can).
- Two commonly used block elements are: &#60;p> and &#60;div>.
- The &#60;p> element defines a paragraph in an HTML document.
- The &#60;div> element defines a division or a section in an HTML document.

>***Block-level Elements***
>```html
><address>  <article>   <aside>   <blockquote>  <canvas>   <dd>   <div>  <dl>  <dt>   <fieldset>   <figcaption>   <figure>   <footer>   <form>   <h1>-<h6>   <header>    <hr>    <li>   <main>   <nav>   <noscript>   <ol>   <p>   <pre>   <section>   <table>  <tfoot>  <ul>  <video>
>```

&nbsp;

>***Example***
>```html
><p>Hello World</p>
><div>Hello World</div>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_block_div)

&nbsp;

## 2. Inline Level Element
- An inline element does not start on a new line.
- An inline element only takes up as much width as necessary.
- This is a &#60;span> element inside a paragraph.

>***Inline Level Elements***
>```html
><a>   <abbr>   <acronym>   <b>   <bdo>   <big>   <br>   <button>   <cite>   <code>   <dfn>   <em>   <i>  <img>   <input>   <kbd>   <label>   <map>   <object>   <output>   <q>   <samp>   <script>   <select>   <small>   <span>   <strong>   <sub>   <sup>   <textarea>   <time>   <tt>   <var>
>```

>***Example***
>```html
><span>Hello World</span>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_inline_span)


***Note***:<mark> An inline element cannot contain a block-level element!</mark>

&nbsp;

## 3. The &#60;div> Element
- The &#60;div> element is often used as a container for other HTML elements.
- The &#60;div> element has no required attributes, but style, class and id are common.
- When used together with CSS, the &#60;div> element can be used to style blocks of content:

>***Example***
>```html
><div style="background-color:black;color:white;padding:20px;">
>  <h2>London</h2>
>  <p>London is the capital city of England. It is the most >populous city in the United Kingdom, with a metropolitan area >of over 13 million inhabitants.</p>
></div>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_div)

&nbsp;

## 4.The &#60;span> Element
- The &#60;span> element is an inline container used to mark up a part of a text, or a part of a document.
- The &#60;span> element has no required attributes, but style, class and id are common.
- When used together with CSS, the &#60;span> element can be used to style parts of the text:
>```html
><p>My mother has <span style="color:blue;font-weight:bold;">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold;">dark green</span> eyes.</p>
>````
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_span)

&nbsp;


# 17.Classes
- The class attribute used to define class for HTMl Element.
- more than one element can share same class at same time.


## 1. Style by Pointing Class Name
- After specifying class for an element , we can give them Style by pointing to class name in css style sheet.
- for Example if we specify a class for &#60;div>, a different &#60;p> Element than can give style both of them together , In sytle sheet we just point a class by it's name starting with a (.).
>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><style>
>.city {
>  background-color: tomato;
>  color: white;
>  border: 2px solid black;
>  margin: 20px;
>  padding: 20px;
>}
></style>
></head>
><body>
>
><div class="city">
>  <h2>London</h2>
>  <p>London is the capital of England.</p>
></div>
>
><div class="city">
>  <h2>Paris</h2>
>  <p>Paris is the capital of France.</p>
></div>
>
><div class="city">
>  <h2>Tokyo</h2>
 > <p>Tokyo is the capital of Japan.</p>
></div>
>
></body>
></html>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_capitals)

&nbsp;

*In the following example we have two &#60;span> elements with a class attribute with the value of "note". Both &#60;span> elements will be styled equally according to the .note style definition in the head section:*
>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><style>
>.note {
>  font-size: 120%;
>  color: red;
>}
></style>
></head>
><body>
>
><h1>My <span class="note">Important</span> Heading</h1>
><p>This is some <span class="note">important</span> text.</p>
>
></body>
></html>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_span)

&nbsp;

***NOTE*** => To create a class; write a period (.) character, followed by a class name. Then, define the CSS properties within curly braces {}:

>***Example***
>```css
>.city {
>  background-color: tomato;
>  color: white;
>  padding: 10px;
>}
>```

&nbsp;

## 2.Multiple Class
- We can use more than one html  class ,
- To define multiple classes, separate the class names with a space, e.g. <ins>&#60;div class="city main"></ins>. The element will be styled according to all the classes specified.

>***Example***
>```html
><h2 class="city main">London</h2>
><h2 class="city">Paris</h2>
><h2 class="city">Tokyo</h2>
>```
>[try  it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_multiple)

&nbsp;

## 3. The Class attribute in JavaScript
- The class name can also be used by JavaScript to perform certain tasks for specific elements.

- JavaScript can access elements with a specific class name with the <ins>getElementsByClassName()</ins> method:

>***Example***
>```js
><script>
>function myFunction() {
>  var x = document.getElementsByClassName("city");
>  for (var i = 0; i < x.length; i++) {
>    x[i].style.display = "none";
>  }
>}
></script>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_js)

&nbsp;


# 18. HTML ID
- The HTML ID attribute use to give a unique ID to an element.
- There must be always a unique ID for an element,  we can not specify same id for more than one element.

## 1.ID Attribute
- The id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document.
- The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.
- The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><style>
>#myHeader {
>  background-color: lightblue;
>  color: black;
>  padding: 40px;
>  text-align: center;
>}
></style>
></head>
><body>
>
><h1 id="myHeader">My Header</h1>
>
></body>
></html>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_id_css)

&nbsp;


## 2.Difference Betweer ID and Class
- There is only one important difference between Id and Class is , ID must be used for only one element , while class can be used by more than one elements.
>***Example***
>```html
><style>
>/* Style the element with the id "myHeader" */
>#myHeader {
>  background-color: lightblue;
>  color: black;
>  padding: 40px;
>  text-align: center;
>}
>
>/* Style all elements with the class name "city" */
>.city {
>  background-color: tomato;
>  color: white;
>  padding: 10px;
>}
></style>
>
><!-- An element with a unique id -->
><h1 id="myHeader">My Cities</h1>
>
><!-- Multiple elements with same class -->
><h2 class="city">London</h2>
><p>London is the capital of England.</p>
>
><h2 class="city">Paris</h2>
><p>Paris is the capital of France.</p>
>
><h2 class="city">Tokyo</h2>
><p>Tokyo is the capital of Japan.</p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_id_class)

&nbsp;

## 4. ID Attribute in JavaScript
- The id attribute can also be used by JavaScript to perform some tasks for that specific element.
- JavaScript can access an element with a specific id with the getElementById() method:

>***Example***
>```
><script>
>function displayResult() {
>  document.getElementById("myHeader").innerHTML = "Have a >nice day!";
>}
></script>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_id_js)

&nbsp;


# 19. IFrame Element
- IFrame element is used to  add web page within the eb page.

## 1.IFrame Syntex 
- The HTML &#60;iframe> tag specifies an inline frame.
- An inline frame is used to embed another document within the current HTML document.
>***Example***
>```html
><iframe src="url" title="description"></iframe>
>```

- It is a good practice to always include a title attribute for the &#60;iframe>. This is used by screen readers to read out what the content of the iframe is.
- Use the height and width attributes to specify the size of the iframe.

>***Example***
>```html
><iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_iframe_height_width)

Or you can add the style attribute and use the CSS height and width properties:

>***Example***
>```html
><iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"></iframe>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_iframe_height_width_css)

&nbsp;

# 20.JavaScript
- JavaScript used  to make HTML pages more dynamic and interactive.

>***Example***
>```html
><button type="button" onclick="document.getElementById('demo').innerHTML=date()">Click here to see data!</button>
><p id="demo"></p>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_scripts_intro)

***Output***

<button type="button" onclick="document.getElementById('demo').innerHTML=date()">Click here to see data!</button>
<p id="demo"></p>

&nbsp;

## 1.&#60;script> Tag
- The HTML &#60;script> tag is used to define a client-side script (JavaScript).
- The &#60;script> element either contains script statements, or it points to an external script file through the src attribute.
- Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.
- To select an HTML element, JavaScript most often uses the document.getElementById() method

>***Example***
>```js
><script>
>document.getElementById("demo").innerHTML = "Hello JavaScript!";
></script>
>```

&nbsp;

=> We can change Content of any element by javascript:
>***Example***
>```js
>document.getElementById("demo").innerHTML = "Hello JavaScript!";
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_script_html)

=> We can Change the style of any element by javascript
>***Example***
>```js
>document.getElementById("demo").style.fontSize = "25px";
>document.getElementById("demo").style.color = "red";
>document.getElementById("demo").style.backgroundColor = "yellow";
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_script_styles)

==>We can change img by  javascript:
>***Example***
>```js
>document.getElementById("image").src = "picture.gif";
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_script_attribute)

&nbsp;

## 2.&#60;nonscript> Element
- The HTML <noscript> tag defines an alternate content to be displayed to users that have disabled scripts in their browser or have a browser that doesn't support scripts:
>***Example***
>```js
><script>
>document.getElementById("demo").innerHTML = "Hello JavaScript!";
></script>
><noscript>Sorry, your browser does not support JavaScript!</noscript>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_noscript)

&nbsp;

# 21.File Path
- A file path describes the location of a file in a web site's folder structure.
- File paths are used when linking to external files, like:
    - Web pages
    - Images
    - Style sheets
    - JavaScripts

**NOTE** => There is type of Filepath .
## 1.Absolute :
- Absolute file path points to the  external file which is not available in current page.
>***Exampe***
>```html
><img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_files_absoulute)

&nbsp;

## 2.Relative:
- A relative file path points to a file relative to the current page.
>***Example***
>```html
><img src="/images/picture.jpg" alt="Mountain">
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_files_relative)

&nbsp;

# 22.HTML Head Element
- The HTML &#60;head> element is a container for the following elements: <title&#62;, &#60;style>, &#60;meta>, &#60;link>, &#60;script>, and &#60;base>.
- The &#60;head> element is a container for metadata (data about data) and is placed between the &#60;html> tag and the &#60;body> tag.
- HTML metadata is data about the HTML document. Metadata is not displayed.
- Metadata typically define the document title, character set, styles, scripts, and other meta information.


&nbsp;

## 1. HTML &#60;title> Element

- The  &#60;title> element:
    - &#60;title> Element defines a title in the browser toolbar
    - &#60;title> Element  provides a title for the page when it is added to favorites
    - &#60;title> Element displays a title for the page in search engine-results

>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
>  <title>A Meaningful Page Title</title>
></head>
><body>
>
>The content of the document......
>
></body>
></html>    
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_title)

&nbsp;

## 2.HTML Style Element
- The &#60;style> element is used to define style information for a single HTML page:

>***Example***
>```html
><style>
>  body {background-color: powderblue;}
>  h1 {color: red;}
>  p {color: blue;}
></style>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_style)

&nbsp;

## 3.HTML Link Element
- The &#60;link> element defines the relationship between the current document and an external resource.
- The &#60;link> tag is most often used to link to external style sheets:

>***Example***
>```html
><link rel="stylesheet" href="mystyle.css">
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_link)

&nbsp;

## 4.HTML &#60;meta> Element
- The &#60;meta> element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.
- The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.

```html
Define the character set used:

<meta charset="UTF-8">
```
```html
Define keywords for search engines:

<meta name="keywords" content="HTML, CSS, JavaScript">
```
```html
Define a description of your web page:

<meta name="description" content="Free Web tutorials">
```
```html
Define the author of a page:

<meta name="author" content="John Doe">
```
```html
Refresh document every 30 seconds:

<meta http-equiv="refresh" content="30">
```
```html
Setting the viewport to make your website look good on all devices:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

&nbsp;

>***Example***
>```html
><meta charset="UTF-8">
><meta name="description" content="Free Web tutorials">
><meta name="keywords" content="HTML, CSS, JavaScript">
><meta name="author" content="John Doe">
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_meta)

&nbsp;

## 5.The ViewPort
- The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen. 
- his gives the browser instructions on how to control the page's dimensions and scaling.
- The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
- The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.<br/>
![](https://www.w3schools.com/css/img_viewport1.png)
**Without Viewport Setting**<br>
![](https://www.w3schools.com/css/img_viewport2.png)
**With view port setting**

>***Example**
>```html
><meta name="viewport" content="width=device-width, initial-scale=1.0">
>```

&nbsp;

## 6.The HTML &#60;script> Element
 - The &#60;script> element is used to define client-side JavaScripts.

>***Example***
>```html
> <script>
>function myFunction() {
>  document.getElementById("demo").innerHTML = "Hello JavaScript!";
>}
></script>
>```
>[[**try it yourself**]](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_script)

&nbsp;

## 7.The HTML <base> Element
- The &#60;base> element specifies the base URL and/or target for all relative URLs in a page.
- The &#60;base> tag must have either an href or a target attribute present, or both.

>***Example***
>```html
><head>
><base href="https://www.w3schools.com/" target="_blank">
></head>
>
><body>
><img src="images/stickman.gif" width="24" height="39" alt="Stickman">
><a href="tags/tag_base.asp">HTML base Tag</a>
></body>
>```
>[[**try it yourself]**](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_head_base)