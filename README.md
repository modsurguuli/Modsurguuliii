<ойн инженерүүдийн мод үржүүлэг>
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
    @media (max-width: 768px) {
      nav { flex-direction: column; }
    }
  </style>
  <script>
    function calculateTotal(input) {
      const row = input.closest('tr');
      const price = parseInt(row.querySelector('.price').textContent);
      const qty = parseInt(input.value);
      const totalCell = row.querySelector('.total');
      let discount = 0;
      if (qty >= 1000) discount = 0.05;
      else if (qty >= 100) discount = 0.02;
      if (!isNaN(qty) && qty > 0) {
        const total = qty * price * (1 - discount);
        totalCell.textContent = total.toLocaleString() + '₮';
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
  <h2>🎓 Сургалт</h2>
  <h3>🌿 Модлог мөчрөөр үржүүлэг хийх арга</h3>
  <p><strong>Төлбөр:</strong> 35,000₮</p>
  <ul>
    <li>Модлог мөчрийн төрөл, сонголт</li>
    <li>Үндэслүүлэлт хийх арга техник (усанд, хөрсөнд)</li>
    <li>Үндэслэлийн ургалтыг дэмжих нөхцөл</li>
    <li>Үндэслүүлсэн мөчрийг хөрсөнд шилжүүлэх</li>
    <li>Арчилгаа, хамгаалалт, амьдралтын хувь дээшлүүлэх</li>
  </ul>
          <td style="padding: 10px; border: 1px solid #ccc;">1. Үрийн танилцуулга</td>
        <td style="padding: 10px; border: 1px solid #ccc;">Үрийн төрөл, хэлбэр, чанарын шалгуур</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ccc;">2. Үр бэлтгэх</td>
        <td style="padding: 10px; border: 1px solid #ccc;">Ариутгал, хөрс сонголт, сав баглаа</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ccc;">3. Үр тарих техник</td>
        <td style="padding: 10px; border: 1px solid #ccc;">Гүн, зай, усалгаа, хүлэмжний нөхцөл</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ccc;">4. Арчилгаа</td>
        <td style="padding: 10px; border: 1px solid #ccc;">Сүүдрэвч, тэжээл, өвчнөөс хамгаалалт</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ccc;">5. Тарилтын дараа</td>
        <td style="padding: 10px; border: 1px solid #ccc;">Амьдралтын хувь, дахин нөхөн тарих</td>
      </tr>
    </tbody>
  </table>
</section>

<section id="course-detail">
  <h2>📚 Хичээлийн агуулга (Тайлбар)</h2>
  <p>
    Энэхүү мастер курс нь үрийн төрөл, хэлбэр, чанарын үнэлгээ зэргээс эхэлж, хөрс болон сав баглаа сонголт, ариутгалын аргад суурилсан үр бэлтгэлд гүнзгий орно. Цаашлаад үрийг хэрхэн тохирсон гүнд, зөв зайнд суулгах, хүлэмж болон байгалийн нөхцөлд ургуулах практик мэдлэгийг эзэмшүүлнэ.
  </p>
  <p>
    Мөн арчилгааны үе шат бүрд шаардлагатай сүүдрэвч, тэжээл, усалгаа, ургамлын хамгаалалт зэрэг мэргэжлийн аргуудыг заана. Сургалтын төгсгөлд модны амьдралтын хувь, нөхөн суулгалтын ач холбогдлыг онцолж, байгальд ээлтэй урт хугацааны арчилгааны талаар чиглүүлнэ.
  </p>
</section>

<section id="trees">
  <h2>🌳 Худалдаалж буй мод (Үнийн санал, хөнгөлөлт)</h2>
  <p>
    Манай мод үржүүлгийн талбайгаас дараах 26 төрлийн мод, бут сөөгийг захиалан худалдан авах боломжтой. Бүх модны үнэ нь өндөр, нас, чанарын ангиллаар ялгаатай бөгөөд 100 ширхэгээс дээш тохиолдолд 2%, 1000 ширхэгээс дээш бол 5% хөнгөлөлт тооцогдоно.

  <p><strong>Төлбөр төлөх:</strong><br>Хаан банк - Чойжоо овогтой Гантуяа - <b>MN700005005313435646</b></p>
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
      <tr><td>Хайлаас</td><td>Ulmus pumila</td><td>0.8–1.5 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Шар хуайс</td><td>Robinia pseudoacacia</td><td>1.0–1.5 м</td><td class="price">3200</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Гацуур</td><td>Picea obovata</td><td>1.0–1.2 м</td><td class="price">220000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Гацуур</td><td>Picea obovata</td><td>1.3–1.5 м</td><td class="price">250000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Гацуур</td><td>Picea obovata</td><td>1.8–2.0 м</td><td class="price">350000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Нарс</td><td>Pinus sylvestris</td><td>1.5–2.0 м</td><td class="price">250000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Нарс</td><td>Pinus sylvestris</td><td>2.5–3.0 м</td><td class="price">350000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Хус</td><td>Betula platyphylla</td><td>2.0–3.0 м</td><td class="price">250000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Шинэс</td><td>Larix sibirica</td><td>0.8–1.2 м</td><td class="price">55000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Шинэс</td><td>Larix sibirica</td><td>1.3–1.5 м</td><td class="price">85000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Шинэс</td><td>Larix sibirica</td><td>1.6–2.0 м</td><td class="price">150000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Шинэс</td><td>Larix sibirica</td><td>2.2–2.5 м</td><td class="price">200000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Голт бор</td><td>Spiraea media</td><td>1.0–1.2 м</td><td class="price">10500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Голт бор</td><td>Spiraea media</td><td>1.3–1.5 м</td><td class="price">15000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Хар интоор</td><td>Prunus padus</td><td>0.3–0.5 м</td><td class="price">10500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Үхрийн нүд</td><td>Ribes nigrum</td><td>0.3–0.6 м</td><td class="price">15000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Чацаргана</td><td>Hippophae rhamnoides</td><td>0.6–0.8 м</td><td class="price">2200</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Чацаргана</td><td>Hippophae rhamnoides</td><td>1.0–1.2 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Улиас</td><td>Populus suaveolens</td><td>1.0–1.2 м</td><td class="price">4500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Улиас</td><td>Populus suaveolens</td><td>1.3–1.5 м</td><td class="price">6500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Улиас</td><td>Populus suaveolens</td><td>1.6–2.0 м</td><td class="price">8500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Бургас</td><td>Salix caprea</td><td>1.2–1.5 м</td><td class="price">2200</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Бургас</td><td>Salix caprea</td><td>1.6–2.0 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Өрөл</td><td>Berberis sibirica</td><td>0.5–0.8 м</td><td class="price">8500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Сарнай</td><td>Rosa rugosa</td><td>0.3–0.5 м</td><td class="price">35000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
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
