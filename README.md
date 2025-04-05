# fictional-guacamole
Rayane 
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مكتبة نِك الإلكترونية</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- الشريط العلوي (Navbar) -->
    <header>
        <div class="logo">
            <h2>مكتبة نِك</h2>
        </div>
        <nav>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#categories">التصنيفات</a></li>
                <li><a href="#books">الكتب</a></li>
                <li><a href="#contact">تواصل معنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- الصفحة الرئيسية -->
    <section id="home" class="home">
        <div class="home-content">
            <h1>أهلاً في مكتبتنا الإلكترونية</h1>
            <p>اكتشف أحدث الكتب وتعلم أكثر!</p>
            <a href="#books" class="btn">ابدأ في الاستكشاف</a>
        </div>
    </section>

    <!-- التصنيفات -->
    <section id="categories" class="categories">
        <h2>تصنيفات الكتب</h2>
        <div class="category-container">
            <div class="category">
                <h3>روايات</h3>
                <a href="#">عرض المزيد</a>
            </div>
            <div class="category">
                <h3>تنمية ذاتية</h3>
                <a href="#">عرض المزيد</a>
            </div>
            <div class="category">
                <h3>كتب أطفال</h3>
                <a href="#">عرض المزيد</a>
            </div>
        </div>
    </section>

    <!-- عرض الكتب -->
    <section id="books" class="books">
        <h2>أحدث الكتب</h2>
        <div class="book-container">
            <div class="book">
                <img src="book1.jpg" alt="غلاف الكتاب">
                <h3>عنوان الكتاب الأول</h3>
                <p>وصف مختصر للكتاب...</p>
                <div class="actions">
                    <a href="#" class="btn">شراء</a>
                    <a href="#" class="btn">تحميل PDF</a>
                </div>
            </div>
            <div class="book">
                <img src="book2.jpg" alt="غلاف الكتاب">
                <h3>عنوان الكتاب الثاني</h3>
                <p>وصف مختصر للكتاب...</p>
                <div class="actions">
                    <a href="#" class="btn">شراء</a>
                    <a href="#" class="btn">تحميل PDF</a>
                </div>
            </div>
        </div>
    </section>

    <!-- تواصل معنا -->
    <section id="contact" class="contact">
        <h2>تواصل معنا</h2>
        <form action="#">
            <input type="text" placeholder="اسمك" required>
            <input type="email" placeholder="بريدك الإلكتروني" required>
            <textarea placeholder="رسالتك" required></textarea>
            <button type="submit" class="btn">إرسال</button>
        </form>
    </section>

    <!-- أسفل الصفحة -->
    <footer>
        <p>&copy; 2025 مكتبة نِك - جميع الحقوق محفوظة</p>
    </footer>

</body>
</html>
