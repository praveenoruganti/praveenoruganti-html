# Audio and Video Tags

## Audio Tag
The <audio> tag is used to embed sound content in a document, such as music or other audio streams.

The <audio> tag contains one or more <source> tags with different audio sources. The browser will choose the first source it supports.

The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element.

There are three supported audio formats in HTML: MP3, WAV, and OGG.

## Video Tag
The <video> tag is used to embed video content in a document, such as a movie clip or other video streams.

The <video> tag contains one or more <source> tags with different video sources. The browser will choose the first source it supports.

The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.

There are three supported video formats in HTML: MP4, WebM, and OGG.


```HTML
<h2>Audio</h2>
  <div>
    <audio controls loop autoplay>
      <source
        src="
        https://s9.naasongs.download/tely138nkr2ncsa/V%20-%20(2020)/[iSongs.info]%2002%20-%20Vasthunnaa%20Vachestunna.mp3"
        type="audio/mp3" />
    </audio>
  </div>

  <h2>Video</h2>
  <div>
    <video controls loop autoplay>
      <source src="video/video.mp4" type="video/mp4" />
      </audio>
  </div>
```

```CSS
body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: black;
    }

    h2 {
      color: white;
      font-size: 40px;
    }

    div {
      background: linear-gradient(45deg, black, orangered);
      width: 400px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 0 10px black;
      border-radius: 10px;
    }

    div video {
      width: 100%;
      outline: none;
    }

    div audio {
      outline: none;
    }
```

You can check out the [Demo](https://praveenoruganti.github.io/praveenoruganti-html/19_Audio_Video/Demo).

### [Buy me a Coffee](http://bit.ly/2WryDT8)