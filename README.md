# Calm-hub
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CalmHub — Emotional Listening & Healing</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet">
</head>

<body>

<!-- NAVBAR -->
<header>
    <div class="logo">CalmHub</div>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Healing</a></li>
            <li><a href="#breath">Breathing</a></li>
            <li><a href="#testimonials">Stories</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- HERO SECTION -->
<section id="home" class="hero">
    <div class="hero-text">
        <h1>Welcome to <span>CalmHub</span></h1>
        <p>Your safe, private space to talk, release, breathe, and heal with presence.</p>
        <a href="https://wa.me/919598243010" class="btn">Talk to Me on WhatsApp</a>
    </div>
</section>

<!-- SERVICES -->
<section id="services" class="services">
    <h2>My Healing Support</h2>
    <div class="service-grid">

        <div class="service-box">
            <h3>Emotional Listening</h3>
            <p>Talk freely. Be fully heard without judgment or interruption.</p>
        </div>

        <div class="service-box">
            <h3>Stress Relief Guidance</h3>
            <p>Gentle practices to release tension and feel grounded.</p>
        </div>

        <div class="service-box">
            <h3>Relationship Clarity</h3>
            <p>Understand emotions, patterns, wounds & intuitive guidance.</p>
        </div>

        <div class="service-box">
            <h3>Anxiety Calm-Down</h3>
            <p>Real-time grounding, breathing, and emotional stabilization.</p>
        </div>

    </div>
</section>

<!-- BREATHING EXERCISE -->
<section id="breath" class="breathing">
    <h2>1-Minute Breathing Exercise</h2>
    <p>Follow the circle. Inhale… Hold… Exhale… Feel your body soften.</p>
    
    <div id="breath-circle"></div>

    <button class="btn" onclick="startBreathing()">Start Breathing</button>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials" class="testimonials">
    <h2>Healing Stories</h2>
    
    <div class="test-card">
        <p>“I felt safe for the first time in months. Her listening healed me deeply.”</p>
        <h4>— Anjali</h4>
    </div>

    <div class="test-card">
        <p>“She helped me understand my emotions and breathe through panic.”</p>
        <h4>— Rohan</h4>
    </div>

    <div class="test-card">
        <p>“A warm presence. CalmHub is now my space when life feels heavy.”</p>
        <h4>— Manya</h4>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
    <h2>Contact & Sessions</h2>
    
    <p>Email: <strong>ritushasingh.5@gmail.com</strong></p>

    <p>Payments UPI: <strong>ritushasingh.5@okicici</strong></p>
    
    <a href="https://wa.me/919598243010" class="btn">Book Session on WhatsApp</a>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2025 CalmHub — Emotional Healing & Listening</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #f6f9f4;
    color: #333;
}

/* NAVBAR */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 25px;
    background: #0f3d2e;
    color: white;
    position: sticky;
    top: 0;
}

header .logo {
    font-family: 'Playfair Display', serif;
    font-size: 26px;
    font-weight: 700;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: 400;
}

/* HERO */
.hero {
    height: 80vh;
    background: linear-gradient(to bottom, rgba(0,0,0,0.4), rgba(0,0,0,0.6)),
    url("https://images.unsplash.com/photo-1506126613408-eca07ce68773") center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    padding: 20px;
}

.hero h1 {
    font-size: 38px;
    font-family: 'Playfair Display', serif;
}

.hero span {
    color: #9be7c4;
}

.hero p {
    margin: 15px auto;
    max-width: 500px;
}

.btn {
    padding: 12px 22px;
    background: #1b5f44;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    display: inline-block;
    margin-top: 10px;
}

/* SERVICES */
.services {
    padding: 50px 20px;
    text-align: center;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.service-box {
    padding: 20px;
    background: white;
    border-radius: 12px;
    border-left: 5px solid #1b5f44;
}

/* BREATHING */
.breathing {
    padding: 50px 20px;
    text-align: center;
    background: #e7f4ec;
}

#breath-circle {
    width: 140px;
    height: 140px;
    margin: 25px auto;
    border-radius: 50%;
    background: #1b5f44;
    animation: none;
}

@keyframes breathe {
    0% { transform: scale(1); }
    50% { transform: scale(1.4); }
    100% { transform: scale(1);}
}

/* TESTIMONIALS */
.testimonials {
    padding: 50px 20px;
    text-align: center;
}

.test-card {
    background: white;
    padding: 20px;
    margin: 20px auto;
    max-width: 500px;
    border-radius: 12px;
    border-top: 5px solid #1b5f44;
}

/* CONTACT */
.contact {
    padding: 50px 20px;
    text-align: center;
}

footer {
    background: #0f3d2e;
    color: white;
    padding: 15px;
    text-align: center;
}
