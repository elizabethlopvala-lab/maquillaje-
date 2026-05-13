<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beauty Glam</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#fff0f5;
      color:#333;
    }

    header{
      background:linear-gradient(90deg,#ff69b4,#ff1493);
      color:white;
      padding:20px;
      text-align:center;
    }

    nav{
      background:#ffb6c1;
      padding:10px;
      text-align:center;
    }

    nav a{
      color:#fff;
      text-decoration:none;
      margin:0 15px;
      font-weight:bold;
    }

    .hero{
      height:400px;
      background:url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9') center/cover;
      display:flex;
      justify-content:center;
      align-items:center;
      color:white;
      text-align:center;
    }

    .hero h1{
      background:rgba(0,0,0,0.5);
      padding:20px;
      border-radius:10px;
      font-size:50px;
    }

    .productos{
      padding:40px;
      text-align:center;
    }

    .productos h2{
      margin-bottom:30px;
      color:#ff1493;
    }

    .cards{
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:20px;
    }

    .card{
      background:white;
      width:250px;
      border-radius:15px;
      overflow:hidden;
      box-shadow:0 4px 10px rgba(0,0,0,0.2);
      transition:0.3s;
    }

    .card:hover{
      transform:scale(1.05);
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card h3{
      margin:15px 0;
    }

    .card p{
      padding:0 10px 15px;
    }

    .btn{
      display:inline-block;
      margin-bottom:20px;
      padding:10px 20px;
      background:#ff1493;
      color:white;
      text-decoration:none;
      border-radius:8px;
    }

    footer{
      background:#ff69b4;
      color:white;
      text-align:center;
      padding:15px;
      margin-top:30px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Beauty Glam</h1>
    <p>Tu mundo de maquillaje y belleza</p>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Productos</a>
    <a href="#">Ofertas</a>
    <a href="#">Contacto</a>
  </nav>

  <section class="hero">
    <h1>Brilla con tu belleza</h1>
  </section>

  <section class="productos">
    <h2>Nuestros Productos</h2>

    <div class="cards">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796" alt="Labial">
        <h3>Labiales</h3>
        <p>Colores intensos y duraderos.</p>
        <a href="#" class="btn">Comprar</a>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1596462502278-27bfdc403348" alt="Maquillaje">
        <h3>Sombras</h3>
        <p>Paletas modernas y elegantes.</p>
        <a href="#" class="btn">Comprar</a>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1526045478516-99145907023c" alt="Brochas">
        <h3>Brochas</h3>
        <p>Herramientas profesionales.</p>
        <a href="#" class="btn">Comprar</a>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2026 Beauty Glam | Página de maquillaje</p>
  </footer>

</body>
</html># maquillaje-