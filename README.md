<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nanny On-Demand</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; text-align: center; background: #f8f8f8; }
        header { background: #ff6f61; color: white; padding: 20px; font-size: 24px; }
        .container { padding: 20px; background: white; margin: 20px auto; width: 80%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .btn { background: #ff6f61; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; border: none; cursor: pointer; }
        .btn:hover { background: #ff3b2f; }
        .dashboard, .login-form { margin-top: 20px; padding: 20px; border: 1px solid #ccc; display: inline-block; background: #fff; }
    </style>
</head>
<body>
    <header>Nanny On-Demand</header><div class="container">
    <h2>Find Trusted Nannies Anytime, Anywhere</h2>
    <p>Book professional nannies with ease.</p>
    <a href="#book" class="btn">Book a Nanny</a>
    <a href="#login" class="btn">Login</a>
</div>

<!-- Booking Section -->
<div id="book" class="container">
    <h3>Book a Nanny</h3>
    <form>
        <input type="text" placeholder="Your Name" required><br><br>
        <input type="email" placeholder="Your Email" required><br><br>
        <input type="datetime-local" required><br><br>
        <button type="submit" class="btn">Pay & Book</button>
    </form>
</div>

<!-- Payment Integration -->
<div id="payment" class="container">
    <h3>Secure Payments</h3>
    <p>We accept payments via Credit/Debit Cards, PayPal, and UPI.</p>
    <button class="btn">Proceed to Payment</button>
</div>

<!-- Nanny Registration -->
<div id="nanny-register" class="container">
    <h3>Nanny Registration</h3>
    <form>
        <input type="text" placeholder="Full Name" required><br><br>
        <input type="email" placeholder="Email" required><br><br>
        <input type="text" placeholder="Experience (Years)" required><br><br>
        <button type="submit" class="btn">Register</button>
    </form>
</div>

<!-- Login Section -->
<div id="login" class="container">
    <h3>Login</h3>
    <form class="login-form">
        <input type="email" placeholder="Email" required><br><br>
        <input type="password" placeholder="Password" required><br><br>
        <button type="submit" class="btn">Login</button>
    </form>
</div>

<!-- Admin Panel -->
<div id="admin" class="container">
    <h3>Admin Panel</h3>
    <div class="dashboard">
        <p>Manage Nannies and Customers</p>
        <button class="btn">View Bookings</button>
        <button class="btn">View Nannies</button>
        <button class="btn">View Customers</button>
        <button class="btn">View Payments</button>
        <button class="btn">View Analytics</button>
    </div>
</div>

<!-- Analytics Dashboard -->
<div id="analytics" class="container">
    <h3>Business Analytics</h3>
    <p>Track nanny bookings, payments, and revenue in real-time.</p>
    <button class="btn">View Reports</button>
</div>

<!-- Ad Sales Section -->
<div class="ads-section container">
    <h3>Advertise Here</h3>
    <p>Promote your business on our platform. Choose from banner ads, featured listings, and sponsored content.</p>
    <button class="btn">Contact Us for Ads</button>
</div>

</body>
</html>
