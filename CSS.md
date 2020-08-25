# Design web pages with CSS

CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

#### The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

#### CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

### CSS Properties Affect How Elements Are Displayed

#### CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

   ##### EXAMPLE :
   h1, h2, h3 {
   font-family: Arial;
   color: yellow;}
   
   ## Using External CSS
   
* The <link> element can be used in an HTML document to tell the browser where to find the CSS
file used to style the page. It is an empty element (meaning it does not need a closing tag), and it
lives inside the <head> element. It should use three attributes:
* href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
* type
This attribute specifies the type
of document being linked to. The
value should be text/css.
* rel
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.


   An HTML page can use more
than one CSS style sheet. To
do this it could have a <link>
element for every CSS file it
uses. For example, some authors
use one CSS file to control the
presentation (such as fonts and
colors) and a second to control
the layout.

## Using Internal CSS

You can also include CSS rules
within an HTML page by placing
them inside a <style> element,
which usually sits inside the
<head> element of the page.
The <style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css.
When building a site with more
than one page, you should use
an external CSS style sheet.


    
