cat-website/
├── index.html          # Homepage
├── about.html          # About page
├── gallery.html        # Photo gallery
├── contact.html        # Contact form
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js      # JavaScript functionality
└── images/            # Folder for cat images
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Purrfect Cats - Home</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1><i class="fas fa-paw"></i> Purrfect Cats</h1>
            <nav>
                <ul>
                    <li><a href="index.html" class="active">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Welcome to the Wonderful World of Cats</h2>
            <p>Discover amazing facts, beautiful photos, and helpful information about our feline friends.</p>
            <a href="gallery.html" class="btn">View Gallery</a>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <h2>Why We Love Cats</h2>
            <div class="feature-grid">
                <div class="feature">
                    <i class="fas fa-heart"></i>
                    <h3>Companionship</h3>
                    <p>Cats provide loving companionship and can help reduce stress and anxiety.</p>
                </div>
                <div class="feature">
                    <i class="fas fa-brain"></i>
                    <h3>Intelligence</h3>
                    <p>Cats are highly intelligent animals with problem-solving skills.</p>
                </div>
                <div class="feature">
                    <i class="fas fa-laugh-beam"></i>
                    <h3>Entertainment</h3>
                    <p>Their playful antics provide endless amusement and joy.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cat-of-the-week">
        <div class="container">
            <h2>Cat of the Week</h2>
            <div class="cat-profile">
                <img src="images/cat-week.jpg" alt="Whiskers the Cat">
                <div class="cat-info">
                    <h3>Whiskers</h3>
                    <p>Meet Whiskers, our cat of the week! This 3-year-old tabby loves cuddles and chasing laser pointers. Whiskers was adopted from a local shelter and has been bringing joy to his family ever since.</p>
                    <p><strong>Favorite Toy:</strong> Feather wand</p>
                    <p><strong>Special Talent:</strong> Opening cabinet doors</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Purrfect Cats. All rights reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-pinterest"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Cats - Purrfect Cats</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1><i class="fas fa-paw"></i> Purrfect Cats</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html" class="active">About</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="about-main">
        <div class="container">
            <h2>About Cats</h2>
            <div class="about-content">
                <img src="images/about-cat.jpg" alt="Cat looking curious">
                <div class="about-text">
                    <h3>The Fascinating World of Felines</h3>
                    <p>Cats (Felis catus) are small carnivorous mammals that have been domesticated for thousands of years. They are one of the most popular pets in the world, valued for their companionship and ability to hunt vermin.</p>
                    <p>Domestic cats are often called 'house cats' when kept as indoor pets. They are highly intelligent animals with excellent night vision and a strong sense of hearing and smell.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cat-facts">
        <div class="container">
            <h2>Fun Cat Facts</h2>
            <div class="facts-grid">
                <div class="fact-card">
                    <i class="fas fa-history"></i>
                    <h3>Ancient Companions</h3>
                    <p>Cats were first domesticated in the Near East around 7500 BC.</p>
                </div>
                <div class="fact-card">
                    <i class="fas fa-bone"></i>
                    <h3>Flexible Bodies</h3>
                    <p>Cats have 230 bones (humans have 206) and lack a collarbone, allowing them to fit through any opening the size of their head.</p>
                </div>
                <div class="fact-card">
                    <i class="fas fa-language"></i>
                    <h3>Communication</h3>
                    <p>Cats can make over 100 different vocal sounds, while dogs can only make about 10.</p>
                </div>
                <div class="fact-card">
                    <i class="fas fa-bed"></i>
                    <h3>Sleepyheads</h3>
                    <p>Cats sleep 12-16 hours a day, spending about 2/3 of their lives asleep.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cat-breeds">
        <div class="container">
            <h2>Popular Cat Breeds</h2>
            <div class="breeds-list">
                <div class="breed">
                    <h3>Persian</h3>
                    <p>Known for their long, luxurious coats and sweet personalities.</p>
                </div>
                <div class="breed">
                    <h3>Siamese</h3>
                    <p>Vocal, intelligent cats with distinctive color points.</p>
                </div>
                <div class="breed">
                    <h3>Maine Coon</h3>
                    <p>One of the largest domestic cat breeds with tufted ears.</p>
                </div>
                <div class="breed">
                    <h3>Bengal</h3>
                    <p>Energetic cats with wild-looking spotted coats.</p>
                </div>
                <div class="breed">
                    <h3>Ragdoll</h3>
                    <p>Large, laid-back cats that go limp when picked up.</p>
                </div>
                <div class="breed">
                    <h3>Sphynx</h3>
                    <p>Hairless cats known for their extroverted behavior.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Purrfect Cats. All rights reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-pinterest"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cat Gallery - Purrfect Cats</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1><i class="fas fa-paw"></i> Purrfect Cats</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="gallery.html" class="active">Gallery</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="gallery-intro">
        <div class="container">
            <h2>Cat Photo Gallery</h2>
            <p>Browse through our collection of beautiful cat photos. Click on any image to enlarge it.</p>
            <div class="filter-options">
                <button class="filter-btn active" data-filter="all">All</button>
                <button class="filter-btn" data-filter="kitten">Kittens</button>
                <button class="filter-btn" data-filter="adult">Adult Cats</button>
                <button class="filter-btn" data-filter="breed">Different Breeds</button>
                <button class="filter-btn" data-filter="funny">Funny Poses</button>
            </div>
        </div>
    </section>

    <section class="photo-gallery">
        <div class="container">
            <div class="gallery-grid">
                <div class="gallery-item" data-category="kitten funny">
                    <img src="images/gallery/kitten1.jpg" alt="Playful kitten">
                    <div class="overlay">
                        <p>Playful kitten</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="adult breed">
                    <img src="images/gallery/siamese.jpg" alt="Siamese cat">
                    <div class="overlay">
                        <p>Beautiful Siamese</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="kitten">
                    <img src="images/gallery/kitten2.jpg" alt="Sleeping kitten">
                    <div class="overlay">
                        <p>Sleeping kitten</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="adult funny">
                    <img src="images/gallery/funny1.jpg" alt="Cat in funny position">
                    <div class="overlay">
                        <p>Yoga master</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="breed">
                    <img src="images/gallery/persian.jpg" alt="Persian cat">
                    <div class="overlay">
                        <p>Fluffy Persian</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="adult">
                    <img src="images/gallery/cat1.jpg" alt="Cat looking at camera">
                    <div class="overlay">
                        <p>Curious gaze</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="breed">
                    <img src="images/gallery/bengal.jpg" alt="Bengal cat">
                    <div class="overlay">
                        <p>Exotic Bengal</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="funny">
                    <img src="images/gallery/funny2.jpg" alt="Cat in box">
                    <div class="overlay">
                        <p>If I fits, I sits</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="lightbox">
        <span class="close-btn">&times;</span>
        <img class="lightbox-content" id="lightbox-img">
        <div class="caption"></div>
        <a class="prev">&#10094;</a>
        <a class="next">&#10095;</a>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2023 Purrfect Cats. All rights reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-pinterest"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Purrfect Cats</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1><i class="fas fa-paw"></i> Purrfect Cats</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                    <li><a href="contact.html" class="active">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="contact-main">
        <div class="container">
            <h2>Contact Us</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get in Touch</h3>
                    <p>Have questions about cats? Want to share your own cat stories or photos? We'd love to hear from you!</p>
                    
                    <div class="info-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <p>123 Cat Street, Meowington, CAT 12345</p>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-phone"></i>
                        <p>(123) 456-7890</p>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-envelope"></i>
                        <p>info@purrfectcats.com</p>
                    </div>
                    
                    <div class="social-contact">
                        <h4>Follow Us</h4>
                        <div class="social-icons">
                            <a href="#"><i class="fab fa-facebook"></i></a>
                            <a href="#"><i class="fab fa-instagram"></i></a>
                            <a href="#"><i class="fab fa-twitter"></i></a>
                            <a href="#"><i class="fab fa-pinterest"></i></a>
                        </div>
                    </div>
                </div>
                
                <div class="contact-form">
                    <h3>Send Us a Message</h3>
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" name="subject" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                    <div id="form-message"></div>
                </div>
            </div>
        </div>
    </section>

    <section class="faq">
        <div class="container">
            <h2>Frequently Asked Questions</h2>
            <div class="faq-item">
                <button class="faq-question">How can I submit my cat's photo to your gallery?</button>
                <div class="faq-answer">
                    <p>You can email us your cat photos at submissions@purrfectcats.com. Please include your cat's name and a brief description. We feature new photos every week!</p>
                </div>
            </div>
            <div class="faq-item">
                <button class="faq-question">Do you have information about adopting cats?</button>
                <div class="faq-answer">
                    <p>Yes! We partner with local shelters and can provide information about adoption procedures, what to expect, and how to prepare your home for a new feline friend.</p>
                </div>
            </div>
            <div class="faq-item">
                <button class="faq-question">Can you help with cat behavior issues?</button>
                <div class="faq-answer">
                    <p>While we're not behaviorists, we can share general advice and resources. For serious issues, we recommend consulting with a veterinarian or certified cat behaviorist.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Purrfect Cats. All rights reserved.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-pinterest"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
