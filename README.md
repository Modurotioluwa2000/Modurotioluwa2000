<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Headphone Website Deisgn</title>
    <!-- Link to CSS -->
    <link rel="stylesheet" href="style.css">
    <!-- Box Icon -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>


</head>
<body>
    <!-- Main Content Container -->
    <div class="main">
        <!-- Header -->
        <header>
            <!-- Navbar -->
            <div class="nav container">
                <!-- Logo -->
                    <a href="#" class="logo">
                        <img src="IMG/logo.png" alt="">
                    </a>
                <!-- Menu Icon -->
                <i class='bx bx-menu' id="menu-icon"></i>
                <!-- Nav List -->
                <ul class="navbar">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#specs">Specs</a></li>
                    <li><a href="#shop">Shop</a></li>
                    <li><a href="#buds">Buds</a></li>
                </ul>
            </div>
        </header>
        <!-- Home -->
        <section class="home" id="home">
            <!-- Home Content -->
            <div class="home-content container">
                <div class="home-img">
                <img src="img/home.png" alt="">
                </div>
                <!-- Home text -->
                <div class="home-text">
                    <h1> Beat Solo 3 </h1>
                    <p> Beats Studio3 Wireless over-ear headphones delivers premium sound while blocking external noise Active Noise Cancelling.</p>
                    <a href="" class="btn">
                        <i class='bx bx-shopping-bag'></i>
                        <span> Add To Bag</span>
                    </a>
                </div>
            </div>
        </section>
        <!-- Specs -->
        <section class="specs" id="specs">
            <h1 class="heading">Specs</h1>
            <!-- Specs content -->
            <div class="specs-container container">
                <div class="specs-details">
                    <div class="box">
                        <i class='bx bxs-battery-charging'></i> 
                        <h3>Up to 22 hours of listening time</h3>
                        <p>Long-term comfort is matched by a battery life of 22 hours, and 40 hours of playback when Noise Cancelling is turned off.</p>
                    </div>
                    <div class="box">
                        <i class='bx bx-headphone' ></i>
                        <h3>Block external noise</h3>
                        <p>Noise cancelling continually pinpoints external sounds to block while automatically responding to individual fit and music playback.</p>
                    </div>
                </div>
                <div class="specs-img">
                    <img src="IMG/specs.png" alt="">
                </div>
            </div>
        </section>
        <!-- Shop -->
        <section class="shop" id="shop">
        <!-- Heading -->
        <h2 class="heading">Shop Now</h2>
        <!-- Shop Content -->
        <div class="shop-container container">
            <!-- Box 1 -->
            <div class="box">
                <img src="IMG/shop1.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            <!-- Box 2 -->
            <div class="box">
                <img src="IMG/shop2.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            <!-- Box 3 -->
            <div class="box">
                <img src="IMG/shop3.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            <!-- Box 4 -->
            <div class="box">
                <img src="IMG/shop4.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            <!-- Box 5 -->
            <div class="box">
                <img src="IMG/shop5.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            <!-- Box 6 -->
            <div class="box">
                <img src="IMG/shop6.png" alt="">
                <h3>Beats Solo</h3>
                <span>$394</span>
                <i class='bx bx-shopping-bag' ></i>
            </div>
            </div>
        </section>
        <!-- Buds  -->
        <section class="buds" id="buds">
            <div class="buds-container container">
                <div class="buds-text">
                    <h2>Beats Studio Bud</h2>
                    <span>$149.95</span>
                    <p>One-touch pairing for Apple and Android</p>
                    <a href="" class="btn">
                        <i class='bx bx-shopping-bag'></i>
                        <span>Buy Now</span>
                    </a>
                </div>
                <!-- Buds Image -->
                <div class="buds-img">
                    <img src="IMG/buds.png" alt="">
                </div>
            </div>
        </section>
        <!-- Footer -->
        <section class="footer container">
            <a href="#" class="logo"><img src="IMG/logo.png" alt=""></a>
            <div class="footer-box">
                <h2>Products</h2>
                <a href="#">Headphone</a>
                <a href="#">Earbuds</a>
                <a href="#">Earphone</a>
                <a href="#">Case</a>
            </div>
            <div class="footer-box">
                <h2>Payments</h2>
                <a href="#">Return Policy</a>
                <a href="#">Refunds Policy</a>
                <a href="#">Support</a>
                <a href="#">Terms of use</a>
            </div>
            <div class="footer-box">
                <h2>Social</h2>
                <div class="social">
                    <a href=""> <i class='bx bxl-facebook' ></i></a>
                    <a href=""> <i class='bx bxl-twitter' ></i></a>
                    <a href=""> <i class='bx bxl-instagram' ></i></a>
                </div>
            </div>
        </section>
        <!-- Copyright -->
        <div class="copyright">
            <p>&#169; CarpoolVenom All Reserved.</p>
        </div>
    </div>
    <!-- Scroll Reveal Animation -->
    <script src="https://unpkg.com/scrollreveal"></script>
     <!-- Link To JS -->
     <script src="main.js"></script>
</body>
</html>
