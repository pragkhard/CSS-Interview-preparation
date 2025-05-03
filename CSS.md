What is CSS Box Model?
------------------------
The CSS box model is essentially a box that wraps around every HTML Element. IT contains of margin, border, padding and the actual content.

Difference between Relative and Absolute position?
----------------------------------------------------

Relative - position relative that means element relative to its current position without changing the layout around it

Absolute - position absolute places an element relative to its parents position and changing the layout around it.

![alt text](image.png)

Difference between visibility hidden and displaynone?
------------------------------------------------------

visibility:hidden - The element is in the DOM but its not visible.
display:none - The element is not in the DOM its does not exist inside the DOM.

Z-Index
-----------
* The z-index property specifies the stack order of an element.

* An element with greater stack order is always in front of an element with a lower stack order.
Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display:flex elements).

* Note: If two positioned elements overlap without a z-index specified, the element positioned last in the HTML code will be shown on top.

