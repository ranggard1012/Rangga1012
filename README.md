<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tentang Saya - Rangga</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color:#0eb914;
      color: #222;
      line-height: 1.7;
    }

    header {
      background-color:#0eb914;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      margin-bottom: 20px;
    }

    main {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }

    h2 {
      color: #0eb914;
      margin-top: 40px;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    ul {
      padding-left: 20px;
    }

    .domain-box {
      background: #f0f0f0;
      padding: 10px;
      border-radius: 6px;
      margin: 5px 0;
    }

    img.section-img {
      width: 100%;
      max-width: 100%;
      border-radius: 8px;
      margin: 15px 0;
    }

    footer {
      text-align: center;
      font-size: 14px;
      padding: 20px;
      background: #eee;
      margin-top: 50px;
    }
        /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
      color: #63e24a;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .nav-links li a {
      text-decoration: none;
      color: black;
      font-weight: 500;
    }

    .nav-links li a:hover {
      color: #4ae261;
    }
    

    /* Hero Section */
    .hero {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
      overflow: hidden;
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    /* Background circles */
    .hero::before, .hero::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.2);
    }

    .hero::before {
      width: 200px;
      height: 200px;
      top: 30px;
      left: 20%;
    }

    .hero::after {
      width: 150px;
      height: 150px;
      bottom: 40px;
      right: 25%;
    }

    /* Section Title */
    .section-title {
      text-align: center;
      font-size: 24px;
      margin: 40px 0 20px;
      position: relative;
    }

    .section-title::after {
      content: "";
      display: block;
      width: 80px;
      height: 3px;
      background: #0eb914;
      margin: 8px auto 0;
    }
    /* Dropdown */
.dropdown {
  position: relative;
}

.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background: white;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  list-style: none;
  padding: 10px 0;
  border-radius: 6px;
  min-width: 160px;
  z-index: 10;
}

.dropdown-menu li {
  padding: 0;
}

.dropdown-menu li a {
  display: block;
  padding: 10px 15px;
  color: black;
  text-decoration: none;
  font-size: 14px;
}

.dropdown-menu li a:hover {
  background: #f5f5f5;
  color: #0eb914;
}

