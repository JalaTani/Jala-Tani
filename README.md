# Jala-Tani
JalaTani adalah platform untuk belajar dan berbagi pengetahuan pertanian. Cerita Petani Milenial, tips dalam bertani, informasi jenis tanaman, dan alat pertanian untuk membantu petani meningkatkan hasil panen.
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JalaTani - Website Pertanian</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Hijau pertanian */
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .tips {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .tip {
            flex: 1 1 300px;
            background: #e8f5e8;
            padding: 15px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Selamat Datang di JalaTani</h1>
        <p>Website Cerita Petani Milenial Bertani Modern</p>
    </header>
    
    <nav>
        <a href="#Cerita Kami">Cerita Kami</a>
        <a href="#tentang">Tentang</a>
        <a href="#tips">Tips Pertanian</a>
        <a href="#kontak">Kontak</a>
    </nav>
    
    <div class="container" id="Cerita Kami">
        <h2>Cerita Kami</h2>
        <p>JalaTani adalah platform untuk belajar dan berbagi pengetahuan pertanian. Cerita Petani Milenial, tips dalam bertani, informasi jenis tanaman, dan alat pertanian untuk membantu petani meningkatkan hasil panen.</p>
        <img src="https://via.placeholder.com/800x400/4CAF50/ffffff?text=Pertanian+Hijau" alt="Ilustrasi pertanian">
    </div>
    
    <div class="container" id="tentang">
        <h2>Tentang JalaTani</h2>
        <p>JalaTani didirikan untuk mendukung petani Indonesia dengan informasi akurat dan praktis. Kami fokus pada pertanian berkelanjutan, mulai dari menanam padi.</p>
        <ul>
            <li>Visi: Meningkatkan produktivitas pertanian.</li>
            <li>Misi: Edukasi dan inovasi untuk petani.</li>
        </ul>
    </div>
    
    <div class="container" id="tips">
        <h2>Tips Pertanian</h2>
        <div class="tips">
            <div class="tip">
                <h3>Menanam Padi</h3>
                <p>Pilih bibit unggul, siram secara teratur, dan gunakan pupuk organik. Panen setelah 3-4 bulan.</p>
            </div>
            <div class="tip">
                <h3>Hidroponik untuk Sayuran</h3>
                <p>Gunakan sistem air untuk menanam tanpa tanah. Cocok untuk lahan terbatas, hasil lebih cepat.</p>
            </div>
            <div class="tip">
                <h3>Pengendalian Hama</h3>
                <p>Gunakan pestisida alami seperti neem oil. Pantau tanaman rutin untuk mencegah kerusakan.</p>
            </div>
        </div>
    </div>
    
    <div class="container" id="kontak">
        <h2>Kontak Kami</h2>
        <p>Email: jalatani2025@gmail.com</p>
        <p>Telepon: 0882003268507</p>
        <p>Alamat: Perum Griya Medoho Asri Nomor 105 Kelurahan Kalicari Kec. Pedurungan, Kota Semarang</p>
        <form>
            <label for="nama">Nama:</label><br>
            <input type="text" id="nama" name="nama"><br><br>
            <label for="pesan">Pesan:</label><br>
            <textarea id="pesan" name="pesan"></textarea><br><br>
            <button type="submit">Kirim</button>
        </form>
    </div>
    
    <footer>
        <p>&copy; 2023 JalaTani. Semua Hak Dilindungi.</p>
    </footer>
    
    <script>
        // JavaScript sederhana untuk alert saat submit form
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Terima kasih! Pesan Anda telah dikirim.');
        });
    </script>
</body>
</html>
