<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Si Kebo</title>
    <style>

        /* CSS untuk halaman dengan tema feminin dan lembut */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #fbc2eb, #a6c1ee);
            color: #333;
            overflow-x: hidden;
            padding-bottom: 50px;
        }

        /* Header */
        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(255, 182, 193, 0.8);
            border-bottom: 3px solid #ff6b81;
        }

        header h1 {

            font-size: 3rem;

            color: #fff;

        }

	header p {
            font-size: 1.5rem;
            color: #fff;
        }

        /* Bagian Kata-Kata Manis */
        .quotes-section {
            padding: 80px 20px;
            text-align: center;
            background-color: #fff;
            border-radius: 15px;
            margin: 50px auto;
            width: 80%;
            max-width: 800px;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
            opacity: 0;
            animation: fadeInUp 2s forwards 0.5s;
        }

        .quote {
            font-size: 1.8rem;
            color: #ff6b81;
            margin-bottom: 20px;
            font-style: italic;
        }

	.author {
            font-size: 1.2rem;
            color: #a18cd1;
            font-weight: bold;
        }

        /* Bagian Foto Kenangan */
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 40px 20px;
            margin-top: 30px;
        }

	.gallery img {
            width: 250px;
            height: 250px;
            border-radius: 15px;
            object-fit: cover;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.15);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            background-color: #ffe4e1;
            margin-top: 50px;
            border-top: 3px solid #ff6b81;
        }

	/* Animasi */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animated-heart {
            font-size: 2rem;
            color: #ff6b81;
            margin: 20px 0;
            animation: heartbeat 1.5s infinite;
        }

	/* Animasi */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animated-heart {
            font-size: 2rem;
            color: #ff6b81;
            margin: 20px 0;
            animation: heartbeat 1.5s infinite;
        }

	@keyframes heartbeat {
            0%, 20%, 50%, 80%, 100% {
                transform: scale(1);
            }
            40% {
                transform: scale(1.2);
            }
            60% {
                transform: scale(1.1);
            }
        }

    </style>
</head>
<body>

    <!-- Bagian Header -->
    <header>
        <h1>Hanya gabut Aja Sih</h1>
        <p>Ga Maksa Buat Suka Juga Hehe</p>
    </header>

     <!-- Bagian Quotes -->
    <section class="quotes-section">
        <p class="quote">"Kamu adalah keajaiban yang ku temukan di tengah-tengah perjalanan hidupku."</p>
        <p class="author">- Dari Hati untukmu</p>
        
        <p class="quote">"Bersamamu, setiap hari adalah petualangan yang tak ternilai."</p>
        <p class="author">- Dengan Sepenuh Cinta</p>
        
        <p class="quote">"Jika cinta itu adalah langit, maka kamu adalah bintangnya."</p>
        <p class="author">- Selamanya Bersamamu</p>
        
	<div class="animated-heart"></div>
    </section>

    <!-- Bagian Galeri Foto -->
    <section class="gallery">
        <!-- Tambahkan foto-foto kenangan di sini -->
        <img src="home/ica1.jpg" alt="Kenangan 1">
        <img src="icons/ica2.jpg" alt="Kenangan 2">
        <img src="icons/ica3.jpg" alt="Kenangan 3">
        <img src="icons/ica4.jpg" alt="Kenangan 4">
        <img src="icons/ica5.jpg" alt="Kenangan 5">
    </section>

     <!-- Footer -->
    <footer>
        <p>&copy; 2024 - Dari Gabutku Khusus Untukmu</p>
    </footer>

</body>
</html>
