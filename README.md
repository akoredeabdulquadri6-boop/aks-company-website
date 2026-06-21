#AKS COMPANY WEBSITE
 <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>AKS Group of Company</title>

    <defs>
        <linearGradient id="gold" x1="0" x2="1">
            <stop offset="0%" stop-color="#d4af37"/>
            <stop offset="100%" stop-color="#ffcc66"/>
        </linearGradient>
    <path d="M40 130 Q100 170 160 130" stroke="url(#gold)" stroke-width="6" fill="none"/>

        <linearGradient id="blue" x1="0" x2="1">
            <stop offset="0%" stop-color="#003366"/>
            <stop offset="100%" stop-color="#0055aa"/>
        </linearGradient>
    </defs>
    <!-- Circle -->
    <circle cx="100" cy="100" r="90" fill="none" stroke="url(#gold)" stroke-width="8"/
    </text>

    <!-- Small base line -->
    <path d="M40 130 Q100 170 160 130" stroke="url(#gold)" stroke-width="6" fill="none"/>
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab') no-repeat center center/cover;
    background-attachment:fixed;
    color:white;
    min-height:100vh;
}

.overlay{
    background:rgba(0,0,0,0.75);
    min-height:100vh;
}

header{
    background:rgba(0,51,102,0.95);
    text-align:center;
    padding:20px 15px;
}

header h1{
    font-size:3rem;
    letter-spacing:1px;
}

header p{
    margin-top:10px;
    font-size:1.1rem;
    line-height:1.6;
}

