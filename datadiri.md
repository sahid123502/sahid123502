<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Diri Sahit Hidayat</title>
    <style>
        /* Gaya Umum Halaman */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #2c3e50, #34495e);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        /* Container untuk data diri */
        .container {
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            width: 80%;
            max-width: 600px;
            text-align: left;
            color: #ecf0f1;
        }

        h1 {
            text-align: center;
            color: #2980b9;
            font-size: 32px;
            margin-bottom: 20px;
        }

        .info {
            margin: 10px 0;
            font-size: 18px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 8px;
            border-bottom: 1px solid #7f8c8d;
        }

        .info span {
            font-weight: bold;
            color: #3498db;
        }

        .info:last-child {
            border-bottom: none;
        }

        .footer {
            text-align: center;
            font-size: 14px;
            color: #95a5a6;
            margin-top: 20px;
        }

        /* Efek saat hover */
        .container:hover {
            transform: translateY(-10px);
            transition: transform 0.3s;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Data Diri Sahit Hidayat</h1>
        
        <div class="info">
            <span>Nama Lengkap:</span>
            <span>Sahit Hidayat</span>
        </div>
        <div class="info">
            <span>Program Studi:</span>
            <span>Teknik Informatika</span>
        </div>
        <div class="info">
            <span>NIM:</span>
            <span>141241018</span>
        </div>
        <div class="info">
            <span>Tempat, Tanggal Lahir:</span>
            <span>Boyolali, 1 Mei 2005</span>
        </div>
        <div class="info">
            <span>Alamat:</span>
            <span>Boyolali, Jawa Tengah</span>
        </div>
        <div class="info">
            <span>Jenis Kelamin:</span>
            <span>Laki-laki</span>
        </div>
        <div class="info">
            <span>Agama:</span>
            <span>Islam</span>
        </div>
        <div class="info">
            <span>No. HP:</span>
            <span>0814-6675-3744</span>
        </div>

        <div class="footer">
            <p>Terima kasih telah melihat profil saya!</p>
        </div>
    </div>
</body>
</html>
