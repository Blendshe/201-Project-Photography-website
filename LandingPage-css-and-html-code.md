```
body {
    margin: 0px;
  }
  .header {
    border: 1px solid black;
  }
  .main {
    border: 1px solid black;
  }
  .footer {
    border: 1px solid black;
  }
  .images {
    border: 4px solid darkblue;
    padding: 2px;
    margin: 20px;
    width: 400px;
    height: 200px;
    background-color: lightblue;
  }
  ul {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
  }
  li {
    margin: 5px;
  }
  ```

```
<html>
  <head>
    <title>201-Project-Flexbox-Landing-Page</title>

    <link rel="stylesheet" href="201-Project-LandingPage.css" />
  </head>

  <body>
    <div class="header">
      <h1>Header Landing Page</h1>

      <a href="details.html">Go to Details Page</a>
      <a href="form.html">Go to Form Page</a>
    </div>

    <div class="main">
      <ul style="list-style-type: none">
        <li class="images">photo1</li>
        <li class="images">photo2</li>
        <li class="images">photo3</li>
        <li class="images">photo4</li>
        <li class="images">photo5</li>
        <li class="images">photo6</li>
        <li class="images">photo7</li>
        <li class="images">photo8</li>
      </ul>
    </div>

    <!--<div class="footer">
      <h1>Footer</h1>
      <button onclick="clickedLandscape()">Landscape</button>
      <button onclick="clickedBeach()">Beach</button>
      <button onclick="clickedPeople()">People</button>
    </div>-->
  </body>
</html>
```