.dropdown:hover .dropdown-menu {
  display: block;
}


    /* Cards */
    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 0 50px 50px;
      flex-wrap: wrap;
    }

    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      width: 300px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card-header {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      height: 120px;
      position: relative;
    }

    .card-header::before,
    .card-header::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
    }

    .card-header::before {
      width: 40px;
      height: 40px;
      top: 20px;
      left: 30px;
    }

    .card-header::after {
      width: 25px;
      height: 25px;
      bottom: 20px;
      right: 40px;
    }

    .card-body {
      padding: 20px;
    }

    .card-body h3 {
      margin-bottom: 10px;
      font-size: 18px;
      color: #333;
    }

    .card-body p {
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }

    /* Footer */
    footer {
      background: #0eb914;
      color: white;
      text-align: center;
      padding: 15px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <header>
        <nav class="navbar">
      <div class="logo">Rangga</div>
      <ul class="nav-links">
        <li><a href="layout web.html">Beranda</a></li>
        <li><a href="aboutme.html">Tentang Saya</a></li>
        <li><a href="lirik lagu.html">Syair Lagu</a></li>
        <li><a href="Jadwal.html">Jadwal Pelajaran</a></li>
          <li class="nav-item dropdown">
          <a href="#">Menghitung ▾</a>
          </a>
          <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="luas persegi panjang.html">Luas</a></li>
          <li><a class="dropdown-item" href="volume kotak.html">Volume</a></li>
          </ul>
        </li>
      </ul>
    </nav>
    <img src="c:\Penyimpanan Utama\Unduhan\Download from chrome\Rangga2.png" alt="foto Rangga2">
    <h1>Rangga Darwin</h1>
    <p>Siswa SMK Negeri 1 Kota Tangerang</p>
  </header>

  <main>

    <section>
      <h2>Latar Belakang</h2>
      <p>Saya adalah seorang siswa yang duduk dibangku kelas 12, dan bersekolah di SMKN 1 Kota Tangerang Jurusan DKV</p>
    </section>

    <section>
      <h2>Tentang Sekolah</h2>
      <ul>
        <li><strong>Kelas X</strong> Dikelas 10 kami diajari dasar-dasar desain grafis dan mulai diajarkan cara menggunakan aplikasi Corel</li>
        <li><strong>Kelas XI</strong> Dikelas 11 tidak hanya diajarkan desain grafis tapi juga diajarkan animasi 2D/3D dan fotografi</li>
        <li><strong>Kelas XII</strong> Dan sekarang saya di kelas 12, kami mulai diajarkan cara penggunaan figma dan belajar dasar-dasar coding</li>

      </ul>
    </section>

    <section>
      <h2>Hobi</h2>
      <ul>
        <li>Bermain bulutangkis</li>
        <li>Jogging</li>
        <li>Belajar software desain grafis</li>
      </ul>
    </section>

    <section>
      <h2>Makanan Kesukaan</h2>
      <ul>
        <li>Bubur ayam</li>
        <li>Mie ayam</li>
        <li>Mie aceh</li>
        <li>Nasi Padang</li>
      </ul>
    </section>

    <section>
      <h2>Minuman Kesukaan</h2>
      <ul>
        <li>Air putih</li>
        <li>Es teh</li>
        <li>Kopi</li>
        <li>Susu anget</li>
        <li>Jus alpukat</li>
      </ul>
    </section>

  </main>

</body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <style>
            table {
                font-family: Arial, Helvetica, sans-serif;
                border-collapse: collapse;
                width: 100%;
            }

            tr:nth-child(even) {
                background-color: white;
            }
            td, th {
                border: 2px solid black;
                text-align: left;
                padding: 8px;
            }
            tr {
                 border: 2px solid black;
                text-align: center;
                padding: 8px;
            }
            th {
                text-align: center;
                background-color: limegreen
            }
            .tengah {
                font-weight: bold;
                text-align: center;
                margin-bottom: 20px;
            }
                /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
      color: #63e24a;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .nav-links li a {
      text-decoration: none;
      color: black;
      font-weight: 500;
    }

    .nav-links li a:hover {
      color: #4ae261;
    }
    

    /* Hero Section */
    .hero {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
      overflow: hidden;
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    /* Background circles */
    .hero::before, .hero::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.2);
    }

    .hero::before {
      width: 200px;
      height: 200px;
      top: 30px;
      left: 20%;
    }

    .hero::after {
      width: 150px;
      height: 150px;
      bottom: 40px;
      right: 25%;
    }

    /* Section Title */
    .section-title {
      text-align: center;
      font-size: 24px;
      margin: 40px 0 20px;
      position: relative;
    }

    .section-title::after {
      content: "";
      display: block;
      width: 80px;
      height: 3px;
      background: #0eb914;
      margin: 8px auto 0;
    }
    /* Dropdown */
.dropdown {
  position: relative;
}

.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background: white;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  list-style: none;
  padding: 10px 0;
  border-radius: 6px;
  min-width: 160px;
  z-index: 10;
}

.dropdown-menu li {
  padding: 0;
}

.dropdown-menu li a {
  display: block;
  padding: 10px 15px;
  color: black;
  text-decoration: none;
  font-size: 14px;
}

.dropdown-menu li a:hover {
  background: #f5f5f5;
  color: #0eb914;
}

