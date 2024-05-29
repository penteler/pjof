# Table of contents
1. [W3](#w3)
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