# Aside Tag

The <aside> tag defines some content aside from the content it is placed in.

The aside content should be indirectly related to the surrounding content.

The <aside> content is often placed as a sidebar in a document.

**Note**: The <aside> element does not render as anything special in a browser. However, you can use CSS to style the <aside> element.


**HTML**

```HTML
<aside>
    <img src="../../0_All/img/PraveenOruganti.jpg" alt="Praveen Oruganti" />
    <a href="">HTML</a>
    <a href="">CSS</a>
    <a href="">JavaScript</a>
    <a href="">JAVA</a>
    <a href="">SpringBoot</a>
    <a href="">PCF</a>
    <a href="">MicroServices</a>
</aside>

```

**CSS**

```CSS
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
}

aside {
    background: linear-gradient(45deg, darkred, black, red);
    float: left;
    width: 250px;
    text-align: center;
    box-shadow: 0 5px 10px black;
    height: 100vh;
    padding: 10px;
}

aside a {
    display: block;
    color: white;
    text-decoration: none;
    font-size: 18px;
    padding: 14px 25px;
}

aside a:hover {
    background: linear-gradient(45deg, deeppink, coral);
    border-radius: 50px;
    box-shadow: 0 0 5px black;
}

aside img {
    width: 150px;
    height: 150px;
    border: 10px solid black;
    ;
    border-radius: 50%;
    box-shadow: 0 0 5px black;
    margin-bottom: 20px;
}

```

You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/15_Aside/Demo).

<script data-name="BMC-Widget" src="https://cdnjs.buymeacoffee.com/1.0.0/widget.prod.min.js" data-id="praveenoruganti" data-description="Support me on Buy me a coffee!" data-message="Thank you for visiting. You can now buy me a coffee!" data-color="#5F7FFF" data-position="Right" data-x_margin="18" data-y_margin="18"></script>


