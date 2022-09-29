<style>
    body{
        background-color:#6666;
        color:b;
        /* border:4px solid white; */
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
# HTML Semantic Element
- A semantic element clearly describes its meaning to both the browser and the developer.
- Examples of non-semantic elements: &#60;div> and &#60;span> - Tells nothing about its content.
- Examples of semantic elements: &#60;form>, &#60;table>, and &#60;article> - Clearly defines its content.
## HTML Semantic Elements

- &#60;article>
- &#60;aside>
- &#60;details>
- &#60;figcaption>
- &#60;figure>
- &#60;footer>
- &#60;header>
- &#60;main>
- &#60;mark>
- &#60;nav>
- &#60;section>
- &#60;summary>
- &#60;time><br/>
 &nbsp;![](https://www.w3schools.com/html/img_sem_elements.gif)

&nbsp;

## HTML &#60;section> Element
-The &#60;ection> element defines a section in a document.
- According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."
- Examples of where a &#60;section> element can be used:

    - Chapters
    - Introduction
    - News items
    - Contact information

>***Example***
>```html
><section>
><h1>WWF</h1>
><p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
></section>
>
><section>
><h1>WWF's Panda symbol</h1>
><p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
></section>
>```
>[try it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml5_section)

&nbsp;

## HTML &#60;article> Element
- The &#60;article> element specifies independent, self-contained content.
- An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.
- Examples of where the &#60;article> element can be used:

    - Forum posts
    - Blog posts
    - User comments
    - Product cards
    - Newspaper articles

>***Example***
>```html
><article>
><h2>Google Chrome</h2>
><p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
></article>
>
><article>
><h2>Mozilla Firefox</h2>
><p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
></article>
>
><article>
><h2>Microsoft Edge</h2>
><p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
></article>    
>```
>[try  it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml5_article)


```html

<html>
<head>
<style>
.all-browsers {
  margin: 0;
  padding: 5px;
  background-color: lightgray;
}

.all-browsers > h1, .browser {
  margin: 10px;
  padding: 5px;
}

.browser {
  background: white;
}

.browser > h2, p {
  margin: 4px;
  font-size: 90%;
}
</style>
</head>
<body>

<article class="all-browsers">
  <h1>Most Popular Browsers</h1>
  <article class="browser">
    <h2>Google Chrome</h2>
    <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
  </article>
  <article class="browser">
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
  </article>
  <article class="browser">
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
  </article>
</article>

</body>
</html>
```
>[try it yourself](https://www.w3schools.com/html/tryit.asp?filename=tryhtml5_article2)

&nbsp;

## HTML &#60;header> Element

- The &#60;header> element represents a container for introductory content or a set of navigational links.
- A &#60;header> element typically contains:
     - one or more heading elements (&#60;h1> - &#60;h6>)
     - logo or icon
     - authorship information

**Note**: You can have several &#60;header> elements in one HTML document. However, &#60;header> cannot be placed within a &#60;footer>, &#60;address> or another &#60;header> element.
>***Examplle***
>```
>
><article>
  <header>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission:</p>
  </header>
  <p>WWF's mission is to stop the degradation of our planet's natural environment,
  and build a future in which humans live in harmony with nature.</p>
</article>
