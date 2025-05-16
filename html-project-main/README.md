<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Gaming Website - News, Reviews, and Tips">
    <title>Gaming Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        header, footer {
            background: #333;
            color: #fff;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaming Hub</h1>
        <nav>
            <ul>
                <li><a href="#news">News</a></li>
                <li><a href="#reviews">Reviews</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="news">
            <h2>Latest News</h2>
            <p>Stay updated with the latest gaming news and trends.</p>
        </section>

        <section id="reviews">
            <h2>Game Reviews</h2>
            <p>Read our latest reviews on popular games.</p>
        </section>

        <section id="gallery">
            <h2>Gallery</h2>
            <p>Check out screenshots and fan art.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Gaming Hub. All Rights Reserved.</p>
    </footer>
</body>
</html>
