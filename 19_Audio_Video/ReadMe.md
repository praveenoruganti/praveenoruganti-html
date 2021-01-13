![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenorugantitech-express-js/master/tech.PNG)


# Audio and Video Tags


## Audio Tag

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenorugantitech-html/master/19_Audio_Video/images/Audio.PNG)

## Video Tag

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenorugantitech-html/master/19_Audio_Video/images/Video.PNG)


**HTML**

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
       <source src="../../0_All/video/video.mp4" type="video/mp4" />
      </audio>
  </div>
```

**CSS**

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

You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/19_Audio_Video/Demo){:target="_blank"}.




