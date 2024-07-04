## OBJECTIVE:
To Create a simplified clone of Dribbble (https://dribbble.com/) landing page.

## DESCRIPTION:
Created a simplified clone of Dribble Landing Page With the use of HTML and CSS

## HTML CODE:
Style.css
```c
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #d71717;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ffffff;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #253dca;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

.auth-buttons {
    display: flex;
}

.auth-buttons button {
    margin-left: 10px;
    padding: 5px 10px;
    border: none;
    cursor: pointer;
}

.auth-buttons .sign-in {
    background-color: #ffffff;
    color: #ea4c89;
    border: 1px solid #ea4c89;
}

.auth-buttons .sign-up {
    background-color: #ea4c89;
    color: #ffffff;
}

.hero {
    text-align: center;
    padding: 50px 20px;
    background-color: #ffffff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 20px;
}

.hero h1 {
    margin: 0 0 10px;
    font-size: 36px;
}

.hero p {
    margin: 0;
    font-size: 18px;
    color: #16b79c;
}

.shots {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 20px;
}

.shot {
    margin: 10px;
}

.shot img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(207, 68, 17, 0.944);
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
    margin-top: 20px;
}
```
page.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Dribbble</div>
        <nav>
            <ul>
                <li><a href="#">Inspiration</a></li>
                <li><a href="#">Find Work</a></li>
                <li><a href="#">Learn Design</a></li>
                <li><a href="#">Go Pro</a></li>
                <li><a href="#">Marketplace</a></li>
            </ul>
        </nav>
        <div class="auth-buttons">
            <button class="sign-in">Sign In</button>
            <button class="sign-up">Sign Up</button>
        </div>
    </header>

    <main>
        <section class="hero">
            <h1>Discover the world's top designers & creatives</h1>
            <p>Dribbble is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
        </section>

        <section class="shots">
            <!-- Example shot thumbnails -->
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-97215af984340e907548a5abf8bec3ae.jpg" alt="Design Shot 1">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-fbdb2345c706a6e30d97e66853bde721.png" alt="Design Shot 2">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\still-92fe863f0cbd64f6e2b8001f6cc5b207.png" alt="Design Shot 3">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-b0a3477189ac4c29e58248f387ac8d6d.jpg" alt="Design Shot 4">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-f23ed57c7f52ac2c8c92956ff44801a7.png" alt="Design Shot 5">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\still-92fe863f0cbd64f6e2b8001f6cc5b207 (1).png" alt="Design Shot 6">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-4d9749365fdfb9c145a7024a97574998.png" alt="Design Shot 7">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-570ff1cd44ef1451e66e377fa52aab66.jpg" alt="Design Shot 8">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-f640f776da193d4ec22261abc50eca48.png" alt="Design Shot 9">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-0b2b46375f7405827a5be52319fe8b0d.gif" alt="Design Shot 10">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-43e859ab8a16db9ad7dfb6cf08242fa3.jpg" alt="Design Shot 11">
            </div>
            <div class="shot">
                <img src="c:\Users\Lenovo\Downloads\original-28789540e847d0e0376b72f77bd0f0be (1).png" alt="Design Shot 12">
            </div>
        </section>
    </main>

    <footer>
        <p>© 2024 Dribbble Clone</p>
    </footer>
</body>
</html>
```
## OUTPUT:
[Screenshot (27)](https://github.com/premjivip/html.css/assets/143831886/fe16d648-cbd6-4e38-9526-b60339f67143)

