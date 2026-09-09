index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Yummy Tummy | Family Restaurant - Anakapalli</title>
    <meta
        name="description"
        content="Yummy Tummy Family Restaurant in Anakapalli. Biryani, Chinese, North Indian and Mughlai cuisine."
    >

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link
        href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@600;700;800&display=swap"
        rel="stylesheet"
    >

    <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- NAVBAR -->
<header class="navbar">
    <a href="#home" class="logo">
        <span>Y</span>
        Yummy Tummy
    </a>

    <nav id="navMenu">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <a class="nav-order" href="tel:+919459669888">
        Call Now
    </a>

    <button class="menu-btn" onclick="toggleMenu()">☰</button>
</header>


<!-- HERO -->
<section id="home" class="hero">

    <div class="hero-content">

        <p class="eyebrow">WELCOME TO YUMMY TUMMY</p>

        <h1>
            Good Food.
            <br>
            <span>Great Memories.</span>
        </h1>

        <p class="hero-text">
            Delicious flavours, generous portions and a warm
            family dining experience in Anakapalli.
        </p>

        <div class="hero-buttons">
            <a href="#menu" class="btn primary">Explore Menu</a>

            <a href="tel:+919459669888" class="btn secondary">
                Call Restaurant
            </a>
        </div>

        <div class="hero-info">
            <div>
                <strong>🍽️</strong>
                <span>Family Dining</span>
            </div>

            <div>
                <strong>🥘</strong>
                <span>Fresh Flavours</span>
            </div>

            <div>
                <strong>📍</strong>
                <span>Anakapalli</span>
            </div>
        </div>

    </div>

    <div class="hero-card">
        <div class="food-circle">
            🍛
        </div>

        <p>Our speciality</p>
        <h3>Authentic Indian Flavours</h3>
    </div>

</section>


<!-- ABOUT -->
<section id="about" class="section about">

    <div class="section-image">
        <div class="image-placeholder large">
            🍽️
        </div>
    </div>

    <div class="section-content">

        <p class="eyebrow">ABOUT US</p>

        <h2>A place for food,<br>family & memories.</h2>

        <p>
            Yummy Tummy Family Restaurant brings together a wide
            variety of flavours in a comfortable family-friendly
            dining environment.
        </p>

        <p>
            From biryanis and Chinese favourites to North Indian
            and Mughlai dishes, there is something for everyone.
        </p>

        <div class="features">
            <div>
                <span>✓</span>
                Family Friendly
            </div>

            <div>
                <span>✓</span>
                Dine-in & Takeaway
            </div>

            <div>
                <span>✓</span>
                Variety of Cuisines
            </div>

            <div>
                <span>✓</span>
                Delivery Available
            </div>
        </div>

    </div>

</section>


<!-- POPULAR -->
<section class="section popular">

    <div class="section-heading">
        <p class="eyebrow">CUSTOMER FAVOURITES</p>

        <h2>Popular Picks</h2>

        <p>
            A few highlights from the restaurant's menu.
        </p>
    </div>

    <div class="food-grid">

        <article class="food-card">
            <div class="food-img">🍗</div>

            <div class="food-info">
                <span class="tag">SPECIAL</span>
                <h3>Avaka Chicken Biryani</h3>
                <p>Flavourful chicken biryani with a special twist.</p>
            </div>
        </article>


        <article class="food-card">
            <div class="food-img">🍛</div>

            <div class="food-info">
                <span class="tag">POPULAR</span>
                <h3>Potlam Chicken Biryani</h3>
                <p>A delicious biryani favourite from the menu.</p>
            </div>
        </article>


        <article class="food-card">
            <div class="food-img">🥘</div>

            <div class="food-info">
                <span class="tag">FOR SHARING</span>
                <h3>Mixed Mandi</h3>
                <p>A generous sharing option for family and friends.</p>
            </div>
        </article>

    </div>

</section>


