<!DOCTYPE html>
<html lang="ar" dir="rtl">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TechStore - متجر الإلكترونيات</title>
    <style>
      body {
        font-family: "Arial", sans-serif;
        margin: 0;
        padding: 0;
        background-color: #fff;
        direction: rtl;
      }

      nav {
        background-color: #1e1e2f;
        color: white;
        position: fixed;
        width: 100%;
        z-index: 999;
        display: flex;
        justify-content: space-around;
        align-items: center;
      }

      nav a {
        color: white;
        text-decoration: none;
        margin-left: 15px;
        font-weight: bold;
      }
      nav a:hover {
        color: #7615c0;
      }

      .header {
        color: white;
        text-decoration: none;
        font-weight: bold;
      }

      .header:hover {
        color: #7615c0;
        cursor: pointer;
      }

      .hero {
        background: url("https://images.unsplash.com/photo-1517336714731-489689fd1ca8")
          no-repeat center center/cover;
        height: 300px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        text-shadow: 2px 2px 4px #000;
        position: relative;
        width: auto;
        top: 50px;
        margin-bottom: 50px;
      }

      .hero h1 {
        font-size: 36px;
      }

      .products {
        padding: 40px;
        background-color: white;
      }

      .category {
        margin-bottom: 70px;
      }

      .category h1 {
        color: #1e1e2f;
        background-color: #e4e4f5;
        padding: 7px;
        border-radius: 5px;
        text-align: center;
        /* border: 2px solid #1e1e2f; */
      }

      .product-grid {
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
      }

      .product {
        background-color: #fff;
        border: 2px solid transparent;
        border-radius: 8px;
        width: 30%;
        padding: 15px;
        text-align: center;
        transition: transform 0.3s;
        box-shadow: 5px 5px 15px #e4e1e1;
      }

      .product:hover {
        transform: scale(1.05);
      }

      .product img {
        max-width: 100%;
        height: 150px;
        object-fit: cover;
        margin-bottom: 10px;
      }

      .product h3 {
        margin: 10px 0 5px;
      }

      .product p {
        color: #666;
        font-size: 14px;
        margin-bottom: 10px;
      }

      .price {
        font-size: 18px;
        color: #e91e63;
        font-weight: bold;
        margin-bottom: 10px;
      }

      .product button {
        background-color: #313158;
        color: white;
        padding: 10px 15px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-weight: bold;
      }

      .product button:hover {
        background-color: #7615c0;
      }

      .contact-form {
        background-color: #e4e4f5;
        padding: 20px 20px;
        width: auto;
        margin: 0 auto 40px;
        border: 1px solid #ddd;
        border-radius: 8px;
      }

      .contact-form h2 {
        text-align: center;
        color: #313158;
      }

      .contact-form label {
        color: #313158;
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
      }

      .contact-form input,
      .contact-form textarea {
        width: 35vw;
        padding: 10px 0;
        margin-bottom: 15px;
        border: 1px solid #ccc;
        border-radius: 4px;
      }

      .contact-form button {
        background-color: #313158;
        color: white;
        border: none;
        padding: 10px 20px;
        font-weight: bold;
        border-radius: 4px;
        cursor: pointer;
      }

      .contact-form button:hover {
        background-color: #7615c0;
      }

      .contact-list {
        background-color: #e4e4f5;
        padding: 20px 20px;
        width: auto;
        margin: 0 auto 40px;
        border: 1px solid #ddd;
        border-radius: 8px;
      }

      .contact-list h2 {
        text-align: center;
        color: #313158;
      }

      .contact-list div {
        text-align: center;
      }
      .contact-list div h4 span a {
        text-decoration: none;
        color: #7615c0;
        font-size: 14px;
        font-weight: 500;
      }

      #contact {
        display: flex;
        justify-content: space-around;
      }

      footer {
        background-color: #1e1e2f;
        color: white;
        text-align: center;
        padding: 20px;
      }

      @media (max-width: 768px) {
        .product {
          width: 100%;
        }
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <div>
          <a href="#main">الرئيسية</a>
          <a href="#product">المنتجات</a>
          <a href="#contact">اتصل بنا</a>
        </div>
        <div>
          <h2 class="header">TechStore</h2>
        </div>
      </nav>
    </header>

    <section class="hero" id="main">
      <h1>مرحبًا بك في متجر روح الأمل</h1>
    </section>

    <section class="products" id="product">
      <div class="category">
        <h1>قسم اللابتوبات</h1>
        <div class="product-grid">
          <div class="product">
            <img
              src="HP.jpg"
              width="300"
              height="300"
              alt=""
            />
            <h3>HP Pavilion</h3>
            <p>لابتوب حديث بأداء قوي ومناسب للطلاب.</p>
            <div class="price">3,200 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="dell.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>Dell Inspiron</h3>
            <p>مثالي للأعمال والدراسة.</p>
            <div class="price">2,850 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="dell.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>Dell laptop</h3>
            <p>مثالي للأعمال والدراسة.</p>
            <div class="price">1,140 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
        </div>
      </div>

      <div class="category">
        <h1>قسم الهواتف ذكية</h1>
        <div class="product-grid">
          <div class="product">
            <img
              src="14.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>iPhone 14</h3>
            <p>أحدث تقنيات Apple.</p>
            <div class="price">4,600 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="Samsung Galaxy S23.jpg"
              width="300"
              height="300"
              alt=""
            />
            <h3>Samsung Galaxy S23</h3>
            <p>شاشة مذهلة وأداء قوي.</p>
            <div class="price">3,900 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="Samsung Galaxy S23.jpg"
              width="300"
              height="300"
              alt=""
            />
            <h3>Samsung Galaxy S23</h3>
            <p>شاشة مذهلة وأداء قوي.</p>
            <div class="price">1,900 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
        </div>
      </div>

      <div class="category">
        <h1>قسم الأجهزة ذكية</h1>
        <div class="product-grid">
          <div class="product">
            <img
              src="Apple Watch.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>Apple Watch</h3>
            <p>ساعة ذكية للصحة واللياقة.</p>
            <div class="price">1,350 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="AirPods Pro.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>AirPods Pro</h3>
            <p>صوت نقي وعزل ممتاز.</p>
            <div class="price">950 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
          <div class="product">
            <img
              src="AirPods Pro.jpeg"
              width="300"
              height="300"
              alt=""
            />
            <h3>AirPods Pro</h3>
            <p>صوت نقي وعزل ممتاز.</p>
            <div class="price">450 ريال</div>
            <button>أضف إلى السلة</button>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="contact-form">
        <h2>اتصل بنا</h2>
        <form>
          <label for="name">الاسم:</label>
          <input type="text" id="name" name="name" required />

          <label for="email">البريد الإلكتروني:</label>
          <input type="email" id="email" name="email" required />

          <label for="phone">الرقم:</label>
          <input type="text" id="phone" name="phone" required />
        </form>
        <button type="submit">إرسال</button>
      </div>
      <div class="contact-list">
        <h2>للتواصل</h2>
        <div>
          <h4>
            إنستاجرام:
            <span>
              <a
                href="https://www.instagram.com/rooh_al_amal11/?igsh=MTY0M2ZrNjdkdjloOA%3D%3D#"
                >rooh_al_amal11</a
              ></span
            >
          </h4>
          <h4>
            واتساب:
            <span>
              <a
                href="https://l.instagram.com/?u=http%3A%2F%2Fwa.me%2F96896967686&e=AT1iScB2krleyGsy38lo6MWAXCEMjLTcJPjzKEdZyjrHmmmXdGF_4S3IxZLPhSQaSD45ufTzm0ArD9ri0EU9RJAtgqxya64i"
                >96967686</a
              ></span
            >
          </h4>
          <h4>
            البريد الالكتروني:
            <span>
              <a href="mailto:info@techstore.com">info@techstore.com</a>
            </span>
          </h4>
          <h4>
            الموقع:
            <span>
              <a
                href="http://maps.app.goo.gl/W3JzYGrbzQPz4eU47?g_st=com.google.maps.preview.copy"
                >Oman, Nizwa</a
              ></span
            >
          </h4>
        </div>
      </div>
    </section>

    <footer>
      <p>جميع الحقوق محفوظة &copy; 2025 TechStore</p>
      <p>للتواصل: info@techstore.com</p>
    </footer>
  </body>
</html> 
