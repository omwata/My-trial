<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Info</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      background-color: ghostwhite;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header, footer {
      background-color: gray;
      color: white;
      text-align: center;
      padding: 20px;
    }

    header img {
      display: block;
      margin: 0 auto;
    }

    header h1 {
      margin: 10px 0;
    }

    header p {
      color: white;
      font-style: italic;
      text-decoration: solid;
    }

    nav {
      text-align: center;
      margin: 20px 0;
    }

    nav h3 {
      display: inline-block;
      margin: 0 15px;
    }

    nav a {
      text-decoration: none;
      color: black;
      font-weight: bold;
      padding: 10px 20px;
      background-color: lightblue; /* Default color for non-active links */
      border-radius: 5px;
      transition: background-color 0.3s, color 0.3s;
    }

    nav a.active {
      background-color: ghostwhite; /* Matches the background color */
      color: black; /* Ensures contrast against the background */
      border: 2px solid gray; /* Optional border to indicate the active link */
    }

    nav a:hover {
      background-color: #add8e6; /* Slightly darker blue on hover */
    }

    main {
      flex: 1;
      padding: 20px;
      text-align: center;
    }

    footer p {
      margin: 5px 0;
    }

    footer p:last-of-type {
      color: black;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <img src="C:\Users\user\Desktop\Omwata\Personal\logo.png" alt="Logo" height="50" width="50">
      <h1>Tigs Collection</h1>
      <p><i><b>Dare dream</b></i></p>
    </div>
  </header>
  <nav>
    <h3><a href="Home.html" class="active">Home</a></h3>
    <h3><a href="personal info.html">Personal Information</a></h3>
    <h3><a href="Products.html">Products</a></h3>
    <h3><a href="contact.html">Contact Us</a></h3>
  </nav>
  <main>
    <p>Visit this site for a collection of designer wears at affordable prices</p>
  </main>
  <footer>
    <div class="container">
      <p>&copy; 2024 - Tigs Mwenyewe</p>
      <p style="color: black;">Contact us:</p>
      <p>Email: omwata@gmail.com</p>
      <p>Phone: +254707330710 / +254787052271</p>
    </div>
  </footer>
</body>
</html>