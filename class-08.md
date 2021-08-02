# **Layout**
________________
* <div> elements are often used as containing elements to group together sections of a page.

* Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

* The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

* Pages can be fixed width or liquid (stretchy) layouts.

* Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

* Grids help create professional and flexible designs.

* CSS Frameworks provide rules for common tasks.

* You can include multiple CSS files in one page.

_____________
## **CSS Layout - The position Property**

![position](https://www.hebergementwebs.com/image/68/68bed84e7e93e5adbf41cf2f653fed5e.png/tutoriel-comment-use-position-property-css-1.png)

- position: static;

HTML elements are positioned static by default.
Static positioned elements are not affected by the top, bottom, left, and right properties.
An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:
This <div> element has position: static;

- position: relative;

An element with position: relative; is positioned relative to its normal position.
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.
This <div> element has position: relative; 

- position: fixed;

An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
A fixed element does not leave a gap in the page where it would normally have been located.

- position: absolute;

An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: A "positioned" element is one whose position is anything except static.

