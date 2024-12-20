# Ex.07 Restaurant Website
## Date:18:12:2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Akshaya Luxury Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="ak.jpg" alt="Akshaya Restaurant Banner" class="banner-image">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="reservation.html">Reservation</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="about-us">
            <h1>Welcome to Akshaya Luxury Western Restaurant</h1>
            <p>Located in the heart of the city, Akshaya is a premium luxury restaurant offering an exquisite dining experience. Since its establishment in 2000, Akshaya has been serving a delightful range of Western cuisine in a modern, luxurious setting. Our focus is on providing high-quality, hygienic, and freshly prepared food with both vegetarian and non-vegetarian options, all available for an affordable price of ₹999 for an unlimited buffet.</p>

            <h2>Our Story</h2>
            <p>Akshaya was founded by Kishore, who had a vision of creating a place where food lovers could enjoy a premium dining experience without compromising on affordability. The restaurant's name, "Akshaya," means "eternal" or "imperishable," which symbolizes our commitment to offering top-quality food and exceptional service that remains unmatched. Since 2000, we've grown into one of the most trusted luxury dining destinations in the city.</p>

            <h2>What Sets Us Apart</h2>
            <ul>
                <li><strong>Unlimited Buffet</strong>: Enjoy a vast selection of vegetarian and non-vegetarian dishes, all you can eat for just ₹999.</li>
                <li><strong>Quality & Hygiene</strong>: Our kitchen maintains the highest standards of cleanliness and food safety, ensuring your dining experience is both delicious and safe.</li>
                <li><strong>Innovative Dishes</strong>: We blend traditional flavors with modern culinary techniques to create unique dishes that will tantalize your taste buds.</li>
                <li><strong>Exclusive Ambience</strong>: Akshaya offers a sophisticated and comfortable atmosphere perfect for any occasion, whether it's a casual meal with friends or a special celebration.</li>
            </ul>

            <h2>Why Choose Akshaya?</h2>
            <p>At Akshaya, we believe that dining is an experience, not just a meal. From the moment you step inside, you’ll be welcomed into a space that exudes elegance and comfort. Our attentive staff is always ready to ensure you have a memorable experience, whether you're here for a business lunch, family gathering, or romantic dinner.</p>

            <h2>Our Commitment</h2>
            <p>We are dedicated to providing our customers with the best possible service and the highest quality food. Our kitchen team works tirelessly to ensure every dish is prepared with care and passion. Whether you're here for our signature dishes or trying something new, we guarantee you’ll leave satisfied and eager to return.</p>
        </section>

        <section class="special-offers">
            <h2>Exclusive Offer</h2>
            <p>For a limited time, enjoy an all-you-can-eat buffet with a selection of our finest dishes for just ₹999! Don’t miss out on this incredible deal at Akshaya, where we serve both vegetarian and non-vegetarian options with unlimited servings.</p>
            <p><strong>Book your table today and experience luxury dining like never before!</strong></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Kishore, Akshaya Luxury Western Restaurant. All rights reserved.</p>
    </footer>
