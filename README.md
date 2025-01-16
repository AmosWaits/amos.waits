<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One-Page Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        .hero {
            height: 100vh;
            background: url('your-photo.jpg') no-repeat center center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            position: relative;
        }

        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            z-index: 1;
        }

        .hero-content {
            z-index: 2;
            max-width: 800px;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }

        .hero p {
            font-size: 1.5rem;
            margin: 20px 0;
        }

        .content {
            padding: 40px 20px;
            text-align: center;
        }

        .content h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .content p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .contact {
            background: #f4f4f4;
            padding: 20px;
        }

        .contact h3 {
            margin-bottom: 10px;
        }

        .contact a {
            color: #007BFF;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }

            .hero p {
                font-size: 1.2rem;
            }

            .content h2 {
                font-size: 2rem;
            }

            .content p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header class="hero">
        <div class="hero-content">
            <h1>Your Name</h1>
            <p>Welcome to my portfolio</p>
        </div>
    </header>

    <section class="content">
        <h2>About Me</h2>
        <p>This is a short bio about you. Highlight your skills, experience, or something unique about yourself.</p>
    </section>

    <section class="contact">
        <h3>Contact</h3>
        <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
