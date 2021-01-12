# Table Tag


- The <table> tag defines an HTML table.

- An HTML table consists of one <table> element and one or more <tr>, <th>, and <td> elements.

- The <tr> element defines a table row, the <th> element defines a table header, and the <td> element defines a table cell.

- An HTML table may also include <caption>, <colgroup>, <thead>, <tfoot>, and <tbody> elements.


**HTML**

```HTML

<h2>Simple Table</h2>
<table border="2">
    <thead>
        <th id="sno">S.No</th>
        <th id="name">Name</th>
        <th id="company">Company</th>
        <th id="city">City</th>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Praveen</td>
            <td>CTS</td>
            <td>Hyderabad</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Vipin</td>
            <td>Wipro</td>
            <td>Ireland</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Praneeth</td>
            <td>CTS</td>
            <td>UK</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Phani</td>
            <td>Tech Mahindra</td>
            <td>USA</td>
        </tr>
    </tbody>
</table>

<h2>Table with col span</h2>
<table border="2">
    <thead>
        <th id="sno">S.No</th>
        <th id="name">Name</th>
        <th colspan="2" id="cc">Company & City</th>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Praveen</td>
            <td>CTS</td>
            <td>Hyderabad</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Vipin</td>
            <td>Wipro</td>
            <td>Ireland</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Praneeth</td>
            <td>CTS</td>
            <td>UK</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Phani</td>
            <td>Tech Mahindra</td>
            <td>USA</td>
        </tr>
    </tbody>
</table>

<h2>Table with row span</h2>
<table border="2">
    <thead>
        <th id="sno">S.No</th>
        <th id="name">Name</th>
        <th id="company">Company</th>
        <th id="city">City</th>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">1</td>
            <td>Praveen</td>
            <td>CTS</td>
            <td>Hyderabad</td>
        </tr>
        <tr>
            <td>Vipin</td>
            <td>Wipro</td>
            <td>Ireland</td>
        </tr>
        <tr>
            <td rowspan="2">2</td>
            <td>Praneeth</td>
            <td>CTS</td>
            <td>UK</td>
        </tr>
        <tr>
            <td>Phani</td>
            <td>Tech Mahindra</td>
            <td>USA</td>
        </tr>
    </tbody>
</table>

<h2>Custom Table</h2>
<table id="custom">
    <thead>
        <th id="sno">S.No</th>
        <th id="name">Name</th>
        <th id="company">Company</th>
        <th id="city">City</th>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Praveen</td>
            <td>CTS</td>
            <td>Hyderabad</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Vipin</td>
            <td>Wipro</td>
            <td>Ireland</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Praneeth</td>
            <td>CTS</td>
            <td>UK</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Phani</td>
            <td>Tech Mahindra</td>
            <td>USA</td>
        </tr>
    </tbody>
</table>

```

**CSS**

```CSS
#custom,
#custom th,
#custom td {
    border: 2px solid orangered;
    border-collapse: collapse;
    padding: 10px;
}

#custom {
    width: 100%;
    text-align: center;
    font-family: 'Courier New', Courier, monospace;
    box-shadow: 0 0 10px black;
}

#custom thead {
    background-color: orangered;
    color: white;
}

#custom tbody {
    background-color: lightsalmon;
}

```
You can check out the [Demo](https://praveenorugantitech.github.io/praveenorugantitech-html/10_Table/Demo){:target="_blank"}.






