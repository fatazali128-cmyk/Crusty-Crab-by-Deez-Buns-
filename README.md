<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crusty Crab (by Deez Buns & Co.)</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #1b1b1b;
      color: #ff8c42;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: left;
      padding: 50px 20px;
    }

    header {
      width: 100%;
      text-align: left;
      margin-bottom: 50px;
    }

    h1 {
      font-size: 3rem;
      color: #ff8c42;
      text-shadow: 0 0 25px rgba(255, 140, 66, 0.4);
      margin: 0;
    }

    h2 {
      font-size: 1rem;
      color: #c0c0c0;
      margin-top: 8px;
      font-weight: 400;
    }

    .menu {
      max-width: 600px;
      width: 100%;
      background: rgba(255, 255, 255, 0.02);
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
    }

    .item {
      display: flex;
      flex-direction: column;
      border-bottom: 1px solid rgba(255, 140, 66, 0.2);
      padding: 20px 0;
    }

    .item:last-child {
      border-bottom: none;
    }

    .name {
      font-size: 1.4rem;
      color: #ff8c42;
      text-shadow: 0 0 8px rgba(255, 140, 66, 0.3);
    }

    .ingredients {
      font-size: 0.95rem;
      color: #c7c7c7;
      margin-top: 6px;
      font-style: italic;
    }

    .price {
      font-size: 1rem;
      color: #bcbcbc;
      margin-top: 5px;
    }

    .note {
      font-size: 0.9rem;
      color: #9a9a9a;
      margin-top: 4px;
    }

    .contact {
      margin-top: 60px;
      text-align: center;
      color: #bdbdbd;
      font-size: 1rem;
    }

    .whatsapp {
      margin-top: 25px;
      background-color: #ff8c42;
      color: #1b1b1b;
      text-decoration: none;
      font-weight: 600;
      padding: 12px 25px;
      border-radius: 8px;
      transition: all 0.3s ease;
      display: inline-block;
      box-shadow: 0 4px 10px rgba(255, 140, 66, 0.3);
    }

    .whatsapp:hover {
      background-color: #ff9f5c;
      transform: translateY(-2px);
      box-shadow: 0 6px 16px rgba(255, 140, 66, 0.4);
    }
  </style>
</head>
<body>

  <header>
    <h1>Crusty Crab</h1>
    <h2>by Deez Buns & Co.</h2>
  </header>

  <section class="menu">
    <div class="item">
      <span class="name">Smash Craby Patty</span>
      <span class="ingredients">Juicy beef smash patty, caramelised onions, cheese slice, soft buns</span>
      <span class="price">Rs 680</span>
      <span class="note">Make it a meal for +Rs 199</span>
    </div>

    <div class="item">
      <span class="name">Crusty Double Deluxe</span>
      <span class="ingredients">Double beef patties, double cheese, crispy onions, signature sauce, soft buns</span>
      <span class="price">Rs 870</span>
      <span class="note">Make it a meal for +Rs 199</span>
    </div>

    <div class="item">
      <span class="name">Loaded Fries</span>
      <span class="ingredients">Golden crispy fries, jalapeño, popcorn chicken, secret sauces</span>
      <span class="price">Rs 390</span>
    </div>

    <div class="item">
      <span class="name">Plain Fries</span>
      <span class="ingredients">Simple salted golden fries</span>
      <span class="price">Rs 240</span>
    </div>
  </section>

  <div class="contact">
    <p>Bahria Town Phase 8, Rawalpindi</p>
    <a class="whatsapp" href="https://wa.me/923329835590?text=Hi%20Crusty%20Crab%2C%20I%E2%80%99d%20like%20to%20order!" 
    target="_blank">Order on WhatsApp</a>
  </div>

</body>
</html>
