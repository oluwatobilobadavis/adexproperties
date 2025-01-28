<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adex Properties</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ae00ff;
            color: #fff;
        }

        header {
            background-color: #d400ff;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .DESSS123.png {
            width: 50px;
            margin-right: 10px;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav li {
            margin-left: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
        }

        .hero {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 5rem 0;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            color: #fff;
        }

        .about {
            background-color: #000;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            grid-gap: 2rem;
        }

        .product {
            background-color: #000;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
            margin-bottom: 1rem;
        }

        .product h3 {
            margin-bottom: 0.5rem;
            color: #fff;
        }

        .product .price {
            font-weight: bold;
            color: #fff;
        }

        .btn {
            display: inline-block;
            padding: 1rem 2rem;
            background-color: #fff;
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }

        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            <img src="DESSS123.png" width="100" height="100"alt="Adex Properties Logo"> 
            <h1>Adex Properties</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#products">Properties</a></li>
                <li><a href="https://wa.me/09070705470">Contact</a></li> 
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h2>Welcome to Adex properties & Consult</h2>
        <p>Affordable and Flexible Payment Plans</p>
    </section>

    <div class="container">
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>This is Adex Properties, a company owned by a skilled real estate realtor, who have gained achievement by helping so many persons own their dream property and home. We are unique by making it easy to get your dream property in affordable rate and flexible payment plans, trust us you won't regret.</p>
            <p>Adex Property is a brand from the Adex group of company, and we are unique because we offer affordable properties with flexible payment plan.</p>
        </section>

        <section id="products">
            <h2>Our Properties</h2>
            <div class="products">
                <div class="product">
                    <img src="adex pro.jpg" "width="250" height="250" alt="Isura phase 2 (epe)">
                    <h3>Isura phase 2</h3>
                    <p>Isura phase 2, is located at igbodu Epe, Lagos, this property is own by pwanxtra, and has a flexible payment plan for 6 month.</p>
                    <p class="price">₦2.5million</p>
                    <a href="learn-more1.html" class="btn">09070705470</a>
                </div>

                <div class="product"> 
                    <img src="enyiaba123.jpg" alt="Property 2">
                    <h3>Enyiaba, Phase 2</h3>
                    <p>this prperty is located in obingwa LGA, Aba.It has amazing landmarks like- The Nigeria television authority (NTA) Aba. this property is own by pwan xtra</p>
                    <p class="price">₦6million</p>
                    <a href="learn-more2.html" class="btn">09070705470</a>
                </div>

                <div class="product">
                    <img src="adex p.jpg" alt="Property 3">
                    <h3>Action ville</h3>
                    <p>This property is located at Eredo epe, and is owned by pwan action, This property also have a six month  flexible payment plan, And have Land Mark like- ketu roundabout, lagos film city, and lot more</p>
                    <p class="price">₦4.5million</p>
                    <a href="learn-more3.html" class="btn">09070705470</a>
                </div>

                <div class="product">
                    <img src="adex pr.jpg" alt="Property 4">
                    <h3>Isura phase 2</h3>
                    <p>currently isura phase 2 is on promo. (buy 2 get 1 free)</p>
                    <p class="price">₦5million</p>
                    <a href="learn-more4.html" class="btn">09070705470</a>
                </div>

                <div class="product">
                    <img src="adex prop.jpg" alt="ddd23.jpg">
                    <h3>Omititun phase 3</h3>
                    <p>This property is located at Awodikura, ode omi, ibejulekki Lagos. & it has a flexible payment plan for six month, own by pwan xtra</p>
                    <p class="price">₦1.2million</p>
                    <a href="learn-more5.html" class="btn">09070705470</a>
                </div>

                <div class="product">
                    <img src="ddd23.jpg" alt="Property 6">
                    <h3>Flourish spring, odeomi phase 3</h3>
                    <p>This property is located at odeomi Ibejulekki Lagos, and is own by Pwan Homes</p>
                    <p class="price">₦1.2million</p>
                    <a href="learn-more6.html" class="btn">09070705470</a>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>09070705470</p>
            <p>Manager: OLUWATOBILOBA Davis</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Adex Properties</p>
        <p>A product from the Adex group of company</p>
    </footer>

</body>
</html>
