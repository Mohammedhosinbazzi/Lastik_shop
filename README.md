# Lastik_shop
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>فروشگاه لاستیک تخلیه</title>
  <style>
    body { font-family: sans-serif; background: #f4f4f4; margin: 0; padding: 0; }
    header { background: #333; color: white; padding: 20px; text-align: center; }
    .container { padding: 20px; max-width: 1000px; margin: auto; }
    .product { background: white; margin-bottom: 20px; padding: 15px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); display: flex; flex-wrap: wrap; align-items: center; }
    .product img { width: 120px; border-radius: 8px; margin-left: 20px; }
    .product-info { flex: 1; }
    .product h3 { margin: 0 0 10px; }
    .product .price { color: green; font-weight: bold; margin-bottom: 10px; }
    .buttons a { display: inline-block; margin: 5px; padding: 10px 15px; background: #2196F3; color: white; text-decoration: none; border-radius: 5px; }
    form { background: white; padding: 15px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); margin-top: 40px; }
    input, textarea { width: 100%; padding: 10px; margin-top: 10px; border-radius: 5px; border: 1px solid #ccc; }
    footer { text-align: center; margin-top: 40px; padding: 20px; background: #eee; }
  </style>
</head>
<body>
  <header>
    <h1>فروشگاه لاستیک تخلیه</h1>
  </header>

  <div class="container">
    <!-- محصولات -->
    <div id="products">
      <!-- محصولات به صورت نمونه -->
      <div class="product">
        <img src="https://via.placeholder.com/120" alt="لاستیک بارز">
        <div class="product-info">
          <h3>لاستیک بارز ۲۰۵/۵۵ R16 مناسب پژو ۲۰۷</h3>
          <div class="price">۳,۲۰۰,۰۰۰ تومان</div>
          <div class="buttons">
            <a href="https://wa.me/989912120655" target="_blank">سفارش واتساپ</a>
            <a href="https://www.instagram.com/lastik.takhleh" target="_blank">اینستاگرام</a>
          </div>
        </div>
      </div>

      <!-- سایر محصولات -->
      <!-- (مابقی محصولات در اینجا قرار می‌گیرند به همین سبک) -->

    </div>

    <!-- فرم تماس -->
    <form>
      <h2>فرم سفارش</h2>
      <input type="text" placeholder="نام و نام خانوادگی" required>
      <input type="tel" placeholder="شماره تماس" required>
      <textarea placeholder="مدل لاستیک و توضیحات سفارش" rows="4"></textarea>
      <button type="submit" style="margin-top:10px; padding:10px 20px; background:#4CAF50; color:white; border:none; border-radius:5px;">ارسال</button>
    </form>

    <!-- اطلاعات تماس -->
    <footer>
      <p>آدرس: استان گلستان، گنبد کاووس، گدم آباد، خیابان آزادی، نبش کوچه ابوحنیفه</p>
      <p>شماره تماس: 09912120655</p>
      <p>اینستاگرام: <a href="https://www.instagram.com/lastik.takhleh" target="_blank">lastik.takhleh</a></p>
    </footer>
  </div>
</body>
</html>
