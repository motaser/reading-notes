# Layout

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

* **position:static** In normal flow, each block-level
element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow,

* **position:relative** Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right.

* **position:absolute** When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

* **position:fixed** Fixed positioning is a type of absolute positioning that requires the position property
to have a value of fixed.


* **float** The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

* **clear** The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.

* **link** on this page you can see the other technique for including multiple style sheets. Inside the <head> element is a separate <link> element for each style sheet.

1. <div> elements are often used as containing elements
to group together sections of a page.
2. Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
3. The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
4. Pages can be fixed width or liquid (stretchy) layouts.
5. Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
6. Grids help create professional and flexible designs.
7. CSS Frameworks provide rules for common tasks.
