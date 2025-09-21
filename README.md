# blogind_duniya
simple website 
here is html part
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloging_karle</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#blog-posts">Blog Posts</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact Us</a></li>
                <!-- <li><a href="#blog-posts">Blog-Section</a></li> -->
            </ul>
        </nav>
 </header>

    <section id="home" class="home-section">
        <h1>Welcome to Our Blog!</h1>
        <p>Explore insightful articles and stories.</p>
        <a href="#blog-posts" class="btn">Read Blog Posts</a>
    </section>

 <section id="blog-posts" class="blog-posts">
        <h2>Blog Posts</h2>
        <div class="post-card">
            <h3>Blog Post 1</h3>
            <p>This is a short description of the blog post...</p>
            <a href="#">Read More</a>
        </div>
        <div class="post-card">
            <h3>Blog Post 2</h3>
            <p>This is a short description of the blog post...</p>
            <a href="#">Read More</a>
        </div>
        <div class="post-card">
            <h3>Blog Post 3</h3>
            <p>This is a short description of the blog post...</p>
            <a href="#">Read More</a>
        </div>
    </section>

    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>We are passionate about sharing knowledge and engaging with our audience. Our mission is to deliver insightful articles on various topics that matter to you.</p>
    </section>
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out to us!</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Blog Website | All Rights Reserved</p>
    </footer> 
    here is the css part 
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.8;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #333333;
    color: #fff;
    padding: 1rem;
    position: sticky;
    top: 1;
    z-index: 100;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: rgb(247, 183, 49);
    transition: color 0.5s;
}

.home-section {
    text-align: center;
    padding: 50px 0;
    background-color:white;
}

.home-section h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.home-section p {
    font-size: 1.2rem;
    /* font-weight: bold; */
    /* margin-top: 20px; */
    margin-bottom: 30px;
}

.home-section .btn {
    background-color: rgb(247, 183, 49);
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    text-decoration: none;
}
.home-section .btn:hover {
    background-color: #d89e2a;
    
}
.blog-posts {
    padding: 30px;
    background-color: white;
}

.blog-posts h2 {
    text-align: center;
    /* margin-top: 5px; */
    margin-bottom: 20px;
    font-size: 2.2rem;
}

.post-card {
    background-color: white ;
    width: 30%;
    margin-bottom: 30px;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(247, 183, 49, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: inline-block;
    margin-right: 3%;
}

.post-card:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
}

.post-card h3 {
    font-size: 1.8rem;
    margin-bottom: 15px;
}

.post-card p {
    font-size: 1rem;
    margin-bottom: 10px;
}

.post-card a {
    color: rgb(247, 183, 49);
    text-decoration: none;
}

.post-card a:hover {
    text-decoration: underline;
}
.about-section {
    padding: 50px;
    text-align: center;
    background-color: rgb(247, 247, 247);
}
.contact-section {
    padding: 50px;
    background-color: rgb(228,228,228);
}
.contact-section h2,p {
   text-align: center;
}

.contact-section form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contact-section input, .contact-section textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid white;
    border-radius: 5px;
}

.contact-section button {
    background-color: rgb(247, 183, 49);
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact-section button:hover {
    background-color: rgb(247, 183, 49);
}
footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

</body>
</html>
