<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Dulces</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff4081;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .product {
            background-color: white;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 20px;
            width: 200px;
            text-align: center;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .product:hover {
            transform: translateY(-10px);
        }

        .product img {
            width: 100%;
            border-radius: 8px;
        }

        .product h3 {
            color: #333;
            font-size: 1.2em;
        }

        .product p {
            color: #777;
            font-size: 1em;
        }

        .price {
            color: #ff4081;
            font-size: 1.2em;
            font-weight: bold;
        }

        .product button {
            background-color: #ff4081;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
        }

        .product button:hover {
            background-color: #f50057;
        }

    </style>
</head>
<body>

<header>
    <h1>Tienda de Dulces</h1>
    <p>¡Los mejores dulces a tu alcance!</p>
</header>

<div class="container">
    <!-- Producto 1 -->
    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Sprat Multi Sabor">
        <h3>Sprat Multisabor</h3>
        <p>Refrescante bebida sabor a varios frutas.</p>
        <div class="price">$350</div>
        <button onclick="window.location.href='https://docs.google.com/forms/d/e/1FAIpQLSdTNK-WrfvC5kGCkC1RzMIMWiN9Ol9a1doPzAH8y0OWjYpe2A/viewform?usp=header'">Encargar</button>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Chicles Grosso">
        <h3>Chicles Grosso</h3>
        <p>Chicles de limón con un toque ácido.</p>
        <div class="price">$150</div>
        <button onclick="window.location.href='https://docs.google.com/forms/d/e/1FAIpQLSdTNK-WrfvC5kGCkC1RzMIMWiN9Ol9a1doPzAH8y0OWjYpe2A/viewform?usp=header'">Encargar</button>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Jaleas Multisabor">
        <h3>Jaleas Multisabor</h3>
        <p>Gelatina en diferentes sabores, suaves y deliciosas.</p>
        <div class="price">$100</div>
        <button onclick="window.location.href='https://docs.google.com/forms/d/e/1FAIpQLSdTNK-WrfvC5kGCkC1RzMIMWiN9Ol9a1doPzAH8y0OWjYpe2A/viewform?usp=header'">Encargar</button>
    </div>

    <!-- Producto 4 -->
    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Gomitas Mogul Ácidas">
        <h3>Gomitas Mogul Ácidas</h3>
        <p>Gomitas en diferentes colores con sabor ácido.</p>
        <div class="price">$350</div>
        <button onclick="window.location.href='https://docs.google.com/forms/d/e/1FAIpQLSdTNK-WrfvC5kGCkC1RzMIMWiN9Ol9a1doPzAH8y0OWjYpe2A/viewform?usp=header'">Encargar</button>
    </div>
</div>

</body>
</html>
