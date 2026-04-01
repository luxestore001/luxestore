[!DOCTYPE html.md](https://github.com/user-attachments/files/26397176/DOCTYPE.html.md)
<!DOCTYPE html>  
<html lang="ru">  
<head>  
  <meta charset="UTF-8">  
  <title>Luxury Store</title>  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <style>  
    body {  
      margin: 0;  
      font-family: Arial, sans-serif;  
      background: #0d0d0d;  
      color: white;  
    }  
  
    header {  
      display: flex;  
      justify-content: space-between;  
      padding: 20px 50px;  
      background: black;  
      border-bottom: 1px solid #222;  
    }  
  
    header h1 {  
      letter-spacing: 3px;  
    }  
  
    nav a {  
      margin-left: 20px;  
      text-decoration: none;  
      color: white;  
      opacity: 0.7;  
    }  
  
    nav a:hover {  
      opacity: 1;  
    }  
  
    .hero {  
      height: 80vh;  
      display: flex;  
      justify-content: center;  
      align-items: center;  
      text-align: center;  
      background: url('https://images.unsplash.com/photo-1521335629791-ce4aec67dd47') center/cover;  
    }  
  
    .hero h2 {  
      font-size: 48px;  
      background: rgba(0,0,0,0.5);  
      padding: 20px;  
    }  
  
    .products {  
      padding: 50px;  
      display: grid;  
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));  
      gap: 30px;  
    }  
  
    .product {  
      background: #111;  
      padding: 20px;  
      border: 1px solid #222;  
      transition: 0.3s;  
    }  
  
    .product:hover {  
      transform: translateY(-5px);  
      border-color: white;  
    }  
  
    .product img {  
      width: 100%;  
      height: 300px;  
      object-fit: cover;  
    }  
  
    .product h3 {  
      margin: 10px 0;  
    }  
  
    .product p {  
      opacity: 0.7;  
    }  
  
    .product button {  
      margin-top: 10px;  
      width: 100%;  
      padding: 10px;  
      background: white;  
      border: none;  
      cursor: pointer;  
      font-weight: bold;  
    }  
  
    footer {  
      padding: 30px;  
      text-align: center;  
      border-top: 1px solid #222;  
      margin-top: 50px;  
    }  
  </style>  
</head>  
<body>  
  
<header>  
  <h1>LUXE</h1>  
  <nav>  
    <a href="#">Главная</a>  
    <a href="#">Каталог</a>  
    <a href="#">Контакты</a>  
  </nav>  
</header>  
  
<section class="hero">  
  <h2>Эксклюзивные брендовые вещи</h2>  
</section>  
  
<section class="products">  
  
  <div class="product">  
    <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff">  
    <h3>Nike Limited</h3>  
    <p>$320</p>  
    <button>Купить</button>  
  </div>  
  
  <div class="product">  
    <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f">  
    <h3>Balenciaga Hoodie</h3>  
    <p>$850</p>  
    <button>Купить</button>  
  </div>  
  
  <div class="product">  
    <img src="https://images.unsplash.com/photo-1520975922284-9e0e4d5e3f5b">  
    <h3>Rolex Style Watch</h3>  
    <p>$1500</p>  
    <button>Купить</button>  
  </div>  
  
</section>  
  
<footer>  
  <p>© 2026 LUXE STORE</p>  
</footer>  
  
</body>  
</html>  
