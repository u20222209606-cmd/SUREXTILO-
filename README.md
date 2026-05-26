<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda - Tu Marca</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            background: #f9f9f9;
        }
        header {
            background: #000;
            color: white;
            padding: 15px 5%;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo { font-size: 26px; font-weight: bold; }
        nav { display: flex; justify-content: space-between; align-items: center; }
        .menu a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            font-weight: 500;
        }

        .filtro {
            padding: 20px 5%;
            background: white;
            text-align: center;
        }

        .productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            padding: 30px 5%;
        }

        .producto {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: 0.3s;
        }
        .producto:hover {
            transform: scale(1.05);
        }
        .producto img {
            width: 100%;
            height: 320px;
            object-fit: cover;
        }
        .info {
            padding: 15px;
            text-align: center;
        }
        .info h3 { margin: 10px 0; }
        .precio {
            color: #e63939;
            font-size: 1.3rem;
            font-weight: bold;
        }
        .btn-comprar {
            margin-top: 10px;
            background: #000;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <div class="logo">TU MARCA</div>
            <div class="menu">
                <a href="index.html">Inicio</a>
                <a href="#">Tienda</a>
                <a href="#">Categorías</a>
            </div>
        </nav>
    </header>

    <div class="filtro">
        <h2>🛍️ Nuestra Tienda</h2>
        <p>Explora nuestra colección completa</p>
    </div>

    <div class="productos">
        <div class="producto">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="">
            <div class="info">
                <h3>Camiseta Oversize Negra</h3>
                <p class="precio">$45.000</p>
                <button class="btn-comprar">Agregar al carrito</button>
            </div>
        </div>

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1542272604-787c3835535d" alt="">
            <div class="info">
                <h3>Jeans Cargo Beige</h3>
                <p class="precio">$89.000</p>
                <button class="btn-comprar">Agregar al carrito</button>
            </div>
        </div>

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1591047139829-d91aecb6caea" alt="">
            <div class="info">
                <h3>Hoodie Gris Premium</h3>
                <p class="precio">$95.000</p>
                <button class="btn-comprar">Agregar al carrito</button>
            </div>
        </div>

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1586790170083-2f9ceadc732d" alt="">
            <div class="info">
                <h3>Chaqueta Jeans</h3>
                <p class="precio">$125.000</p>
                <button class="btn-comprar">Agregar al carrito</button>
            </div>
        </div>
    </div>

</body>
</html>
