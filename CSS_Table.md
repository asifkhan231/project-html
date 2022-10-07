
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
</style>
# CSS Table
- With  We can improve the style if  any html table.

## 1 Table Border
- We will use border property create border for any table.
- The example below specifies a solid border for &#60;table>, &#60;th>, and &#60;td> elements:
<table Style="border:1px solid gray">
    <tr>
       <th>Name</th>
       <th>Age</th>
       <th>Degree</th>
       <th>College</th>
    </tr>
    <tr>
       <td>Ayush Pathak</td>
       <td>23</td>
       <td>B.tech</td>
       <td>UCET(Bikaner)</td>
    </tr>
    <tr>
       <td>Anish Saini</td>
       <td>21</td>
       <td>B.tech</td>
       <td>UCET(Bikaner)</td>
    </tr>
    <tr>
       <td>Ajay Saini</td>
       <td>24</td>
       <td>B.tech</td>
       <td>UCET(Bikaner)</td>
    </tr>
</table> 

&nbsp;


>***Example***
>```css
>table, th, td{
>    border: 1px solid;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_border)

&nbsp;

## 2. Full-Width Table
- The table above might seem small in some cases. If you need a table that should span the entire screen (full-width), add width: 100% to the &#60;table> element:
>***Example***
>```css
>table {
>  width: 100%;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_fullwidth)

&nbsp;

## 3.Collapse Table Border
- The border-collapse property sets whether the table borders should be collapsed into a single border:

>***Example***
>```css
>table {
>  border-collapse: collapse;
>}
>```
>[try it  yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_border-collapse)

&nbsp;

***Note:-*** If you only want a border around the table, only specify the border property for &#60;table>: 
>***Example***
>```css
>table {
>     border: 1px solid;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_border2)

&nbsp;

## 4.Table Width & Height
- you can set any width and height of table by  width & height properties.

>***Example***
>```css
>table {
>  width: 100%;
>}
>
>th {
>  height: 70px;
>}
>```
>[try it yourself](https://www.w3schools.com/css/css_table_size.asp)

&nbsp;

***Note***:- To create a table that should only span half the page, use width: 50%:

>***Example***
>```css
>table {
>  width: 50%;
>}
>```
>[try it  yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_width2)

&nbsp;

## 5.Horizonatal Alignment
- The text-align property sets the horizontal alignment (like left, right, or center) of the content in &#60;th> or &#60;td>.

- By default, the content of &#60;th> elements are center-aligned and the content of &#60;td> elements are left-aligned.


>***Example***
>```
>td {
>  text-align: center;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_align_center)


&nbsp;

## 6.Vertical Alignment
- The vertical-align property sets the vertical alignment (like top, bottom, or middle) of the content in &#60;th> or &#60;td>.
- By default, the vertical alignment of the content in a table is middle (for both &#60;th> and &#60;td> elements).

&nbsp;

>***Example***
>```css
>td {
>  height: 50px;
>  vertical-align: bottom;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_vertical-align)

&nbsp;

## 7.Table Padding
- To control the space between the border and the content in a table, use the padding property on <td&#62; and <th&#62; elements:

>***Example***
>```css
>th, td {
>  padding: 15px;
>  text-align: left;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_padding)

&nbsp;

## 8.Horizontal Divider
- Add the border-bottom property to &#60;h> and &#60;td> for horizontal dividers:

&nbsp;

>***Example***
>```css
>th, td {
>  border-bottom: 1px solid #ddd;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_border_divider)

&nbsp;

## 9.Hoverable Table
- Use the :hover selector on &#60;tr> to highlight table rows on mouse over:

>***Example***
>```css
>tr:hover {background-color: coral;}
>```
>[tryit yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_hover)

&nbsp;

## 10.Striped Table
- For zebra-striped tables, use the nth-child() selector and add a background-color to all even (or odd) table rows:

>***Example***
>```css
> tr:nth-child(even) {background-color: #f2f2f2;}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_striped)

&nbsp;

## 11. Table Color

>***Example***
>```css
> th {
>    background-color: #04AA6D;
>  color: white;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_color)


&nbsp;

## 12.Responsive Table
- A responsive table will display a horizontal scroll bar if the screen is too small to display the full content:
- Add a container element (like &#60;div>) with overflow-x:auto around the <table&#62; element to make it responsive:

>***Example***
>```
><div style="overflow-x:auto;">
>
><table>
>... table content ...
></table>
>
></div>
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_responsive)

***NOTE***:- We can also define position for  any table caption.

>```
>caption {
>  caption-side: bottom;
>}
>```
>[try it yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_table_caption-side)

