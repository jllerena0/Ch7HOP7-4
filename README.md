# Ch7HOP7-4

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chapter 7 HOP 7.4</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    
    #wrapper {
      display: grid;
      grid-template-columns: 150px 1fr;
      grid-template-rows: 100px auto 50px;
      max-width: 1200px;
      min-width: 960px;
      margin: 0 auto;
      background-color: #B3C7E6;
      color: #000066;
    }

    header {
      grid-row: 1 / 2;
      grid-column: 1 / 3;
      background-color: #869DC7;
      color: #00005D;
      font-size: 150%;
      padding: 10px;
      text-align: center;
    }

    nav {
      grid-row: 2 / 3;
      grid-column: 1 / 2;
      background-color: #B3C7E6;
      padding: 10px;
      font-weight: bold;
    }

    nav ul {
      list-style-type: none;
    }

    nav a {
      display: block;
      padding: 10px;
      text-decoration: none;
      color: #00005D;
    }

    nav a:hover {
      background-color: #869DC7;
      color: #FFF;
    }

    main {
      grid-row: 2 / 3;
      grid-column: 2 / 3;
      background-color: #FFF;
      padding: 20px;
    }

    #floatright {
      float: right;
      margin: 10px;
      max-width: 200px;
    }

    footer {
      grid-row: 3 / 4;
      grid-column: 1 / 3;
      background-color: #869DC7;
      text-align: center;
      font-size: 80%;
      padding: 10px;
    }
  </style>
</head>
<body>
  <div id="wrapper">
    <header>
      <h1>Lighthouse Island Bistro</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Directions</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

    <main>
      <h2>Locally Roasted Free-Trade Coffee</h2>
      <p>
        <img src="images/light2.jpg" alt="Lighthouse image" id="floatright">
        Indulge in the aroma of freshly brewed coffee with a conscience. Our beans are locally roasted and sourced through fair trade partnerships, ensuring farmers are paid fairly and communities thrive. Enjoy a cup today!
      </p>
    </main>

    <footer>
      <p>&copy; 2025 Lighthouse Island Bistro</p>
    </footer>
  </div>
</body>
</html>
