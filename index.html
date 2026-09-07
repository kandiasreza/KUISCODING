<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kuis Pengertian HTML, CSS & JavaScript</title>
<style>
  :root{
    --bg1:#1e1b4b;
    --bg2:#4c1d95;
    --card:#ffffff;
    --accent:#7c3aed;
    --accent2:#a855f7;
    --correct:#16a34a;
    --wrong:#dc2626;
    --text:#1f2937;
    --muted:#6b7280;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background:linear-gradient(135deg,var(--bg1),var(--bg2));
    min-height:100vh;
    padding:24px 12px;
    color:var(--text);
  }
  .wrap{
    max-width:760px;
    margin:0 auto;
  }
  header{
    text-align:center;
    color:#fff;
    margin-bottom:20px;
  }
  header h1{
    margin:0 0 6px;
    font-size:1.7rem;
  }
  header p{
    margin:0;
    color:#e0d7ff;
    font-size:0.95rem;
  }
  .progress-wrap{
    background:rgba(255,255,255,0.15);
    border-radius:20px;
    height:10px;
    margin:16px 0 24px;
    overflow:hidden;
  }
  .progress-bar{
    height:100%;
    width:0%;
    background:linear-gradient(90deg,var(--accent2),var(--accent));
    border-radius:20px;
    transition:width .3s ease;
  }
  .card{
    background:var(--card);
    border-radius:16px;
    padding:24px;
    box-shadow:0 10px 30px rgba(0,0,0,0.25);
  }
  .qnum{
    display:inline-block;
    background:var(--accent);
    color:#fff;
    font-size:0.8rem;
    font-weight:600;
    padding:4px 12px;
    border-radius:20px;
    margin-bottom:14px;
  }
  .question{
    font-size:1.15rem;
    font-weight:600;
    margin-bottom:20px;
    line-height:1.5;
  }
  .options{
    display:flex;
    flex-direction:column;
    gap:10px;
  }
  .option{
    text-align:left;
    padding:13px 16px;
    border:2px solid #e5e7eb;
    border-radius:10px;
    background:#f9fafb;
    cursor:pointer;
    font-size:0.98rem;
    transition:all .15s ease;
  }
  .option:hover{
    border-color:var(--accent2);
    background:#f3e8ff;
  }
  .option.selected{
    border-color:var(--accent);
    background:#ede9fe;
  }
  .option.correct{
    border-color:var(--correct);
    background:#dcfce7;
    color:#166534;
    font-weight:600;
  }
  .option.wrong{
    border-color:var(--wrong);
    background:#fee2e2;
    color:#991b1b;
    font-weight:600;
  }
  .option:disabled{
    cursor:not-allowed;
  }
  .explain{
    margin-top:16px;
    padding:12px 14px;
    background:#f3f4f6;
    border-left:4px solid var(--accent);
    border-radius:8px;
    font-size:0.9rem;
    color:var(--muted);
    display:none;
  }
  .nav{
    display:flex;
    justify-content:space-between;
    margin-top:22px;
    gap:10px;
  }
  button.nav-btn{
    padding:11px 20px;
    border:none;
    border-radius:10px;
    font-size:0.95rem;
    font-weight:600;
    cursor:pointer;
    background:var(--accent);
    color:#fff;
    transition:background .15s;
  }
  button.nav-btn:disabled{
    background:#d1d5db;
    cursor:not-allowed;
  }
  button.nav-btn:hover:not(:disabled){
    background:#6d28d9;
  }
  .result{
    text-align:center;
  }
  .result h2{
    font-size:1.6rem;
    margin-bottom:6px;
  }
  .score-circle{
    width:140px;
    height:140px;
    border-radius:50%;
    background:conic-gradient(var(--accent) calc(var(--pct)*1%), #e5e7eb 0);
    display:flex;
    align-items:center;
    justify-content:center;
    margin:20px auto;
  }
  .score-circle span{
    background:#fff;
    width:110px;
    height:110px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:1.6rem;
    font-weight:700;
    color:var(--accent);
  }
  .result p{
    color:var(--muted);
  }
  .restart-btn{
    margin-top:18px;
    padding:12px 26px;
    border:none;
    border-radius:10px;
    background:var(--accent);
    color:#fff;
    font-weight:600;
    font-size:1rem;
    cursor:pointer;
  }
  .restart-btn:hover{
    background:#6d28d9;
  }
  .review-list{
    text-align:left;
    margin-top:20px;
    max-height:340px;
    overflow-y:auto;
    padding-right:6px;
  }
  .review-item{
    padding:10px 12px;
    border-radius:8px;
    margin-bottom:8px;
    font-size:0.85rem;
    background:#f9fafb;
    border-left:4px solid #d1d5db;
  }
  .review-item.correct{border-left-color:var(--correct);}
  .review-item.wrong{border-left-color:var(--wrong);}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>🧠 Kuis Pengertian HTML, CSS & JavaScript</h1>
    <p>35 Soal Pilihan Ganda Seputar Dasar Website</p>
  </header>

  <div class="progress-wrap"><div class="progress-bar" id="progressBar"></div></div>

  <div class="card" id="quizCard">
    <div class="qnum" id="qNum">Soal 1 / 35</div>
    <div class="question" id="qText"></div>
    <div class="options" id="options"></div>
    <div class="explain" id="explain"></div>
    <div class="nav">
      <button class="nav-btn" id="prevBtn" disabled>&larr; Sebelumnya</button>
      <button class="nav-btn" id="nextBtn" disabled>Selanjutnya &rarr;</button>
    </div>
  </div>

  <div class="card result" id="resultCard" style="display:none;">
    <h2>Hasil Kuis Kamu 🎉</h2>
    <div class="score-circle" id="scoreCircle"><span id="scoreText">0%</span></div>
    <p id="scoreDesc"></p>
    <button class="restart-btn" id="restartBtn">Ulangi Kuis</button>
    <div class="review-list" id="reviewList"></div>
  </div>
</div>

<script>
const questions = [
  {q:"Apa kepanjangan dari HTML?", o:["Hyper Text Markup Language","High Text Markup Language","Hyper Transfer Markup Language","Hyper Text Mode Language"], a:0, e:"HTML adalah singkatan dari Hyper Text Markup Language, bahasa markup untuk membuat struktur halaman web."},
  {q:"Apa kepanjangan dari CSS?", o:["Cascading Style Sheets","Colorful Style Sheets","Creative Style System","Computer Style Sheets"], a:0, e:"CSS adalah singkatan dari Cascading Style Sheets, digunakan untuk mengatur tampilan halaman web."},
  {q:"Apa fungsi utama JavaScript pada sebuah website?", o:["Menambahkan interaktivitas dan logika pada halaman web","Mengatur struktur dokumen","Mengatur warna dan tata letak","Menyimpan data di server saja"], a:0, e:"JavaScript adalah bahasa pemrograman yang membuat halaman web menjadi interaktif dan dinamis."},
  {q:"HTML termasuk dalam kategori bahasa apa?", o:["Bahasa markup","Bahasa pemrograman berorientasi objek","Bahasa query database","Bahasa scripting sisi server"], a:0, e:"HTML adalah bahasa markup, bukan bahasa pemrograman, karena digunakan untuk menandai struktur konten."},
  {q:"Apa pengertian dari elemen HTML?", o:["Komponen dasar pembentuk halaman HTML yang terdiri dari tag pembuka, isi, dan tag penutup","Sebuah file gambar dalam halaman web","Bahasa pemrograman untuk animasi","Sebuah database untuk website"], a:0, e:"Elemen HTML adalah bagian pembentuk struktur halaman, umumnya terdiri dari tag pembuka, konten, dan tag penutup."},
  {q:"Apa yang dimaksud dengan tag dalam HTML?", o:["Kode penanda yang digunakan untuk membuat elemen HTML","Sebuah file CSS eksternal","Variabel dalam JavaScript","Alamat website"], a:0, e:"Tag adalah kode berupa tanda kurung siku < > yang digunakan untuk membentuk elemen dalam HTML."},
  {q:"Apa pengertian dari atribut pada HTML?", o:["Informasi tambahan yang diberikan pada sebuah elemen HTML","Bahasa pemrograman baru","Sebuah warna latar belakang","Jenis file gambar"], a:0, e:"Atribut adalah informasi tambahan yang ditempatkan di dalam tag pembuka untuk memberi detail lebih pada elemen."},
  {q:"Apa fungsi dari tag <head> dalam dokumen HTML?", o:["Menyimpan informasi meta dan pengaturan dokumen yang tidak tampil langsung di halaman","Menampilkan judul besar di halaman","Membuat tabel data","Menyisipkan gambar"], a:0, e:"Tag <head> berisi informasi meta seperti judul halaman, link CSS, dan pengaturan lain yang tidak tampil langsung."},
  {q:"Apa fungsi dari tag <body> dalam dokumen HTML?", o:["Menampung seluruh konten yang akan ditampilkan pada halaman web","Menyimpan judul website di tab browser","Mengatur koneksi ke server","Menyimpan file CSS eksternal"], a:0, e:"Tag <body> adalah tempat semua konten yang terlihat oleh pengguna di halaman web diletakkan."},
  {q:"Apa pengertian dari CSS selector?", o:["Pola yang digunakan untuk memilih elemen HTML yang akan diberi gaya (style)", "Bahasa pemrograman baru", "Tool untuk membuat animasi", "Cara menyimpan file gambar"], a:0, e:"Selector adalah pola untuk menentukan elemen HTML mana yang akan diberi aturan gaya (styling)."},
  {q:"Apa yang dimaksud dengan class dalam CSS/HTML?", o:["Atribut yang digunakan untuk mengelompokkan elemen agar dapat diberi gaya yang sama","Sebuah fungsi dalam JavaScript","Jenis file dokumen","Bahasa markup baru"], a:0, e:"Class digunakan untuk memberi nama kelompok pada elemen sehingga bisa diberi styling yang sama secara bersamaan."},
  {q:"Apa yang dimaksud dengan id dalam HTML?", o:["Atribut unik yang digunakan untuk menandai satu elemen tertentu secara spesifik","Nama file HTML","Warna latar belakang halaman","Jenis font pada teks"], a:0, e:"ID adalah pengenal unik yang hanya boleh digunakan sekali dalam satu halaman untuk menandai elemen tertentu."},
  {q:"Apa pengertian dari box model dalam CSS?", o:["Konsep yang menggambarkan elemen HTML sebagai kotak yang terdiri dari content, padding, border, dan margin","Model 3D dalam website","Jenis tampilan grid","Struktur tabel HTML"], a:0, e:"Box model adalah konsep dasar CSS yang menggambarkan setiap elemen sebagai kotak dengan lapisan content, padding, border, dan margin."},
  {q:"Apa yang dimaksud dengan properti 'margin' pada CSS?", o:["Jarak ruang di luar border sebuah elemen","Warna latar belakang elemen","Jenis huruf pada teks","Ukuran gambar"], a:0, e:"Margin adalah jarak kosong di luar border yang memisahkan sebuah elemen dengan elemen lain di sekitarnya."},
  {q:"Apa yang dimaksud dengan properti 'padding' pada CSS?", o:["Jarak ruang di dalam elemen antara konten dan border","Jarak antar elemen yang berbeda","Ukuran font teks","Warna teks"], a:0, e:"Padding adalah ruang kosong di dalam elemen, antara konten dengan border elemen tersebut."},
  {q:"Apa pengertian dari variabel dalam JavaScript?", o:["Wadah untuk menyimpan data atau nilai yang dapat digunakan kembali dalam program","Sebuah tag dalam HTML","Warna pada CSS","Bagian dari struktur tabel"], a:0, e:"Variabel adalah tempat penyimpanan data yang diberi nama, sehingga nilainya bisa dipanggil dan digunakan kembali."},
  {q:"Apa yang dimaksud dengan fungsi (function) dalam JavaScript?", o:["Sekumpulan kode yang dibuat untuk melakukan tugas tertentu dan dapat dipanggil berulang kali","Sebuah elemen dalam HTML","Properti warna pada CSS","Jenis file gambar web"], a:0, e:"Fungsi adalah blok kode yang dirancang untuk menjalankan tugas tertentu dan bisa dipanggil kapan pun dibutuhkan."},
  {q:"Apa pengertian dari event dalam JavaScript?", o:["Sebuah aksi atau kejadian yang terjadi pada halaman web, seperti klik atau ketikan pengguna","Nama file CSS","Struktur dasar HTML","Ukuran layar browser"], a:0, e:"Event adalah kejadian yang terjadi pada halaman, seperti klik tombol, gerakan mouse, atau input keyboard, yang bisa direspons oleh JavaScript."},
  {q:"Apa yang dimaksud dengan DOM (Document Object Model)?", o:["Representasi struktur dokumen HTML dalam bentuk objek yang bisa diakses dan dimanipulasi oleh JavaScript","Sebuah database website","Bahasa pemrograman baru","Alat untuk mendesain logo"], a:0, e:"DOM adalah struktur pohon objek yang merepresentasikan dokumen HTML, memungkinkan JavaScript mengakses dan mengubah kontennya."},
  {q:"Apa pengertian dari array dalam JavaScript?", o:["Struktur data yang menyimpan kumpulan nilai dalam satu variabel","Sebuah tag HTML untuk tabel","Warna latar belakang halaman","Jenis file CSS"], a:0, e:"Array adalah struktur data yang dapat menyimpan banyak nilai sekaligus di dalam satu variabel."},
  {q:"Apa yang dimaksud dengan objek dalam JavaScript?", o:["Struktur data yang menyimpan data dalam bentuk pasangan key dan value","Sebuah gambar dalam halaman web","Jenis tag dalam HTML","Properti warna CSS"], a:0, e:"Objek adalah struktur data yang menyimpan informasi dalam bentuk pasangan properti (key) dan nilai (value)."},
  {q:"Apa pengertian dari responsive design pada website?", o:["Teknik desain yang membuat tampilan website menyesuaikan berbagai ukuran layar perangkat","Desain website dengan banyak animasi","Website yang hanya bisa diakses di komputer","Desain website tanpa gambar"], a:0, e:"Responsive design memastikan tampilan website menyesuaikan diri secara otomatis pada berbagai ukuran layar, dari HP hingga desktop."},
  {q:"Apa yang dimaksud dengan hyperlink dalam HTML?", o:["Tautan yang menghubungkan satu halaman web dengan halaman atau sumber lain","Sebuah warna pada teks","Jenis font khusus","Struktur tabel data"], a:0, e:"Hyperlink adalah tautan yang memungkinkan pengguna berpindah dari satu halaman ke halaman lain dengan mengklik teks atau gambar."},
  {q:"Apa fungsi dari tag <a> dalam HTML?", o:["Membuat tautan (link) ke halaman atau sumber lain","Menampilkan gambar","Membuat daftar berurutan","Membuat garis horizontal"], a:0, e:"Tag <a> (anchor) digunakan untuk membuat hyperlink menuju halaman atau file lain."},
  {q:"Apa fungsi dari tag <img> dalam HTML?", o:["Menyisipkan gambar ke dalam halaman web","Membuat tabel data","Membuat form input","Menampilkan video"], a:0, e:"Tag <img> digunakan untuk menyisipkan dan menampilkan gambar pada halaman web."},
  {q:"Apa pengertian dari form dalam HTML?", o:["Bagian halaman web yang digunakan untuk mengumpulkan input atau data dari pengguna","Struktur dasar sebuah dokumen","Jenis file CSS","Bahasa pemrograman baru"], a:0, e:"Form adalah elemen HTML yang digunakan untuk mengumpulkan data atau input dari pengguna, seperti nama dan email."},
  {q:"Apa yang dimaksud dengan CSS eksternal (external CSS)?", o:["File CSS terpisah yang dihubungkan ke dokumen HTML menggunakan tag <link>","CSS yang ditulis langsung di dalam tag HTML","CSS yang disimpan di dalam JavaScript","Bahasa pemrograman baru untuk styling"], a:0, e:"CSS eksternal adalah file .css terpisah yang dihubungkan ke HTML melalui tag <link>, memisahkan struktur dan gaya."},
  {q:"Apa yang dimaksud dengan CSS internal (internal CSS)?", o:["Aturan CSS yang ditulis di dalam tag <style> pada bagian head dokumen HTML","CSS yang disimpan dalam file terpisah","CSS yang ditulis di dalam JavaScript","Bahasa markup baru"], a:0, e:"CSS internal ditulis langsung di dalam tag <style> yang terletak pada bagian <head> dokumen HTML."},
  {q:"Apa yang dimaksud dengan inline CSS?", o:["Aturan gaya yang ditulis langsung pada atribut style di dalam tag HTML tertentu","CSS yang disimpan di file eksternal","CSS yang ditulis di dalam tag <script>","Sebuah framework CSS"], a:0, e:"Inline CSS adalah gaya yang ditulis langsung pada atribut style di dalam sebuah tag HTML tertentu, hanya berlaku untuk elemen itu."},
  {q:"Apa pengertian dari browser dalam konteks website?", o:["Perangkat lunak yang digunakan untuk mengakses dan menampilkan halaman web","Bahasa pemrograman untuk membuat website","Server tempat website disimpan","Jenis file HTML"], a:0, e:"Browser adalah aplikasi perangkat lunak yang digunakan pengguna untuk membuka dan menampilkan halaman web, seperti Chrome atau Firefox."},
  {q:"Apa pengertian dari web server?", o:["Komputer atau perangkat lunak yang menyimpan dan mengirimkan halaman web kepada pengguna","Perangkat lunak untuk mendesain gambar","Bahasa pemrograman untuk animasi","Jenis file CSS"], a:0, e:"Web server adalah komputer atau perangkat lunak yang menyimpan file website dan mengirimkannya ke browser saat diminta."},
  {q:"Apa yang dimaksud dengan syntax dalam pemrograman?", o:["Aturan penulisan kode yang harus diikuti agar dapat dijalankan dengan benar oleh komputer","Tampilan visual sebuah website","Warna pada halaman web","Struktur file gambar"], a:0, e:"Syntax adalah aturan tata bahasa dalam penulisan kode program agar dapat dipahami dan dijalankan oleh mesin."},
  {q:"Apa pengertian dari komentar (comment) dalam kode pemrograman?", o:["Catatan dalam kode yang tidak dieksekusi, digunakan untuk memberi penjelasan","Kode yang wajib dijalankan oleh program","Sebuah tag HTML untuk paragraf","Warna latar belakang halaman"], a:0, e:"Komentar adalah teks dalam kode yang diabaikan oleh mesin saat dijalankan, biasanya digunakan untuk memberi penjelasan pada kode."},
  {q:"Apa yang dimaksud dengan flexbox dalam CSS?", o:["Metode tata letak (layout) pada CSS untuk mengatur elemen dalam satu baris atau kolom secara fleksibel","Sebuah bahasa pemrograman baru","Jenis file gambar","Fungsi dalam JavaScript"], a:0, e:"Flexbox adalah model layout CSS yang memudahkan pengaturan posisi dan ukuran elemen secara fleksibel dalam satu arah (baris/kolom)."},
  {q:"Apa yang dimaksud dengan CSS Grid?", o:["Sistem tata letak CSS yang membagi halaman menjadi baris dan kolom untuk mengatur posisi elemen","Sebuah plugin JavaScript","Jenis warna pada CSS","Struktur dasar HTML"], a:0, e:"CSS Grid adalah sistem layout dua dimensi yang membagi halaman ke dalam baris dan kolom untuk penempatan elemen yang lebih terstruktur."},
  {q:"Apa pengertian dari framework dalam pengembangan web?", o:["Kumpulan kode dan alat siap pakai yang membantu mempercepat proses pengembangan website","Sebuah warna tema website","Jenis file gambar khusus","Nama domain website"], a:0, e:"Framework adalah kerangka kerja berisi kumpulan kode dan alat bantu siap pakai yang mempermudah dan mempercepat pengembangan website."}
];

let current = 0;
let answers = new Array(questions.length).fill(null);

const qNum = document.getElementById('qNum');
const qText = document.getElementById('qText');
const optionsDiv = document.getElementById('options');
const explainDiv = document.getElementById('explain');
const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');
const progressBar = document.getElementById('progressBar');
const quizCard = document.getElementById('quizCard');
const resultCard = document.getElementById('resultCard');

function renderQuestion(){
  const item = questions[current];
  qNum.textContent = `Soal ${current+1} / ${questions.length}`;
  qText.textContent = item.q;
  optionsDiv.innerHTML = '';
  explainDiv.style.display = 'none';
  explainDiv.textContent = '';

  item.o.forEach((opt, idx) => {
    const btn = document.createElement('button');
    btn.className = 'option';
    btn.textContent = String.fromCharCode(65+idx) + '. ' + opt;
    if(answers[current] !== null){
      btn.disabled = true;
      if(idx === item.a) btn.classList.add('correct');
      if(idx === answers[current] && idx !== item.a) btn.classList.add('wrong');
    }
    btn.addEventListener('click', () => selectAnswer(idx));
    optionsDiv.appendChild(btn);
  });

  if(answers[current] !== null){
    explainDiv.style.display = 'block';
    explainDiv.textContent = '💡 ' + item.e;
  }

  prevBtn.disabled = current === 0;
  nextBtn.disabled = answers[current] === null;
  nextBtn.textContent = current === questions.length - 1 ? 'Lihat Hasil ✔' : 'Selanjutnya →';
  progressBar.style.width = ((current) / (questions.length-1) * 100) + '%';
}

function selectAnswer(idx){
  if(answers[current] !== null) return;
  answers[current] = idx;
  renderQuestion();
}

prevBtn.addEventListener('click', () => {
  if(current > 0){ current--; renderQuestion(); }
});

nextBtn.addEventListener('click', () => {
  if(current < questions.length - 1){
    current++;
    renderQuestion();
  } else {
    showResult();
  }
});

function showResult(){
  quizCard.style.display = 'none';
  resultCard.style.display = 'block';
  progressBar.style.width = '100%';

  let correctCount = 0;
  answers.forEach((ans, i) => { if(ans === questions[i].a) correctCount++; });
  const pct = Math.round((correctCount / questions.length) * 100);

  document.getElementById('scoreCircle').style.setProperty('--pct', pct);
  document.getElementById('scoreText').textContent = pct + '%';

  let desc = '';
  if(pct >= 90) desc = `Luar biasa! Kamu benar ${correctCount} dari ${questions.length} soal. Pemahamanmu tentang HTML, CSS & JS sangat mantap! 🚀`;
  else if(pct >= 70) desc = `Bagus! Kamu benar ${correctCount} dari ${questions.length} soal. Sedikit lagi menuju sempurna! 👍`;
  else if(pct >= 50) desc = `Lumayan! Kamu benar ${correctCount} dari ${questions.length} soal. Terus belajar ya! 📘`;
  else desc = `Kamu benar ${correctCount} dari ${questions.length} soal. Yuk pelajari lagi dasar-dasar HTML, CSS & JS! 💪`;

  document.getElementById('scoreDesc').textContent = desc;

  const reviewList = document.getElementById('reviewList');
  reviewList.innerHTML = '';
  questions.forEach((item, i) => {
    const div = document.createElement('div');
    const isCorrect = answers[i] === item.a;
    div.className = 'review-item ' + (isCorrect ? 'correct' : 'wrong');
    div.innerHTML = `<strong>${i+1}. ${item.q}</strong><br>
      Jawabanmu: ${answers[i] !== null ? item.o[answers[i]] : '-'} ${isCorrect ? '✅' : '❌'}<br>
      ${!isCorrect ? 'Jawaban benar: ' + item.o[item.a] : ''}`;
    reviewList.appendChild(div);
  });
}

document.getElementById('restartBtn').addEventListener('click', () => {
  current = 0;
  answers = new Array(questions.length).fill(null);
  quizCard.style.display = 'block';
  resultCard.style.display = 'none';
  renderQuestion();
});

renderQuestion();
</script>
</body>
</html>
