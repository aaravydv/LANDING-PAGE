// HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="dgg.css">
    <title>Your Landing Page</title>
</head>
<body>

    <header>
        <h1>LANDING PAGE WEB</h1>
        <p>Welcome to our awesome website</p>
    </header>

    <section id="hero">
        <h2>Discover Something Amazing</h2>
        <p>Your catchy tagline goes here. Briefly describe what you offer.</p>
        <a href="#features" class="cta-button">Learn More</a>
    </section>

    <section id="features">
        <div class="feature">
            <h3>Feature 1</h3>
            <p>Description of the first awesome feature.</p>
        </div>
        <div class="feature">
            <h3>Feature 2</h3>
            <p>Description of the second awesome feature.</p>
        </div>
        <div class="feature">
            <h3>Feature 3</h3>
            <p>Description of the third awesome feature.</p>
        </div>
        <div class="feature">
            <h3>Product 1</h3>
            <p> this was the first awesome feature.</p>
        </div>
        <div class="feature">
            <h3>product 2</h3>
            <p>Description of the second awesome feature.</p>
        </div>
        <div class="feature">
            <h3>Product 3</h3>
            <p>Description of the third awesome feature.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Brand. All rights reserved.</p>
    </footer>

</body>
</html>



//CSS
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

header h1 {
    margin: 0;
}

section {
    text-align: center;
}

#hero {
    background-color: #f8f8f8;
    padding: 60px 20px;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 20px;
    text-decoration: none;
    color: #fff;
    background-color: #333;
    border-radius: 5px;
}

#features {
    background-color: #e0e0e0;
    display: flex;
    justify-content: space-around;
    padding: 40px;
}

.feature {
    max-width: 300px;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    margin: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
