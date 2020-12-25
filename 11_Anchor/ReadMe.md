# Anchor Tag

The <a> tag defines a hyperlink, which is used to link from one page to another.

The most important attribute of the <a> element is the href attribute, which indicates the link's destination.

By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red

If the <a> tag has no href attribute, it is only a placeholder for a hyperlink.

A linked page is normally displayed in the current browser window, unless you specify another target.

```HTML

<div id="home">
    <h2 style="background-color:orangered">Home Page</h2>
</div>
<h2>Simple Link / External Link</h2>
<a href="https://www.google.com">Google</a>

<h2>Simple Link / Local Link</h2>
<a href="9_HTML_Table_Tag.html">Table Page</a> |
<a href="8_HTML_Image_Tag.html">Images Page</a>

<h2>HTML Link with Target</h2>
<a href="https://github.com/praveenoruganti" target="_blank">GitHub</a>

<h2>Image as a Link with Target</h2>
<a href="https://github.com/praveenoruganti" target="_blank">
    <img src="../0_All/img/PraveenOruganti.jpg" width=200 height=100 /></a>

<h2>Send an Email</h2>
<a href="mailto:praveenorugantitech@gmail.com&Subject='Praveen Oruganti
Tech Training'">Email Me</a>

<h2>Make a Phone Call</h2>
<a href="tel:+919059341019">Call Me</a>

<h2>Download a File</h2>
<a href="../0_All/img/PraveenOruganti.jpg" download="Sample">Download</a>

<h2>HTML Link with Bookmark</h2>
<a href="#home"> Go to Home</a>

```
```CSS
html {
    scroll-behavior: smooth;
}

body {
    margin-bottom: 500px;
}

h2 {
    font-family: 'Courier New', Courier, monospace;
}
```

You can check out the [Demo](https://praveenoruganti.github.io/praveenoruganti-html/11_Anchor/Demo).


### [Buy me a Coffee](http://bit.ly/2WryDT8)