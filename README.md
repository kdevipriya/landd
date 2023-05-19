# landd

<!DOCTYPE html>
<html>
<head>
  <title>My Landing Page</title>
  <link rel="stylesheet" type="text/css" href="global land.css">
</head>
<body>
  <header>
    <h1>Welcome to My Landing Page about tiffins</h1>
    <nav>
      <ul>
        <li><a href="#">HOME</a></li>
        <li><a href="#">ABOUT</a></li>
        <li><a href="#">SERVICES</a></li>
        <li><a href="#">CONTACT</a></li>
      </ul>
    </nav>
  </header>


<section class="hero">
    <div class="container">
      <div class="column">
        <h2>Discover best food</h2>
        <p>Get the best offers on your favourite food orders.</p>
        <a href="#" class="btn">order Now</a>
      </div>
      <div class="column">
        <img src="C:\Users\konda\Downloads\product.jpg" alt="Product Image">
      </div>
    </div>
  </section>

<section id="HOME">
<h2>HOME</h2>
<ul>
<li>DOSA</li><img src="C:\Users\konda\Downloads\dosa.jpg" >
<li>IDLE</li><img src="C:\Users\konda\Downloads\idli.jpg">
<li>CHAPATHI</li><img src="C:\Users\konda\Downloads\chapathi.jpg">
<li>PURI</li><img src="C:\Users\konda\Downloads\puri.jpg">
<li>UPMA</li><img src= "C:\Users\konda\Downloads\upma.jpg">
</ul>
</section>



  <section id="SERVICES">
<h1>SERVICES</h1>
    <div class="container">
      <div class="column">
        <p>We provide only high-quality to our customers.</p>
      </div>
      <div class="column">
        <h3>Fast home delivery</h3>
        <p>Enjoy quick and reliable prices for all orders.</p>
      </div>
      <div class="column">
        <h3>Excellent Customer Support</h3>
        <p>Our dedicated support team is available 24/7 to assist you.</p>
      </div>
    </div>
  </section>

<section id="CONTACT">
    <h2>CONTACT</h2>
    <p>Email: kondadevipriya123@gmail.com</p>
    <p>Phone: 123-456-7890</p>
  </section>

  <footer>
    <p>&copy; 2023 My Landing Page. All rights reserved.</p>
  </footer>
</body>
</html>

/* Global Styles */
body {
  font-family: Lucide Console,Monospace;
  margin:10px;
  background-image:url("product.jpg");
  padding: 10px;
}

/* Header Styles */
header {
  background-color: black;
  padding: 20px;
 
}

h1 {
  margin: 10px;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  text-decoration: none;
  color: yellow;
}

/* Hero Section Styles */
.hero {
  background-color: light green;
  text-align: center;
  padding: 50px;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.column {
  flex-basis: 50%;
}

h2 {
  color:sky blue;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color:grey;
  color: white;
  text-decoration: none;
}

/* Features Section Styles */
.features {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: violet;
  padding: 50px;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.column {
  flex-basis:20.33%;
 
