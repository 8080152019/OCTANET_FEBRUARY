<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="shop.css">
    <title>The Little Bookshop</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#aboutus">About Us</a></li>
                <li><a href="shop.html">Shop</a></li>
                <li><a href="cart.html">Cart</a></li>
                <li><a href="account.html">My Account</a></li>
                <li><a href="reviews.html">Book Reviews</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div>
        <h1>Welcome to The Little Bookshop!</h1>
        <img src="c:\Users\icon\Downloads\shop.jpeg" alt="Bookstore"> 
        <p>The Little Bookshop believes in the power of books, and the ability they have to transport you to places that seem impossible to reach.</p>
        <p>Although we have store outlets located in different suburbs of the country, we pay special attention to our online community that does not have access to these spaces.</p>
        <p>Take your time and scour our shelves, you'll be sure to find something that is to your liking.</p>
        <p>We are deeply interested in the welfare of our customers, and their literary tastes, which is why we stock up books of all genres and authors at affordable prices for you!</p>

        <div class="container">
            <h2>Feedback Form</h2>
            <form action="submit.php" method="POST">
                <label for="fname">First Name</label>
                <input type="text" id="fname" name="firstname" placeholder="First Name" required>

                <label for="lname">Last Name</label>
                <input type="text" id="lname" name="lastname" placeholder="Last Name" required>

                <label for="country">Country</label>
                <select id="country" name="country" required>
                    <option value="india">India</option>
                    <option value="america">America</option>
                    <option value="england">England</option>
                </select>

                <label for="subject">Say Something</label>
                <textarea id="subject" name="subject" placeholder="Say something" style="height:200px" required></textarea>

                <input type="submit" value="Submit">
            </form>
        </div>
    </div>
    <footer>
        <!-- Footer content goes here -->
    </footer>
</body>
</html>
