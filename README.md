# dvgebook
DVGEBOOK.com
[Uploading index.html…]()<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>E-kitap Satış</title>
  <style>
    body {
      background: linear-gradient(135deg, #f8f1e4, #d3c0b0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #4a403a;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      padding: 20px;
    }
    .container {
      background: #fff9f2;
      padding: 30px 40px;
      border-radius: 15px;
      box-shadow: 0 12px 25px rgba(0,0,0,0.15);
      max-width: 380px;
      text-align: center;
    }
    h1 {
      margin-bottom: 15px;
      font-weight: 700;
      font-size: 2rem;
    }
    p {
      font-size: 1.1rem;
      margin: 10px 0 30px;
    }
    .price {
      font-size: 1.6rem;
      font-weight: 700;
      color: #bb5a2c;
      margin-bottom: 35px;
    }
    .price sup {
      font-size: 0.7rem;
      margin-left: 3px;
      color: #7a5a42;
    }
    button {
      background-color: #bb5a2c;
      border: none;
      color: white;
      font-size: 1.2rem;
      padding: 15px 45px;
      border-radius: 50px;
      cursor: pointer;
      box-shadow: 0 6px 12px rgba(187, 90, 44, 0.4);
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #a04b26;
    }
    footer {
      margin-top: 35px;
      font-size: 0.9rem;
      color: #a78c73;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>David Goggins<br>Can't Hurt Me</h1>
    <p>E-kitap satış sayfasına hoş geldiniz!</p>
    <div class="price">10<sup>USD</sup> &nbsp; / &nbsp; ₺</div>
    <button id="buyBtn">Satın Al</button>
    <footer>Satın al butonuna tıklayınca Instagram hesabıma yönlendirileceksiniz.</footer>
  </div>

  <script>
    document.getElementById('buyBtn').addEventListener('click', function() {
      window.location.href = 'https://www.instagram.com/davidmentalites/';
    });
  </script>
</body>
</html>

