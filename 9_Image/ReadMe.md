# Image Tag

The <img> tag is used to embed an image in an HTML page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed
Note: Also, always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.

Tip: To link an image to another document, simply nest the <img> tag inside an <a> tag (see example below).

```HTML

<h2>Image1</h2>
<img src="../0_All/img/image1.jpg" width="600" height="400" alt="Image1" />

<h2>Image2</h2>
<img src="../0_All/img/image2.jpg" width="600" height="400" alt="Image2" />

<h2>Image3</h2>
<img id="photo" src="../0_All/img/image3.jpg" width="600" height="400" alt="Image3" />

<h2>Image4</h2>
<img src="../0_All/img/image4.jpg" width="600" height="400" alt="Image4" />

<h2>Image5</h2>
<img src="https://leaderonomics.com/wp-content/uploads/2017/10/jess-770x470.jpg" width="600" height="400"
    alt="Image5" />

```

```CSS
h2 {
    font-family: 'Courier New', Courier, monospace;
}

#photo {
    border: 10px solid saddlebrown;
    padding: 5px;
}

img {
    box-shadow: 5px 10px 20px black;
    margin: 10px;
    border-radius: 10px;
}

```

You can check out the [Demo](https://praveenoruganti.github.io/praveenoruganti-html/9_Image/Demo).

### [Buy me a Coffee](http://bit.ly/2WryDT8)