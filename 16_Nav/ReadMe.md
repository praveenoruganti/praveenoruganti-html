# Nav Tag

The <nav> tag defines a set of navigation links.

Notice that NOT all links of a document should be inside a <nav> element. The <nav> element is intended only for major block of navigation links.

Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

**HTML**

```HTML
<header>
    <h1>Praveen Oruganti Technologies</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#aboutus">About Us</a>
      <a href="#contactus">Contact Us</a>
      <a href="#courses">Courses</a>
      <a href="#careers">Careers</a>
    </nav>
  </header>
  <section id="home">
    <h2>Home</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </section>

  <section id="aboutus">
    <h2>About us</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </section>

  <section id="contactus">
    <h2>Contact us</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </section>

  <section id="courses">
    <h2>Courses</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </section>

  <section id="careers">
    <h2>Careers</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </section>

  <footer>
    <h3>&copy;2021 Praveen Oruganti Technologies</h3>
    <p>All Rights Reserved</p>
    <p>
      Developed & Maintaned by
      <a href="https://praveenorugantitech.blogspot.com" target="blank">
        Praveen Oruganti
      </a>
    </p>
  </footer>
```

**CSS**

```CSS
html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      text-align: center;
    }

    header {
      background: white url(../../0_All/img/image3.jpg) no-repeat scroll center;
      background-size: cover;
      color: white;
      box-shadow: 0 0 10px black;
      text-shadow: 0 3px 3px black;
      top: 0;
      position: fixed;

      width: 100%;
    }

    nav {
      background: black;
      box-shadow: 0 0 10px black;
      padding: 5px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 18px;
      padding: 10px 25px;
      display: inline-block;
    }

    nav a:hover {
      background: lightgreen;
      color: black;
    }

    section {
      background: linear-gradient(45deg, black, darkred);
      color: white;
      font-family: "Comic Sans MS", sans-serif;
      padding: 15px;
      margin: 15px;
      border-radius: 15px;
      box-shadow: 0 5px 10px black;
    }

    #home {
      margin: 0 auto;
      padding-top: 160px;
    }

    section {
      margin: 0;
      scroll-margin-top: 10em;
    }

    footer {
      background: black;
      box-shadow: 0 0 10px black;
      color: white;
      padding: 3px;
    }

    footer a {
      color: lightblue;
      text-decoration: none;
    }

    footer a:hover {
      background: lightgreen;
      color: black;
    }
```

You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/16_Nav/Demo).

### [Buy me a Book](https://bit.ly/388sUbE)


