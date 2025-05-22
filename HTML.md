                <!DOCTYPE html>
                ===============

<!DOCTYPE>
tag is used to inform the browser about the version of HTML used in the document. It is called as the document type declaration (DTD).
here are many type of HTML e.g. HTML 4.01 Strict, HTML 4.01 Transitional, HTML 4.01 Frameset, XHTML 1.0 Strict, XHTML 1.0 Transitional, XHTML 1.0 Frameset, XHTML 1.1 etc.
The doctype declaration differs between HTML versions. the valid Doctype declaration for each version of HTML.
        HTML 5
        <!DOCTYPE HTML>
        HTML 4.01
        Strict
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
        "http://www.w3.org/TR/html4/strict.dtd">
        Transitional
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
        "http://www.w3.org/TR/html4/loose.dtd">
        Frameset
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
        "http://www.w3.org/TR/html4/frameset.dtd">
        XHTML 1.0
        Strict (quick reference)
        <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
        "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
        Transitional
        <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
        "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
        Frameset
        <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN"
        "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">

So by matching with the standard Doctype ,you can find out the version of HTML file .
It is an instruction to the web browser about what version of HTML the page is written in.
Tips: always add the doctype declaration to your HTML documentations, so the browser knowwhat type of document to expect.
Tag we are using in html5- figure, caption.

------------------------------------------------------------------------------------------------------

        If I do not put <!DOCTYPE html> will HTML 5 work?
        ----------------------------------------------------
* No, the browser will not be able to identify that it is an HTML document and HTML 5 tags do not function properly.
* If we are not written <!doctype> code will run perfectly. We are facing the problem at the time of Validation, search engine.
* For example: new features & tags in HTML5 such as <article>,<footer>, <header>,<nav>, <section> may not be supported if the <!DOCTYPE> is not declared.

------------------------------------------------------------------------------------------------------

                <html lang="en-US">
               ----------------------
It basically a Lang attribute. Always use a lang attribute on the html tag to declare the default lang. of the text in the page. When the page contain in another lang, add a lang attribute to an element surrounding that content.
Helpful in Search engine optimization.
------------------------------------------------------------------------------------------------------

Diff between Inline & Block level element?
-------------------------------------------

* Block level element-> Block level element always starts on a new line and takes up the full width available(Stretches out to the left and right as far as it can).

                Ex- <h1>, <p>, <div>, <li>

* Inline element-> Inline element does not start on a new line and only takes up as much width as necessary. Inline element does not accept width and height values as well as margin top and margin bottom.

                Ex- <span>, <a>, <img>

* Inline-block- Inline-block it is the combination of the inline and block element. It does not start on new line but we can set width and height.

------------------------------------------------------------------------------------------------------

New tags in HTML5?
----------------------
New semantic element- header, section, footer, nav etc.
New graphics element- svg, canvas.
New muiltimedia elements- audio, video New form element- details, keygen etc.

------------------------------------------------------------------------------------------------------

what is semantic element?
---------------------------
* Semantic element- element with a meaning.
* Means an element that clearly describes its meaning to both the browser and developer.
* Ex- header, form, table etc.
* Note- div , span are the non-semantic element.
------------------------------------------------------------------------------------------------------

Diff between HTML Elements and Tags?
-------------------------------------
If there is some content between start tag and end tag of html then it is know as html element otherewise html tag.
               
                <p></p> -Tag
                <p>milestone creator</p>- Element

------------------------------------------------------------------------------------------------------

Why and how are shorthand property is used give example?
----------------------------------------------------------
Ans- Using shorthand properties we can improve page load time and reduce file size
Example- padding- 10px 20px 30px 40px;

------------------------------------------------------------------------------------------------------

Diff. between Class and ID?
---------------------------------
The main difference is that the same class selector can be applied to multiple HTML Elements, whereas ID selector are unique element of the html.

------------------------------------------------------------------------------------------------------
What is viewport?
-------------------
The viewport is the visible area of the web page. The viewport varies the device and will be smaller on a mobile phone whereas it will be larger on a computer screen.

------------------------------------------------------------------------------------------------------

Diff  between <b> and <strong> or <i> and <em> tags?
--------------------------------------------
* <b> and <strong> both are used to bold the text but strong text will provide extra emphasis to the text.
* <i> and <em> both are used to italic text but <em> text will provide extra emphasis to the text.






