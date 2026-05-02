<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DeenDrafts</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0b1120;
  color: #e2e8f0;
}

nav {
  text-align: center;
  padding: 15px;
  background: #020617;
  border-bottom: 1px solid #1e293b;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 60px 20px;
  background: linear-gradient(135deg, #064e3b, #020617);
}

.container {
  max-width: 900px;
  margin: auto;
  padding: 20px;
}

.product {
  background: #1e293b;
  padding: 25px;
  border-radius: 15px;
  margin-top: 30px;
}

.price {
  font-size: 22px;
  color: #22c55e;
  margin: 15px 0;
}

.btn {
  display: block;
  padding: 12px;
  margin: 10px 0;
  border-radius: 8px;
  text-align: center;
  font-weight: bold;
  text-decoration: none;
}

.pay { background: #16a34a; color: white; }
.paypal { background: #0070ba; color: white; }
.dm { background: #e1306c; color: white; }

footer {
  text-align: center;
  padding: 20px;
  border-top: 1px solid #1e293b;
}
</style>
</head>

<body>

<nav>🌙 DeenDrafts</nav>

<section class="hero">
  <h1>DeenDrafts</h1>
  <p>Premium Islamic Digital Products</p>
</section>

<div class="container">

  <div class="product">
    <h2>📘 Daily Islamic Routine Guide</h2>
    <p>Improve your daily life, build discipline, and strengthen your Imaan.</p>

    <div class="price">₹99</div>

    <!-- UPI PAYMENT -->
    <a class="btn pay" href="upi://pay?pa=6006604926@fam&pn=DeenDrafts&am=99">
      Pay via UPI
    </a>

    <!-- PAYPAL -->
    <a class="btn paypal" href="https://www.paypal.com/paypalme/yourusername">
      Pay with PayPal
    </a>

    <!-- INSTAGRAM DM -->
    <a class="btn dm" 
       href="https://ig.me/m/deendrafts1">
      Send Payment Screenshot on Instagram
    </a>

    <p style="font-size:14px;color:#94a3b8;">
      After payment, click the button above and send screenshot. You will receive your PDF instantly.
    </p>

  </div>

</div>

<footer>
  <p>Instagram: @deendrafts1</p>
  <p>© 2026 DeenDrafts</p>
</footer>

</body>
</html>
