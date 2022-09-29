<style>
    body{
        background-color:black;
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

    button.b1:hover{
background-color:azure;
font-size:15px;
    }

</style>    
# 1.HTML Entities
- Some characters are reserved in HTML.
- If you use the less than (<) or greater than (>) signs in your text, the browser might mix them with tags.
- Character entities are used to display reserved characters in HTML.
- To display a less than sign (<) we must write: ```&lt; or &#60;```

***To learn more about HTML Entities and To all HTML Entities code Click the button below:-***<br>
[<button class="b1" type="button" onclick="kl1">click here</button>](https://www.freeformatter.com/html-entities.html)

&nbsp;

# 2.HTML Symbols
- Many mathematical, technical, and currency symbols, are not present on a normal keyboard.
- To add such symbols to an HTML page, you can use the entity name or the entity number (a decimal or a hexadecimal reference) for the symbol.

>***Example***
>```html
><p>I will display &euro;</p>
><p>I will display &#8364;</p>
><p>I will display &#x20AC;</p>
>```

***To learn more about HTML Entities and To all HTML Entities code Click the button below:-***<br>
[<button class="b1" type="button" onclick="kl1">click here</button>](https://www.thoughtco.com/html-code-for-common-symbols-and-signs-2654021)

&nbsp;

#  3.HTML Symbol Entities
- Emojis look like images, or icons, but they are not.
- They are letters (characters) from the UTF-8 (Unicode) character set.
- UTF-8 covers almost all of the characters and symbols in the world.

&nbsp;
Many UTF-8 characters cannot be typed on a keyboard, but they can always be displayed using numbers (called entity numbers):

   - A is 65
   - B is 66 
   - C is 67


>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><meta charset="UTF-8">
></head>
><body>
>
><p>I will display A B C</p>
><p>I will display &#65; &#66; &#67;</p>
>
></body>
></html>
>```

Emojis are also characters from the UTF-8 alphabet:

- 😄 is 128516
- 😍 is 128525
- 💗 is 128151
>***Example***
>```html
><!DOCTYPE html>
><html>
><head>
><meta charset="UTF-8">
></head>
><body>
>
><h1>My First Emoji</h1>
>
><p>&#128512;</p>
>
></body>
></html>
>```

&nbsp;
***To learn more about HTML Entities and To all HTML Entities code Click the button below:-***<br>
[<button class="b1" type="button" onclick="kl1">click here</button>](https://www.quackit.com/character_sets/emoji/emoji_v3.0/unicode_emoji_v3.0_characters_all.cfm5)
