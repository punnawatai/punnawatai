<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Agency</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <a href="#home">หน้าแรก</a>
            <a href="#about">เกี่ยวกับเรา</a>
            <a href="#services">บริการ</a>
            <a href="#portfolio">ผลงาน</a>
            <a href="#contact">ติดต่อเรา</a>
        </div>
        <div class="hero">
            <h1>ยกระดับธุรกิจของคุณด้วยบริการดิจิทัลครบวงจร</h1>
            <p>เราให้บริการการตลาดออนไลน์ที่มีประสิทธิภาพและคุ้มค่า</p>
            <a href="#contact" class="btn">ติดต่อเราเลย!</a>
        </div>
    </header>
    <section id="about">
        <h2>เกี่ยวกับเรา</h2>
        <p>เราเป็นเอเจนซี่ที่มีความเชี่ยวชาญในด้านการตลาดและเทคโนโลยี...</p>
    </section>
    <section id="services">
        <h2>บริการของเรา</h2>
        <ul>
            <li>การตลาดดิจิทัล</li>
            <li>ออกแบบเว็บไซต์</li>
            <li>การทำโฆษณาออนไลน์</li>
        </ul>
    </section>
    <section id="portfolio">
        <h2>ผลงานที่ผ่านมา</h2>
        <p>ตัวอย่างงานที่เราภูมิใจนำเสนอ...</p>
    </section>
    <section id="contact">
        <h2>ติดต่อเรา</h2>
        <form>
            <label for="name">ชื่อ:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">อีเมล:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">ข้อความ:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">ส่งข้อความ</button>
        </form>
    </section>
    <footer>
        <p>© 2024 Online Agency. All Rights Reserved.</p>
    </footer>
</body>
</html>
