<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LUXSNEAKER - คืนชีวิตให้รองเท้าคู่โปรด</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display&family=Sarabun&display=swap');
    :root {
      --color-bg: #0a0a0a;
      --color-gold: #c59d5f;
      --color-white: #f5f5f5;
      --color-muted: #bbbbbb;
    }
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Sarabun', sans-serif;
      background-color: var(--color-bg);
      color: var(--color-white);
      line-height: 1.6;
    }
    header {
      display: flex;
      align-items: center;
      padding: 20px 40px;
      background-color: #111;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header .logo {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      font-weight: 700;
      color: var(--color-gold);
      flex-grow: 1;
      cursor: pointer;
    }
    nav a {
      color: var(--color-white);
      text-decoration: none;
      margin-left: 30px;
      font-weight: 600;
      font-size: 16px;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: var(--color-gold);
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1519744792095-2f2205e87b6f?auto=format&fit=crop&w=1350&q=80') center center/cover no-repeat;
      height: 70vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 60px;
      color: var(--color-gold);
      text-shadow: 0 0 12px rgba(0,0,0,0.8);
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3.8rem;
      margin: 0 0 10px;
      max-width: 600px;
    }
    .hero p {
      font-size: 1.4rem;
      max-width: 500px;
      margin: 0 0 20px;
      font-weight: 600;
    }
    .hero a.cta-btn {
      background-color: var(--color-gold);
      color: var(--color-bg);
      padding: 14px 36px;
      border-radius: 30px;
      font-weight: 700;
      font-size: 1.2rem;
      text-decoration: none;
      width: fit-content;
      transition: background-color 0.3s ease;
    }
    .hero a.cta-btn:hover {
      background-color: #d4b875;
    }
    main {
      padding: 60px 40px;
      max-width: 1000px;
      margin: auto;
    }
    main section {
      margin-bottom: 60px;
    }
    main h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.4rem;
      color: var(--color-gold);
      margin-bottom: 24px;
      border-bottom: 2px solid var(--color-gold);
      display: inline-block;
      padding-bottom: 6px;
    }
    .about p {
      font-size: 1.2rem;
      color: var(--color-muted);
      max-width: 700px;
      margin: 0 auto;
      line-height: 1.8;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 24px;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.6);
      transition: transform 0.3s ease;
      cursor: pointer;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #111;
      color: var(--color-muted);
      text-align: center;
      padding: 24px 16px;
      font-size: 14px;
    }
    @media (max-width: 600px) {
      .hero {
        padding-left: 20px;
        height: 50vh;
      }
      .hero h1 {
        font-size: 2.2rem;
        max-width: 100%;
      }
      .hero p {
        font-size: 1rem;
        max-width: 100%;
      }
      header {
        flex-wrap: wrap;
        padding: 16px 20px;
      }
      nav {
        margin-top: 12px;
        width: 100%;
        display: flex;
        justify-content: center;
      }
      nav a {
        margin-left: 16px;
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">LUXSNEAKER</div>
  <nav>
    <a href="#services">บริการ</a>
    <a href="#works">ผลงาน</a>
    <a href="#pricing">ราคา</a>
    <a href="#contact">ติดต่อ</a>
  </nav>
</header>

<section class="hero">
  <h1>คืนชีวิตให้รองเท้าคู่โปรดของคุณ</h1>
  <p>บริการทำความสะอาดและรีสโตร์รองเท้าแบบครบวงจร โดยทีมงานมืออาชีพ</p>
  <a href="#contact" class="cta-btn">จองคิวตอนนี้</a>
</section>

<main>
  <section id="services">
    <h2>บริการของเรา</h2>
    <p class="about">
      LUXSNEAKER ให้บริการทำความสะอาด รีสโตร์ และดูแลรองเท้าทุกชนิดอย่างพิถีพิถันด้วยน้ำยาคุณภาพสูง พร้อมรับงานทั้งในและนอกสถานที่
    </p>
  </section>

  <section id="works">
    <h2>ผลงานก่อน-หลัง</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1519744792095-2f2205e87b6f?auto=format&fit=crop&w=600&q=80" alt="Before Cleaning">
      <img src="https://images.unsplash.com/photo-1552346154-9c65188f7e16?auto=format&fit=crop&w=600&q=80" alt="After Cleaning">
      <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?auto=format&fit=crop&w=600&q=80" alt="Before Cleaning 2">
      <img src="https://images.unsplash.com/photo-1598300056693-1c2b3a40d3b8?auto=format&fit=crop&w=600&q=80" alt="After Cleaning 2">
    </div>
  </section>

  <section id="pricing">
    <h2>ราคาและแพ็คเกจ</h2>
    <p class="about">
      - ทำความสะอาดพื้นผิวผ้า เริ่มต้นที่ 250 บาท<br />
      - รีสโตร์สีและฟื้นฟูสภาพ เริ่มต้นที่ 350 บาท<br />
      - บริการทำความสะอาดลึกพิเศษ เริ่มต้นที่ 500 บาท
    </p>
  </section>

  <section id="contact">
    <h2>ติดต่อเรา</h2>
    <p class="about">
      เบอร์โทร: 080-372-7233<br />
      Facebook: <a href="https://www.facebook.com/profile.php?id=61557145057130" target="_blank" style="color: var(--color-gold); text-decoration: underline;">LUXSNEAKERTH</a><br />
      พิกัดร้าน: <a href="https://maps.app.goo.gl/uzrpZkxNbrASmzwe6" target="_blank" style="color: var(--color-gold); text-decoration: underline;">ดูแผนที่</a>
    </p>
  </section>
</main>

<footer>
  &copy; 2025 LUXSNEAKER • สร้างด้วยความตั้งใจโดย ChatGPT
</footer>

</body>
</html>
