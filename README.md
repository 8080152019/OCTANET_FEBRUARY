# OCTANET_FEBRUARY
<!DOCTYPE html>
<html>
    <head>
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <link rel="stylesheet" href="shop.css">
            <title>The Little Bookshop</title>
        </head>
        <body>
            <div class="nav">
                <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about us">About Us</a></li>
                <li><a href="shop">Shop</a></li>
                <li><a href="cart">Cart</a></li>
                <li><a href="my account">My Account</a></li>
                <li><a href="book reviews">Book Reviews</a></li>
                <li><a href="contact us">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h1>Welcome to The Little Bookshop!</h1>
                <img src="c:\Users\icon\Downloads\shop.jpeg" alt="Bookstore"> 
                <h2>
                    <p>The Little Bookshop believes in the power of books, and the ability they have to transport 
                        you to places that seem impossible to reach.
                        <br><br>
                        Although we have store outlets located in
                         different surbubs of the country, we pay special attention to our online community that do 
                         not have access to these spaces. 
                         <br><br>
                         Take your time and scour our shelves, you'll be sure 
                         to find something that is to your liking. 
                         <br><br>
                         We are deeply interested in the welfare of our 
                         customers, and their literary tastes, which is why we stock up books of all genres and
                          authors at affordable prices for you!
                    </p>

                          <br><br> 
                          <div class="container">
                          <h3>Feedback Form</h3>

                            <form action>

                              <label for="fname">First Name</label>
                              <input type="text" id="fname" name="firstname" placeholder="First Name">

                              <label for="lname">Last Name</label>
                              <input type="text" id="lname" name="lastname" placeholder="Last Name">

                              <label for="country">Country</label>
                              <select id="country" name="country">
                                <option value="india">India</option>
                                <option value="america">America</option>
                                <option value="england">England</option>
                              </select>

                              <label for="subject">Say Something</label>
                              <textarea id="subject" name="subject" placeholder="say something" style="height:200px"></textarea>

                              <input type="submit" value="Submit">

                            </form>
                          </div>
                </h2>
            </div>
        </body>
        </html>
    </head>
</html>
h1, h3 {
    font-family:'Times New Roman';
    font-size: 72px;
    font-weight: bolder;
    text-align: center;
    color: darkred;
}
h2 {
    text-align: center;
    font-size: medium;
    font-weight: 100;
    font-size: 20px;
}

p {
    text-align: left;
    font-family: Helvetica;

}

img{
    width:1250px; height:450px; object-fit:cover;
}
ul {
    list-style-type:none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}
li {display: inline;
    float: right;

}
a {display: block;
    padding: 8px;
    color: white;
    font-family: Helvetica;
    text-align: center;
    text-decoration: none;
}
/* Style inputs with type="text", select elements and textareas */
input[type=text], select, textarea {
    width: 100%; /* Full width */
    padding: 12px; /* Some padding */ 
    border: 1px solid #ccc; /* Black border */
    border-bottom: solid black 2px;
    border-radius: 4px; /* Rounded borders */
    box-sizing: border-box; /* Make sure that padding and width stays in place */
    margin-top: 6px; /* Add a top margin */
    margin-bottom: 16px; /* Bottom margin */
    resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
  }

  /* Style the submit button with a specific background color etc */
  input[type=submit] {
    background-color: #04AA6D;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }

  /* When moving the mouse over the submit button, add a black color */
  input[type=submit]:hover {
    background-color: #010e01;
  }

  /* Add a background color and some padding around the form */
  .container {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
  }
  
