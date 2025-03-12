
<!DOCTYPE html>
<html>
<head>
	<title>Menu Card</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		
		.menu-card {
			width: 300px;
			height: 400px;
			background-color: #f7f7f7;
			padding: 20px;
			margin: 50px auto;
			border: 1px solid #ddd;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		
		.menu-card h1 {
			margin-top: 0;
			font-size: 24px;
			color: #333;
		}
		
		.menu-item {
			margin-bottom: 20px;
		}
		
		.menu-item h2 {
			margin-top: 0;
			font-size: 18px;
			color: #666;
		}
		
		.menu-item p {
			font-size: 14px;
			color: #999;
		}
		
		.price {
			font-size: 16px;
			color: #333;
			font-weight: bold;
		}
	</style>
</head>
<body>
	<div class="menu-card">
		<h1>Today's Special</h1>
		<div class="menu-item">
			<h2>Grilled Chicken Burger</h2>
			<p>Tender grilled chicken, crispy bacon, melted cheddar cheese, lettuce, tomato, and mayo on a toasted brioche bun.</p>
			<span class="price">$12.99</span>
		</div>
		<div class="menu-item">
			<h2>Crispy Fish Tacos</h2>
			<p>Beer-battered cod, shredded lettuce, diced tomatoes, sliced avocado, and chipotle tartar sauce in a crispy corn tortilla.</p>
			<span class="price">$10.99</span>
		</div>
		<div class="menu-item">
			<h2>Vegetarian Quinoa Bowl</h2>
			<p>Roasted vegetables, quinoa, mixed greens, and a citrus vinaigrette dressing.</p>
			<span class="price">$9.99</span>
		</div>
	</div>
</body>
</html>

CSS code:
/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  color: #333;
  background-color: #f7f7f7;
}

/* Header Styles */

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 24px;
}

/* Navigation Styles */

nav {
  background-color: #444;
  color: #fff;
  padding: 10px;
  text-align: center;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: space-between;
}

nav li {
  margin-right: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

/* Main Content Styles */

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

section {
  background-color: #f7f7f7;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
  margin-top: 0;
  font-size: 18px;
}

p {
  font-size: 14px;
  color: #666;
}

/* Footer Styles */

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
  clear: both;
}

footer p {
  margin: 0;
  font-size: 12px;
}

/* Responsive Design */

@media only screen and (max-width: 768px) {
  main {
    flex-direction: column;
  }
  section {
    margin-bottom: 10px;
  }
}

@media only screen and (max-width: 480px) {
  header h1 {
    font-size: 18px;
  }
  nav {
    padding: 5px;
  }
  nav ul {
    flex-direction: column;
  }
  nav li {
    margin-right: 0;
  }
}
