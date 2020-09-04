# Extra-Markup
## DOCTYPES
### Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included). We will therefore be including one in each example for the rest of the book.
### As you will see when we come to look at CSS and its box model onpage 316, the use of a DOCTYPE can also help the browser to render a page correctly.
### Because XHTML was written in XML, you will sometimes see pages that use the XHTML strict DOCTYPE start with the optional XML declaration. Where this is used, it should be the first thing in a document. There must be nothing before it, not even a space.
![Doctypes](https://user-images.githubusercontent.com/70091044/92270215-4f670480-eeee-11ea-8fb7-41117b05b9cc.PNG)
## Comments in HTML
### < !-- --> (without space)
### If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
### < !-- comment goes here --> (without space)
![Coment code](https://user-images.githubusercontent.com/70091044/92270916-8853a900-eeef-11ea-92f1-a570c97aa45f.PNG)
![Cmment result](https://user-images.githubusercontent.com/70091044/92270922-8c7fc680-eeef-11ea-9c91-d6e8371c27f1.PNG)

## ID Attribute
### Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
![Id](https://user-images.githubusercontent.com/70091044/92271293-365f5300-eef0-11ea-821a-17d8f0969366.PNG)
## Class Attribute
### Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. For example, you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, to do this you can use the class attribute. 
![class](https://user-images.githubusercontent.com/70091044/92271814-1e3c0380-eef1-11ea-9e5a-ea363bfce2c6.PNG)
## Block Elements
### Some elements will always appear to start on a new line in the browser window. These are known as *block level* elements. 
### Examples of block elements are < h1 >, < p >, < ul >, and < li >.
![block](https://user-images.githubusercontent.com/70091044/92272238-da95c980-eef1-11ea-8705-339b10c835f7.PNG)
## Inline Elements
### Some elements will always appear to continue on the same line as their neighbouring elements. These are known as *inline* elements.
### Examples of inline elements are < a >, < b >, < em >, and < img >.
![inline](https://user-images.githubusercontent.com/70091044/92274408-db305f00-eef5-11ea-848c-04daffb61936.PNG)
## Grouping Text & Elements In a Block
## < div > 
### The < div > element allows you to group a set of elements together in one block-level box. For example, you might create a < div > element to contain all of the elements for the header of your site (the logo and the navigation), or you might create a  < div > element to contain comments from visitors.


