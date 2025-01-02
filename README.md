<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NoamShop - חנות אינטרנטית</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            color: #000;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 20px 1%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h2 {
            font-size: 1.2em;
            margin-top: 10px;
        }
        .product p {
            font-size: 1.1em;
            color: #555;
        }
        .product .price {
            font-size: 1.2em;
            color: green;
            margin-top: 10px;
        }
        .product button {
            background-color: #000;
            color: white;
            border: none;
            padding: 10px;
            font-size: 1em;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        .product button:hover {
            background-color: #444;
        }
        footer {
            background-color: #000;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>NoamShop - חנות אינטרנטית</h1>
</header>

<div class="container">
    <h2>מוצרים שלנו</h2>

    <div class="product">
        <img src="https://via.placeholder.com/300" alt="מוצר 1">
        <h2>מוצר 1</h2>
        <p>תיאור קצר של המוצר הזה</p>
        <p class="price">מחיר: ₪100</p>
        <button onclick="alert('המוצר נוסף לעגלת הקניות')">הוסף לעגלה</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/300" alt="מוצר 2">
        <h2>מוצר 2</h2>
        <p>תיאור קצר של המוצר הזה</p>
        <p class="price">מחיר: ₪150</p>
        <button onclick="alert('המוצר נוסף לעגלת הקניות')">הוסף לעגלה</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/300" alt="מוצר 3">
        <h2>מוצר 3</h2>
        <p>תיאור קצר של המוצר הזה</p>
        <p class="price">מחיר: ₪200</p>
        <button onclick="alert('המוצר נוסף לעגלת הקניות')">הוסף לעגלה</button>
    </div>
</div>

<footer>
    <p>&copy; 2025 NoamShop - כל הזכויות שמורות</p>
</footer>

</body>
</html>
