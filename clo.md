
    1. [At rules](#at-rules)
3. [Another paragraph](#paragraph2)

## Properties and Selectors of course

## W3 link: <a name="w3"></a>
[Named after the letter M, the em unit has a long-standing tradition in typography where it has been used to measure horizontal widths. For example, the long dash (—) often found in American texts is known as an em dash because historically, it has had the same width as the letter M.](https://www.w3.org/Style/LieBos3e/em.en.html#:~:text=Named%20after%20the%20letter%20M,width%20as%20the%20letter%20M.)
### At rules DGC3
At-rules in CSS are instructions for the browser that start with an "@" symbol.They go beyond the standard CSS properties and selectors. They are used to define various directives, conditions and special behaviours within the CSS stylesheet. They can be used to define various behaviors, import external resources, set media queries, define keyframes for animations, and more. An `@import` at rule can be used to import a resource such as a font file or a CSS file. The browser then fetches the resource and applies it to the current stylesheet.
#### Fetching a resource
In order to do this the browser will stop parsing the current CSS file when it encounters the `@import` rule and it will make a request to fetch the external resource. This resource can be any supported resource like a CSS file or a font file.
Only after applying the imported resouce it will continue parsing the rest of the stylesheet. This is to ensure that any prerequisite for the rules that follow will be imported it the right order. For instance an imported font will be available for use in the rest of the stylesheet as a consequence of this the webpage is rendered with the combined styles from the the css file and the imported resources.
#### Modularizing
The `@import` at rule is usefull for modularizing the CSS code, reuse styles across multiple files and seperate concerns. You also get to use external resources that other people may have provided and it doesn't have to be included in your project. It goes without saying that every import requires an additional HTTP request so you will increase the load times of the webpage if you don't limit the number of import statements.
# Table of contents <a name="TOC"></a>
1. [W3](#w3)
# C
[TOC][def]
##### cpas Dte
In CSS, the @import rule is used to import external style sheets or resources into the current style sheet. When you use @import to import a resource, such as a font or another CSS file, several things happen behind the scenes:

Parsing the CSS File:
When the browser encounters an @import rule in a CSS file, it stops parsing the current file and fetches the resource specified in the @import rule.
The browser then parses the imported resource as if its contents were directly included in the original CSS file.
Fetching the Resource:
The browser makes an HTTP request to fetch the external resource specified in the @import rule.
If the resource is a CSS file, the browser downloads the file and processes its contents.
Applying the Imported Styles:
Once the external resource is fetched and parsed, the styles defined in that resource are applied to the elements in the document.
This allows you to use styles, fonts, or other resources defined in the imported file within the current CSS file.
Order of Import:
It's important to note that @import rules must precede all other rules in a CSS file, except for @charset rules.
The imported styles are applied in the order they are imported, so the order of @import rules can affect the cascade of styles.
Loading and Rendering:
Importing external resources using @import can impact the loading and rendering performance of a webpage.
Multiple @import rules can result in additional HTTP requests, potentially slowing down the loading of the page.
Specificity and Inheritance:
Styles imported using @import have the same specificity and inheritance rules as other styles in the CSS file.
Imported styles can cascade and override existing styles based on specificity and order of declaration.
Overall, the @import rule in CSS provides a way to modularize styles, reuse resources, and manage the organization of CSS files. It allows for better code organization and separation of concerns by breaking up styles into different files and importing them where needed.


[def]: #TOC