# Details and Summary Tags

The <details> tag specifies additional details that the user can open and close on demand.

The <details> tag is often used to create an interactive widget that the user can open and close. By default, the widget is closed. When open, it expands, and displays the content within.

Any sort of content can be put inside the <details> tag. 

The <summary> tag is used in conjuction with <details> to specify a visible heading for the details.

The <summary> tag defines a visible heading for the <details> element. The heading can be clicked to view/hide the details.

The <summary> element should be the first child element of the <details> element.

```HTML
<details>
    <summary>HTML</summary>
    <div>
      <h2>HTML</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>

  <details>
    <summary>CSS</summary>
    <div>
      <h2>CSS</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>

  <details>
    <summary>JavaScript</summary>
    <div>
      <h2>JavaScript</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>

  <details>
    <summary>Express JS</summary>
    <div>
      <h2>Express JS</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>

  <details>
    <summary>Java</summary>
    <div>
      <h2>Java</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>

  <details>
    <summary>SpringBoot</summary>
    <div>
      <h2>SpringBoot</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
        non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </details>
```

```CSS
body {
      font-family: Arial, Helvetica, sans-serif;
    }

    details {
      background: linear-gradient(45deg, black, darkred);
      padding: 15px;
      color: white;
      width: 60%;
      box-shadow: 0 5px 10px black;
      border-radius: 5px;
      margin:15px;
    }

    details summary {
      outline: none;
    }

    details div {
      background: linear-gradient(45deg, darkred, orangered);
      padding: 10px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 5px 10px whitesmoke;
    }
```

You can check out the [Demo](https://praveenoruganti.github.io/praveenoruganti-html/18_Details_Summary/Demo).

### [Buy me a Coffee](http://bit.ly/2WryDT8)