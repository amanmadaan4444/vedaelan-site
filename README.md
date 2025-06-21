<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      display: flex;
      flex-wrap: wrap;
    }

    .product-image {
      flex: 1 1 300px;
      padding: 20px;
    }

    .product-image img {
      width: 100%;
      border-radius: 10px;
    }

    .product-details {
      flex: 2 1 400px;
      padding: 20px;
    }

    .product-title {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .product-price {
      color: #e67e22;
      font-size: 24px;
      margin: 10px 0;
    }

    .product-description {
      margin-bottom: 20px;
      line-height: 1.6;
    }

    .add-to-cart {
      padding: 12px 24px;
      background-color: #27ae60;
      color: white;
      border: none;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }

    .add-to-cart:hover {
      background-color: #219150;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="product-image">
      <img src="https://via.placeholder.com/400x400" alt="Product Image">
    </div>
    <div class="product-details">
      <h1 class="product-title">Organic Herbal Supplement</h1>
      <div class="product-price">$24.99</div>
      <p class="product-description">
        This premium herbal supplement is made with 100% natural ingredients to support immunity, digestion, and overall wellness. Ideal for daily use.
      </p>
      <button class="add-to-cart">Add to Cart</button>
    </div>
  </div>
</body>
</html>
