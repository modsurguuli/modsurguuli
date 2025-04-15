<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мод Сургууль - Мастер Курс & Худалдаа</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f4f9f4; color: #333; }
    header, footer { background: #2e7d32; color: white; text-align: center; padding: 1rem; }
    nav { background: #388e3c; display: flex; justify-content: center; flex-wrap: wrap; }
    nav a { color: white; text-decoration: none; margin: 10px; font-weight: bold; }
    .hero {
      background: url('https://images.unsplash.com/photo-1506765515384-028b60a970df') center/cover no-repeat;
      height: 250px; display: flex; align-items: center; justify-content: center;
      color: white; text-shadow: 1px 1px 3px rgba(0,0,0,0.7); text-align: center; padding: 1rem;
    }
    section { padding: 2rem 1rem; max-width: 1000px; margin: auto; }
    table { width: 100%; border-collapse: collapse; }
    th, td { padding: 10px; border: 1px solid #ccc; text-align: center; }
    .tree-card img { width: 100%; height: 180px; object-fit: cover; border-radius: 6px; }
    .pagination { text-align: center; margin-top: 2rem; animation: flipIn 0.6s ease-in-out; }
    .pagination span { display: inline-block; margin: 0 5px; padding: 8px 14px; background: #ccc; border-radius: 50%; cursor: pointer; }
    .pagination span.active { background: #2e7d32; color: white; }
    @keyframes flipIn {
      from { transform: rotateY(90deg); opacity: 0; }
      to { transform: rotateY(0deg); opacity: 1; }
    }
    iframe { width: 100%; max-width: 100%; height: 700px; border: none; }
    @media (max-width: 768px) {
      nav { flex-direction: column; }
      .tree-card { width: 100%; }
      iframe { height: 500px; }
    }
  </style>
  <script>
    function calculateTotal(input) {
      const row = input.closest('tr');
      const price = parseInt(row.querySelector('.price').textContent);
      const qty = parseInt(input.value);
      const totalCell = row.querySelector('.total');
      if (!isNaN(qty) && qty > 0) {
        totalCell.textContent = (qty * price).toLocaleString() + '₮';
      } else {
        totalCell.textContent = '0₮';
      }
    }
  </script>
</head>
<body>
<header>
  <h1>Мод Сургууль</h1>
  <p>Мод үржүүлэг, тарилт, арчилгааны цахим сургалт</p>
</header>
<nav>
  <a href="#hero">Нүүр хуудас</a>
  <a href="#about">Танилцуулга</a>
  <a href="#courses">Сургалт</a>
  <a href="#trees">Худалдаа</a>
  <a href="#contact">Холбоо барих</a>
</nav>
<section id="hero" class="hero">
  <h2>Байгальд ээлтэй Мастер Курс: Үрээс ой хүртэл! 🌱</h2>
</section>

<section id="about">
  <h2>🟢 Танилцуулга</h2>
  <p>“Мод Сургууль” бол байгальд ээлтэй, тогтвортой ирээдүйг бүтээхэд чиглэсэн цахим сургалтын платформ юм. Манай сургалтууд нь ойн инженерүүдийн боловсруулсан, онол-практикийг хослуулсан агуулгатай.</p>
</section>

<section id="courses">
  <h2>🎓 Сургалтын агуулга</h2>
  <ul>
    <li><strong>1. Үрийн танилцуулга:</strong> Үрийн төрөл, хэлбэр, чанарын шалгуур</li>
    <li><strong>2. Үр бэлтгэх:</strong> Ариутгал, хөрс сонголт, сав баглаа</li>
    <li><strong>3. Үр тарих техник:</strong> Гүн, зай, усалгаа, хүлэмжний нөхцөл</li>
    <li><strong>4. Арчилгаа:</strong> Сүүдрэвч, тэжээл, өвчнөөс хамгаалалт</li>
    <li><strong>5. Тарилтын дараа:</strong> Амьдралтын хувь, дахин нөхөн тарих</li>
  </ul>
  <h3>🌿 Модлог мөчрөөр үржүүлэг хийх арга</h3>
  <p><strong>Төлбөр:</strong> 35,000₮</p>
  <ul>
    <li>Модлог мөчрийн төрөл, сонголт</li>
    <li>Үндэслүүлэлт хийх арга техник (усанд, хөрсөнд)</li>
    <li>Үндэслэлийн ургалтыг дэмжих нөхцөл</li>
    <li>Үндэслүүлсэн мөчрийг хөрсөнд шилжүүлэх</li>
    <li>Арчилгаа, хамгаалалт, амьдралтын хувь дээшлүүлэх</li>
  </ul>
  <p><strong>Төлбөр төлөх:</strong><br>Хаан банк - Чойжоо овогтой Гантуяа - <b>5022562786</b></p>
  <div style="text-align:center;">
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScd_xxxxxxxxxxxxxx/viewform?embedded=true" width="100%" height="800" frameborder="0">Түр хүлээнэ үү…</iframe>
    <p style="margin-top:1rem;"><strong>Сургалтын төлбөр:</strong> Голомт банк - Оренжэри Ган ХХК - <b>MN75 0015 00 6205150721</b></p>
  </div>
</section>

<section id="trees">
  <h2>🌳 Худалдаа - Модны үнийн санал</h2>
  <table>
    <thead style="background:#2e7d32; color:white;">
      <tr>
        <th>Монгол нэр</th>
        <th>Латин нэр</th>
        <th>Өндөр</th>
        <th>Үнэ (₮)</th>
        <th>Тоо ширхэг</th>
        <th>Нийт үнэ</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Хайлаас</td>
        <td>Ulmus pumila</td>
        <td>1.0–1.5 м</td>
        <td class="price">2500</td>
        <td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td>
        <td class="total">0₮</td>
      </tr>
      <tr>
        <td>Шинэс</td>
        <td>Larix sibirica</td>
        <td>2.0–2.5 м</td>
        <td class="price">200000</td>
        <td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td>
        <td class="total">0₮</td>
      </tr>
      <tr>
        <td>Гацуур</td>
        <td>Picea obovata</td>
        <td>1.3–1.5 м</td>
        <td class="price">250000</td>
        <td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td>
        <td class="total">0₮</td>
      </tr>
    </tbody>
  </table>
  <p style="margin-top:1rem;"><strong>Худалдааны данс:</strong><br>Хаан банк - Чойжоо овогтой Гантуяа - <b>MN700005005313435646</b></p>
</section>

<section id="contact">
  <h2>📞 Холбоо барих</h2>
  <p>Бидэнтэй холбогдохын тулд дараах мэдээллийг ашиглана уу:</p>
  <ul>
    <li>📍 Хаяг: Улаанбаатар хот, Хан-Уул дүүрэг, 52-р байр</li>
    <li>📞 Утас: +976 7211-1311, 8045-6988</li>
    <li>📧 Имэйл: modsurguuli@gmail.com</li>
  </ul>
</section>

<footer>
  &copy; 2025 Мод Сургууль — Урамшуулалт мод захиалга. Бүх эрх хуулиар хамгаалагдсан.
</footer>
</body>
</html>
