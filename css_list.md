<style>
    body{
        background-color:black;
        /* font-weight:bold; */
        /* border:4px solid white; */
        padding:5px;
        font-style:italic;
        

    }
    ul{
        font-size:15px;
    }
    h1{
        text-align:center;
        /* color:black; */
    }

    ol {
  background: #ff9999;
  padding: 20px;
}

ul#id2 {
  background: #3399ff;
  padding: 20px;
}

ol#id1 li {
  background: #ffe5e5;
  color: darkred;
  padding: 5px;
  margin-left: 35px;
}b

ul#id2 li {
  background: #cce5ff;
  color: darkblue;
  margin: 5px;
}
  
</style>
# CSS List
-  By Css we can style our List however we want.<br>

|unordered List       |   ordered List      |
|-------------        |  -------------      |
|   - First item      |     1. first item   |
|   - second item     |     2. second item  |
|   - third item      |     3. third item   |

&nbsp;

## 1.CSS List Property
- In HTML, there are two main types of lists:
- unordered lists (&#60;ul>) - the list items are marked with bullets
- ordered lists (&#60;ol>) - the list items are marked with numbers or letters.<br>

The CSS list properties allow you to:

   - Set different list item markers for ordered lists
   - Set different list item markers for unordered lists
   - Set an image as the list item marker
   - Add background colors to lists and list items.

&nbsp;

##  2.List Item Markers
- For different list item marker we use the  <mark>list-style-type</mark> property.

>***Example***
>```css
>ul.a {
>  list-style-type: circle;
>}
>
>ul.b {
>  list-style-type: square;
>}
>
>ol.c {
 > list-style-type: upper-roman;
>}
>
>ol.d {
>  list-style-type: lower-alpha;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-type_ex)


&nbsp;

## 3. An Image as The List Item Marker
- For Using images as list item marker , we use <mark>list-style-image</mark> property.

>***Example***
>```css
>ul {
> list-style-image: url('sqpurple.gif');
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-image)


&nbsp;

## 4. The List Item Position
- the <mark>list-style-position</mark> defines the position of item marker.
>***Example***
>```css
>ul.a {
>  list-style-position: outside;
>}
>
>ul.b {
>  list-style-position: inside;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-position)


&nbsp;

## 5. Remove Default Setting
- he list-style-type:none property can also be used to remove the markers/bullets. Note that the list also has default margin and padding. To remove this, add margin:0 and padding:0 to &#60;ul> or &#60;ol>:

>***Example***
>```css
>ul {
>  list-style-type: none;
 > margin: 0;
>  padding: 0;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style_none)

&nbsp;

## 6.Styling List With Color
- We can also style lists with colors, to make them look a little more interesting.

- Anything added to the &#60;ol> or &#60;ul> tag, affects the entire list, while properties added to the &#60;li> tag will affect the individual list items:

>***Example***
>```css
>ol {
>  background: #ff9999;
>  padding: 20px;
>}
>
>ul {
>  background: #3399ff;
>  padding: 20px;
>}
>
>ol li {
>  background: #ffe5e5;
>  color: darkred;
>  padding: 5px;
>  margin-left: 35px;
>}
>
>ul li {
>  background: #cce5ff;
>  color: darkblue;
>  margin: 5px;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style_colors)

&nbsp;
***OUTPUT***
<ol id="id1">
<li>coffee</li>
<li>tea</li>
<li>coca cola</li>
</ol>

<ul id="id2">
<li>coffee</li>
<li>tea</li>
<li>coca cola</li>
</ul>


&nbsp;

<strong>This example demonstrates how to create a list with a red left border.</strong>
[<button type="button" onclick="link">click here</button> ](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-red-border)

&nbsp;

<strong>This example demonstrates how to create a bordered list without bullets.</strong>
[<button type="button" onclick="link">click here</button> ](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-border)

&nbsp;

<strong>This example demonstrates all the different list-item markers in CSS.</strong>
[<button type="button" onclick="link">click here</button> ](https://www.w3schools.com/css/tryit.asp?filename=trycss_list-style-type_all)