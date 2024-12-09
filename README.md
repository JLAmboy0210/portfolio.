body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f4f4f9;
}

header {
    background-color: #333;
    color: white;
    padding: 1em 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    margin-left: 1em;
    font-size: 1.5em;
    text-decoration: none;
    color: white;
}

header nav {
    margin-right: 1em;
}

header nav a {
    margin: 0 0.5em;
    color: white;
    text-decoration: none;
}

header nav a:hover,
header nav a.active {
    text-decoration: underline;
}

.home {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 2em;
    background-color: #ff6347;
    color: white;
}

.home-img img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

.home-content {
    max-width: 600px;
}

.home-content h1 span {
    color: #ffa500;
}

.social-icons {
    margin-top: 1em;
}

.social-icons a {
    margin: 0 0.5em;
    color: white;
    font-size: 1.2em;
}

section {
    padding: 2em;
    text-align: center;
    background-color: #f4f4f9;
    color: #333;
}

#skills ul {
    list-style: none;
    padding: 0;
}

#skills ul li {
    background-color: #e0e0e0;
    margin: 0.5em 0;
    padding: 0.5em;
    border-radius: 5px;
}

.project-item {
    background-color: #e0e0e0;
    margin: 1em auto;
    padding: 1em;
    border-radius: 5px;
    text-align: center;
    max-width: 300px; /* Set the maximum width for the project box */
}

.project-item img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

#contact div {
    margin-top: 1em;
}

#contact a {
    color: #333;
    text-decoration: none;
    font-size: 1.2em;
}

#contact a:hover {
    text-decoration: underline;
}

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="stylesheet" href="amboy.css">
    <title>Portfolio Website</title>
</head>

<body>
    <header>
        <a href="#" class="logo">John Lloyd</a>
        <nav>
            <a href="#home" class="active">Home</a>
            <a href="#about">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section class="home" id="home">
        <div class="home-img">
            <img src="C:/Users/DREAM PC/Downloads/main.jpg" alt="Profile Picture">
        </div>
        <div class="home-content">
            <h1>Hi, I'm <span>John Lloyd Amboy</span></h1>
            <div class="social-icons">
                <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#"><i class="fa-brands fa-github"></i></a>
                <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>I'm 20 years old, an ambitious IT student who balances academics with the responsibilities of a working
            student. Despite the challenges, I excel at managing my time effectively, ensuring both my studies and work
            commitments receive the attention they deserve. My dedication to learning and professional growth is evident
            in my proactive approach to tackling complex IT projects. At work, my technical skills and problem-solving
            abilities make me an invaluable asset to my team. I continually strive to apply our classroom knowledge in
            practical, real-world scenarios, enhancing my expertise. My resilience and determination to succeed in both
            my education and career path make me a standout individual.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-item">
            <h3>Project 1</h3>
            <img src="C:/Users/DREAM PC/Downloads/dddd.png" alt="Project 1 Image">
        </div>
        <div class="project-item">
            <h3>Project 2</h3>
            <img src="C:/Users/DREAM PC/Downloads/132.png" alt="Project 2 Image">
        </div>
        <div class="project-item">
            <h3>Project 3</h3>
            <img src="C:/Users/DREAM PC/Downloads/LH.png" alt="Project 3 Image">
        </div>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out via Instagram.</p>
        <div>
            <a href="#"><i class="fa-brands fa-instagram"> https://www.instagram.com/amboy_johnlloyd</i></a>
        </div>
    </section>
</body>

</html>

