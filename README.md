<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Graphic Designer Portfolio</title>
    <link rel='preconnect' href='https://fonts.googleapis.com'>
    <link rel='preconnect' href='https://fonts.gstatic.com' crossorigin>
    <link href='https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap' rel='stylesheet'>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: #353535;
            color: #333333;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #222222;
            color: #fff;
        }

        header h1 {
            font-size: 2rem;
        }

        header nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        header nav ul li {
            font-size: 1.1rem;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        header nav ul li a:hover {
            color: #f4b400;
        }

        .hero {
            height: 90vh;
            background-image: url('n:\Untitled-1.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
            color: rgb(31, 31, 31);
            text-align: center;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 10px;
            animation: fadeIn 2s ease-in-out;
        }

        .hero p {
            font-size: 1.3rem;
            animation: fadeIn 3s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .portfolio {
            padding: 50px 0;
            background-color: #fff;
        }

        .portfolio h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 0 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .about, .contact {
            padding: 50px 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        .about h2, .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .about p {
            font-size: 1.2rem;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }

        .contact form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact input, .contact textarea {
            padding: 15px;
            font-size: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact button {
            padding: 15px;
            font-size: 1.1rem;
            border: none;
            background-color: #333;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .contact button:hover {
            background-color: #f4b400;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer p {
            font-size: 1rem;
        }

        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2.5rem;
            }

            .hero p {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Designer Portfolio</h1>
        <nav>
            <ul>
                <li><a href='#portfolio'>Portfolio</a></li>
                <li><a href='#about'>About</a></li>
                <li><a href='#contact'>Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class='hero'>
        <div>
            <h2>Creative Graphic Designer</h2>
            <p>Transforming ideas into visual reality.</p>
        </div>
    </section>

    <section id='portfolio' class='portfolio'>
        <h2>Portfolio</h2>
        <div class='gallery'>
            <img src='n:\work\470902533_393490183789369_1974861356124070791_n.jpg' alt='Design 1'>
            <img src='n:\work\472433347_1345799863256555_7411362981519629188_n.jpg' alt='Design 2'>
            <img src='n:\work\472540853_600321135919578_5183454200196724078_n.jpg' alt='Design 3'>
            <img src='n:\work\473670518_1764944494338114_919490530151033370_n.jpg' alt='Design 4'>
            <img src='n:\work\474681194_1663041887964511_870181155928652675_n.jpg' alt='Design 5'>
            <img src='n:\work\audi@3x.jpg' alt='Design 6'>
            <img src='n:\work\dodge challenger@3x.jpg' alt='Design 7'>
            <img src='n:\work\dodge@3x.jpg' alt='Design 8'>
            <img src='n:\work\lambo@3x.jpg' alt='Design 9'>
            <img src='n:\work\lambot@3x.jpg' alt='Design 10'>
            <img src='n:\work\Nexit.jpg' alt='Design 11'>
            <img src='n:\work\porsche@3x.jpg' alt='Design 12'>
            <img src='n:\work\Untitled-1@3x.png' alt='Design 13'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.32 AM (1).jpeg' alt='Design 14'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.32 AM (2).jpeg' alt='Design 15'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.32 AM.jpeg' alt='Design 16'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.33 AM (1).jpeg' alt='Design 17'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.33 AM (2).jpeg' alt='Design 18'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.33 AM (3).jpeg' alt='Design 19'>
            <img src='n:\work\WhatsApp Image 2025-01-27 at 4.29.33 AM.jpeg' alt='Design 20'>
        </div>
    </section>

    <section id='about' class='about'>
        <h2>About Me</h2>
        <p>Hello! I'm a creative graphic designer who loves turning ideas into eye-catching designs. I specialize in branding, illustration, and digital design, helping businesses stand out with unique visuals. Whether you need a logo, website, or marketing materials, I'm here to bring your vision to life. Let's work together to make your brand shine!</p>
    </section>

    <section id='contact' class='contact'>
        <h2>Contact Me</h2>
        <form>
            <input type='text' placeholder='Your Name' required>
            <input type='email' placeholder='Your Email' required>
            <textarea rows='5' placeholder='Your Message' required></textarea>
            <button type='submit'>Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Designer Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
