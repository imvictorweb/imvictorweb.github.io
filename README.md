<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Victor Arboleda</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #fff;
            padding: 20px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .container {
            display: flex;
            align-items: center;
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .profile-picture {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            margin-right: 20px;
        }

        .header-info {
            flex: 1;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
            color: #333;
        }

        header p {
            margin: 5px 0;
            color: #777;
        }

        .social-links img {
            width: 24px;
            height: 24px;
            margin-right: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            background-color: #fff;
            border-top: 1px solid #eee;
            border-bottom: 1px solid #eee;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #333;
            text-decoration: none;
            font-size: 1em;
            padding: 15px 0;
            display: block;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        main {
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-top: 20px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section h2 {
            font-size: 1.8em;
            margin-bottom: 10px;
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
        }

        .section p {
            font-size: 1em;
            line-height: 1.6;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <img src="images/profile-picture.jpg" alt="Victor Arboleda" class="profile-picture">
            <div class="header-info">
                <h1>Victor Arboleda</h1>
                <p>Assistant Professor, XYZ University</p>
                <p>Contact: <a href="mailto:email@example.com">email@example.com</a></p>
                <div class="social-links">
                    <a href="https://twitter.com"><img src="images/twitter-icon.png" alt="Twitter"></a>
                    <a href="https://github.com"><img src="images/github-icon.png" alt="GitHub"></a>
                    <!-- Add more social links as needed -->
                </div>
            </div>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#bio">Bio</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#teaching">Teaching</a></li>
                <li><a href="#advising">Advising</a></li>
                <li><a href="#vita">Vita</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about" class="section">
            <h2>About</h2>
            <p>I'm an Assistant Professor of Computer Science at XYZ University. My research seeks to make machine learning more broadly applicable...</p>
            <!-- Add more content as needed -->
        </section>
        <!-- Add more sections for Bio, News, Publications, etc. -->
    </main>
</body>
</html>
