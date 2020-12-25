# Figure and Figcaption Tags

The <figure> tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

While the content of the <figure> element is related to the main flow, its position is independent of the main flow, and if removed it should not affect the flow of the document.

The <figcaption> element is used to add a caption for the <figure> element.

The <figcaption> tag defines a caption for a <figure> element.

The <figcaption> element can be placed as the first or last child of the <figure> element.

```HTML
<figure>
    <img src="../0_All/img/image1.jpg" alt="" />
    <figcaption>Image1</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image2.jpg" alt="" />
    <figcaption>Image2</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image3.jpg" alt="" />
    <figcaption>Image3</figcaption>
  </figure>

  <figure>
    <img src="../0_All/img/image1.jpg" alt="" />
    <figcaption>Image4</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image2.jpg" alt="" />
    <figcaption>Image5</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image3.jpg" alt="" />
    <figcaption>Image6</figcaption>
  </figure>

  <figure>
    <img src="../0_All/img/image1.jpg" alt="" />
    <figcaption>Image7</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image2.jpg" alt="" />
    <figcaption>Image8</figcaption>
  </figure>
  <figure>
    <img src="../0_All/img/image3.jpg" alt="" />
    <figcaption>Image9</figcaption>
  </figure>
```

```CSS
body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: black;
      text-align: center;
    }

    figure {
      width: 300px;
      text-align: center;
      padding: 5px;
      border-radius: 10px;
      background-color: orangered;
      display: inline-block;
    }

    figure:hover {
      box-shadow: 0 0 10px white;
    }

    figure img {
      width: 100%;
      border-radius: 10px;
      height: 200px;
    }

    figure figcaption {
      background: linear-gradient(45deg, darkslategrey, orangered);
      padding: 10px;
      color: white;
      border-radius: 10px;
    }
```

You can check out the [Demo](https://praveenoruganti.github.io/praveenoruganti-html/17_Figure_Figcaption/Demo).

### [Buy me a Coffee](http://bit.ly/2WryDT8)