</body>
</html> 
```

menu.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Akshaya Luxury Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="ak.jpg" alt="Akshaya Restaurant Banner" class="banner-image">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="reservation.html">Reservation</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Our Menu</h1>
        <p>At Akshaya, we offer a wide variety of dishes to choose from. All our meals are unlimited for just ₹999, and we serve both vegetarian and non-vegetarian options.</p>
        <div class="menu-items">
            <div class="menu-item">
                <img src="Vegetarian Thali.jpg" alt="Vegetarian Thali" class="menu-image">
                <h2>Vegetarian Thali</h2>
                <p>Unlimited servings of traditional vegetarian dishes. Fresh, flavorful, and healthy!</p>
                <p><strong>₹999</strong></p>
            </div>
            <div class="menu-item">
                <img src="Non-Vegetarian Thali.jpg" alt="Non-Vegetarian Thali" class="menu-image">
                <h2>Non-Vegetarian Thali</h2>
                <p>Delicious, unlimited servings of non-vegetarian dishes prepared with care.</p>
                <p><strong>₹999</strong></p>
            </div>
            <div class="menu-item">
                <img src="Paneer Tikka.jpg" alt="Paneer Tikka" class="menu-image">
                <h2>Paneer Tikka</h2>
                <p>Marinated paneer cooked to perfection, served with a side of chutney.</p>
                <p><strong>₹250</strong></p>
            </div>
            <div class="menu-item">
                <img src="Butter Chicken.jpeg" alt="Butter Chicken" class="menu-image">
                <h2>Butter Chicken</h2>
                <p>Classic creamy butter chicken served with naan or rice.</p>
                <p><strong>₹350</strong></p>
            </div>
            <div class="menu-item">
                <img src="Grilled Salmon.jpg" alt="Grilled Salmon" class="menu-image">
                <h2>Grilled Salmon</h2>
                <p>Fresh salmon grilled to perfection with a blend of spices.</p>
                <p><strong>₹450</strong></p>
            </div>
            <div class="menu-item">
                <img src="Veg Biryani.jpeg" alt="Veg Biryani" class="menu-image">
                <h2>Veg Biryani</h2>
                <p>Fragrant basmati rice with mixed vegetables and spices.</p>
                <p><strong>₹299</strong></p>
            </div>
            <div class="menu-item">
                <img src="Chicken Biryani.jpg" alt="Chicken Biryani" class="menu-image">
                <h2>Chicken Biryani</h2>
                <p>Flavorful chicken biryani made with premium basmati rice.</p>
                <p><strong>₹399</strong></p>
            </div>
            <div class="menu-item">
                <img src="French Fries.jpg" alt="French Fries" class="menu-image">
                <h2>French Fries</h2>
                <p>Golden and crispy French fries served with a dipping sauce.</p>
                <p><strong>₹150</strong></p>
            </div>
            <div class="menu-item">
                <img src="Caesar Salad.jpeg" alt="Caesar Salad" class="menu-image">
                <h2>Caesar Salad</h2>
                <p>Fresh greens with Caesar dressing and crunchy croutons.</p>
                <p><strong>₹180</strong></p>
            </div>
            <div class="menu-item">
                <img src="Chocolate Lava Cake.jpeg" alt="Chocolate Lava Cake" class="menu-image">
                <h2>Chocolate Lava Cake</h2>
                <p>Decadent molten chocolate cake served with vanilla ice cream.</p>
                <p><strong>₹200</strong></p>
            </div>
            <div class="menu-item">
                <img src="Ice Cream.jpeg" alt="Ice Cream Sundae" class="menu-image">
                <h2>Ice Cream Sundae</h2>
                <p>Delicious ice cream topped with chocolate sauce and nuts.</p>
                <p><strong>₹150</strong></p>
            </div>
            <div class="menu-item">
                <img src="Masala Dosa.jpg" alt="Masala Dosa" class="menu-image">
                <h2>Masala Dosa</h2>
                <p>Crispy dosa stuffed with spiced potatoes, served with chutneys.</p>
                <p><strong>₹120</strong></p>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Kishore, Akshaya Luxury Western Restaurant</p>
    </footer>
</body>
</html>
```
administration.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Akshaya Luxury Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="ak.jpg" alt="Akshaya Restaurant Banner" class="banner-image">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="reservation.html">Reservation</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Meet Our Team</h1>
        <p>At Akshaya, we pride ourselves on having an exceptional team that ensures the best dining experience for our guests.</p>
        <div class="team">
            <div class="team-member">
                <img src="kis.jpg" alt="Chef" class="team-photo">
                <h3>Kishore (Owner)</h3>
                <p>Owner of Akshaya, responsible for overseeing the overall operations and quality.</p>
            </div>
            <div class="team-member">
                <img src="head cheif.jpeg" alt="Head Chef" class="team-photo">
                <h3>Ravi Kumar (Head Chef)</h3>
                <p>Leads the kitchen and ensures all dishes are prepared to perfection.</p>
            </div>
            <div class="team-member">
                <img src="Sous Chef.avif" alt="Sous Chef" class="team-photo">
                <h3>Simran Kaur (Sous Chef)</h3>
                <p>Assists in kitchen operations and helps with the preparation of delicacies.</p>
            </div>
            <div class="team-member">
                <img src="Restaurant Manager.jpg" alt="Manager" class="team-photo">
                <h3>Arjun Patel (Restaurant Manager)</h3>
                <p>Handles day-to-day operations and ensures a smooth dining experience for customers.</p>
            </div>
            <div class="team-member">
                <img src="Senior Waiter.jpeg" alt="Waitstaff" class="team-photo">
                <h3>Priya Singh (Senior Waiter)</h3>
                <p>Provides excellent customer service, ensuring guests are satisfied and well attended to.</p>
            </div>
            <div class="team-member">
                <img src="Cleaner.jpg" alt="Cleaner" class="team-photo">
                <h3>Kiran (Cleaner)</h3>
                <p>Maintains the cleanliness and hygiene of the restaurant at all times.</p>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Kishore, Akshaya Luxury Western Restaurant</p>
    </footer>