.dropdown:hover .dropdown-menu {
  display: block;
}


    /* Cards */
    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 0 50px 50px;
      flex-wrap: wrap;
    }

    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      width: 300px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card-header {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      height: 120px;
      position: relative;
    }

    .card-header::before,
    .card-header::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
    }

    .card-header::before {
      width: 40px;
      height: 40px;
      top: 20px;
      left: 30px;
    }

    .card-header::after {
      width: 25px;
      height: 25px;
      bottom: 20px;
      right: 40px;
    }

    .card-body {
      padding: 20px;
    }

    .card-body h3 {
      margin-bottom: 10px;
      font-size: 18px;
      color: #333;
    }

    .card-body p {
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }

    /* Footer */
    footer {
      background: #0eb914;
      color: white;
      text-align: center;
      padding: 15px 0;
    }
        </style>
    </head>
    <body>
     <!-- Navbar -->
  <header>
    <nav class="navbar">
      <div class="logo">Rangga</div>
      <ul class="nav-links">
        <li><a href="layout web.html">Beranda</a></li>
        <li><a href="aboutme.html">Tentang Saya</a></li>
        <li><a href="lirik lagu.html">Syair Lagu</a></li>
        <li><a href="Jadwal.html">Jadwal Pelajaran</a></li>
          <li class="nav-item dropdown">
          <a href="#">Menghitung ▾</a>
          </a>
          <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="luas persegi panjang.html">Luas</a></li>
          <li><a class="dropdown-item" href="volume kotak.html">Volume</a></li>
          </ul>
        </li>
      </ul>
    </nav>
  </header>
     <h1><p>Jadwal Kelas 12 DKV 2</h1></p>
        <table>
        <tr>
            <th>Jam</th>
            <th>Senin</th>
            <th>Selasa</th>
            <th>Rabu</th>
            <th>Kamis</th>
        </tr>
        <tr>
            <td>07.00-07.40</td>
            <td>Upacara</td>
            <td>Pendidikan Pancasila</td>
            <td>B.Inggris</td>
            <td>KK DKV 4</td>
        </tr>
        <tr>
            <td>07.40-08.20</td>
            <td>KK DKV 5</td>
            <td>Pendidikan Pancasila</td>
            <td>B.Inggris</td>
            <td>KK DKV 4</td>
        </tr>
        <tr>
            <td>08.20-09.00</td>
            <td>KK DKV 5</td>
            <td>KK DKV 3</td>
            <td>B.Inggris</td>
            <td>KK DKV 4</td>
        </tr>
        <tr>
            <td>09.00-09.40</td>
            <td>KK DKV 5</td>
            <td>KK DKV 3</td>
            <td>B.Inggris</td>
            <td>B.Indo</td>
        </tr>
        <tr>
            <td>09.40-10.00</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
        </tr>
        <tr>
            <td>10.00-10.40</td>
            <td>KK DKV 5</td>
            <td>Matematika</td>
            <td>KK DKV 4</td>
            <td>PAI</td>
        </tr>
        <tr>
            <td>10.40-11.20</td>
            <td>KK DKV 3</td>
            <td>Matematika</td>
            <td>KK DKV 4</td>
            <td>PAI</td>
        </tr>
        <tr>
            <td>11.20-12.00</td>
            <td>KK DKV 3</td>
            <td>Matematika</td>
            <td>KK DKV 4</td>
            <td>PAI</td>
        </tr>
        <tr>
            <td>12.00-12.45</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
            <td>Istirahat</td>
        </tr>
        <tr>
            <td>12.45-13.25</td>
            <td>KK DKV 3</td>
            <td>Mapel Pilihan DKV</td>
            <td>KK DKV 5</td>
            <td>KK DKV 5</td>
        </tr>
        <tr>
            <td>13.25-14.05</td>
            <td>KK DKV 3</td>
            <td>Mapel Pilihan DKV</td>
            <td>KK DKV 5</td>
            <td>KK DKV 5</td>
        </tr>
        <tr>
            <td>14.05-14.45</td>
            <td>KK DKV 3</td>
            <td>Mapel Pilihan DKV</td>
            <td>PKK</td>
            <td>B.Korea</td>
        </tr>
        <tr>
            <td>14.45-15.25</td>
            <td>KK DKV 3</td>
            <td>Mapel Pilihan DKV</td>
            <td>PKK</td>
            <td>B.Korea</td>
        </tr>
        </table>

         <h1><p>Jadwal Hari Jumat</h1></p>      
        <table>
        <tr>
            <th>Jam</th>
            <th>Jumat</th>
        </tr>
        <tr>
            <td>07.00-07.40</td>
            <td>Pengajian</td>
        </tr>
        <tr>
            <td>07.40-08.20</td>
            <td>PKK</td>
        </tr>
        <tr>
            <td>08.20-09.00</td>
            <td>PKK</td>
        </tr>
        <tr>
            <td>09.00-09.40</td>
            <td>PKK</td>
        </tr>
        <tr>
            <td>09.40-10.00</td>
            <td>Istirahat</td>
        </tr>
        <tr>
            <td>10.00-10.40</td>
            <td>B.Indo</td>
        </tr> 
        <tr>
            <td>10.40.11.20</td>
            <td>B.Indo</td>
        </tr>
        <tr>
            <td>11.20-11.50</td>
            <td>Istirahat</td>
        </tr>
        <tr>
            <td>11.50-12.50</td>
            <td>Sholat Jumat</td>
        </tr>
        <tr>
            <td>12.50-14.00</td>
            <td>Jumat Bersih</td>
        </tr>    
        <tr>
            <td>14.00-17.00</td>
            <td>Ektra Kurikuler</td>
        </tr>                               
        </table>
    </body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Dari Sabang Sampai Merauke - Chords & Play</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: sans-serif;
      padding: 20px;
    }
    .chord {
      color: limegreen;
      font-weight: bold;
    }
    .line {
      white-space: pre;
      margin: 2px 0;
    }
    .section {
      margin-bottom: 20px;
    }
    /* Tombol play custom */
    #playBtn {
      cursor: pointer;
      width: 60px;
      height: 60px;
      background-color: transparent;
      border: none;
      outline: none;
      margin-bottom: 30px;
    }
    #playBtn img {
      width: 100%;
      height: 100%;
      filter: invert(90%) sepia(10%) saturate(500%) hue-rotate(100deg);
      /* warna hijau cerah */
    }
        /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
      color: #63e24a;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .nav-links li a {
      text-decoration: none;
      color: black;
      font-weight: 500;
    }

    .nav-links li a:hover {
      color: #4ae261;
    }
    

    /* Hero Section */
    .hero {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
      overflow: hidden;
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    /* Background circles */
    .hero::before, .hero::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.2);
    }

    .hero::before {
      width: 200px;
      height: 200px;
      top: 30px;
      left: 20%;
    }

    .hero::after {
      width: 150px;
      height: 150px;
      bottom: 40px;
      right: 25%;
    }

    /* Section Title */
    .section-title {
      text-align: center;
      font-size: 24px;
      margin: 40px 0 20px;
      position: relative;
    }

    .section-title::after {
      content: "";
      display: block;
      width: 80px;
      height: 3px;
      background: #0eb914;
      margin: 8px auto 0;
    }
    /* Dropdown */
