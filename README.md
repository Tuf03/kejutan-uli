<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kejutan Spesial untukmu!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff69b4;
            padding: 20px;
            color: white;
        }
        h1 {
            margin: 0;
        }
        .login-form {
            margin: 20px 0;
        }
        .login-input {
            padding: 10px;
            margin: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-button {
            background-color: #ff69b4;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        .login-button:hover {
            background-color: #ff1493;
        }
        .content {
            padding: 20px;
            display: none; /* Sembunyikan konten sampai login berhasil */
        }
        .surprise {
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0;
            color: #ff4500;
        }
        .button {
            background-color: #ff69b4;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #ff1493;
        }
        .gift-image {
            width: 300px;
            height: auto;
            margin: 20px 10px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .gift-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        footer {
            margin-top: 20px;
            font-size: 14px;
            color: #666;
        }

        .teks-kedip {
      color: blue;
      font-size: 40px;
      font-weight: bold;
      animation: kedip 1s infinite;
      position: relative;
      display: inline-block;
    }

    @keyframes kedip {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }

    .emotikon {
      position: absolute;
      top: 0;
      left: 50%;
      font-size: 24px;
      animation: terbang 3s infinite ease-in-out;
      opacity: 0;
    }

    @keyframes terbang {
      0% {
        transform: translateX(-50%) translateY(0);
        opacity: 1;
      }
      100% {
        transform: translateX(-50%) translateY(-120px);
        opacity: 0;
      }
    }

    /* Delay dan posisi random agar lebih hidup */
    .emotikon:nth-child(2)  { left: 45%; animation-delay: 0s;    }
    .emotikon:nth-child(3)  { left: 55%; animation-delay: 0.5s;  }
    .emotikon:nth-child(4)  { left: 40%; animation-delay: 1s;    }
    .emotikon:nth-child(5)  { left: 60%; animation-delay: 1.5s;  }
    .emotikon:nth-child(6)  { left: 43%; animation-delay: 2s;    }
    .emotikon:nth-child(7)  { left: 57%; animation-delay: 2.5s;  }
    .emotikon:nth-child(8)  { left: 50%; animation-delay: 3s;    }
    </style>
</head>
<body>

<header>
    <h1>HELLO ULI</h1>
    <br>
    <div class="teks-kedip">
        SELAMAT DATANG🌟
        <div class="emotikon">🌸</div>
        <div class="emotikon">💖</div>
        <div class="emotikon">🌼</div>
        <div class="emotikon">🌹</div>
        <div class="emotikon">💞</div>
        <div class="emotikon">💐</div>
        <div class="emotikon">❤️</div>
      </div>
</header>
<div class="login-form">
    <H2>MASUKAN USER & PASSWORD!!!</H2>
    
    <input type="text" id="username" class="login-input" placeholder="User" required>
    <input type="password" id="password" class="login-input" placeholder="Password" required>
    <button class="login-button" onclick="login()">Login</button>
</div>

<div class="content" id="content">
    
    <p>Halo, <strong id="user-name"></strong>!</p>
    <p class="surprise">Aku punya kejutan untukmu!</p>
    <p>Semoga kamu menyukainya! 🎉</p>
    <button class="button" onclick="showGift()">Lihat Kejutan</button>
    
    <div id="gift" style="display:none; margin-top: 20px;">
        <h2>Kejutanmu adalah:</h2>
        <div class="gift-gallery">

            <img src="img/gambar1.jpg" alt="Kejutan 1" class="gift-image">
            <br>
            <p> Dalam sunyi, kau hadir bagai cahaya,<br>
                tak gemerlap—namun hangat, meresap jiwa. <br>
                Uli, namamu lembut memeluk luka, <br>
                membisikkan tenang di tengah gelisah dunia. <br> <br>
                
                Bukan hanya wajahmu yang menawan, <br>
                tapi caramu mendengar, caramu memahami—
                itulah keelokan sejati, <br>
                yang tak lekang meski waktu pergi.</p> <br>
            <img src="img/gambar2.jpg" alt="Kejutan 2" class="gift-image">
            <br>
            <p>Di setiap langkahmu, ada bijak yang bicara, <br>
                bukan suara keras, melainkan hati yang dewasa. <br>
                Uli, engkau bukan hanya elok dalam rupa, <br>
                tapi dalam cara kau mencintai tanpa cela. <br><br>
                
                Tak banyak bicara, namun makna membuncah, <br>
                membuat kami merasa cukup, meski hidup resah. <br>
                Engkau adalah puisi itu sendiri, <br>
                tak ditulis—namun dirasakan, abadi.</p>
                <br>
            <img src="img/gambar3.jpg" alt="Kejutan 3" class="gift-image">
            <p>
                Ada perempuan yang bersinar tanpa sorotan, <br>
                yang mencintai tanpa mengikat, <br>
                yang mendewasa tanpa memaksa. <br>
                Itulah engkau, Uli, <br>
                anggun dalam tutur, <br>
                lembut dalam sikap, <br>
                tegas dalam nilai yang kau genggam erat. <br> <br>
                
                Engkau bukan sekadar cantik, <br>
                engkau adalah ketenangan yang dicari <br>
                dalam dunia yang sibuk berlari.</p> <br>
            <img src="img/gambar4.jpg" alt="kejutan 4" class="gift-image">
            <p>Uli, engkau ibarat pagi yang datang pelan, <br>
                tidak mengagetkan, tapi menyejukkan. <br>
                Dewasamu bukan karena usia, <br>
                tapi karena luka yang kau peluk dengan bijaksana. <br>
                <br>
                Kecantikanmu bukan hanya pada paras, <br>
                namun pada sikap yang tak lekas goyah. <br>
                Kau ajarkan arti tenang saat badai tiba, <br>
                dan itu… jauh lebih indah dari rupa semata.</p><br>
        </div>
        <hr>
        <p>Aku sediakan musik untuk kau dengar, tolong dengarkan!</p>
        <br>
        <audio controls>
            <source src="audio/@coldplay - Fix You (Lyrics).mp3" type="audio/mpeg">
            Browser Anda tidak mendukung audio tag.
          </audio>
          <hr>

        <p>Semoga kamu senang! ❤️ <br> maaf jika caraku alay ataupun norak jujur aku minder dan benar-benar pesimis mau mulai dari mana, karena aku banyak sekali kekurangan, penampilan biasa saja sifatku mungkin banyak buruknya tapi aku hanya ingin mengenalmu lebih dekat dan lebih dalam lagi, semoga kamu senang dengan kejutannya</p>
        <p>salam hangat dari saya Tufa'il Ashabi</p>
    <br>
    <img src="img/gambar5.jpg" alt="creator" class="gift-image">
    </div>
</div>

<footer>
    &copy; Created by Tufa'il Ashabi.
</footer>

<script>
    function login() {
        const username = document.getElementById('username').value;
        const password = document.getElementById('password').value;

        // Cek username dan password (ini hanya contoh sederhana)
        if (username === "ULI" && password === "ULI123%") {
            document.getElementById('user-name').innerText = username;
            document.getElementById('content').style.display = 'block';
            document.querySelector('.login-form').style.display = 'none';
        } else {
            alert('Nama pengguna atau sandi salah. Silakan coba lagi.');
        }
    }

    function showGift() {
        document.getElementById('gift').style.display = 'block';
    }
</script>

</body>
</html>