nav{
    background:#0055aa;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:1000;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

nav a:hover{
    color:gold;
}

.hero{
    text-align:center;
    padding:100px 20px;
}

.hero h2{
    font-size:3rem;
    margin-bottom:15px;
}

.hero p{
    font-size:1.2rem;
    max-width:820px;
    margin:0 auto;
    line-height:1.7;
}

section{
    max-width:1100px;
    margin:auto;
    padding:50px 20px;
}

.card{
    background:rgba(255,255,255,0.12);
    padding:30px;
    border-radius:15px;
    backdrop-filter:blur(8px);
    box-shadow:0 15px 30px rgba(0,0,0,0.25);
}

h2{
    color:gold;
    margin-bottom:20px;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.service-box{
    background:rgba(255,255,255,0.15);
    padding:20px;
    border-radius:10px;
    text-align:center;
    transition:transform 0.3s ease, box-shadow 0.3s ease;
}

.service-box:hover{
    transform:translateY(-6px);
    box-shadow:0 15px 30px rgba(0,0,0,0.2);
}

.service-box img{
    max-width:100%;
    border-radius:10px;
    margin-top:15px;
}

.contact-info p{
    margin:10px 0;
    line-height:1.7;
}

.contact-info a{
    color:gold;
    text-decoration:none;
}

.contact-info a:hover{
    text-decoration:underline;
}

form{
    margin-top:20px;
}

input,
textarea{
    width:100%;
    padding:12px;
    margin-bottom:15px;
    border:none;
    border-radius:5px;
}

textarea{
    min-height:140px;
}

button{
    background:#0055aa;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:5px;
    cursor:pointer;
    transition:background 0.3s ease,color 0.3s ease;
}

button:hover{
    background:gold;
    color:black;
}

.whatsapp-btn{
    display:inline-block;
    margin-top:15px;
    background:#25D366;
    color:white;
    padding:12px 20px;
    border-radius:5px;
    text-decoration:none;
}

footer{
    background:#003366;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

img{
    max-width:100%;
    display:block;
}

@media(max-width:768px){
    header h1{
        font-size:2rem;
    }

    .hero h2{
        font-size:2rem;
    }

    nav a{
        display:block;
        margin:10px 0;
    }
}
</style>
</head>

<body>
<svg width="200" height="200" viewBox="0 0 200 200">
    <defs>
        ...
    </defs>
</svg>

<div class="overlay">

<header>
    <h1>AKS GROUP OF COMPANY</h1>
    <p>Building Excellence, Innovation & Sustainable Growth</p>
</header>

<nav>
    <a href="#about">About Us</a> <a href="#services">Services</a> <a href="#location">Location</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <h2>Welcome to AKS Group of Company</h2>
    <p>Your trusted partner in Construction, Logistics, Oil & Gas, Motors and Real Estate.</p>
    OWNED AND CONTROL BY : ALHAJI AHMAD ISHOLA ADESHINA
</section>

<section id="about">
    <div class="card">
        <h2>About Us</h2>

        <p>
            AKS Group of Company is a diversified business organization based in
            Ibadan, Oyo State, Nigeria. We provide reliable and professional
            solutions across various sectors, delivering excellence, integrity,
            innovation and customer satisfaction.we are committed to contributing to economic growth and creating value. and we are high quality we deliver with peacuful mind
        </p>

        <br>

        <p>
            Our mission is to provide high-quality services that contribute to
            economic growth while creating value for our clients and communities.and help the nation.
            . and we are committed to delivering excellence in every project we undertake. 
        </p>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>

    <div class="services">

        <div class="service-box" onclick="showService('construction')">
            <h3>🏗 Construction</h3>
            <p>Building and civil engineering projects.</p>
            <img src="images/construction.jpg" alt="My Image" width="300">
        </div>

        <div class="service-box" onclick="showService('logistics')">
            <h3>🚛 Logistics</h3>
            <p>Transportation and supply chain solutions.</p>
            <img src="images/logistics.jpg" alt="My Image" width="300">
        </div>

        <div class="service-box" onclick="showService('oilgas')">
            <h3>⛽ Oil & Gas</h3>
            <p>Professional oil and gas services.</p>
            <img src="images/oil&gas.jpg" alt="My Image" width="300">
        </div>

        <div class="service-box" onclick="showService('motors')">
            <h3>🚗 Motors</h3>
            <p>Automobile sales and maintenance services.</p>
            <img src="images/motors.jpg" alt="My Image" width="350">a
        </div>

        <div class="service-box" onclick="showService('realestate')">
            <h3>🏠 Real Estate</h3>
            <p>Property development and management.</p>
            <img src="images/realestate.jpg" alt="My Image" width="300">
        </div>
        
        <div class="service-box" onclick="showService('hajjumrah')">
        <h3>🕋 Hajj & Umrah</h3>
        <p>Reliable pilgrimage travel, visa processing, accommodation, and guided Hajj & Umrah services.</p>
        <img src="images/hajj&umurah.jpg" alt="my image" width="300">
         </div> 

        <div class="service-box" onclick="showService('hajjumrah')">
        <h3>🕋 Hotel</h3>
        <p>Reliable pilgrimage travel, visa processing, accommodation, and guided Hajj & Umrah services.</p>
        <img src="images/hotel.jpg" alt="my image" width="300">

    </div>
</section>

<!-- Service Details -->
<section id="serviceDetails" class="card" style="display:none; margin-top:30px;">
    <h2 id="serviceTitle"></h2>

    <img id="serviceImage"
         src=""
         style="width:100%; max-width:700px; border-radius:10px; margin:20px 0;">

    <p id="serviceDescription"></p>
</section>
    </div>
</section>

</a>

<section id="location">
    <div class="card">
        <h2>Our Location</h2>

        <p>
            AKS Group of Company<br>
            Oju Odo, Olomi,<br>
            Ibadan, Oyo State,<br>
            Nigeria.
        </p>
    </div>

<section id="contact">
    <div class="card">

        <h2>Contact Us</h2>

        <div class="contact-info">

                <p>
    📧 Email:
    <a href="mailto:akoredeabdulquadri6@gmail.com"
       style="color:gold; font-weight:bold; text-decoration:none;">
        akoredeabdulquadri6@gmail.com
    </a>

            <p>
                📞 Phone:
                <a href="tel:+2349045267657">
                    +234 904 526 7657
                </a>
            </p>

                📍 Address:
<a href="https://www.google.com/maps/search/?api=1&query=Oju+Odo+Olomi+beside+risadet+filling+station+Ibadan+Oyo+State+Nigeria"
   target="_blank"
   style="color:gold; text-decoration:none;">
   Oju Odo, Olomi, beside Risadet Filling Station, Ibadan, Oyo State, Nigeria
</a>
            </p>

            <a class="whatsapp-btn"
               href="https://wa.me/2349045267657"
               target="_blank">
               Chat with us on WhatsApp
            </a>
        <!-- modify this form HTML and place wherever you want your form -->
<<form action="https://formspree.io/f/xbdeejqe" method="POST">

    <label for="name">Your Name:</label>
    <input type="text"
           id="name"
           name="name"
           placeholder="Enter your full name"
           required>

    <label for="email">Your Email:</label>
    <input type="email"
           id="email"
           name="email"
           placeholder="Enter your email address"
           required>

    <label for="phone">Phone Number:</label>
    <input type="tel"
           id="phone"
           name="phone"
           placeholder="Enter your phone number"
           required>

    <label for="subject">Subject:</label>
    <input type="text"
           id="subject"
           name="subject"
           placeholder="Message subject"
           required>

    <label for="message">Your Message:</label>
    <textarea id="message"
              name="message"
              placeholder="Type your message here..."
              rows="6"
              required></textarea>

    <button type="submit">Send Message</button>

</form>

</form>
    </div>
</section>

<footer>
    <p>&copy; 2026 AKS Group of Company. All Rights Reserved.</p>
</footer>

</div>
</html>


