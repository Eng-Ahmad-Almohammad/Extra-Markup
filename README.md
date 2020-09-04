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
![div](https://user-images.githubusercontent.com/70091044/92274886-b983a780-eef6-11ea-83ec-a909dd49eb05.PNG)
## Grouping Text & Elements Inline
## < span > 
### The < span > element acts like an inline equivalent of the < div > element. It is used to either:
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
2. Contain a number of inline elements.
### The most common reason why people use < span > elements is so that they can control the appearance of the content of these elements using CSS.
![span](https://user-images.githubusercontent.com/70091044/92275309-90afe200-eef7-11ea-8438-37993423ad79.PNG)
## IFrames
## < iframe >
### An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
### One common use of iframes (that you may have seen on various websites) is to embed a Google Map into a page. The content of the iframe can be any html page (either located on the same server or anywhere else on the web).
### An iframe is created using the < iframe > element. There are a few attributes that you will need to know to use it:
## src
### The src attribute specifies the URL of the page to show in the frame.
## height
### The height attribute specifies the height of the iframe in pixels.
## width
### The width attribute specifies the width of the iframe in pixels.
## scrolling
### The scrolling attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the iframe should have scrollbars or not. This is important if the page inside the iframe is larger than the space you have allowed for it (using the height and width attributes). Scrollbars allow the user to move around the frame to see more content. It can take one of three values: yes (to show scrollbars), no (to hide scrollbars) and auto (to show them only if needed).
## frameborder
### The frameborder attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the frame should have a border or not. A value of 0 indicates that no border should be shown. A value of 1 indicates that a border should be shown.
## seamless
### In HTML5, a new attribute called seamless can be applied to an iframe where scrollbars are not desired. The seamless attribute (like some other new HTML5 attributes) does not need a value, but you will often see authors give it a value of seamless. Older browsers do not support the seamless attribute.
![iframe](https://user-images.githubusercontent.com/70091044/92276618-061cb200-eefa-11ea-90eb-14380087dbab.PNG)
## Information About Your Pages
## < meta >
### The < meta > element lives inside the < head > element and contains information about that web page. 
### It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. (If the page is time sensitive, it can be set to expire.)
### The < meta > element is an empty element so it does not have a closing tag. It uses attributes to carry the information. 
### The most common attributes are the name and content attributes, which tend to be used together. These attributes specify properties of the entire page. The value of the name attribute is the property you are setting, and the value of the content attribute is the value that you want to give to this property.
### The value of the name attribute can be anything you want it to be. Some defined values for this attribute that are commonly used are:
## description
### This contains a description of the page. This description is commonly used by search engines to understand what the page is about and should be a maximum of 155 characters. Sometimes it is also displayed in search engine results.
## keywords
### This contains a list of commaseparated words that a user might search on to find the page. In practice, this no longer has any noticeable effect on how search engines index your site.
## robots
### This indicates whether search engines should add this page to their search results or not. A value of noindex can be used if this page should not be added. A value of nofollow can be used if search engines should add this page in their results but not any pages that it links to.
### The <meta> element also uses the http-equiv and content attributes in pairs. In our example, you can see three instances of the http-equiv attribute. Each one has a different purpose:
## author
### This defines the author of the web page.
## pragma
### This prevents the browser from caching the page. (That is, storing it locally to save time downloading it on subsequent visits.)
## expires
### Because browsers often cache the content of a page, the expires option can be used to indicate when the page should expire (and no longer be cached). Note that the date must be specified in the format shown.
![meta](https://user-images.githubusercontent.com/70091044/92277966-de7b1900-eefc-11ea-962d-110902e0075a.PNG)
## Escape Characters
### There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)
![esPNG](https://user-images.githubusercontent.com/70091044/92278382-c5bf3300-eefd-11ea-8ebb-cd881b2d11a9.PNG
