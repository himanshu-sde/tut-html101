HTML 101
Details of the HTML structure
1st element is the DOCTYPE wich tells the browser the version of html used
Next element is the HTML element which is the root of the document. ALSO lang is an ATTRIBUTE which specifies the language of the content
HEAD ele is used to put meta-data info like tags for search engines. Also UTF-8 encoding ensures that the webpage will display special symbols and characters from different languages correctly in the browser.
TITLE ele comes under head gives webpages a human-readable title which is displayed in our webpage’s browser tab
To complete boilerplate, the final element needed to complete the HTML boilerplate is the BODY element. All the content needs to be put inside the BODY element.
Below is the use of lang attribute

This paragraph is defined as British English.

Ce paragraphe est défini en français.

Working with texts
Below is the Use of lorem , type "lorem9" to generate 9 words

Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis.

The STRONG element makes text bold. It also semantically marks text as important; this affects tools, like screen readers, that users with visual impairments will rely on to use your website

The EM element makes text italic. It also semantically places emphasis on the text, which again may affect things like screen readers.

View the html to see the hidden comments

Some paragraph text

Ordered and Unordered list
The li HTML element is used to represent an item in a list. It must be contained in a parent element:either an ordered list ( ol) or an unordered list ( ul )

Links and Images
LINKS - "a" tag and IMAGES - "img" tag

LINKS
click me This is an absolute link using "a" tag and "href"(hyperlink reference) attribute i.e, Links to pages on other websites on the internet are called absolute links.
Creating a new About page for relative link. In this we will give href="about.html" => About Page . This works because the index and about page are in the same directory. That means we can simply use its name (about.html) as the link’s href value.
Relative links only include the file path to the other page, relative to the page you are creating the link on.
IMAGES
"img" element is self-closing with "src" attribute which works exactly like "href".
For e.g: Abosulte path Image is as follows:

The alt attribute is used to describe an image. It will be used in place of the image if it cannot be loaded. It is also used with screen readers to describe. Also, Besides the src attribute, every image element should also have an alt (alternative text) attribute.
For e.g: ALT use + Relative path Image is as follows:
USEFUL HTML TAGS
