# CafeMenuFCC
# HTML


1. `<!DOCTYPE html>`: This is a document type declaration and tells the browser that this document is an HTML5 document.

2. `<html lang="en">`: This is the opening tag for the HTML document. The `lang="en"` attribute specifies that the language of the document is English.

3. `<head>`: This is the opening tag for the head section of the document. The head section contains meta-information about the document, such as its title, character encoding, and links to stylesheets or scripts.

4. `<meta charset="utf-8" />`: This meta tag specifies the character encoding of the document, which is UTF-8, a widely used character encoding for websites.

5. `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: This meta tag sets the viewport properties. It ensures that the webpage is displayed correctly on devices with different screen sizes by setting the initial scale to 1.0 and the width to the device's width.

6. `<title>Cafe Menu</title>`: This tag sets the title of the webpage, which is displayed in the browser's title bar or tab.

7. `<link href="styles.css" rel="stylesheet"/>`: This tag links an external stylesheet (`styles.css`) to the HTML document, allowing for the styling of the webpage.

8. `<body>`: This is the opening tag for the body section of the document. The body section contains the content of the webpage that is displayed to the user.

9. `<div class="menu">`: This is a `div` element with a class of "menu". It is used to group related content together.

10. `<main>`: This tag defines the main content of the webpage.

11. `<h1>CAMPER CAFE</h1>`: This is a heading element (`h1`) that displays the name of the cafe.

12. `<p class="established">Est. 2020</p>`: This is a paragraph element (`p`) with a class of "established", indicating the establishment year of the cafe.

13. `<hr>`: This tag represents a thematic break or horizontal rule, which is used here as a visual separator.

14. `<section>`: This tag defines a section of the webpage. There are two sections in this document, one for coffee and one for desserts.

15. `<h2>Coffee</h2>`: This is a heading element (`h2`) that indicates the section is about coffee.

16. `<img src="..." alt="...">`: This tag inserts an image (`img`) into the webpage. The `src` attribute specifies the URL of the image, and the `alt` attribute provides alternative text for the image.

17. `<article class="item">`: This tag defines an article element with a class of "item", representing a menu item.

18. `<p class="flavor">French Vanilla</p><p class="price">3.00</p>`: These are paragraph elements (`p`) with classes of "flavor" and "price", respectively, displaying the flavor and price of a coffee item.

19. `<footer>`: This tag defines the footer section of the webpage, typically containing information such as copyright notices or links.

20. `<a href="..." target="_blank">Visit our website</a>`: This is an anchor (`a`) element that creates a hyperlink to another webpage. The `href` attribute specifies the URL, and the `target="_blank"` attribute opens the link in a new tab.

21. `<p class="address">123 Free Code Camp Drive</p>`: This is a paragraph element (`p`) with a class of "address", displaying the address of the cafe.

22. `</body>`: This is the closing tag for the body section of the document.

23. `</html>`: This is the closing tag for the HTML document.

# CSS



1. `body`: This selector targets the `<body>` element of the HTML document.

   - `background-image`: Sets the background image of the body.
   - `font-family`: Sets the font family for the text in the body.
   - `padding`: Adds padding around the content of the body.

2. `h1`: This selector targets all `<h1>` elements in the document.

   - `font-size`: Sets the font size of the heading.
   - `margin-top`, `margin-bottom`: Sets the top and bottom margins of the heading.

3. `h2`: This selector targets all `<h2>` elements in the document.

   - `font-size`: Sets the font size of the heading.

4. `.established`: This selector targets elements with a class of "established".

   - `font-style`: Sets the font style to italic.

5. `h1, h2, p`: This selector targets all `<h1>`, `<h2>`, and `<p>` elements in the document.

   - `text-align`: Aligns the text to the center.

6. `.menu`: This selector targets elements with a class of "menu".

   - `width`: Sets the width of the element.
   - `background-color`: Sets the background color of the element.
   - `margin-left`, `margin-right`: Centers the element horizontally.
   - `padding`: Adds padding around the content of the element.
   - `max-width`: Sets the maximum width of the element.

7. `img`: This selector targets all `<img>` elements in the document.

   - `display`: Sets the display property to block, which allows the image to be centered.
   - `margin-left`, `margin-right`: Centers the image horizontally.

8. `hr`: This selector targets all `<hr>` elements in the document.

   - `height`: Sets the height of the horizontal rule.
   - `background-color`, `border-color`: Sets the color of the horizontal rule.

9. `.bottom-line`: This selector targets elements with a class of "bottom-line".

   - `margin-top`: Sets the top margin of the element.

10. `h1, h2`: This selector targets all `<h1>` and `<h2>` elements in the document.

    - `font-family`: Sets the font family of the headings.

11. `.item p`: This selector targets `<p>` elements inside elements with a class of "item".

    - `display`: Sets the display property to inline-block, which allows the paragraphs to be displayed next to each other.
    - `margin-top`, `margin-bottom`: Sets the top and bottom margins of the paragraphs.
    - `font-size`: Sets the font size of the paragraphs.

12. `.flavor, .dessert`: This selector targets elements with a class of "flavor" or "dessert".

    - `text-align`: Aligns the text to the left.
    - `width`: Sets the width of the element.

13. `.price`: This selector targets elements with a class of "price".

    - `text-align`: Aligns the text to the right.
    - `width`: Sets the width of the element.

14. `footer`: This selector targets the `<footer>` element in the document.

    - `font-size`: Sets the font size of the text in the footer.

15. `.address`: This selector targets elements with a class of "address".

    - `margin-bottom`: Sets the bottom margin of the element.

16. `a`: This selector targets all `<a>` elements in the document.

    - `color`: Sets the text color of the link.

17. `a:visited`: This selector targets visited `<a>` elements in the document.

    - `color`: Sets the text color of the visited link.

18. `a:hover`: This selector targets `<a>` elements when the mouse is over them.

    - `color`: Sets the text color of the link when hovered.

19. `a:active`: This selector targets `<a>` elements when they are being activated (clicked).

    - `color`: Sets the text color of the link when activated.