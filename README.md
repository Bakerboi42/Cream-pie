# Cream-pie
body {
    font-family: 'Arial, sans-serif';
    background-color: #f8f8f8;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #ffcccb;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    color: #444;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #ffe4e1;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #444;
    padding: 10px 20px;
}

nav ul li a:hover {
    background-color: #ffcccb;
    border-radius: 5px;
}

main {
    padding: 20px;
    text-align: center;
}

.intro, .recipe {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 20px auto;
    max-width: 600px;
}

.intro img, .recipe img {
    width: 100%;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #ffe4e1;
    position: fixed;
    width: 100%;
    bottom: 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cream Pie Recipe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Cream Pie Delight</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="recipe.html">Recipe</a></li>
        </ul>
    </nav>
    <main>
        <section class="recipe">
            <h2>Cream Pie Recipe</h2>
            <p>Follow these simple steps to create your own delicious cream pie:</p>
            <ol>
                <li>Prepare the crust...</li>
                <li>Mix the filling...</li>
                <li>Bake and cool...</li>
                <li>Decorate and serve...</li>
            </ol>
            <img src="images/cream_pie_process.jpg" alt="Baking process of cream pie">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Cream Pie Delight</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cream Pie Recipe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Cream Pie Delight</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="recipe.html">Recipe</a></li>
        </ul>
    </nav>
    <main>
        <section class="intro">
            <h2>Welcome to the Cream Pie Recipe</h2>
            <p>Discover the deliciousness of our classic cream pie recipe. Perfect for any occasion!</p>
            <img src="images/cream_pie_intro.jpg" alt="Delicious cream pie">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Cream Pie Delight</p>
    </footer>
</body>
</html>
