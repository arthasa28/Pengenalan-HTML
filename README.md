# Pengenalan-HTML

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARTHA SYARIF A.</title>
</head>
<body>

<!-- ELEMEN TEKS -->
<h1>Hello World</h1>
<p>Ini Contoh Paragraf</p>
<strong>Teks tebal</strong>
<em>Teks miring</em>
<p>Ini adalah <span>teks dengan elemen <em>miring</em> di dalamnya</span>.</p>
<!-- END ELEMEN TEKS -->


<!-- ELEMEN MULTIMEDIA -->
<h1>IMAGE</h1>
<!-- IMAGE-->
<img src="footage/img.jpg" alt="Deskripsi Gambar" style="width:500px">

<br>
<br>

<h1>AUDIO</h1>
<!-- AUDIO -->
   <audio controls>
        <source src="footage/musik.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

 <br>
 <br>

<h1>VIDEO</h1>
<!-- VIDEO -->
    <video controls width="640" height="360">
        <source src="footage/intro.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>

<!-- END ELEMEN MULTIMEDIA -->


<!-- ELEMEN HYPERLINK -->

<p>Silakan kunjungi situs website ARTHA</p>
    <a href="https://www.arthasa.online" target="_blank">KLIK</a>
<!-- END ELEMEN HYPERLINK -->


<!-- ELEMEN FORMULIR -->
    <h1>Elemen Formulir</h1>
    <form action="proses.php" method="POST">
        <label for="nama">Nama:</label>
        <input type="text" id="nama" name="nama" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="pesan">Pesan:</label><br>
        <textarea id="pesan" name="pesan" rows="4" cols="50" required></textarea><br><br>

        <input type="submit" value="Kirim">
    </form>

<!-- END ELEMEN FORMULIR -->


<!-- ELEMEN TABEL -->
    <h1>Data Owner Robotik</h1>
    <table border="1">
        <tr>
            <th>No</th>
            <th>Nama</th>
            <th>Jabatan</th>
            <th>Alamat</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Dicky Asqelani</td>
            <td>Leader Robotik</td>
            <td>Kota Bintang</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Artha Syarif A</td>
            <td>IT Support</td>
            <td>Pondok Ungu</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Rahmat Nurraya</td>
            <td>Robotic Engineer</td>
            <td>Bintara</td>
        </tr>
    </table>
<!-- END ELEMEN TABEL -->



<!-- ELEMEN WRAPPER -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">

    <div class="container">
        <h1>ARTHA SYARIF ATHAYA</h1>
        <h2>Content Container</h2>
        <p>Saya Dari Kelas 11 TKJ B, Saya Orang lapangan dalam jaringan networking</p>
    </div>

    <!-- Boostrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<!-- END ELEMEN Wrapper -->


    
</body>
</html>
```
