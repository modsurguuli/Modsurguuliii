<Ойн инженерүүдийн мод үржүүлэг>
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
<h2>📚 Хичээлийн агуулга (Тайлбар)</h2>
  <p>
    Энэхүү мастер курс нь үрийн төрөл, хэлбэр, чанарын үнэлгээ зэргээс эхэлж, хөрс болон сав баглаа сонголт, ариутгалын аргад суурилсан үр бэлтгэлд гүнзгий орно. Цаашлаад үрийг хэрхэн тохирсон гүнд, зөв зайнд суулгах, хүлэмж болон байгалийн нөхцөлд ургуулах практик мэдлэгийг эзэмшүүлнэ.
  </p>
  <p>
    Мөн арчилгааны үе шат бүрд шаардлагатай сүүдрэвч, тэжээл, усалгаа, ургамлын хамгаалалт зэрэг мэргэжлийн аргуудыг заана. Сургалтын төгсгөлд модны амьдралтын хувь, нөхөн суулгалтын ач холбогдлыг онцолж, байгальд ээлтэй урт хугацааны арчилгааны талаар чиглүүлнэ.
<section id="courses">
  <h2>🎓 Сургалт</h2>
  <h3>🌿 Модлог мөчрөөр үржүүлэг хийх сургалт</h3>
  <ul>
    <li>Модлог мөчрийн төрөл, сонголт</li>
    <li>Үндэслүүлэлт хийх арга техник (усанд, хөрсөнд)</li>
    <li>Үндэслэлийн ургалтыг дэмжих нөхцөл</li>
    <li>Үндэслүүлсэн мөчрийг хөрсөнд шилжүүлэх</li>
    <li>Арчилгаа, хамгаалалт, амьдралтын хувь дээшлүүлэх</li>
  </ul>

  <h3>🌱 Үрээр тарих сургалт</h3>

    <li>Үрийн төрөл, чанар, хэлбэр</li>
    <li>Үр ариутгах арга</li>
    <li>Хөрс, сав баглаа, хүлэмжний орчин</li>
    <li>Үр тарих гүн, зай, усалгаа</li>
    <li>Намар болон хаврын тарилтын ялгаа</li>
    <li>Үрслэг арчилгаа, хамгаалалт</li>
  </ul>
   <p><strong>Төлбөр:</strong> 35,000₮</p>
  <ul>
  <p><strong>Төлбөр төлөх:</strong><br>Голомт банк - Оренжэри Ган ХХК - <b>MN75 0015 00 6205150721</b></p>
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
    
<tr><td>Хайлаас</td><td>Ulmus pumila</td><td>0.8–1.5 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Шар хуайс</td><td>Robinia pseudoacacia</td><td>1.0–1.5 м</td><td class="price">3200</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Гацуур</td><td>Picea obovata</td><td>1.3–1.5 м</td><td class="price">250000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Нарс</td><td>Pinus sylvestris</td><td>2.5–3.0 м</td><td class="price">350000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Хус</td><td>Betula platyphylla</td><td>2.0–3.0 м</td><td class="price">250000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Шинэс</td><td>Larix sibirica</td><td>2.2–2.5 м</td><td class="price">200000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
      <tr><td>Сарнай</td><td>Rosa rugosa</td><td>0.3–0.5 м</td><td class="price">35000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Агч</td><td>Acer ginnala</td><td>1.2–1.5 м</td><td class="price">3500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Голт бор</td><td>Spiraea media</td><td>1.3–1.5 м</td><td class="price">15000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Хар интоор</td><td>Prunus padus</td><td>0.3–0.5 м</td><td class="price">10500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Үхрийн нүд</td><td>Ribes nigrum</td><td>0.3–0.6 м</td><td class="price">15000</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Чацаргана</td><td>Hippophae rhamnoides</td><td>1.0–1.2 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Улиас</td><td>Populus suaveolens</td><td>1.6–2.0 м</td><td class="price">8500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Бургас</td><td>Salix caprea</td><td>1.6–2.0 м</td><td class="price">2500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
<tr><td>Өрөл</td><td>Berberis sibirica</td><td>0.5–0.8 м</td><td class="price">8500</td><td><input type="number" value="0" min="0" onchange="calculateTotal(this)"></td><td class="total">0₮</td></tr>
    </tbody>
  </table>
  <p style="margin-top:1rem;"><strong>Урамшуулал:</strong> 100 ширхэгээс дээш -2%, 1000 ширхэгээс дээш -5%</p>
  <p style="margin-top:1rem;"><strong>Худалдааны данс:</strong><br>Голомт банк - Оренжэри Ган ХХК - <b>MN75 0015 00 6205150721</b></p>
<p style="margin-top:1rem;"><strong>📞 Захиалга өгөх:</strong><br>7211-1311, 8045-6988<br>modsurguuli@gmail.com</p>
<p style="margin-top:2rem;"><strong>📩 Захиалга өгөх форм:</strong><br><a href="https://forms.gle/your-form-link" target="_blank">Захиалгын форм бөглөх</a></p>
<p style="margin-top:2rem;"><strong>📦 Хүргэлтийн нөхцөл:</strong><br>Захиалсан модыг Улаанбаатар хот дотор хүргэх боломжтой. Хөдөө орон нутгийн хүргэлтийг унаанд тавьж өгнө. Хүргэлтийн зардлыг захиалагч хариуцна.</p>
<p style="margin-top:2rem; background:#fff3cd; padding:1rem; border:1px solid #ffeeba;"><strong>💡 Сануулга:</strong><br>Төлбөрөө шилжүүлсний дараа бидэнтэй утсаар эсвэл имэйлээр холбогдон, гүйлгээний мэдээллээ илгээнэ үү. Таны захиалгыг баталгаажуулахын тулд энэ шаардлагатай.</p>
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
