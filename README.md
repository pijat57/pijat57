<!DOCTYPE html>
<html>
<head>
<title>crate.header sticky</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: serif;
}

.top-container {
  background-image: url("https://i.imgur.com/1BdWBn0.png");
  padding: 20px;
  color: #d37100;
  text-align: center;
}

.header {
  padding: 3px 0px;
  background-image: url("https://i.imgur.com/1BdWBn0.png");
  color: #000;
  font-size: 20px;
}

.content {
  padding: 3px;
  text-align: center;
  background: #330000;
  color: #fff;
}

.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}

.sticky + .content {
  padding: 12px;
}
.menu {
  background-color: #fff;
  padding: 30px;
  color: #000;
  padding: 3px 4px;
  text-align: center;
}
.tentang {
  background-color: #ddd;
  padding: 30px;
  color: #000;
  padding: 3px 4px;
  text-align: left;
}
.footer {
  background-color: #555;
  padding: 30px;
  color: #fff;
  padding: 3px 4px;
  text-align: left;
}
.copy {
  background-color: #000;
  padding: 30px;
  color: #fff;
  padding: 3px 4px;
  text-align: center;
}
</style>
</head>
<div class="header" id="myHeader">
  <h2><img src="https://i.imgur.com/zQAlDvP.png"width=30 height=30>
  PIJAT PANGGILAN
  <a href="https://api.whatsapp.com/send?phone=+6282114600438&text=Halo" style="text-decoration:none">
  <button style="background: #00ff77;
                 height: 36px;
                 float : right;
                 font-family: serif;
                 text-align: center;
                 border-radius: 5px;">
                <img src="https://i.imgur.com/C03AOJZ.png"width=11 height=11"> Chat</a>
  <a href="tel:+6282114600438" style="text-decoration:none">
  <button style="background: #00ff77;
                 height: 36px;
                 float : right;
                 font-family: serif;
                 text-align: center;
                 border-radius: 5px;">
                 <img src="https://i.imgur.com/dAiCmeG.png"width=11 height=11"> Call</a>
</h2>
</div>
<body>
<div class="top-container">
  <h1>Massage&Reflexy</h1>
  <h3>SELAMAT DATANG DI</br>website kami</h3>
  </br></br>
  <p>SELALU SIAP UNTUK ANDA</p>
  <p>Terapis kami yang profesional dan kompeten senantiasa akan memberikan pengalaman massage anda bersama kami Massage&Reflexy</p>
</div>

<div class="content">
  <h1>Layanan Kami pijat panggillan</h1>
</div>

<div class="menu">
  <img src="https://i.imgur.com/x2P4Mwn.jpg"width=100% height=250>
  <p>01.massage full body 60menit Rp.100.000</p>
  <img src="https://i.imgur.com/x2P4Mwn.jpg"width=100% height=250>
  <p>02.massage full body 90menit Rp.150.000</p>
  <img src="https://i.imgur.com/ZMrath7.jpg"width=100% height=250>
  <p>03.massage full body+urut perut Rp.150.000</p>
  <img src="https://i.imgur.com/NBVZ5Kg.jpg"width=100% height=250>
  <p>04.Thai massage 60menit Rp.130.000</p>
  <img src="https://i.imgur.com/NBVZ5Kg.jpg"width=100% height=250>
  <p>05.Thai massage 90menit Rp.150.000</p>
  <img src="https://i.imgur.com/K2OzN5Z.jpg"width=100% height=250>
  <p>06.Bekam basah(ambil darah kotor) Rp.150.000</p>
  <img src="https://i.imgur.com/bW1DTzy.jpg"width=100% height=250>
  <p>07.Bekam kering/kerikan/cop Rp.60.000</p>
  <img src="https://i.imgur.com/IR0RNbL.png"width=100% height=250>
  <p>08.Lulur full body Rp.80.000</p>
  <img src="https://i.imgur.com/rsBKENf.jpg"width=100% height=250>
  <p>09.Totok wajah+masker Rp.70.000</p>
  <img src="https://i.imgur.com/A1nd6Qg.jpg"width=100% height=250>
  <p>10.masker wajah Rp.50.000</p>
</div>

<div class="tentang">
<p><b>TENTANG KAMI</b></p>
<p>JASA MASSAGE PANGGILAN DI JAKARTA PELAYANAN TERBAIK DAN PROFESIONAL.</p>
<p>Massage&Reflexy adalah jasa pijat atau massage panggilan profesional khusus panggilan di jakarta selatan untuk area Rumah, Apartemen, Kost atau Hotel. Kami akan membantu memulihkan kesehatan, kebugaran, kecantikan anda, Anda tidak perlu buang waktu karena antri ataupun terjebak macet di jalan karena harus ketempat massage, Cukup hubungi kami dan kami akan kirimkan terapis profesional & berpengalaman terbaik kami untuk memberikan perlayan ke pada anda. Kami melayani pijat panggilan mulai dari jam 09.00 pagi sampai jam 23.00 malam di Jakarta Selatan, Anda bisa menghubungi kami via Telepon & Whatsapp di kontak yang tersedia.</p>
</div>

<div class="footer">
<p><b>HUBUNGI KAMI</b></p>
<p>jl.fatmawati raya kebayoran baru jakarta selatan.</p>
<p><a href="tel:+6282114600438" style="text-decoration:none">Contact:+62821-1460-0438</a></p>
<p><a href="mailto:pijatonly@gmail.com" style="text-decoration:none">E-mail&ensp;:pijatonly@gmail.com</a></p>
</div>

<div class="copy">
<p><b>©PIJAT PANGGILAN</b></p>
</div>

<script>
window.onscroll = function() {myFunction()};

var header = document.getElementById("myHeader");
var sticky = header.offsetTop;

function myFunction() {
  if (window.pageYOffset > sticky) {
    header.classList.add("sticky");
  } else {
    header.classList.remove("sticky");
  }
}
</script>

</body>
</html>
