# Lesson One Recap

We spoke about the different elements such as the H1 - H6 tags, p tags, a (anchor) tags, unordered lists and list items, image tags, and div tags. These are some of the most common tags that are used to build websites!

## Heading Tags
If you remember when you used to write essays for school you usually had one big heading as the title of your document and then subsequent heading tags to denote the different paragraphs you were talking about. This same approach can be used in HTML! Where h1 is used for your main heading on your page and h2 and h3 are usually grouped with divs on a page.

```html
<h1>My Recipe Book</h1>
<div>
    <h2>World Famous Cookies</h2>
    <p>...</p>
</div>
```

## Anchor tags
Anchor tags or `a` tags are very simple! Essentially they are used to help you navigate around your website. The most important attribute for an anchor tag is the `href=''` attribute. This will tell the anchor tag exactly what page to navigate to in your website.

## Unordered Lists and List Items
In HTML if you want to have a list of items we usually use the unordered list element `<ul></ul>`. This element is a parent wrapper and requies you to wrap the appropriate child element for it to work. In this case the child element is the `<li></li>` element.

## Div
Div elements don't have any special purpose and can be used for a wide range of functionality. Sometimes you want a line that separates your text and elements. Or you just want to group and organize your page -- divs are like a swiss army knife they can be used for many things! One of the most common uses of a div is to group elements together like this:

```html
<h1>My Recipe Book</h1>
<div>
    <h2>World Famous Cookies</h2>
    <img src="..." alt="..." />
    <p>...</p>
</div>
```

## Image
The `<img>` HTML element embeds an image into the document. It requires a `src` attribute because this tells you where to grab the image from and it also takes an `alt` attribute. The `alt` attribute holds a textual representation of the image which is mandatory and useful for accesibility 

## Home Work
Build a very simple recipe website that has 3 recipes group together with a div. Use list items to list out the required ingredients and an image with the width and height properties to make the size of the image fit the page.

# Word Bank
- HTML Document
- Block Level vs Inline Level
- HTML Attributes
- Rendering (displaying content)
- hyperlink (href)