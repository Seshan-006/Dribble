# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
**html**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" con
    tent="width=device-width, initial-scale=1.0">
    <title>Ecommerce Responsive full website</title>
    <!-- CSS-link -->
    <link rel="stylesheet" href="res.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css?family=Jost:wght@100;200;300;400;500;
600;700&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBOVD591QIYicR65iaqukzvf/ nwasF0nqhPay5w/91JmVM2hMDcnK10nMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />

<link rel="stylesheet"
href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">
</head>
<body>
    <header>
        <a href="#" class="logo"><img src="./logo-no-background.png" alt=""></a>

        <ul class="navmenu">
            <li><a href="#">home</a></li>
            <li><a href="#">shop</a></li>
            <li><a href="#">products</a></li>
            <li><a href="#">page</a></li>
            <li><a href="#">Docs</a></li>
        </ul>

        <div class="nav-icon">
            <a href="#"><i class='bx bx-search'></i></a>
            <a href="#"><i class='bx bx-user' ></i></a>
            <a href="#"><i class='bx bx-cart' ></i></a>
            
            <div class="bx bx-menu" id="menu-icon"></div>
        </div>
    </header>

    <section class="main-home">
        <div class="main-text">
        <h1><br></h1>
        <h1><br></h1>
        <h5>Winter Collection</h5>
        <h2>New Winter <br> Collection</h2> 
        <p>There's Nothing like Trend</p>
        
        <a href="#" class="main-btn">Shop Now <i class='bx bx-right-arrow-alt' ></i></a>
        </div>

        <div class="down-arrow">
            <a href="#trending" class="down"><i class='bx bx-down-arrow-alt' ></i></a>
        </div>
    </section>

        <section class="trending-product" id="trending"> 
            <div class="center-text"> 
                <h2>Our Trending <span>Products</span></h2> 
            </div>

            <div class="products">
                <div class="row">
                    <img src="./trend.jpg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>Sale</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Half Running Set</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>
                

                <div class="row">
                    <img src="./fashion-stylish-model-dressed-elegant-light-pink-suit-posing-near-white-wall.jpg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>New</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Coat-suits</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src=".//man-fitness-workout.jpg" height="500px" width="300px" alt="">
         
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Half Running Suit</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src="./woman-with-hand-her-hair.jpg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>Hot</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Half Fancy Lady Dress</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src="./full-shot-smiley-woman-posing-outdoors.jpg" height="700px" width="300px" alt="">

                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Flix Flox Jeans</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src="./fancy-salwar-kameez-1000x1000.jpeg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>Hot</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Fancy Salwar Suit</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src="./front-view-woman-green-house.jpg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>Sale</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Printed Straight Kurta</h4> 
                        <p>$99-$129</p>
                    </div>
                </div>

                <div class="row">
                    <img src="./young-handsome-hipster-man-standing-talking-phone.jpg" height="500px" width="300px" alt="">
                    <div class="product-text">
                        <h5>Sale</h5>
                    </div>
                    <div class="heart-icon">
                    <i class='bx bx-heart'></i>
                    </div>
                    <div class="ratting">
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bx-star'></i>
                        <i class='bx bxs-star-half' ></i>
                    </div>
                    
                    <div class="price"> 
                        <h4>Casuals</h4> 
                        <p>$99-$129</p>
            </div>

        </section>

        <section class="client-reviews">
            <div class="reviews">
                <h3>Client Reviews</h3>
                <img src="./ceo.jpeg" alt="">
                <p>Facsinate has become my go-to brand for timeless elegance. From their impeccably tailored blazers to their buttery-soft leather accessories, every piece feels like an investment in style. The attention to detail—subtle stitching, hidden pockets, and exquisite linings—sets them apart. Whether I’m dressing for a boardroom meeting or a weekend brunch, LuxeCo effortlessly bridges sophistication and comfort. Plus, their sustainable practices make me feel good about my choices. Five stars from this satisfied shopper</p>
                
                <h2>Mark Jevenue</h2>
                <p>CEO of Addle</p>
            </div>
        </section>

    <section class="Update-news">
        <div class="up-center-text">
            <h2>New Updates</h2>
        </div>

        <div class="update-cart">
            <div class="cart">
                <img src="./group-young-asian-woman-shopping-outdoor-market-with-shopping-bags-their-hands.jpg" alt="">
                <h5>26 jan 2022</h5>
                <h4>Let's Start bring sale on this summer vacation.</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
                
                <h6><b>Continue Reading..</b></h6>
            </div>

            <div class="cart">
                <img src="./happy-overjoyed-woman-rejoicing-her-success.jpg" alt="">
                <h5>26 jan 2022</h5>
                <h4>Let's Start bring sale on this summer vacation.</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
                
                <h6><b>Continue Reading..</b></h6>
            </div>

            <div class="cart">
                <img src="./fff.jpg" alt="">
                <h5>26 jan 2022</h5>
                <h4>Let's Start bring sale on this summer vacation.</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis</p>
                
                <h6><b>Continue Reading..</b></h6>
            </div>
        </div>
    </section>

    <!-- contact-section -->
<section class="contact">
    <div class="contact-info">
        <div class="first-info">
            <img src="./logo-no-background.png" alt="">
            <p>3245 Grant Street Longview, <br> TX united kingdom 765378</p>
            <p>01601348732</p>
            <p>saidulahmed3080@gmail.com</p>
           
            <div class="social-icon">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-twitter' ></i></a>
                <a href="#"><i class='bx bxl-instagram' ></i></a>
                <a href="#"><i class='bx bxl-youtube' ></i></a>
                <a href="#"><i class='bx bxl-linkedin' ></i></a>
            </div>
        </div>
            <div class="second-info">
                <h4>Support</h4>
                <p>Contact us</p>
                <p>About page</p>
                <p>Size Guide</p>
                <p>Shopping & Resturns</p>
                <p>Privacy</p>
        </div>

        <div class="third-info">
            <h4>Shop</h4>
            <p>Men's Shopping</p>
            <p>Women's Shopping</p>
            <p>Kids's Shopping</p>
            <p>Furniture</p>
            <p>Discount</p>
        </div>

        <div class="fourth-info">
            <h4>Company</h4>
            <p>About</p>
            <p>Blog</p>
            <p>Affiliate</p>
            <p>Login</p>
        </div>

        <div class="five">
            <h4>Subscribe</h4>
            <p>Receive Updates, Hot Deals, Discounts Sent Straight In Your Inbox
            Daily</p>
            <p>Lorem Ipsum Dolor Sit Amet Consectetur Adipisicing Elit. Eum,
            Debitis.</p>
            <p>Receive Updates, Hot Deals, Discounts Sent Straight In Your Inbox
            Daily</p>
        </div>
    </div>
    </section>

    <div class="end-text" >
        <p>Copyright © @2024. All Rights Reserved.</p>
    </div>
    
    <script src="res.js"></script>

</body>
</html>
```


## OUTPUT:


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
