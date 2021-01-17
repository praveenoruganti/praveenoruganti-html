


# Header and Footer Tags





## Header Tag
The <header> element represents a container for introductory content or a set of navigational links.

A <header> element typically contains:
- one or more heading elements (<h1> - <h6>)
- logo or icon
- authorship information
**Note**: You can have several <header> elements in one HTML document. However, <header> cannot be placed within a <footer>, <address> or another <header> element.

# Footer Tag
The <footer> tag defines a footer for a document or section.

A <footer> element typically contains:
- authorship information
- copyright information
- contact information
- sitemap
- back to top links
- related documents

You can have several <footer> elements in one document.

Contact information inside a <footer> element should go inside an <address> tag.


**HTML**

```HTML
<header>
  <h1>Praveen Oruganti Technologies</h1>
</header>
<section>
  <article>
    <h2>Praveen Oruganti Technologies Training</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </article>
  <article>
    <h2>Core Java Training</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </article>
  <article>
    <h2>SpringBoot Training</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </article>
  <article>
    <h2>React Training</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
      non proident, sunt in culpa qui officia deserunt mollit anim id est
      laborum.</p>
  </article>
</section>

<footer>
  <h3>&copy;2020-2021 Praveen Oruganti Technologies</h3>
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
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    text-align: center;
  }

  section {
    padding-top: 150px;
    width: 80%;
    margin: 0 auto;
  }

  article h2 {
    color: blue;
    border-radius: 50%;
    width: 800px;
    margin: auto;
    box-shadow: 0 0 10px black;
    background: black;

  }

  article p {
    font-size: 18px;
    color: darkslategray;
  }


  header {
    width: 100%;
    position: fixed;
    background: black;
    padding: 10px 0;
    color: #fff;
  }

  header {
    top: 0;
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


You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/14_Header_Footer/Demo){:target="_blank"}.




