# permatadina.cv
about me

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV Pribadi - TKJ</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #0f172a;
    color: white;
    line-height: 1.7;
}

header {
    background: #1e293b;
    padding: 20px;
    text-align: center;
    border-bottom: 3px solid #38bdf8;
}

header h1 {
    color: #38bdf8;
}

nav {
    margin-top: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
}

nav a:hover {
    color: #38bdf8;
}

.container {
    width: 85%;
    max-width: 900px;
    margin: auto;
}

.hero {
    text-align: center;
    padding: 60px 20px;
}

.hero img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #38bdf8;
    object-fit: cover;
}

.hero h2 {
    margin-top: 15px;
    font-size: 30px;
    color: #38bdf8;
}

section {
    background: #1e293b;
    margin: 20px 0;
    padding: 25px;
    border-radius: 12px;
}

h3 {
    color: #38bdf8;
    margin-bottom: 15px;
}

ul {
    padding-left: 25px;
}

.skill {
    background: #334155;
    padding: 10px;
    margin: 8px 0;
    border-radius: 6px;
}

footer {
    text-align: center;
    background: #020617;
    padding: 20px;
    margin-top: 30px;
    color: #94a3b8;
}

button {
    background: #38bdf8;
    color: #020617;
    padding: 12px 25px;
    border: none;
    border-radius: 8px;
    margin-top: 15px;
    cursor: pointer;
    font-weight: bold;
}

button:hover {
    background: white;
}
</style>
</head>

<body>

<header>
    <h1>MY PERSONAL CV</h1>
    <nav>
        <a href="#profil">Profil</a>
        <a href="#pendidikan">Pendidikan</a>
        <a href="#skill">Keahlian</a>
        <a href="#kontak">Kontak</a>
    </nav>
</header>

<div class="container">

<div class="hero" id="profil">
    <img src="foto.jpg" alt="Foto Profil">
    <h2>NAMA KAMU</h2>
    <p>Siswa Teknik Komputer dan Jaringan</p>
    <p>Calon Teknisi Jaringan | Web Developer</p>
    <button onclick="window.print()">Download / Cetak CV</button>
</div>

<section>
    <h3>👤 Tentang Saya</h3>
    <p>
        Saya adalah seorang siswa jurusan Teknik Komputer
        dan Jaringan (TKJ) yang memiliki minat dalam bidang
        teknologi komputer, jaringan internet, dan
        pengembangan website. Saya memiliki semangat belajar
        dan mampu bekerja sama dalam tim.
    </p>
</section>

<section id="pendidikan">
    <h3>🎓 Pendidikan</h3>
    <ul>
        <li>SMK - Jurusan Teknik Komputer dan Jaringan</li>
        <li>SMP - Nama Sekolah</li>
        <li>SD - Nama Sekolah</li>
    </ul>
</section>

<section id="skill">
    <h3>💻 Keahlian TKJ</h3>
    <div class="skill">Instalasi Sistem Operasi</div>
    <div class="skill">Perakitan Komputer</div>
    <div class="skill">Konfigurasi Jaringan LAN</div>
    <div class="skill">Konfigurasi Router</div>
    <div class="skill">HTML dan CSS</div>
    <div class="skill">Troubleshooting Komputer</div>
</section>

<section>
    <h3>🏆 Pengalaman</h3>
    <ul>
        <li>Praktik perakitan komputer</li>
        <li>Membuat kabel jaringan LAN</li>
        <li>Konfigurasi jaringan menggunakan MikroTik</li>
    </ul>
</section>

<section id="kontak">
    <h3>📞 Kontak</h3>
    <p>Email: emailkamu@gmail.com</p>
    <p>Telepon: 08xxxxxxxxxx</p>
    <p>Alamat: Kota / Kabupaten Kamu</p>
</section>

</div>

<footer>
    <p>© 2026 My Personal CV | Dibuat dengan HTML & CSS</p>
</footer>

</body>
</html>

