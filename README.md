<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RulfStore - متجر الملابس الرجالية الفاخرة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 200px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h3 {
            margin: 15px 0 10px;
            font-size: 1.2em;
        }
        .product p {
            color: #666;
            font-size: 0.9em;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- رأس الصفحة -->
    <header>
        <h1>RulfStore</h1>
        <p>متجر الملابس الرجالية الفاخرة</p>
    </header>

    <!-- قائمة التنقل -->
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#products">المنتجات</a>
        <a href="#about">من نحن</a>
        <a href="#contact">اتصل بنا</a>
    </nav>

    <!-- قسم المنتجات -->
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="قميص تومي هيلفيغر">
            <h3>قميص تومي هيلفيغر</h3>
            <p>قميص رجالي أنيق من تومي هيلفيغر.</p>
            <p><strong>السعر: 250 ريال</strong></p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="بولوزة لاكوست">
            <h3>بولوزة لاكوست</h3>
            <p>بولوزة رجالية كلاسيكية من لاكوست.</p>
            <p><strong>السعر: 300 ريال</strong></p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="جينز تومي هيلفيغر">
            <h3>جينز تومي هيلفيغر</h3>
            <p>جينز رجالي مريح من تومي هيلفيغر.</p>
            <p><strong>السعر: 350 ريال</strong></p>
        </div>
    </section>

    <!-- تذييل الصفحة -->
    <footer>
        <p>&copy; 2023 RulfStore. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
