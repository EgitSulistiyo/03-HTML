<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" type="text/css" href="style.css" />
    <script src="script.js"></script>
</head>
<body>
    <header id="Website Pertamaku">
        <h1>Website Pertamaku</h1>
        <p>Ini adalah pertama kali saya membuat sebuah website menggunakan HTML</p>
        <a href="https://www.google.com/" target="_blank">tekan ini untuk pergi ke google</a>
    </header>
    <br>
    <br>
    <section id="profilku">
        <h1>profilku</h1>
        <img    
            src="https://d1bpj0tv6vfxyp.cloudfront.net/articles/253564_20-5-2021_13-2-0.webp"
            width="200px"
            height="200px"
            alt="fotoku"
        />
        <ul>
            <li>nama: Egit sulistiyo bahr</li>
            <li>email: bang.eg60@gmail.com</li>
            <li>daerah: Kabupaten Sumbawa Barat</li>
            <li>hobi: </li>
                <ol>
                    <li>Memancing</li>
                    <li>Futsal</li>
                    <li>Makan</li>
                </ol>
        </ul>
    </section>
    <br>
    <br>
    <section id="Film Favoritku">
        <h1>Film Favoritku</h1>
        <table>
            <thead>
                <tr>
                    <th>no</th>
                    <th>nama</th>
                    <th>produsen</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1.</td>
                    <td>Avengers EndsGame</td>
                    <td>MCU</td>
                </tr>
                <tr>
                <td>2.</td>
                <td>Ironman</td>
                <td>MCU</td>
                </tr>
            </tbody>
        </table>
    </section>
    <br>
    <br>
    <section id="Get in Touch">
        <h1>Get in Touch</h1>
        <form>
            <label for="nama">nama :</label>
            <input type="text" id="nama" name="nama"><br>
            <label for="email">email :</label>
            <input type="email" id="email" name="email">
            <br>
            <br>
            <input type="submit" value="submit">
        </form>
    </section>
    <br>
    <br>
        <nav>
            <a href="Website Pertamaku"></a>
            <a href="profilku"></a>
            <a href="Film Favoritku"></a>
            <a href="Get in Touch"></a>
        </nav>
</body>
</html>
