What are the features of CSS3?
-------------------------------
Features of CSS3
* Animations.
* Multiple Backgrounds & Gradient.
* Multiple Column layouts.
* Opacity.
* Rounded Corner:
* Selectors. Advanced


How To Add CSS
---------------
There are three ways of inserting a style sheet:

•	External CSS-
To add a style sheet to HTML, we use the <link> tag in the header section of HTML page, like this:
 
•	Internal CSS
If you do not want to have a separate style sheet then you can simply write your CSS in the head section of HTML page.

        <head>
        <style> h1 {color:#008000;} p {margin-left:10px;} body {text-align:center;}
        </style>
        </head>

•	Inline CSS
You can code the CSS along with the HTML tags itself.

        <p style="color:blue; font-size: 16px; margin:20px;">This is the content of my paragraph</p>


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

* visibility:hidden - The element is in the DOM but its not visible.
* display:none - The element is not in the DOM its does not exist inside the DOM.

Z-Index
-----------
* The z-index property specifies the stack order of an element.

* An element with greater stack order is always in front of an element with a lower stack order.
Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display:flex elements).

* Note: If two positioned elements overlap without a z-index specified, the element positioned last in the HTML code will be shown on top.

Overflow
---------- 
* The overflow property specifies what should happen if content overflows an element's box.
* This property specifies whether to clip content or to add scrollbars when an element's content is too big to fit in a specified area.
* Note: The overflow property only works for block elements with a specified height.
* overflow-x and overflow-y to control horizontal and vertical overflow separately.

        CSS overflow types:

        visible – Default. Content spills out.
        hidden – Extra content is clipped (no scroll).
        scroll – Always shows scrollbars.
        auto – Scrollbars appear only when needed.
        clip – Clips content, no scroll allowed.


What is a Media Query?
---------------------------
Media queries can be used to check many things, such as:
    •	width and height of the viewport
    •	width and height of the device
    •	orientation (is the tablet/phone in landscape or portrait mode?)
    •	resolution

        /* Extra small devices (phones, 600px and down) */ @media only screen and (max-width: 600px) {...}
        /* Small devices (portrait tablets and large phones, 600px and up) */
        @media only screen and (min-width: 600px) {...}
        /* Medium devices (landscape tablets, 768px and up) */
        @media only screen and (min-width: 768px) {...}
        /* Large devices (laptops/desktops, 992px and up) */
        @media only screen and (min-width: 992px) {...}
        /* Extra large devices (large laptops and desktops, 1200px and up) */
        @media only screen and (min-width: 1200px) {...}

        Orientation: Portrait / Landscape
        @media only screen and (orientation: landscape) { body {
        background-color: lightblue;
        }
        }

🔹 All CSS Pseudo-Classes (:)
-------------------------------
        📌 User Action / UI State
        :hover
        :active
        :focus
        :focus-visible
        :focus-within
        :target
        :enabled
        :disabled
        :checked
        :indeterminate
        :default
        :valid
        :invalid
        :in-range
        :out-of-range
        :required
        :optional
        :read-only
        :read-write
        :placeholder-shown
        📌 Structural / Tree-Related
        :root
        :empty
        :first-child
        :last-child
        :only-child
        :nth-child(n)
        :nth-last-child(n)
        :first-of-type
        :last-of-type
        :only-of-type
        :nth-of-type(n)
        :nth-last-of-type(n)
        📌 Logical / Negation
        :not(selector)
        :is(selector)
        :where(selector)
        :has(selector) (experimental, supported in modern browsers)
        📌 Link States
        :link
        :visited
        :any-link
        :local-link
        📌 Language / Direction
        :lang(language)
        :dir(ltr|rtl)
        📌 Miscellaneous
        :fullscreen
        :picture-in-picture
        :defined (for custom elements)
------------------------------------------------------------------------------------------------
🔸 All CSS Pseudo-Elements (::)
--------------------------------
        📌 Content Insertion
        ::before
        ::after
        📌 Text Styling
        ::first-letter
        ::first-line
        ::selection
        ::spelling-error
        ::grammar-error
        📌 Form Elements
        ::placeholder
        ::file-selector-button
        📌 Lists and UI
        ::marker
        ::cue (for WebVTT captions)
        ::cue-region
        📌 Media and Dialogs
        ::backdrop
        ::slotted(selector) (for Shadow DOM)


