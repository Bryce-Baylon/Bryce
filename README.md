<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Shopping</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #ff69b4; /* Pink color */
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #ff69b4; /* Pink color */
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #fff;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ff85c0; /* Slightly lighter pink on hover */
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #d3d3d3; /* Grey color */
        }
        .products {
            display: flex;
            justify-content: space-around;
        }
        .product {
            background-color: #fff;
            padding: 15px;
            border: 1px solid #ddd;
            width: 30%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            margin: 5px 0;
        }
        .product input[type="number"] {
            width: 50px;
            padding: 5px;
            margin-top: 10px;
        }
        .product button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 8px 16px;
            margin-left: 10px;
            cursor: pointer;
            border-radius: 4px;
        }
        .product button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #ff69b4; /* Pink color */
            color: #fff;
            text-align: center;
            padding: 80px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>SHOOPPEE</h1>
</header>

<nav>
    <a href="#">HOME</a>
    <a href="#">ABOUT US</a>
    <a href="#">PRODUCTS</a>
    <a href="#">SIGN UP</a>
</nav>

<div class="container">
    <h2>Online Shopping</h2>
    <div class="products">
        <div class="product">
            <img src="placeholder.jpg" alt="Product Image">
            <h3>Product Name:</h3>
            <p>Price: </p>
            <p>
                QTY: <input type="number" min="1" value="1">
                <button>Add</button>
            </p>
        </div>
        <div class="product">
            <img src="placeholder.jpg" alt="Product Image">
            <h3>Product Name: </h3>
            <p>Price: </p>
            <p>
                QTY: <input type="number" min="1" value="1">
                <button>Add</button>
            </p>
        </div>
        <div class="product">
            <img src="placeholder.jpg" alt="Product Image">
            <h3>Product Name: </h3>
            <p>Price: </p>
            <p>
                QTY: <input type="number" min="1" value="1">
                <button>Add</button>
            </p>
        </div>
    </div>
</div>

<footer>
</footer>

</body>
</html>