.dropdown {
  position: relative;
}

.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background: white;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  list-style: none;
  padding: 10px 0;
  border-radius: 6px;
  min-width: 160px;
  z-index: 10;
}

.dropdown-menu li {
  padding: 0;
}

.dropdown-menu li a {
  display: block;
  padding: 10px 15px;
  color: black;
  text-decoration: none;
  font-size: 14px;
}

.dropdown-menu li a:hover {
  background: #f5f5f5;
  color: #0eb914;
}

.dropdown:hover .dropdown-menu {
  display: block;
}


    /* Cards */
    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 0 50px 50px;
      flex-wrap: wrap;
    }

    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      width: 300px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card-header {
      background: linear-gradient(180deg, #0eb914, #0eb914);
      height: 120px;
      position: relative;
    }

    .card-header::before,
    .card-header::after {
      content: "";
      position: absolute;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
    }

    .card-header::before {
      width: 40px;
      height: 40px;
      top: 20px;
      left: 30px;
    }

    .card-header::after {
      width: 25px;
      height: 25px;
      bottom: 20px;
      right: 40px;
    }

    .card-body {
      padding: 20px;
    }

    .card-body h3 {
      margin-bottom: 10px;
      font-size: 18px;
      color: #333;
    }

    .card-body p {
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }

    /* Footer */
    footer {
      background: #0eb914;
      color: white;
      text-align: center;
      padding: 15px 0;
    }
  </style>
</head>
<body>
    <!-- Navbar -->
  <header>
    <nav class="navbar">
      <div class="logo">Rangga</div>
      <ul class="nav-links">
        <li><a href="layout web.html">Beranda</a></li>
        <li><a href="aboutme.html">Tentang Saya</a></li>
        <li><a href="lirik lagu.html">Syair Lagu</a></li>
        <li><a href="Jadwal.html">Jadwal Pelajaran</a></li>
          <li class="nav-item dropdown">
          <a href="#">Menghitung ▾</a>
          </a>
          <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="luas persegi panjang.html">Luas</a></li>
          <li><a class="dropdown-item" href="volume kotak.html">Volume</a></li>
          </ul>
        </li>
      </ul>
    </nav>
  </header>
   <h2><p>Dari Sabang Sampai Merauke</p></h2>
   <h2><p>Ciptaan: R Suharjo</p></h2>

  <!-- Tombol Play dengan gambar icon -->
  <button id="playBtn" aria-label="Play Lagu">
    <img src="c:\Penyimpanan Utama\Unduhan\lagu\tombol_play-removebg-preview.png" alt="Play Icon" />
  </button>

  <!-- Audio player tersembunyi -->
  <audio id="audioPlayer" src="c:\Penyimpanan Utama\Unduhan\lagu\DARI SABANG SAMPAI MERAUKE Ciptaan R. Soerarjo.mp3" preload="auto"></audio>

  <div class="section">
    <div class="line"><span class="chord">Intro :</span> <span class="chord">C</span> - <span class="chord">G</span> - <span class="chord">C</span></div>
  </div>

  <div class="section">
    <div class="line">        <span class="chord">C</span>                   <span class="chord">G</span></div>
    <div class="line">Dari Sabang sampai Merauke</div>
    <div class="line">          <span class="chord">G</span>             <span class="chord">C</span></div>
    <div class="line">berjajar pulau-pulau</div>
    <div class="line">      <span class="chord">C</span>               <span class="chord">F</span></div>
    <div class="line">sambung-menyambung menjadi satu</div>
    <div class="line">          <span class="chord">G</span>             <span class="chord">C</span></div>
    <div class="line">itulah Indonesia</div>
  </div>

  <div class="section">
    <div class="line">      <span class="chord">F</span>                    <span class="chord">C</span></div>
    <div class="line">Indonesia tanah airku</div>
    <div class="line">     <span class="chord">G</span>                 <span class="chord">C</span></div>
    <div class="line">Aku berjanji padamu</div>
    <div class="line">       <span class="chord">F</span>                 <span class="chord">C</span></div>
    <div class="line">Menjunjung tanah airku</div>
    <div class="line">       <span class="chord">G</span>                  <span class="chord">C</span></div>
    <div class="line">Tanah airku Indonesia</div>
  </div>

  <div class="section">
    <div class="line">        <span class="chord">C</span>                   <span class="chord">G</span></div>
    <div class="line">Dari Sabang sampai Merauke</div>
    <div class="line">          <span class="chord">G</span>             <span class="chord">C</span></div>
    <div class="line">berjajar pulau-pulau</div>
    <div class="line">      <span class="chord">C</span>               <span class="chord">F</span></div>
    <div class="line">sambung-menyambung menjadi satu</div>
    <div class="line">          <span class="chord">G</span>             <span class="chord">C</span></div>
    <div class="line">itulah Indonesia</div>
  </div>

  <div class="section">
    <div class="line">      <span class="chord">F</span>                    <span class="chord">C</span></div>
    <div class="line">Indonesia tanah airku</div>
    <div class="line">     <span class="chord">G</span>                 <span class="chord">C</span></div>
    <div class="line">Aku berjanji padamu</div>
    <div class="line">       <span class="chord">F</span>                 <span class="chord">C</span></div>
    <div class="line">Menjunjung tanah airku</div>
    <div class="line">       <span class="chord">G</span>                  <span class="chord">C</span></div>
    <div class="line">Tanah airku Indonesia</div>
  </div>

  <script>
    const playBtn = document.getElementById('playBtn');
    const audioPlayer = document.getElementById('audioPlayer');

    playBtn.addEventListener('click', () => {
      if (audioPlayer.paused) {
        audioPlayer.play();
        playBtn.querySelector('img').style.filter = 'invert(40%) sepia(80%) saturate(200%) hue-rotate(50deg)'; // sedikit gelap saat playing
      } else {
        audioPlayer.pause();
        playBtn.querySelector('img').style.filter = 'invert(90%) sepia(10%) saturate(500%) hue-rotate(100deg)'; // hijau cerah saat pause
      }
    });

    // Jika audio selesai, kembalikan ikon ke warna normal
    audioPlayer.addEventListener('ended', () => {
      playBtn.querySelector('img').style.filter = 'invert(90%) sepia(10%) saturate(500%) hue-rotate(100deg)';
    });
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hitung Volume Kotak</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }

    /* Navbar */
    .navbar-custom {
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px 50px;
    }

    .navbar-custom .navbar-brand {
      font-weight: bold;
      color: #28c12d !important;
      font-size: 20px;
    }

    .navbar-custom .nav-link {
      color: black !important;
      font-weight: 500;
    }

    .navbar-custom .nav-link:hover {
      color: #28c12d !important;
    }

    /* Dropdown */
    .dropdown-menu {
      border-radius: 8px;
      border: none;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .dropdown-menu a {
      color: black !important;
    }

    .dropdown-menu a:hover {
      background: #f7f7f7;
      color: #28c12d !important;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-custom">
    <div class="container-fluid">
      <a class="navbar-brand" href="layout web.html">Rangga</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="layout web.html">Beranda</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="aboutme.html">Tentang Saya</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="lagu.html">Syair Lagu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Jadwal.html">Jadwal Pelajaran</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
              Menghitung
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="luas persegi panjang.html">Luas Persegi</a></li>
              <li><a class="dropdown-item" href="volume kotak.html">Volume Kotak</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-5">
        <div class="card shadow-lg rounded-4">
          <div class="card-body p-4">
            <h3 class="card-title text-center mb-4">Hitung Volume Kotak</h3>
            <form id="volumeForm">
              <div class="mb-3">
                <label for="panjang" class="form-label">Panjang (cm)</label>
                <input type="number" class="form-control" id="panjang" placeholder="Masukkan panjang" required min="1">
              </div>
              <div class="mb-3">
                <label for="lebar" class="form-label">Lebar (cm)</label>
                <input type="number" class="form-control" id="lebar" placeholder="Masukkan lebar" required min="1">
              </div>
              <div class="mb-3">
                <label for="tinggi" class="form-label">Tinggi (cm)</label>
                <input type="number" class="form-control" id="tinggi" placeholder="Masukkan tinggi" required min="1">
              </div>
              <button type="submit" class="btn btn-success w-100">Hitung</button>
            </form>

            <div class="mt-4 text-center">
              <h5>Hasil:</h5>
              <p id="hasil" class="fw-bold fs-4 text-success">-</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- Script -->
  <script>
    document.getElementById("volumeForm").addEventListener("submit", function(e) {
      e.preventDefault();
      const panjang = parseFloat(document.getElementById("panjang").value);
      const lebar = parseFloat(document.getElementById("lebar").value);
      const tinggi = parseFloat(document.getElementById("tinggi").value);

      if (panjang > 0 && lebar > 0 && tinggi > 0) {
        const volume = panjang * lebar * tinggi;
        document.getElementById("hasil").textContent = volume + " cm³";
      } else {
        document.getElementById("hasil").textContent = "Masukkan angka yang valid!";
      }
    });
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hitung Luas Persegi Panjang</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }

    /* Navbar */
    .navbar-custom {
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px 50px;
    }

    .navbar-custom .navbar-brand {
      font-weight: bold;
      color: #28c12d !important;
      font-size: 20px;
    }

    .navbar-custom .nav-link {
      color: black !important;
      font-weight: 500;
    }

    .navbar-custom .nav-link:hover {
      color: #28c12d !important;
    }

    /* Dropdown */
    .dropdown-menu {
      border-radius: 8px;
      border: none;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .dropdown-menu a {
      color: black !important;
    }

    .dropdown-menu a:hover {
      background: #f7f7f7;
      color: #28c12d !important;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-custom">
    <div class="container-fluid">
      <a class="navbar-brand" href="index.html">Rangga</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="layout web.html">Beranda</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="aboutme.html">Tentang Saya</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="lagu.html">Syair Lagu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Jadwal.html">Jadwal Pelajaran</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
              Menghitung
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="luas persegi panjang.html">Luas Persegi</a></li>
              <li><a class="dropdown-item" href="volume kotak.html">Volume Kotak</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-5">
        <div class="card shadow-lg rounded-4">
          <div class="card-body p-4">
            <h3 class="card-title text-center mb-4">Hitung Luas Persegi Panjang</h3>
            <form id="luasForm">
              <div class="mb-3">
                <label for="panjang" class="form-label">Panjang (cm)</label>
                <input type="number" class="form-control" id="panjang" placeholder="Masukkan panjang" required min="1">
              </div>
              <div class="mb-3">
                <label for="lebar" class="form-label">Lebar (cm)</label>
                <input type="number" class="form-control" id="lebar" placeholder="Masukkan lebar" required min="1">
              </div>
              <button type="submit" class="btn btn-success w-100">Hitung</button>
            </form>

            <div class="mt-4 text-center">
              <h5>Hasil:</h5>
              <p id="hasil" class="fw-bold fs-4 text-success">-</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- JavaScript -->
  <script>
    document.getElementById("luasForm").addEventListener("submit", function(e) {
      e.preventDefault();
      const panjang = parseFloat(document.getElementById("panjang").value);
      const lebar = parseFloat(document.getElementById("lebar").value);

      if (panjang > 0 && lebar > 0) {
        const luas = panjang * lebar;
        document.getElementById("hasil").textContent = luas + " cm²";
      } else {
        document.getElementById("hasil").textContent = "Masukkan angka yang valid!";
      }
    });
  </script>
</body>
</html>
<img width="2550" height="3300" alt="Rangga2" src="https://github.com/user-attachments/assets/c3bfc31d-b236-4eeb-8340-b2707d1dfe2f" />
[DARI SABANG SAMPAI MERAUKE Ciptaan R. Soerarjo.mp3](https://github.com/user-attachments/files/22734191/DARI.SABANG.SAMPAI.MERAUKE.Ciptaan.R.Soerarjo.mp3)
<img width="225" height="225" alt="tombol_play-removebg-preview" src="https://github.com/user-attachments/assets/ed8823f6-069f-432a-b1a0-c5f426e8e5cf" />
