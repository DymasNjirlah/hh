<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>@call.medym</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            background-color: #000;
            color: #fff;
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }
        .container {
            text-align: center;
            position: relative;
            width: 100%;
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .background-image {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        .content {
            z-index: 1;
            position: relative;
            padding: 20px;
            backdrop-filter: blur(5px);
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            max-width: 90%;
            margin: 0 auto;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0.5em;
            color: #ed1805;
        }
        p {
            font-size: 1.2em;
            margin: 0.5em 0;
            color: #ffffff;
        }

        /* Navbar di bawah */
        .navbar {
            width: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            left: 0;
        }
        .navbar a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1em;
        }
        .navbar a:hover {
            color: #e1ebe1;
        }

        .span {
            color: aqua;
        }

        

        /* Responsiveness for smaller screens */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5em;
            }
            p {
                font-size: 1em;
            }
        }

        @media (max-width: 480px) {
            .content {
                padding: 15px;
            }
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 0.9em;
            }
            .navbar a {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Gambar Background Fullscreen -->
        <img src="@call.medym.png" alt="Hacker Background" class="background-image">

        <!-- Konten Halaman -->
        <div class="content">
            <h1>Hacker Attacks</h1>
            <p>DimasPrikitiw,</p>
            <p>BeginnerCyber C&S, BeginnerProgramer,</p>
            <p>WebDesign, Midget Student.</p>
            <p><span class="span">@call.medym</span></p>
        </div>
    </div>
</body>
</html>
