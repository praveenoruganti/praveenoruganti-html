# iFrame Tag

The <iframe> tag specifies an inline frame.

An inline frame is used to embed another document within the current HTML document.

Use CSS to style the <iframe> (see example below).

It is a good practice to always include a title attribute for the <iframe>. This is used by screen readers to read out what the content of the <iframe> is.

**HTML**

```HTML

<h2> Internal Webpage</h2>
<iframe src="./9_Image/index.html" width=500 height=300></iframe>

<h2> External Webpage</h2>
<iframe src="https://praveenorugantitech.blogspot.com" title="praveenorugantitech" width=500 height=300></iframe>

<h2>Youtube Video</h2>
<iframe width="500" height="300" src="https://www.youtube.com/embed/eBcYKDUT8fs" frameborder="0" allow="accelerometer; autoplay; encrypted-media;
        gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>PDF Reader</h2>
<iframe src="../../0_All/img/oops.pdf" width=500 height=300></iframe>

<h2>Google Maps</h2>
<iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d30452.37085272319!2d78.54283011145931!3d17.433544989338188!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xd2d04009a502a51c!2sSaiBaba%20Temple!5e0!3m2!1sen!2sin!4v1599507655171!5m2!1sen!2sin"
    width="500" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false"
    tabindex="0"></iframe>

<h2>360 Degree Image</h2>
<iframe
    src="https://momento360.com/e/u/f8202fbbb255420da8659a94de732d24?utm_campaign=embed&utm_source=other&heading=-61.173581928316366&pitch=7.008391809537988&field-of-view=47.5"
    width=500 height=300 frameborder=0 />

```

**CSS**

```CSS
body {
    margin-bottom: 500px
}

h2 {
    font-family: 'Courier New', Courier, monospace;
}

iframe {
    box-shadow: 0 5px 10px black;
}
```

You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/12_iFrame/Demo){:target="_blank"}.