<!-- MENU -->
<section id="menu" class="section menu-section">

    <div class="section-heading">
        <p class="eyebrow">OUR MENU</p>

        <h2>Something for everyone</h2>

        <p>
            Explore some of the dishes available at Yummy Tummy.
        </p>
    </div>


    <div class="menu-tabs">

        <button class="active" onclick="filterMenu('all', this)">
            All
        </button>

        <button onclick="filterMenu('special', this)">
            Specials
        </button>

        <button onclick="filterMenu('veg', this)">
            Veg
        </button>

        <button onclick="filterMenu('nonveg', this)">
            Non-Veg
        </button>

        <button onclick="filterMenu('rice', this)">
            Rice & Noodles
        </button>

    </div>


    <div class="menu-grid" id="menuGrid">

        <article class="menu-item special">
            <div class="menu-icon">🍚</div>
            <div>
                <h3>Veg Rice Bowl</h3>
                <p>Special vegetarian rice bowl.</p>
            </div>
        </article>


        <article class="menu-item special">
            <div class="menu-icon">🍗</div>
            <div>
                <h3>Avaka Chicken Biryani</h3>
                <p>Special chicken biryani.</p>
            </div>
        </article>


        <article class="menu-item special">
            <div class="menu-icon">🍗</div>
            <div>
                <h3>Gongura Chicken Biryani</h3>
                <p>Chicken biryani with gongura flavours.</p>
            </div>
        </article>


        <article class="menu-item special">
            <div class="menu-icon">🍛</div>
            <div>
                <h3>Potlam Chicken Biryani</h3>
                <p>Popular biryani speciality.</p>
            </div>
        </article>


        <article class="menu-item special">
            <div class="menu-icon">🍤</div>
            <div>
                <h3>Potlam Prawns Biryani</h3>
                <p>Flavourful prawns biryani.</p>
            </div>
        </article>


        <article class="menu-item special">
            <div class="menu-icon">🍖</div>
            <div>
                <h3>Mixed Mandi</h3>
                <p>Sharing option for family and friends.</p>
            </div>
        </article>


        <article class="menu-item veg">
            <div class="menu-icon">🥦</div>
            <div>
                <h3>Mushroom Manchurian</h3>
                <p>Crispy mushroom preparation.</p>
            </div>
        </article>


        <article class="menu-item veg">
            <div class="menu-icon">🧀</div>
            <div>
                <h3>Paneer Chilli</h3>
                <p>Spicy Indo-Chinese paneer.</p>
            </div>
        </article>


        <article class="menu-item veg">
            <div class="menu-icon">🍄</div>
            <div>
                <h3>Pepper Mushroom</h3>
                <p>Mushroom tossed with pepper spices.</p>
            </div>
        </article>


        <article class="menu-item nonveg">
            <div class="menu-icon">🍗</div>
            <div>
                <h3>Chicken Fried Rice</h3>
                <p>Classic chicken fried rice.</p>
            </div>
        </article>


        <article class="menu-item nonveg">
            <div class="menu-icon">🍗</div>
            <div>
                <h3>Chicken Chettinad</h3>
                <p>Rich and aromatic chicken preparation.</p>
            </div>
        </article>


        <article class="menu-item nonveg">
            <div class="menu-icon">🐟</div>
            <div>
                <h3>Fish Curry</h3>
                <p>Traditional style fish curry.</p>
            </div>
        </article>


        <article class="menu-item rice">
            <div class="menu-icon">🍚</div>
            <div>
                <h3>Veg Fried Rice</h3>
                <p>Classic vegetable fried rice.</p>
            </div>
        </article>


        <article class="menu-item rice">
            <div class="menu-icon">🍜</div>
            <div>
                <h3>Veg Schezwan Fried Rice</h3>
                <p>Spicy Schezwan-style fried rice.</p>
            </div>
        </article>


        <article class="menu-item rice">
            <div class="menu-icon">🍜</div>
            <div>
                <h3>Chicken Fried Rice</h3>
                <p>Popular chicken rice dish.</p>
            </div>
        </article>

    </div>

</section>


<!-- WHY US -->
<section class="why-us">

    <div>
        <p class="eyebrow">WHY YUMMY TUMMY?</p>

        <h2>Made for good food<br>and good company.</h2>
    </div>

    <div class="why-grid">

        <div>
            <span>01</span>
            <h3>Variety</h3>
            <p>
                Indian, Chinese and Mughlai favourites
                under one roof.
            </p>
        </div>

        <div>
            <span>02</span>
            <h3>Family Dining</h3>
            <p>
                A comfortable place to enjoy meals
                with family and friends.
            </p>
        </div>

        <div>
            <span>03</span>
            <h3>Convenient</h3>
            <p>
                Dine-in, takeaway and delivery options
                make ordering easy.
            </p>
        </div>

    </div>

</section>


<!-- GALLERY -->
<section id="gallery" class="section">

    <div class="section-heading">
        <p class="eyebrow">GALLERY</p>

        <h2>A taste of Yummy Tummy</h2>

        <p>
            Replace these placeholders with your real restaurant
            and food photographs.
        </p>
    </div>


    <div class="gallery">

        <div class="gallery-box big">🍛</div>

        <div class="gallery-box">🍗</div>

        <div class="gallery-box">🥘</div>

        <div class="gallery-box">🍜</div>

        <div class="gallery-box">🍽️</div>

    </div>

</section>


<!-- CONTACT -->
<section id="contact" class="contact">

    <div class="contact-content">

        <p class="eyebrow">VISIT US</p>

        <h2>Come hungry.<br>Leave happy.</h2>

        <div class="contact-details">

            <div>
                <span>📍</span>
                <div>
                    <strong>Address</strong>
                    <p>
                        Visakhapatnam NH-5 Road,<br>
                        Anakapalli, Andhra Pradesh 531002
                    </p>
                </div>
            </div>


            <div>
                <span>📞</span>
                <div>
                    <strong>Phone</strong>
                    <p>
                        <a href="tel:+919459669888">
                            +91 94596 69888
                        </a>
                    </p>
                </div>
            </div>


            <div>
                <span>🕐</span>
                <div>
                    <strong>Opening Hours</strong>
                    <p>
                        Daily: approximately 12:00 PM – 10:45 PM
                    </p>
                </div>
            </div>

        </div>


        <div class="contact-buttons">

            <a
                href="https://maps.app.goo.gl/snJWHTRWCr12Km8XA?g_st=ac"
                target="_blank"
                class="btn primary"
            >
                Get Directions
            </a>

            <a
                href="tel:+919459669888"
                class="btn secondary"
            >
                Call Us
            </a>

        </div>

    </div>

</section>


<!-- FOOTER -->
<footer>

    <div class="footer-logo">
        Yummy Tummy
    </div>

    <p>
        Good Food. Great Memories.
    </p>

    <p class="copyright">
        © <span id="year"></span> Yummy Tummy Family Restaurant.
        All rights reserved.
    </p>

</footer>


<!-- MOBILE BAR -->
<div class="mobile-bar">

    <a href="tel:+919459669888">
        📞 Call
    </a>

    <a href="#menu">
        🍽️ Menu
    </a>

    <a
        href="https://maps.app.goo.gl/snJWHTRWCr12Km8XA?g_st=ac"
        target="_blank"
    >
        📍 Directions
    </a>

</div>


<script src="script.js"></script>

</body>
</html>
