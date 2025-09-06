<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ConnectKenya - Affordable WiFi Access</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #4a8c5f;
            --secondary: #e3b448;
            --accent: #3d6cb9;
            --light: #f9f7f2;
            --dark: #2c3e50;
            --success: #27ae60;
            --warning: #e67e22;
            --error: #e74c3c;
            --radius: 12px;
            --shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    
    body {
        background-color: var(--light);
        color: #333;
        line-height: 1.6;
    }
    
    .container {
        width: 90%;
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    
    header {
        background: linear-gradient(135deg, var(--primary) 0%, #2c6b48 100%);
        color: white;
        padding: 20px 0;
        box-shadow: var(--shadow);
        border-bottom: 4px solid var(--secondary);
    }
    
    .logo-container {
        display: flex;
        align-items: center;
        gap: 15px;
    }
    
    .logo {
        font-size: 2.5rem;
        color: var(--secondary);
    }
    
    .logo-text {
        font-size: 1.8rem;
        font-weight: 700;
    }
    
    .nav-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    nav ul {
        display: flex;
        list-style: none;
        gap: 30px;
    }
    
    nav a {
        color: white;
        text-decoration: none;
        font-weight: 500;
        transition: all 0.3s ease;
        padding: 5px 10px;
        border-radius: 4px;
    }
    
    nav a:hover {
        background-color: rgba(255, 255, 255, 0.2);
    }
    
    .hero {
        padding: 60px 0;
        text-align: center;
        background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%" viewBox="0 0 800 400"><rect fill="%234a8c5f" width="800" height="400"/><path fill="%23357a4d" fill-opacity="0.4" d="M0 192L26.7 202.7C53.3 213 107 235 160 234.7C213.3 235 267 213 320 197.3C373.3 181 427 171 480 186.7C533.3 203 587 245 640 250.7C693.3 256 747 224 773.3 208L800 192L800 401L773.3 401C746.7 401 693 401 640 401C586.7 401 533 401 480 401C426.7 401 373 401 320 401C266.7 401 213 401 160 401C106.7 401 53 401 27 401L0 401Z"></path></svg>') center bottom no-repeat;
        background-size: cover;
        color: white;
        border-radius: 0 0 var(--radius) var(--radius);
        margin-bottom: 40px;
    }
    
    .hero h1 {
        font-size: 2.8rem;
        margin-bottom: 20px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }
    
    .hero p {
        font-size: 1.2rem;
        max-width: 700px;
        margin: 0 auto 30px;
    }
    
    .pricing-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 25px;
        margin-bottom: 40px;
    }
    
    .pricing-card {
        background: white;
        border-radius: var(--radius);
        padding: 25px;
        width: 100%;
        max-width: 300px;
        box-shadow: var(--shadow);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        text-align: center;
        border: 2px solid transparent;
        position: relative;
        overflow: hidden;
    }
    
    .pricing-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
        border-color: var(--secondary);
    }
    
    .pricing-card.popular {
        border-color: var(--secondary);
        transform: scale(1.05);
    }
    
    .pricing-card.popular::before {
        content: 'MOST POPULAR';
        position: absolute;
        top: 15px;
        right: -30px;
        background: var(--secondary);
        color: var(--dark);
        padding: 5px 30px;
        font-size: 0.8rem;
        font-weight: 700;
        transform: rotate(45deg);
    }
    
    .price-icon {
        font-size: 2.5rem;
        color: var(--primary);
        margin-bottom: 15px;
    }
    
    .price-amount {
        font-size: 2.2rem;
        font-weight: 700;
        color: var(--dark);
        margin-bottom: 10px;
    }
    
    .price-duration {
        color: var(--accent);
        font-weight: 600;
        margin-bottom: 20px;
    }
    
    .price-features {
        list-style: none;
        margin-bottom: 25px;
        text-align: left;
    }
    
    .price-features li {
        padding: 8px 0;
        border-bottom: 1px solid #eee;
    }
    
    .price-features li:last-child {
        border-bottom: none;
    }
    
    .price-features i {
        color: var(--success);
        margin-right: 10px;
    }
    
    .btn {
        display: inline-block;
        background: var(--primary);
        color: white;
        padding: 12px 25px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 600;
        border: none;
        cursor: pointer;
        transition: all 0.3s ease;
    }
    
    .btn:hover {
        background: #3a7050;
        transform: translateY(-2px);
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    }
    
    .btn-secondary {
        background: var(--secondary);
        color: var(--dark);
    }
    
    .btn-secondary:hover {
        background: #d09f3a;
    }
    
    .payment-section {
        background: white;
        border-radius: var(--radius);
        padding: 40px;
        box-shadow: var(--shadow);
        margin-bottom: 40px;
    }
    
    .section-title {
        text-align: center;
        margin-bottom: 40px;
        color: var(--dark);
        position: relative;
        padding-bottom: 15px;
    }
    
    .section-title::after {
        content: '';
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        width: 80px;
        height: 4px;
        background: var(--secondary);
        border-radius: 2px;
    }
    
    .payment-form {
        max-width: 600px;
        margin: 0 auto;
    }
    
    .form-group {
        margin-bottom: 25px;
    }
    
    .form-group label {
        display: block;
        margin-bottom: 8px;
        font-weight: 600;
        color: var(--dark);
    }
    
    .form-control {
        width: 100%;
        padding: 15px;
        border: 2px solid #ddd;
        border-radius: var(--radius);
        font-size: 1rem;
        transition: border-color 0.3s ease;
    }
    
    .form-control:focus {
        border-color: var(--primary);
        outline: none;
    }
    
    .payment-methods {
        display: flex;
        justify-content: center;
        gap: 20px;
        margin: 30px 0;
    }
    
    .payment-method {
        border: 2px solid #eee;
        border-radius: var(--radius);
        padding: 20px;
        text-align: center;
        width: 150px;
        transition: all 0.3s ease;
    }
    
    .payment-method:hover {
        border-color: var(--primary);
        transform: translateY(-5px);
    }
    
    .payment-icon {
        font-size: 2.5rem;
        margin-bottom: 15px;
    }
    
    .mpesa { color: #00A650; }
    .paypal { color: #003087; }
    .venmo { color: #3D95CE; }
    
    .how-it-works {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
        margin-bottom: 40px;
    }
    
    .step-card {
        background: white;
        border-radius: var(--radius);
        padding: 30px;
        box-shadow: var(--shadow);
        text-align: center;
        transition: transform 0.3s ease;
    }
    
    .step-card:hover {
        transform: translateY(-5px);
    }
    
    .step-number {
        display: inline-block;
        width: 50px;
        height: 50px;
        line-height: 50px;
        background: var(--primary);
        color: white;
        border-radius: 50%;
        font-weight: 700;
        font-size: 1.5rem;
        margin-bottom: 20px;
    }
    
    .about-section {
        background: linear-gradient(to right, #f9f7f2, #e3dfd2);
        padding: 60px 0;
        border-radius: var(--radius);
        margin-bottom: 40px;
    }
    
    .about-content {
        display: flex;
        align-items: center;
        gap: 40px;
    }
    
    .about-text {
        flex: 1;
    }
    
    .about-image {
        flex: 1;
        text-align: center;
    }
    
    .kenya-flag {
        font-size: 8rem;
        border-radius: 50%;
        box-shadow: var(--shadow);
    }
    
    .faq-container {
        margin-bottom: 40px;
    }
    
    .faq-item {
        background: white;
        border-radius: var(--radius);
        margin-bottom: 15px;
        overflow: hidden;
        box-shadow: var(--shadow);
    }
    
    .faq-question {
        padding: 20px;
        cursor: pointer;
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-weight: 600;
        background: var(--primary);
        color: white;
    }
    
    .faq-answer {
        padding: 0 20px;
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease, padding 0.3s ease;
    }
    
    .faq-item.active .faq-answer {
        max-height: 200px;
        padding: 20px;
    }
    
    footer {
        background: var(--dark);
        color: white;
        padding: 40px 0;
        text-align: center;
    }
    
    .footer-content {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 30px;
        text-align: left;
        margin-bottom: 30px;
    }
    
    .footer-column h3 {
        color: var(--secondary);
        margin-bottom: 20px;
        font-size: 1.2rem;
    }
    
    .footer-column ul {
        list-style: none;
    }
    
    .footer-column ul li {
        margin-bottom: 10px;
    }
    
    .footer-column a {
        color: #ddd;
        text-decoration: none;
        transition: color 0.3s ease;
    }
    
    .footer-column a:hover {
        color: var(--secondary);
    }
    
    .social-icons {
        display: flex;
        gap: 15px;
        margin-top: 15px;
    }
    
    .social-icons a {
        display: inline-block;
        width: 40px;
        height: 40px;
        line-height: 40px;
        text-align: center;
        background: rgba(255, 255, 255, 0.1);
        border-radius: 50%;
        color: white;
        transition: all 0.3s ease;
    }
    
    .social-icons a:hover {
        background: var(--secondary);
        color: var(--dark);
        transform: translateY(-3px);
    }
    
    .copyright {
        padding-top: 20px;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    @media (max-width: 768px) {
        .nav-container {
            flex-direction: column;
            gap: 20px;
        }
        
        nav ul {
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        
        .about-content {
            flex-direction: column;
        }
        
        .pricing-container {
            flex-direction: column;
            align-items: center;
        }
        
        .pricing-card.popular {
            transform: scale(1);
        }
    }
</style></head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container nav-container">
            <div class="logo-container">
                <i class="fas fa-wifi logo"></i>
                <div class="logo-text">ConnectKenya</div>
            </div>
            <nav>
                <ul>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#payment">Payment</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#faq">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

<!-- Hero Section -->
<section class="hero">
    <div class="container">
        <h1>Affordable, High-Speed WiFi Access in Kenya</h1>
        <p>Choose from our flexible pricing options to stay connected wherever you are. Fast, reliable internet access tailored for Kenyans.</p>
        
        <div class="pricing-container" id="pricing">
            <div class="pricing-card">
                <i class="fas fa-clock price-icon"></i>
                <div class="price-amount">KSH 10</div>
                <div class="price-duration">1 Hr 30 Min Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 1 Hr 30 Min</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">1 Device Connection</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-hourglass-half price-icon"></i>
                <div class="price-amount">KSH 20</div>
                <div class="price-duration">3 Hr 30 Min Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 3 Hr 30 Min</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">1 Device Connection</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card popular">
                <i class="fas fa-fire price-icon"></i>
                <div class="price-amount">KSH 30</div>
                <div class="price-duration">6 Hr 30 Min Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 6 Hr 30 Min</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">1 Device Connection</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn btn-secondary">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-calendar-day price-icon"></i>
                <div class="price-amount">KSH 50</div>
                <div class="price-duration">8 Hr 30 Min Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 8 Hr 30 Min</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">2 Device Connections</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-calendar-alt price-icon"></i>
                <div class="price-amount">KSH 100</div>
                <div class="price-duration">12 Hr 30 Min Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 12 Hr 30 Min</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">3 Device Connections</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-infinity price-icon"></i>
                <div class="price-amount">KSH 300</div>
                <div class="price-duration">1 WEEK Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 1 WEEK </font></li>
                    <li><i class="fas fa-check"></i><font color=" black">5 Device Connections</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-calendar-week price-icon"></i>
                <div class="price-amount">KSH 600</div>
                <div class="price-duration">2 WEEKS Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 2 WEEKS </font></li>
                    <li><i class="fas fa-check"></i><font color=" black">5 Device Connections</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
            
            <div class="pricing-card">
                <i class="fas fa-calendar price-icon"></i>
                <div class="price-amount">KSH 1500</div>
                <div class="price-duration">4 WEEKS Access</div>
                <ul class="price-features">
                    <li><i class="fas fa-check"></i><font color=" black">Access for 4 WEEKS </font></li>
                    <li><i class="fas fa-check"></i><font color=" black">10 Device Connections</font></li>
                    <li><i class="fas fa-check"></i><font color=" black">unlimited usage</font></li>
                </ul>
                <button class="btn">Select Plan</button>
            </div>
        </div>
    </div>
</section>

<!-- Payment Section -->
<section class="container payment-section" id="payment">
    <h2 class="section-title">Secure Payment</h2>
    
    <div class="payment-methods">
        <div class="payment-method">
            <i class="fab fa-mpesa payment-icon mpesa"></i>
            <h3>M-Pesa</h3>
        </div>
        
        <div class="payment-method">
            <i class="fab fa-paypal payment-icon paypal"></i>
            <h3>PayPal</h3>
        </div>
        
        <div class="payment-method">
            <i class="fab fa-vimeo payment-icon venmo"></i>
            <h3>Venmo</h3>
        </div>
    </div>
    
    <div class="payment-form">
        <div class="form-group">
            <label for="phone">Enter your M-Pesa Phone Number</label>
            <input type="tel" id="phone" class="form-control" placeholder="e.g., 07XX XXX XXX">
        </div>
        
        <div class="form-group">
            <label for="plan">Select Your WiFi Plan</label>
            <select id="plan" class="form-control">
                <option value="">-- Select a plan --</option>
                <option value="10">KSH 10 - 1 Hr 30 Min Access</option>
                <option value="20">KSH 20 - 3 Hr 30 Min Access</option>
                <option value="30">KSH 30 - 6 Hr 30 Min Access</option>
                <option value="50">KSH 50 - 8 Hr 30 Min Access</option>
                <option value="100">KSH 100 - 12 Hr 30 Min Access</option>
                <option value="300">KSH 300 - 1 WEEK Access</option>
                <option value="600">KSH 600 - 2 WEEKS Access</option>
                <option value="1500">KSH 1500 - 4 WEEKS Access</option>
            </select>
        </div>
        
        <button class="btn" style="width: 100%;">Pay Now</button>
    </div>
</section>

<!-- How It Works Section -->
<section class="container" id="how-it-works">
    <h2 class="section-title">How To Use ConnectKenya WiFi</h2>
    
    <div class="how-it-works">
        <div class="step-card">
            <div class="step-number">1</div>
            <h3>Connect to WiFi</h3>
            <p>Select "ConnectKenya" from available WiFi networks on your device.</p>
        </div>
        
        <div class="step-card">
            <div class="step-number">2</div>
            <h3>Login Page</h3>
            <p>Our portal will automatically open. If it doesn't, open your browser and go to any website.</p>
        </div>
        
        <div class="step-card">
            <div class="step-number">3</div>
            <h3>Select Plan</h3>
            <p>Choose the WiFi plan that best fits your needs and budget.</p>
        </div>
        
        <div class="step-card">
            <div class="step-number">4</div>
            <h3>Make Payment</h3>
            <p>Pay securely via M-Pesa, PayPal, or Venmo using your preferred method.</p>
        </div>
        
        <div class="step-card">
            <div class="step-number">5</div>
            <h3>Get Connected</h3>
            <p>Once payment is confirmed, you'll be automatically connected to high-speed internet.</p>
        </div>
        
        <div class="step-card">
            <div class="step-number">6</div>
            <h3>Enjoy Browsing</h3>
            <p>Stream, browse, and work with our reliable internet connection.</p>
        </div>
    </div>
</section>

<!-- About Section -->
<section class="about-section" id="about">
    <div class="container about-content">
        <div class="about-text">
            <h2 class="section-title">Proudly Kenyan</h2>
            <p>ConnectKenya was developed and launched in Nairobi, Kenya, with a mission to provide affordable and reliable internet access to all Kenyans. Our team of local engineers designed the platform specifically for the Kenyan market, understanding the unique needs and challenges of internet connectivity in our country.</p>
            <p>We're committed to digital inclusion and supporting Kenya's vision of becoming a technology hub in Africa. By using locally developed solutions and integrating with popular payment methods like M-Pesa, we're making internet access more accessible to everyone.</p>
            <p>Our infrastructure is built on reliable MikroTik systems, ensuring 99% uptime and consistent performance for all our users. We're continuously improving our services based on feedback from our Kenyan customers.</p>
            <button class="btn">Learn More About Us</button>
        </div>
        
        <div class="about-image">
            <i class="fas fa-flag kenya-flag" style="color: #000000; background: linear-gradient(135deg, #000000 0%, #000000 33%, #DE2910 33%, #DE2910 66%, #FFFFFF 66%, #FFFFFF 100%); border-radius: 50%; padding: 20px;"></i>
        </div>
    </div>
</section>

<!-- FAQ Section -->
<section class="container faq-container" id="faq">
    <h2 class="section-title">Frequently Asked Questions</h2>
    
    <div class="faq-item active">
        <div class="faq-question">
            How do I pay with M-Pesa? <i class="fas fa-chevron-down"></i>
        </div>
        <div class="faq-answer">
            <p>To pay with M-Pesa, select your preferred WiFi plan and enter your M-Pesa phone number when prompted. You will receive a payment request on your phone. Enter your M-Pesa PIN to confirm the payment, and your internet access will be activated immediately upon successful payment.</p>
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">
            Can I use multiple devices? <i class="fas fa-chevron-down"></i>
        </div>
        <div class="faq-answer">
            <p>The KSH 10, KSH 20, and KSH 30 plans allow 1 device, the KSH 50 plan allows 2 devices, the KSH 100 plan allows 3 devices, the KSH 300 and KSH 600 plans allow up to 5 devices, and the KSH 1500 plan allows up to 10 devices simultaneously.</p>
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">
            What if I have connection problems? <i class="fas fa-chevron-down"></i>
        </div>
        <div class="faq-answer">
            <p>If you experience any connection issues, try disconnecting and reconnecting to the WiFi network. If problems persist, please contact our support team via the help desk on our portal, and we'll assist you promptly.</p>
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">
            How do I use PayPal or Venmo? <i class="fas fa-chevron-down"></i>
        </div>
        <div class="faq-answer">
            <p>For international users or those with PayPal/Venmo accounts, simply select your preferred payment method at checkout. You'll be redirected to a secure payment page to complete your transaction. Note that PayPal and Venmo transactions may take slightly longer to process compared to M-Pesa.</p>
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">
            Can I get a refund? <i class="fas fa-chevron-down"></i>
        </div>
        <div class="faq-answer">
            <p>Due to the digital nature of our service, we generally do not offer refunds once internet access has been granted. However, if you experience technical issues that prevent you from using the service, please contact our support team, and we'll work to resolve the problem or provide appropriate compensation.</p>
        </div>
    </div>
</section>

<!-- Footer -->
<footer>
    <div class="container">
        <div class="footer-content">
            <div class="footer-column">
                <h3>Connect With Us</h3>
                <p>Stay updated with the latest offers and news from ConnectKenya</p>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
            
            <div class="footer-column">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#pricing">Pricing Plans</a></li>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#payment">Payment Methods</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#faq">FAQ</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Contact Information</h3>
                <ul>
                    <li><i class="fas fa-map-marker-alt"></i> Nairobi, Kenya</li>
                    <li><i class="fas fa-phone"></i> +254 700 123 456</li>
                    <li><i class="fas fa-envelope"></i> support@connectkenya.com</li>
                </ul>
            </div>
        </div>
        
        <div class="copyright">
            <p>&copy; 2025 ConnectKenya. All rights reserved. Proudly developed in Kenya for Kenyans.</p>
        </div>
    </div>
</footer>

<script>
    // FAQ toggle functionality
    document.querySelectorAll('.faq-question').forEach(question => {
        question.addEventListener('click', () => {
            const item = question.parentElement;
            item.classList.toggle('active');
        });
    });
    
    // Plan selection functionality
    document.querySelectorAll('.pricing-card .btn').forEach(button => {
        button.addEventListener('click', () => {
            const plan = button.parentElement.querySelector('.price-amount').textContent;
            const duration = button.parentElement.querySelector('.price-duration').textContent;
            
            document.getElementById('plan').value = plan.replace('KSH ', '');
            document.getElementById('payment').scrollIntoView({ behavior: 'smooth' });
            
            // Show notification
            alert(`You've selected the ${plan} ${duration} plan. Please complete your payment below.`);
        });
    });
</script></body>
</html>