</body>
</html>
```

contact.html:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Akshaya Luxury Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="ak.jpg" alt="Akshaya Restaurant Banner" class="banner-image">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="reservation.html">Reservation</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Contact Us</h1>
        <p>If you have any questions or would like to make a reservation, feel free to contact us!</p>
        <address>
            <p><strong>Phone:</strong> +91 123 456 7890</p>
            <p><strong>Email:</strong> info@akshaya.com</p>
            <p><strong>Address:</strong> Akshaya Luxury Restaurant, 123 Elite Street, New Delhi, India</p>
        </address>
    </main>
    <footer>
        <p>&copy; 2024 Kishore, Akshaya Luxury Western Restaurant</p>
    </footer>
</body>
</html>

```
reservation.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reservation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="ak.jpg" alt="Banner" class="banner-image">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="reservation.html">Reservation</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Make a Reservation</h1>
        <form action="#" method="POST" class="reservation-form">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="date">Reservation Date</label>
            <input type="date" id="date" name="date" required>

            <label for="time">Reservation Time</label>
            <input type="time" id="time" name="time" required>

            <label for="guests">Number of Guests</label>
            <input type="number" id="guests" name="guests" required>

            <button type="submit">Reserve Now</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2024 Kishore, Luxury Restaurant</p>
    </footer>
</body>
</html>

```
style.css

```
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  line-height: 1.6;
}

header {
  background: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.banner-image {
  width: 100%;
  max-height: 250px;
  object-fit: cover;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
  background: #444;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  padding: 10px;
}

nav ul li a:hover {
  background: #555;
  border-radius: 5px;
}

main {
  padding: 20px;
  max-width: 1200px;
  margin: auto;
}

h1, h2, h3 {
  color: #333;
  text-align: center;
}

p {
  margin: 10px 0;
  color: #555;
  text-align: justify;
}

.menu-items {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.menu-item {
  border: 1px solid #ddd;
  border-radius: 10px;
  overflow: hidden;
  width: calc(33.333% - 20px);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  background: #fff;
}

.menu-image {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.menu-item h2 {
  font-size: 1.5em;
  margin: 10px 0;
}

.menu-item p {
  padding: 0 10px;
  margin: 0 0 10px;
}

.menu-item strong {
  display: block;
  text-align: center;
  color: #333;
  margin-bottom: 10px;
}

.reservation-form {
  max-width: 600px;
  margin: auto;
  background: #f9f9f9;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.reservation-form label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

.reservation-form input, .reservation-form button {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-size: 1em;
}

.reservation-form button {
  background: #333;
  color: #fff;
  border: none;
  cursor: pointer;
  font-weight: bold;
}

.reservation-form button:hover {
  background: #555;
}

.team {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.team-member {
  text-align: center;
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 10px;
  width: calc(33.333% - 20px);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  background: #fff;
}

.team-photo {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 10px;
}

.team-member h3 {
  margin: 10px 0;
  font-size: 1.2em;
  color: #333;
}

.team-member p {
  color: #555;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
  margin-top: 20px;
}

footer p {
  margin: 0;
  font-size: 0.9em;
}

```

## OUTPUT:

![alt text](<Screenshot 2024-12-20 115350.png>)

![alt text](image.png)

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

![alt text](image-6.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
