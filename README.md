<!DOCTYPE html>

<html lang="en">

  <!-- 

  Code Made By Ridho

  Instagram by ridho.laksono_



  -->

  <head>

    <meta charset="UTF-8" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Hai My Love</title>

    <link rel="preconnect" href="https://fonts.googleapis.com" />

    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;500;700&display=swap" rel="stylesheet" />

    <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Sharp" rel="stylesheet" />

    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.4.4/dist/sweetalert2.all.min.js"></script>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

    <style> * { padding: 0; margin: 0; font-family: "Roboto", sans-serif; } body { background: #121212; position: fixed; } .loading { width: 59vh; margin-left: 50vw; transform: translateX(-29.5vh); height: 100%; position: fixed; top: 0; display: flex; justify-content: center; align-items: center; z-index: 100; background: #121212; } .loading .content { text-align: center; font-weight: 500; color: white; font-size: 1.1em; } .loading img { width: 60px; width: 60px; } .background1 { height: 100vh; width: 59vh; margin: auto; position: absolute; top: 0; left: calc(50vw - 29.5vh); background-color: #121212; background-image: url("https://raw.githubusercontent.com/Tzyy05/HUG/main/91A2727E-259B-4B3B-A71A-D75E3A04F2F1.jpeg"); background-size: cover; filter: brightness(70%); } .background2 { margin: auto; width: 59vh; height: 100vh; position: absolute; top: 0; left: calc(50vw - 29.5vh); background-color: #c93434; background-image: url("https://raw.githubusercontent.com/Tzyy05/HUG/main/91A2727E-259B-4B3B-A71A-D75E3A04F2F1.jpeg"); background-size: cover; filter: brightness(70%); } .copyright { text-decoration: none; position: fixed; bottom: 10px; width: 120px; margin-left: 50vw; transform: translateX(-60px); display: flex; justify-content: space-around; align-items: center; color: white; z-index: 99; opacity: 0.5; } .main { position: absolute; top: 0; width: 100vw; height: 100vh; /* background: blue; */ } .main .content { /* width: 100%; */ overflow-x: hidden; width: 59vh; margin: auto; } .main .content .jam h1 { color: white; font-weight: 100; font-size: 4.3em; text-align: center; margin-top: 120px; } .main .content .tanggal { display: flex; justify-content: center; color: white; margin: 0px 0 20px 0; font-size: 1.2em; } .main .content .notif { background: rgba(231, 231, 231, 0.945); width: 88%; padding: 15px; margin: 10px auto; border-radius: 15px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.801); cursor: pointer; transform: translateX(-100vw); transition: 300ms all ease; } .main .content .notif .header { width: 100%; display: flex; justify-content: space-between; align-items: center; color: rgb(65, 65, 65); margin-bottom: 5px; } .main .content .notif .header .wa { display: flex; align-items: center; } .main .content .notif .header .wa h3 { margin-right: 6px; font-weight: 400; font-size: 0.9em; } .main .content .notif .header .wa h3 .logo { display: flex; justify-content: center; align-items: center; background-image: linear-gradient(190deg, #72e587, #23a542); color: white; width: 23px; height: 23px; border-radius: 6px; font-size: 1.3em; } .main .content .notif .header .time { font-size: 0.9em; } .main .content .notif .nama { font-weight: 500; font-size: 1.1em; } .btn-mulai { position: absolute; color: rgb(0, 0, 0); bottom: 150px; right: 0; left: 0; text-align: center; } .btn-mulai p { background: rgba(231, 231, 231, 0.788); color: rgb(36, 36, 36); padding: 5px 10px; border-radius: 10px; display: inline-block; font-size: 1.1em; font-weight: bold; cursor: pointer; animation: goyang 1200ms infinite ease; box-shadow: 1px 1px 10px rgb(0, 0, 0); } .btn-mulai p.hilang2 { display: none; } .btn-mulai p.kirimWA { display: none; color: white; background: #23a542; } @keyframes goyang { 0% { transform: translateY(0); } 50% { transform: translateY(5px); } 100% { transform: translateY(10); } } .kelip { animation: kelip 1200ms infinite ease; } @keyframes kelip { 0% { opacity: 1; } 50% { opacity: 0.8; } 100% { opacity: 1; } } @media screen and (max-width: 600px) { .background1 { width: 100vw; left: 0; } .main .content { width: 100%; } .loading { width: 100%; margin-left: 0; transform: none; } .background2 { width: 100vw; left: 0; } } .border-radius { border-radius: 15px !important; } /*LOADING*/ @keyframes loadingmy { 0% { transform: rotate(0); } 100% { transform: rotate(360deg); } } .loadingmy div { box-sizing: border-box !important; } .loadingmy > div { position: absolute; width: 74px; height: 74px; top: 13px; left: 13px; border-radius: 50%; border: 10px solid #000; border-color: #e81a46 transparent #e81a46 transparent; animation: loadingmy 1s linear infinite; } .loadingmy > div:nth-child(2) { border-color: transparent; } .loadingmy > div:nth-child(2) div { position: absolute; width: 100%; height: 100%; transform: rotate(45deg); } .loadingmy > div:nth-child(2) div:before, .loadingmy > div:nth-child(2) div:after { content: ""; display: block; position: absolute; width: 10px; height: 10px; top: -10px; left: 22px; background: #e81a46; border-radius: 50%; box-shadow: 0 64px 0 0 #e81a46; } .loadingmy > div:nth-child(2) div:after { left: -10px; top: 22px; box-shadow: 64px 0 0 0 #e81a46; } .myloading { width: 52px; height: 52px; display: inline-block; overflow: hidden; background: #121212; } .loadingmy { width: 100%; height: 100%; position: relative; transform: translateZ(0) scale(0.52); backface-visibility: hidden; transform-origin: 0 0; } .loadingmy div { box-sizing: content-box; } </style>

  </head>

  <body onload="startTime()">

    <div class="loading">

      <div class="content">

        <div class="myloading">

          <div class="loadingmy">

            <div></div>

            <div><div></div></div>

          </div>

        </div>

      </div>

    </div>

    <audio class="audio" src="https://dekatutorial.github.io/Sezairi%20-%20It's%20You.mp3" autoplay type="audio" loop=""></audio>

    <audio class="notif" src="https://dekatutorial.github.io/notif.mp3" type="audio"></audio>

    <div class="background1"></div>

    <div class="background2"></div>

    <div class="main">

      <div class="content">

        <div class="jam">

          <h1 id="jam">00:00</h1>

        </div>

        <div class="tanggal">

          <p class="tgl">Sunday, 22 January</p>

        </div>

        <div class="notif notif1 kelip" onclick="balas()">

          <div class="header">

            <div class="wa">

              <h3>Instagram</h3>

            </div>

            <div class="time">

              <p>Now</p>

            </div>

          </div>

          <div class="nama nama1">

            <p>Semestaku🤍</p>

          </div>

          <div class="isi">

            <p>Hai, Kenalan Dong. .</p>

          </div>

        </div>

        <div class="notif notif2">

          <div class="header">

            <div class="wa">

              <h3>Instagram</h3>

            </div>

            <div class="time">

              <p>Now</p>

            </div>

          </div>

          <div class="nama nama2">

            <p>Semestaku🤍</p>

          </div>

          <div class="isi">

            <p class="gombal"></p>

          </div>

        </div>

        <div class="btn-mulai">

          <p class="hilang1" onclick="notif1()">Sentuh Aku</p>

          <p class="hilang2">Klik Pesan Diatas</p>

          <p class="kirimWA">Kirim Pesan Whatsapp</p>

        </div>

      </div>

    </div>

    <a href="https://wa.me/6281298829876" class="copyright">

      <p class="cr"><i class="material-icons-sharp cr-logo"> copyright </i></p>

      <p>Fakhrurrozy.ID</p>

    </a>

    <script type="text/javascript">



      // Custom

      var pengirim = "";

      var musik = "";

      var ucapan = "";

      var background1 = "";

      var background2 = "";

      var noWhatsapp = "";

      var pesanWhatsapp = "";



      // ======================================

      var audio = document.querySelector(".audio"); if (musik) audio.src = musik; var notif = document.querySelector(".notif"); if (pengirim) { document.querySelector(".nama1").innerHTML = pengirim; document.querySelector(".nama2").innerHTML = pengirim; } if (background1) { document.querySelector(".background2").style.backgroundImage = "url('" + background1 + "')"; } if (background2) { document.querySelector(".background1").style.backgroundImage = "url('" + background2 + "')"; } $(window).on("load", function () { $(".loading").fadeOut("slow"); }); function tanggal() { const days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]; const months = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]; const d = new Date(); let hari = days[d.getDay()]; let tgl = d.getDate(); let bln = months[d.getMonth()]; document.querySelector(".tgl").innerHTML = hari + ", " + tgl + " " + bln; } function notif1() { document.querySelector(".hilang1").style.display = "none"; document.querySelector(".hilang2").style.display = "inline-block"; audio.play(); notif.play(); document.querySelector(".notif1").style.transform = "translateX(0)"; } const swalo = Swal.mixin({ confirmButtonColor: "#23a542", allowOutsideClick: false, showCancelButton: false, customClass: { popup: "border-radius", }, }); async function balas() { var { value: nama } = await swalo.fire({ imageUrl: "https://dekatutorial.github.io/stiker_mylove.gif", imageHeight: 120, title: "Hai, Manis , Kenalan Dong , Namakamu Siapa?", input: "text", confirmButtonText: "Kirim", }); if (nama) { document.querySelector(".hilang2").style.display = "none"; txt = "Hai " + nama + ", "; if (ucapan) { txt += ucapan; } else { txt += "Inget Ga. Aku Selalu Bilang Ke Kamu Kan, Kalo Tuhan Itu Baik Yah, Saat Aku Minta Bunga Mawar, Aku Diberi Taman Yang Indah. Saat Aku Meminta Setetes Air, Aku Diberi Lautan. Eh, Saat Aku Minta Bidadari, Aku Diberi Kamu, BTW Makasih Ya Udah Selalu Sayang Buat Aku"; } typeWriter(); notif2(); } else { await swalo.fire({ imageUrl: "https://dekatutorial.github.io/stiker2_mylove.gif", imageHeight: 120, confirmButtonText: "Iya deh", title: "Kenapa gak diisi? Aku kan pengin kenalan...", }); balas(); } } function notif2() { notif.play(); document.querySelector(".notif1").style.display = "none"; document.querySelector(".notif2").style.transform = "translateX(0)"; } var i = 0; var speed = 120; function typeWriter() { if (i < txt.length) { document.querySelector(".gombal").innerHTML += txt.charAt(i); i++; setTimeout(typeWriter, speed); } else { document.querySelector(".notif2").style.animation = "kelip 1200ms infinite ease"; document.querySelector(".background2").style.transition = "3s all ease"; document.querySelector(".background2").style.opacity = "0"; if (noWhatsapp && pesanWhatsapp) { document.querySelector(".kirimWA").style.display = "inline-block"; } } } function startTime() { tanggal(); const today = new Date(); let h = today.getHours(); let m = today.getMinutes(); h = checkTime(h); m = checkTime(m); document.getElementById("jam").innerHTML = h + ":" + m; setTimeout(startTime, 1000); } function checkTime(i) { if (i < 10) { i = "0" + i; } return i; } document.querySelector(".kirimWA").addEventListener("click", function () { location.assign("https://wa.me/" + noWhatsapp + "/?text=" + pesanWhatsapp); });

      </script>

  </body>

</html>
