# ZAHRA CITRA APRILIANA
# 2317051049
# KELAS B
# QUIZ 1 PEMWEB (R)

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zyelous - Linktree</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

    <style>
        body {
            font-family: 'Sitka Text', sans-serif;
            background-image: url('rainy roses.jpg'); 
            background-position: center; 
            background-attachment: fixed;             
            text-align: center;
            margin: 0;
            padding: 20px;
        }

        .container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            max-width: 400px;
            width: 90%; 
            background: rgba(240, 237, 237, 0.2);
            backdrop-filter: blur(10px);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .profile img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }

        .profile h2 {
            margin: 10px 0 5px;
        }

        .profile p {
            font-size: 14px;
            color: #170e04;
        }

        .social-icons {
            margin: 15px 0;
        }

        .social-icons a {
            text-decoration: none;
            font-size: 24px;
            margin: 0 10px;
            color: black;
        }

        .button {
            display: block;
            background: #130901ec;
            color: rgb(229, 181, 181);
            text-decoration: none;
            padding: 10px;
            margin: 10px 0;
            border-radius: 25px;
            font-weight: bold;
            cursor: pointer;
        }

        .button:hover {
            background: #f6f5f5;
        }

        .jadwal-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 750px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            display: none;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            background: white;
        }

        th, td {
            border: 1.5px solid #6b4f4f;
            padding: 8px;
            text-align: center;
            font-size: 14px;
            background: white;
        }

        th {
            background: #bc90b1;
            color: black;
        }

        .peminatan { color: red; font-weight: bold; }
        .responsi { color: green; font-weight: bold; }
        .teori { color: black; }
    </style>
</head>
<body>

    <div class="container">
        <div class="profile">
            <img src="adik labubu.jpg" alt="Zyelous">
            <h2>ZYELOUS</h2>
            <p><b>Pretty and Funny Explains Me Well <br> Follow Me On My Socials</b></p>
        </div>

        <div class="social-icons">
            <a href="https://www.instagram.com/zyee.u" target="_blank"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://x.com/zyelous" target="_blank"><i class="fa-brands fa-x-twitter"></i></a>
            <a href="https://www.tiktok.com/@zyeewu" target="_blank"><i class="fa-brands fa-tiktok"></i></a>
            <a href="https://youtube.com/@2317zahracitraapriliana" target="_blank"><i class="fa-brands fa-youtube"></i></a>
        </div>

        <a href="https://siakadu.unila.ac.id/gate/login" target="_blank" class="button"><i class="fa-solid fa-graduation-cap"></i> Siakadu</a>
        <a href="https://vclass.unila.ac.id/" target="_blank" class="button"><i class="fa-solid fa-chalkboard-user"></i> VClass</a>
        <a href="#" class="button" onclick="tampilkanJadwal()"><i class="fa-solid fa-calendar-days"></i> Jadwal Kuliah</a>
        <a href="https://wa.me/6285903701329" target="_blank" class="button"><i class="fa-brands fa-whatsapp"></i> Business Inquiries</a>
    </div>

    <div id="jadwal-container" class="jadwal-container">
        <h2>Jadwal Kuliah</h2>
        <table>
            <thead>
                <tr>
                    <th>Time</th>
                    <th>Senin</th>
                    <th>Selasa</th>
                    <th>Rabu</th>
                    <th>Kamis</th>
                    <th>Jumat</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>07:30 - 09:10</td>
                    <td class="peminatan">MAPEN_G2</td>
                    <td>TI_G2</td>
                    <td></td>
                    <td></td>
                    <td class="peminatan">PDT_G2</td>
                </tr>
                <tr>
                    <td>09:15 - 10:55</td>
                    <td>TAM_G2</td>
                    <td>ADSI_G2</td>
                    <td class="responsi">IOT(R)_L1</td>
                    <td>ML_GC</td>
                    <td class="responsi">ML(R)_MB</td>
                </tr>
                <tr>
                    <td>11:00 - 12:40</td>
                    <td>AI_G2</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>13:55 - 15:35</td>
                    <td class="peminatan">IOT_GB</td>
                    <td class="responsi">AI_MA</td>
                    <td class="responsi">PEMDEK(R)_RPL</td>
                    <td class="responsi">ADSI(R)_MB</td>
                    <td class="responsi">TAM(R)_L1</td>
                </tr>
                <tr>
                    <td>15:50 - 17:30</td>
                    <td class="peminatan">PDT(R)_L1</td>
                    <td class="peminatan">PEMDEK_GB</td>
                    <td class="responsi">WEB(R)_L1</td>
                    <td>WEB_GC</td>
                    <td></td>
                </tr>
            </tbody>
        </table>
        <button class="button" onclick="tampilkanHome()">⬅ Kembali</button>
    </div>

    <script>
        function tampilkanJadwal() {
            document.querySelector('.container').style.display = "none";
            document.getElementById('jadwal-container').style.display = "block";
        }

        function tampilkanHome() {
            document.querySelector('.container').style.display = "block";
            document.getElementById('jadwal-container').style.display = "none";
        }
    </script>

</body>
</html>
