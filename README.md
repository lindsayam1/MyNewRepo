<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="chapter4/index.html">Chapter 4</a></li>
            <li><a href="chapter5/index.html">Chapter 5</a></li>
            <li><a href="project/index.html">Project</a></li>
        </ul>
    </nav>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chapter 4</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <header>
        <h1>Chapter 4</h1>
    </header>
    <nav>
        <ul>
            <li><a href="hop.html">Hands-On Practice</a></li>
            <li><a href="../index.html">Home</a></li>
        </ul>
    </nav>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chapter 5</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <header>
        <h1>Chapter 5</h1>
    </header>
    <nav>
        <ul>
            <li><a href="hop1.html">Hands-On Practice 1</a></li>
            <li><a href="hop2.html">Hands-On Practice 2</a></li>
            <li><a href="assignment1.html">Assignment 1</a></li>
            <li><a href="../index.html">Home</a></li>
        </ul>
    </nav>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <header>
        <h1>Group Project</h1>
    </header>
    <nav>
        <ul>
            <li><a href="../index.html">Home</a></li>
        </ul>
    </nav>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
    background-color: #555;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}
<!DOCTYPE html>
<html lang="en">
<head>
<title>Chapter 6 - Lighthouse Island Bistro</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div id="wrapper">
  <div id="header">
    <h1>Chapter 6: Enhancements & Flexbox</h1>
  </div>

  <div id="nav">
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="map.html">Map</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="chapter7.html">Next: Chapter 7</a></li>
    </ul>
  </div>

  <div id="content">
    <h2>Understanding Flexbox</h2>
    <p>Flexbox is a powerful CSS tool that allows for responsive designs with minimal effort...</p>

    <h2>Key Flexbox Properties</h2>
    <ul>
      <li><code>display: flex;</code> - Defines a flex container</li>
      <li><code>justify-content</code> - Aligns items horizontally</li>
      <li><code>align-items</code> - Aligns items vertically</li>
    </ul>

    <h2>Hands-On Example</h2>
    <pre>
      #container {
        display: flex;
        justify-content: center;
        align-items: center;
      }
    </pre>
  </div>

  <div id="footer">Copyright &copy; 2025</div>
</div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<title>Chapter 7 - Lighthouse Island Bistro</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="../styles.css">
</head>
<body>
<div id="wrapper">
  <div id="header">
    <h1>Chapter 7: Grid & Responsive Design</h1>
  </div>

  <div id="nav">
    <ul>
      <li><a href="../index.html">Home</a></li>
      <li><a href="../chapter6/index.html">Chapter 6</a></li>
      <li><a href="hop.html">Hands-On Practice</a></li>
    </ul>
  </div>

  <div id="content">
    <h2>Understanding CSS Grid</h2>
    <p>CSS Grid Layout allows for complex, responsive designs using simple properties...</p>

    <h2>Grid Template Areas</h2>
    <pre>
      #wrapper {
        display: grid;
        grid-template-areas: 
          "header header header"
          "nav main aside"
          "footer footer footer";
      }
    </pre>

    <h2>Viewport Meta Tag</h2>
    <p>Ensuring mobile-friendliness by adding <code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code>.</p>
  </div>

  <div id="footer">Copyright &copy; 2025</div>
</div>
</body>
</html>

