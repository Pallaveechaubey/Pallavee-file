
**HTML & CSS**





![](Aspose.Words.25de6710-6df8-4126-a62b-b898da011939.001.png)







Submitted by - Pallavee Chaubey

**Table of Content**

[**Hypertext Mark-up Language**	](#_n5foiwyerjzy)**3****

[Structure of HTML	](#_slmvgln0o1r8)3

[Anatomy of HTML document	](#_m7au4t4e84ke)5

[HTML Text fundamentals	](#_ywbrm7pknikf)6

[Heading 2	](#_x2i8ngvhi60y)8

[Heading 3	](#_k82fgx803red)8

[Heading 4	](#_1nrwfjrth0w5)8

[Heading 5	](#_neb57r8a30iv)8

[Heading 6	](#_4n0sn2tirz7)8

[Why  do we need structure ?	](#_d5ihgyt10754)9

[Adding supporting information with title attribute	](#_7jekre9eypct)13

[Document and Web Structure	](#_4k3qh8d2ake6)13

[Quotation	](#_2f4aklbfywml)14

[**Normal Text**	](#_o024vk7gta6)**15**

[Blockquote	](#_fj3bv8xgwjyx)15

[**Normal Text**	](#_wpbhwjk9k2gb)**16**

[Inlinequotes	](#_dlfrbj565mm3)17

[**Cascading Style sheet**	](#_ak38hrt9302r)**19**

[There are 3 ways to connect CSS  in our document	](#_rbkpyy1rn87)19

[Importance of CSS Priority in the file	](#_rjavh597gmxh)20

[CSS Order of Priority	](#_dg5t2oxolh49)20

[Selectors in CSS	](#_pnhxb8mlw0x6)21

[Introduction to Google Fonts	](#_v5yf19f401ux)25

[What is Box Model	](#_2u0050oktveb)26

[Flex	](#_iwt2feg12dq)28

[Grid	](#_132b9ottrjup)32

[Properties associated with grid items	](#_bbwgi66ybm4)32

[Benefits of grid :	](#_uktqtd57o3dg)33

[Reference	](#_gq55ehtzd405)33










#
# <a name="_5ujyw6cl32on"></a><a name="_n5foiwyerjzy"></a>**Hypertext Mark-up Language**

“Hypertext” means links that connect web pages to one another, either within a single website or between websites. Whereas “Markup” means any text, images, and other content for display in a web browser.

## <a name="_slmvgln0o1r8"></a>**Structure of HTML**

**<!DOCTYPE html>**

**<html>**

**<head>**

`   `**<meta charset="UTF-8">**

`   `**<title>Document</title>**

**</head>**

**<body>**
**


**</body>**

**</html>**

Before delving into the HTML structure, let's clarify a few important words.

***Open tag :*** Open tag consists of the name of an element wrapped in opening < and closing > angle brackets. 

***Content :*** Content sandwich in opening and closing tag.

***Closing tag :*** Same as Open tag but having a forward slash / before name of element.

***Example*** 

***<p>My name is Pallavee.</p>***

***Here, <p> is the opening tag p is the name of the element i.e used for paragraphs will be discussed further. My name is pallavee and it is content and </p> is the closing tag.***

**Element**

The element is an opening tag followed by content followed by a closing tag.

**Nesting Element**

Elements placed within other elements are called Nesting elements.

**Example**

***<p>My name is <strong>Pallavee<strong>***

***We will discuss later about the <p> tag and <strong> tag.***

**Void Element**

- Not all elements follow the pattern of opening, content and closing tag.
- Some elements consist of a single tag which is typically used to insert/embed in the document.
- We may or may not use slash (/) at the end.

**Example**

***<img src = “http/image”> or <img src = “http/image”/>*** 

**Attribute**

- Extra information about elements that won't appear on the webpage.
- Attribute should have space between it and element name
- Attribute name followed by =
- Attribute values wrapped with opening and closing quotes marks.

**Example** 

***<img src = “http/image”>  Here src is an attribute and the content written inside the “ ” is the value.***

**Boolean Attribute**

- Attribute written without value.
- Boolean attributes can only have one value, which is generally the same as attribute name.

**Example** 

***<input type=”text” disabled=”disabled”/> Here the disabled is the boolean attribute.***

***Or***

***<input type=”text” disabled />*** 


## <a name="_m7au4t4e84ke"></a>**Anatomy of HTML document**

**<!DOCTYPE html>**

**<html>**

**<head>**

`   `**<meta charset="UTF-8">**

`   `**<title>Document</title>**

**</head>**

**<body>**
**


**</body>**

**</html>**

**<!DOCTYPE html>**  

- It is used by web browsers to fetch what version of html the website is written in.
- Help the browser in understanding how the document should be interpreted, thus eases in the rendering process.

**<html> </html>**

- It is referred to as root elements; all other elements must be descendants of this element.

**<head> </head>**

- The [head](https://developer.mozilla.org/en-US/docs/Glossary/Head) of an HTML document is the part that is not displayed in the web browser when the page is loaded.
- Web browsers use information contained in the [head](https://developer.mozilla.org/en-US/docs/Glossary/Head) to render the HTML document correctly. 
- Head contains the metadata about the page.

**<meta charset="UTF-8">**

`   `**<title>Document</title>**


**<meta>**

- Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the <meta> element.

**Example**

***<meta charset="utf-8" />***

This element specifies the document's character encoding - the character set that the document is permitted to use. utf-8 is a universal character set that includes pretty much any character from any human language. This means that your web page will be able to handle displaying any language.

**<body></body>**

- Contain the content that displays on the webpage.

## <a name="_ywbrm7pknikf"></a>**HTML Text fundamentals**
Most structured text consists of headings and paragraphs, whether you are reading a story, a newspaper, a college textbook, a magazine, etc.

**Heading**

In HTML there are 6 heading elements h1,h2,h3,h4,h5,h6 .Each element represents a different level of content in the document; <h1> represents the main heading, <h2> represents subheadings, <h3> represents sub-subheadings, and so on.

- Preferably, you should use a single <h1> per page—this is the top level heading, and all others sit below this in the hierarchy.
- Make sure you use the headings in the correct order in the hierarchy. Don't use <h3> elements to represent subheadings, followed by <h2> elements to represent sub-subheadings—that doesn't make sense and will lead to weird results.
- Of the six heading levels available, you should aim to use no more than three per page, unless you feel it is necessary. Documents with many levels become unwieldy and difficult to navigate. On such occasions, it is advisable to spread the content over multiple pages if possible.



<!DOCTYPE html>

<html lang="en">

<head>

`   `<meta charset="UTF-8">

`   `<title>Document</title>

</head>

<body>

`   `<h1>Heading 1</h1>

`   `<h2>Heading 2</h2>

`   `<h3>Heading 3</h3>

`   `<h4>Heading 4</h4>

`   `<h5>Heading 5</h5>

`   `<h6>Heading 6</h6>

</body>

</html>



**Output**

**Heading 1**
## <a name="_x2i8ngvhi60y"></a>**Heading 2**
### <a name="_k82fgx803red"></a>**Heading 3**
#### <a name="_1nrwfjrth0w5"></a>**Heading 4**
##### <a name="_neb57r8a30iv"></a>**Heading 5**
###### <a name="_4n0sn2tirz7"></a>**Heading 6**

**Paragraph**

In HTML, each paragraph has to be wrapped in a <p> element.

**Example**

<!DOCTYPE html>

<html lang="en">

<head>

`   `<meta charset="UTF-8">

`   `<title>Document</title>

</head>

<body>

`   `<h1>Heading 1</h1>

`   `<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.

`       `Tempora cumque perferendis qui.</p>

</body>

</html>


***Output***

**Heading 1**

Lorem ipsum dolor, sit amet consectetur adipiscing elit. Tempora cumque perferendis qui.

***Note*** 

***Lorem is simple dummy text.***

## <a name="_d5ihgyt10754"></a>**Why  do we need structure ?**
- This is because there are no elements to give the content structure, so the browser does not know what is a heading and what is a paragraph.
- If you want your web page to show up well on search engines like Google, it's important to use headings on your page. Search engines see headings as important words, and without them, your page might not do well in search results. Headings help improve your page's SEO, making it more likely to be found by people searching for related topics.
- People who have severe visual impairments often don't read web pages visually; instead, they use a tool called a screen reader. This software reads the content of the page aloud. To help users navigate quickly, screen readers rely on headings. Headings act like a guide, allowing users to jump to specific sections of the content. Without headings, visually impaired users would have to listen to the entire document, making it more difficult for them to find the information they're looking for.



**What is semantic HTML** 

Semantic HTML means using specific HTML elements that tell us something about the structure and content of a webpage. These elements not only control how things look but also show what the content means. Semantic HTML is important because it helps create web pages that are easy for everyone to use, organised well, and understood by both regular browsers and special tools like screen readers.

For instance, using semantic HTML includes using tags like `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`, and specific heading tags (`<h1>` to `<h6>`) in the right way to organise your content. Instead of just using general tags like `<div>` or `<span>` for everything, semantic HTML gives more information to the elements. This makes it simpler for both people and computers to figure out how the webpage is set up.

In short, semantic HTML means picking HTML tags that truly say what's inside, making websites easier to use, improving how they show up in search engines, and making everything clearer in web development.

**List**

In HTML, there are two types of lists: ordered lists and unordered lists.

1. **Ordered list**
- Ordered lists are lists in which the order of the items *does* matter. 
- Every ordered list begins with a “<ol>” element, which encloses all the list items.
- Each list item is enclosed or wrapped in an “<li>” element.


**Example** 

***If  we create a roadmap for a developer, and order is important*** 

**<!DOCTYPE html>**

**<html lang="en">**

**<head>**

`   `**<meta charset="UTF-8">**

`   `**<title>Document</title>**

**</head>**

**<body>**

`   `**<ol>**

`       `**<li>HTML</li>**

`       `**<li>CSS</li>**

`       `**<li>Javascript</li>**  

`   `**</ol>**

**</body>**

**</html>**


Output

1. HTML
1. CSS
1. Javascript

**2. Unordered list**

- Unordered lists are used to mark up lists of items for which the order of the items doesn't matter.
- Every ordered list begins with a “<ul>” element, which encloses all the list items.
- Each list item is enclosed or wrapped in an “<li>” element.

**Example**

***If you create a shopping list where order is not important.***

***<!DOCTYPE html>***

***<html lang="en">***

***<head>***

`   `***<meta charset="UTF-8">***

`   `***<title>Document</title>***

***</head>***

***<body>***

`   `***<ul>***

`       `***<li>Milk</li>***

`       `***<li>bread</li>***

`       `***<li>butter</li>***  

`   `***</ul>***

***</body>***

***</html>***



Output

- Milk
- Bread
- Butter

**Emphasis and Importance**

In human language, we often emphasise certain words to alter the meaning of a sentence, and we often want to mark certain words as important or different in some way. HTML provides various semantic elements to allow us to mark up textual content with such effects, and in this section, we'll look at a few of the most common ones.

**Emphasis**

When we want to emphasise something in speech, we stress specific words, subtly changing the meaning of our message. Similarly, in writing, we often emphasise words by putting them in italics.

**Example**

**I am glad you weren't late.**

**I am *glad* you weren't *late*.**

**The first sentence sounds truly relieved that the person wasn't late. On the other hand, the second one, with both the words "glad" and "late" in italics, sounds sarcastic or indirectly expressing annoyance that the person arrived a bit late.**

In HTML, we use the “<em>”(emphasis) element to mark such instances. This not only makes the document more engaging to read but is also acknowledged by screen readers. Screen readers can be set up to speak these emphasised parts in a different tone of voice.

**Strong Importance**

To highlight important words, we typically emphasise them when speaking and make them bold in written language.

**Example**

This liquid is **highly toxic.**

I am counting on you. **Do not** be late!

In HTML, we use the “<strong>”(strong importance) element to mark such instances. This not only makes the document more helpful but is also acknowledged by screen readers. Screen readers can be set up to speak these strongly emphasised parts in a different tone of voice. Browsers automatically style this as bold text, but it's important to note that you shouldn't use this tag only to achieve bold styling.

**Hyperlink** 

Hyperlinks are a fascinating aspect of the internet. They've been around since the early days of the web and are what gives the web its interconnected nature. Hyperlinks enable us to connect documents to other documents or resources, link to specific sections of documents, or provide access to applications at a web address. Virtually any web content can be turned into a link. When clicked or activated, the web browser takes you to another web address.

- A basic link is created by wrapping the text or other content inside an <a> element and using the href attribute, also known as a Hypertext Reference.

**Example**

**<!DOCTYPE html>**

**<html lang="en">**

**<head>**

`   `**<meta charset="UTF-8">**

`   `**<title>Document</title>**

**</head>**

**<body>**

**<a herf=”https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction\_to\_HTML/Creating\_hyperlinks”>**

`       `**Click on me</a>**


**</body>**

**</html>**

## <a name="_7jekre9eypct"></a>**Adding supporting information with title attribute**
You might also want to include another thing with your links, called a "title." The title gives extra information about the link, like the type of information on the linked page or important things to know about the website. This makes it so that when you hover over the link, the title shows up as a tooltip.

## <a name="_4k3qh8d2ake6"></a>**Document and Web Structure**
Webpages can and will look pretty different from one another, but they all tend to share similar standard components, unless the page is displaying a fullscreen video or game, is part of some kind of art project, or is just badly structured:

1. ***Header:***

`  `- A big strip at the top with a large heading, logo, and maybe a tagline. Stays the same on different webpages.

1. ***Navigation Bar:***

`  `- Links to the main sections of the site, usually in the form of buttons, links, or tabs. Consistency is crucial to avoid confusing users. Some say it's part of the header, while others think separating them is better for accessibility.

1. ***Main Content:***

`  `- The central area that holds the unique content of a webpage, like the video, main story, map, or news headlines. This part varies from page to page.

1. ***Sidebar:***

`  `- Extra info, links, quotes, ads, etc. Often related to the main content (e.g., on a news article page, it might have the author's bio or links to related articles). Sometimes, recurring elements or a secondary navigation system are present.




1. ***Footer:***

`  `- A strip at the bottom of the page with fine print, copyright notices, or contact info. Similar to the header, it holds common information, but it's usually less critical. It's also used for SEO by providing quick links to popular content.

## <a name="_2f4aklbfywml"></a>**Quotation**
The element you use depends on whether you are marking up a block or inline quotation.

***Blockquotes***

If you have block-level content, like a paragraph, multiple paragraphs, or a list, that comes from somewhere else, you should put it inside a <blockquote> element. This helps show that the content is a quote. Additionally, you can include a web link to the source of the quote using the ***cite*** attribute.

- Browser default styling will render this as an indented paragraph, as an indicator that it is a quote

<!DOCTYPE html>

<html>

<head>

`   `<meta charset="UTF-8">

`   `<title>Document</title>

</head>

<body>

`   `<h1>Normal Text</h1>

`   `<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus vitae rerum eum iusto repudiandae, ratione ad error perspiciatis corporis reprehenderit quibusdam. Ratione autem eum odit inventore vel soluta eos laboriosam quibusdam, dolor eveniet!</p>

`  `<h2>Blockquote</h2>

`   `<blockquote cite="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction\_to\_HTML/Advanced\_text\_formatting">

`   `<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores in ducimus deleniti, vitae explicabo quas, minus, voluptatum ipsum perspiciatis cumque a quisquam aliquid ratione quis quam neque repellendus? Ea ut veniam quae cupiditate.</p></blockquote>

</body>

</html>

***Output***
# <a name="_o024vk7gta6"></a>*Normal Text*
*Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus vitae rerum eum iusto repudiandae, ratione ad error perspiciatis corporis reprehenderit quibusdam. Ratione autem eum odit inventore vel soluta eos laboriosam quibusdam, dolor eveniet!*
## <a name="_fj3bv8xgwjyx"></a>***Blockquote***
*Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores in ducimus deleniti, vitae explicabo quas, minus, voluptatum ipsum perspiciatis cumque a quisquam aliquid ratione quis quam neque repellendus? Ea ut veniam quae cupiditate.*

**Inline Quotations**

Inline quotations function in the same manner, but they use the <q> element.

- Browser default styling will render this as normal text put in quotes .

<!DOCTYPE html>

<html>

<head>

`   `<meta charset="UTF-8">

`   `<title>Document</title>

</head>

<body>

`   `<h1>Normal Text</h1>

`   `<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus vitae rerum eum iusto repudiandae, ratione ad error perspiciatis corporis reprehenderit quibusdam. Ratione autem eum odit inventore vel soluta eos laboriosam quibusdam, dolor eveniet!</p>

`  `<h2>Inlinequotes</h2>

`  `<q cite="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction\_to\_HTML/Advanced\_text\_formatting">

`   `Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis velit voluptatem nostrum laboriosam cumque veniam molestias? Officia suscipit maxime eligendi earum commodi inventore error, harum, adipisci fugiat eos, consectetur explicabo est aperiam architecto?

`  `</q>

</body>

</html>

***Output***
# <a name="_wpbhwjk9k2gb"></a>***Normal Text***
***Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus vitae rerum eum iusto repudiandae, ratione ad error perspiciatis corporis reprehenderit quibusdam. Ratione autem eum odit inventore vel soluta eos laboriosam quibusdam, dolor eveniet!***
## <a name="_dlfrbj565mm3"></a>***Inlinequotes***
***“Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis velit voluptatem nostrum laboriosam cumque veniam molestias? Officia suscipit maxime eligendi earum commodi inventore error, harum, adipisci fugiat eos, consectetur explicabo est aperiam architecto?”***

**Citations**

- The information in the cite attribute might seem useful, but unfortunately, browsers and screen readers don't often make use of it.
- Browsers don't have a built-in way to directly show the content of the cite attribute. It doesn't visibly appear to users viewing the page.

**Abbreviation**

- Use the <abbr> element on the web to enclose abbreviations or acronyms.
- When introducing an abbreviation for the first time, include the full expansion of the term in plain text.
- Wrap the abbreviation with the <abbr> tags to mark it up.
- This practice informs all users of the abbreviation's meaning and provides a hint to user agents on displaying or announcing the content.

**Marking up contact details**

HTML has a specific element for formatting contact details, and it's called <address>. You use this element to enclose your contact information.


<!DOCTYPE html>

<html>

<head>

`   `<meta charset="UTF-8">

`   `<title>Document</title>

</head>

<body>

`   `<address>

`       `House no- 1362A sector 48<br>

`       `Faridabad <br>

`       `Haryana<br>

`   `</address>

</body>

</html>

***Output***

*House no- 1362A sector 48*

*Faridabad*

*Haryana*

**Superscript and Subscript**

Sometimes, when you're marking up things like dates, chemical formulas, or mathematical equations in HTML, you might need to use superscript and subscript to ensure they have the correct meaning. To do this, you use the ***<sup> element for superscript and the <sub> element for subscript.***







![](Aspose.Words.25de6710-6df8-4126-a62b-b898da011939.002.png)





































# <a name="_ak38hrt9302r"></a>**Cascading Style sheet**

## <a name="_rbkpyy1rn87"></a>**There are 3 ways to connect CSS  in our document** 
- Internal CSS
- External CSS
- Inline CSS

**Internal CSS**

The `<link>` element tells the browser where to find a stylesheet using the 'rel' attribute, which indicates the relationship between the current document and the linked resource, and the 'href' attribute, which specifies the location of the stylesheet. To check if the CSS is working, you can add a rule to the 'styles.css' file. Open your code editor and include the following rule in your CSS file.

<!DOCTYPE html>

<html lang="en">

<head>

`    `<meta charset="UTF-8">

`    `<meta name="viewport" content="width=device-width, initial-scale=1.0">

`    `<title>Document</title>

`    `<link rel="stylesheet" href="styles.css" />

</head>

<body>



</body>

</html>


This `<link>` element informs the browser that a stylesheet is present, using the 'rel' attribute to define its relationship, and specifying the location of the stylesheet with the 'href' attribute. To verify that the CSS is functioning correctly, you can add a rule to the 'styles.css' file.


## <a name="_rjavh597gmxh"></a>**Importance of CSS Priority in the file**
The priority of CSS rules is important because it determines which styles are

applied to an element when there are conflicting rules or multiple CSS applied

to a single element
## <a name="_dg5t2oxolh49"></a>**CSS Order of Priority**
1\. Inline styles

2\. Internal styles

3\. External style

**Changing the priority order**

If you want the rules in the external stylesheet to be prioritised over the rules in

the internal stylesheet, you should include the external stylesheet after the

internal stylesheet in the head of the document.

It's generally a good idea to use external stylesheets for most of your CSS, and

only use internal style sheets in specific cases where you need to override

those styles. This helps to keep your styles organised and maintainable.

## <a name="_pnhxb8mlw0x6"></a>**Selectors in CSS**
- CSS selectors are used to choose HTML elements for styling purposes.
- They constitute a fundamental aspect of CSS manipulation.
- In essence, selectors serve as patterns to designate elements to which styles are applied.
- CSS selectors can target elements based on their:

  Type

`  `Class

`  `ID

`  `Attributes

`  `Dynamic state or position




**Types of CSS Selectors**

We can divide CSS selectors into five categories:

1\. Simple selectors.

2\. Combinators.

3\. Attribute selectors.

4\. Pseudo-class selectors.

5\. Pseudo-elements selectors.

***NOTE: CSS Selectors cannot be used with inline CSS.***

**Simple Selectors**

A simple selector is either a type selector or a universal selector. Simple

selectors are pretty straightforward and used most of the time in

Development.

Simple Selectors include

1\. Universal Selector.

2\. Element Selector.

3\. Class Selector.

4\. ID Selector.

5\. Selector list.

**Universal Selector**

The universal selector(\*) applies the same styles to every element on the

Page.

*Asterisk (\*): symbol denotes the universal selector in CSS*.

**Element Selector**

The Element Selector only selects all the instances of a tag or element present

on the webpage.

**Class Selector**

The CSS class selector is probably the most useful and used selector, it selects

all elements that have given the class value in their class attribute.

To select elements with a specific class, write a period (.) character, followed

by the name of the class.

**ID Selector**

ID selectors are the most powerful in terms of CSS specificity, just like the class

selector, it targets specific elements in our HTML document that we can then

use as a reference in our CSS.

To select an element with a specific id, write a hash (#) character, followed by

the id of the element.

***NOTE: IDs must be always unique and each element must have only one id to identify the element uniquely.***

**Selector List**

The CSS selector list (,) allows us to select multiple elements with different

selectors at once and style them. We have more than one thing which uses

the same CSS then the individual selectors can be combined into a selector

list so that the rule is applied to all of the individual selectors.

This is done by grouping them in a comma-separated list and CSS selects all

the matching elements in the list.

**CSS Combinators**

A CSS selector can contain more than one simple selector.Between the simple selectors, we can include a combinator.

Combinator Selectors include

1\. Descendent selector.

2\. Child selector.

3\. Adjacent sibling selector.

4\. General sibling selector.

**Descendent selector**

Descendent in general means the one who is under or the one who is a child Element.This selector allows us to select elements that are descendants of some

other selector. The descendant selector uses a space character to target an element that is a descendant of another element.

**Child selector**

The child selector is also called a direct selector. It can only target the direct or immediate child of the parent selector.

The > combinator acts more like the descendant combinator except that it is more particular and selects direct children of the parent element.

**Adjacent sibling selector**

The + combinator selects adjacent element siblings.It will select only the element that is immediately after the mentioned element.

**General sibling selector**

The CSS general sibling selector is used to select all elements that follow the first element such that all are children of the same parent.

**Attribute selectors**

The [attribute="value"] selector is used to select elements with a specified attribute and value.

**[attribute~="value"] Selector**

The [attribute~="value"] selector is used to select elements with an attribute value containing a specified word.

**[attribute|="value"] Selector**

The [attribute|="value"] selector is used to select elements with the specified

attribute, whose value can be exactly the specified value or the specified

value followed by a hyphen (-).

**[attribute^="value"] Selector**

The [attribute^="value"] selector is used to select elements with the specified

attribute, whose value starts with the specified value.

**[attribute$="value"] Selector**

The [attribute$="value"] selector is used to select elements whose attribute

value ends with a specified value.

**Introduction to fonts**

Fonts are an essential aspect of design and can greatly affect the look and

feel of a website or document.

● They can also play a role in how easily the content is understood and

absorbed by the reader. Different fonts can convey different tones and

moods, so it's important to choose a font that is appropriate for the context

and aligns with a project's overall design and branding.

● Consistent font throughout a project helps to create a cohesive and

professional look.






## <a name="_v5yf19f401ux"></a>**Introduction to Google Fonts**
Google Fonts is a library of free, open-source fonts that you can use on your web

projects.

● It was launched in 2010 and has since become one of the most popular sources for web fonts, with over 800 fonts available.

● The fonts are optimised for the web and can be easily integrated into a website by including a link to the Google Fonts in the HTML file.

● The fonts are free to use and can be easily customised.

● Google Fonts also consists of a range of useful tools, such as the ability to preview and compare different fonts and generate the necessary code for implementation.

**Adding Google Fonts to a Web Project**

Step 1: Browse the Google Fonts library

Step 2: Select the fonts and customise the styles.

Step 3: Generate the code for adding the fonts to your project.

Step 4: Use the fonts in your CSS.

## <a name="_2u0050oktveb"></a>**What is Box Model**
The term "box model" is used when discussing a web application's  design and layout.

● It is a box that wraps around every HTML element.

● It consists of: margins, borders, padding, and the actual content.

**Margin**

When no defined borders surround an element, a space is created using the CSS

margin attributes.

● You have complete control over the margins through CSS. Each side of an element can have its margin set using attributes (top, right, bottom, and left)

.

● You have complete control over the margins through CSS. Each side of an

element can have its margin set using attributes (top, right, bottom, and left).

● CSS has properties for specifying the margin for each side of an element:

1\. margin-top

2\. margin-right

3\. margin-bottom

4\. margin-left

***Eg.***

***margin-top: 100px;***

***margin-bottom: 100px;***

***margin-right: 150px;***

***margin-left: 80px;***

**Margins**

Margin properties can have the following values:



● auto - when the browser calculates the margin

● length - specifies a margin in terms of px, pt, cm, etc.

● % - specifies a margin in % of the width of the containing element

● inherit - specifies that margin would be inherited from the parent element

***Note: Negative values are also allowed.***

Margin - Shorthand Property :

it is acceptable to specify all the margin properties in one go. You may specify all or

less (eg. only two margin property etc)

***Eg. margin: 75px 100px;***

***Here, top and bottom margins would be 75px and right and left margin would be 100px***

**Padding**

All the padding properties can have the following values:

● length - specifies a padding in px, pt, cm, etc.

● % - specifies a padding in % of the width of the containing element

● inherit - specifies that the padding should be inherited from the parent element

***Note: Negative values are not allowed.***

***Eg.***

***div {***

***padding-top: 50px;***

***padding-right: 30px;***

***padding-bottom: 50px;***

***padding-left: 80px;***

***}***

**Padding - Shorthand Property** 

To shorten the code, it is possible to specify all the padding properties in one property.

- ` `If the padding property has four values then it may be specified as:

padding: 25px 50px 75px 100px; and the values are clearly assigned.

- ` `But, padding can have lesser values as well, it purely depends on how many you wish to specify/as per requirement.

If the padding property has three values:

***padding: 25px 50px 75px;***

` `***top padding is 25px***

` `***right and left paddings are 50px***

***bottom padding is 75px***

## <a name="_iwt2feg12dq"></a>**Flex**
The Flexible Box Layout Module, which is popularly known as Flexbox, is a powerful way of designing the efficient and responsive layout in CSS.

**Some fundamental terminologies of Flexbox**

1\. Flex Container

2\. Flex Items

3\. Main Axis

4\. Cross Axis

**Benefits of using Flexbox**

It helps us to create one-dimensional layout and provides much more flexibility

and control over the layout design. It also allows us to put our elements in a row or

column within our layout.

One can easily distribute the space between elements within a flex container.

**Different flexbox property**

Flexbox offers a variety of properties to create layout efficiently. Generally we can

`           `categorise the flexbox properties into two parts-

1\. Flex Container Properties

2\. Flex Items Properties

**Flex Container Property**

These are the properties that are used over the flex container (parent container).

Flex container properties are as follows-

a. Display

b. flex-direction

c. flex-wrap

d. flex-flow

e. justify-content

f. align-items

g. align-content

h. gap

`    `i. row-gap

`    `ii. Column-gap

**Flex Items Property**

These are the properties that are used over the flex items (child elements). Flex items properties are as follows-

a. Order

b. flex-grow

c. flex-shrink

d. flex-basis

e. flex

f. align-self

**Display property**

It is used to define a flex container. After defining a flex container using display flex or inline-flex, it will enable a flex context for all its direct children and will allow

users can use flex properties over the flex container and its flex items respectively.

**Difference between flex and inline-flex**

The major difference between two is that the display:inline-flex will make the flex

container display inline but will not make flex items display inline.

**Flex Direction Property**

It is used to define the direction in which all the flex items should be laid out. By

default the flex direction of a flex container is row to which we can change by using this property.

There can be four values of a flex direction-

1\. Row

2\. row-reverse

3\. column

4\. Column-reverse


**Flex Wrap Property**

This property is used to define whether the flex items should wrap themself to fit

the container width or not if the total required width of flex items are more than the

flex container width.

Flex wrap can have three possible values-

1\. Nowrap

2\. wrap

3\. Wrap-reverse

**Flex Flow Property**

It is a shorthand property for setting both flex-direction and flex-wrap properties in

one line.

Syntax- flex-flow: flex-direction flex-wrap

**Justify Content Property**

It is used to align the flex items along with the main axis of the container within the

flexbox layout.

It can have these possible values-

1\. Flex-start

2\. flex-end

3\. center

4\. space-between

5\. space-around

6\. Space-evenly

**Align Items Property**

It is used to align the flex items along with the cross axis of the container within the flexbox layout.

It can have these possible values-

1\. Stretch

2\. flex-start

3\. flex-end

4\. center

5\. Baseline

**Gap Property**

This property defines the amount of space between the rows and columns of a flex container. The gap is a shorthand property for defining the row-gap and

Column-gap.

Syntax

1\. gap:10px;

***This is similar to row-gap:10px and column-gap:10px***

`           `2. gap:10px 20px

***This is similar to row-gap:10px and column-gap:20px***

## <a name="_132b9ottrjup"></a>**Grid**
An intersection of vertical and horizontal lines is known as a grid.

● Major sections of a page are separated using CSS Grid layout.

● A grid-based layout system with rows and columns is provided by the grid attribute. It eliminates the need for positioning and floating, making web page

creation simple.

● The grid layout enables us to construct grid structures represented in CSS rather than HTML.

● The user can align the pieces into rows and columns like a table. But using the

CSS grid to construct a layout is simpler than using tables.

## <a name="_bbwgi66ybm4"></a>**Properties associated with grid items**
● Grid-row: defines on which row to place an item. You can also state here,

where the item will start, and where the item will end. To place an item, you

can either use line numbers, or use span to define how many columns the

item will span.

● Grid-column: defines on which column the item is to be placed. Like a row,

here too, it can be stated where the item will start and end. Here again, you

can either use line numbers, or use span to define how many columns the

item will span.

● Grid-area: For the attributes grid-row-start, grid-column-start,

grid-row-end, and grid-column-end, the grid-area property can be used

as a shorthand.

● Naming grid: grid-area property can also be used to assign names to grid

Items.

## <a name="_uktqtd57o3dg"></a>**Benefits of grid :**
● Grid Layout enables us to clearly distinguish between the visual display of elements and their order in the source.

● Code reduction The columns, rows, and grid tracks for your grid are built within your CSS rather than as separate HTML elements.

● Smaller file size There is no requirement for huge frameworks like Bootstrap in your projects because CSS Grid is native.

● Developmental pace CSS Grid makes prototyping quick and easy after you master the syntax.

● Two-dimensional layouts Rows and columns are respected in a two-dimensional grid. If an element's cell cannot accommodate it, the row and/or column will expand to accommodate it. For the layout of pages and forms, a grid is excellent.

● Grids in Nests Smaller components like content sections with









## <a name="_gq55ehtzd405"></a>**Reference** 

[**https://developer.mozilla.org/en-US/docs/Web/HTML**](https://developer.mozilla.org/en-US/docs/Web/HTML)

[**https://developer.mozilla.org/en-US/docs/Web/CSS**](https://developer.mozilla.org/en-US/docs/Web/CSS)

[**https://www.w3schools.com/html/**](https://www.w3schools.com/html/)

[**https://www.w3schools.com/css/**](https://www.w3schools.com/css/)


