<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title><span style="color:#00e397">Ashok Enterprises</span></title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
      overflow-x: hidden;
      overflow-y: auto;
    }
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(0,227,151,0.2) 10%, transparent 40%),
                  radial-gradient(circle, rgba(0,227,151,0.15) 10%, transparent 40%);
      background-size: 20% 20%;
      animation: animateBg 40s linear infinite;
      z-index: -1;
    }
    @keyframes animateBg {
      0% { transform: translate(0, 0); }
      100% { transform: translate(-50%, -50%); }
    }
    header {
      padding: 5rem 1rem 2rem;
      min-height: 100vh;}
    nav {
      position: absolute;
      top: 0;
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      z-index: 2;
      background-color: rgba(0, 0, 0, 0.5);
    }
    nav ul {
      display: flex;
      gap: 1.5rem;
      list-style: none;
      color: white;
    }
    nav ul li {
      cursor: pointer;
      font-weight: bold;
    }
    nav .right-nav {
      display: flex;
      gap: 1rem;
      align-items: center;
    }
    nav .book-btn {
      background-color: #00e397;
      color: #000;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero-content {
      z-index: 1;
    }
    .hero-content h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero-content span {
      color: #00e397;
    }
    .hero-content p {
      font-size: 1.1rem;
      margin-bottom: 2rem;
    }
    .hero-content .cta-btn {
      background-color: #00e397;
      color: black;
      padding: 0.75rem 1.5rem;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
    }
    section {
      padding: 2rem;
      background-color: rgba(255, 255, 255, 0.9);
      color: #000;
    }
    h2 {
      color: #005baa;
    }
    ul li {
      margin: 0.5rem 0;
    }
    i {
      margin-right: 10px;
      color: #005baa;
    }
    footer {
      background-color: #003f7f;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .contact {
      padding: 2rem;
      background-color: #e6f2ff;
    }
    .highlight {
      color: #00e397;
      font-weight: bold;
    }
      html {
      scroll-behavior: smooth;
    }
    section {
      position: relative;
      overflow: hidden;
    }
    section::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(0,227,151,0.1) 10%, transparent 40%), radial-gradient(circle, rgba(0,227,151,0.07) 10%, transparent 40%);
      background-size: 20% 20%;
      animation: animateBg 50s linear infinite;
      z-index: -1;
    }
</style>
</head>
<body>
  <header>
    <nav>
      <ul>
  <li><a href="#services" style="color:white;text-decoration:none">Services</a></li>
  <li><a href="#contact" style="color:white;text-decoration:none">Contact</a></li>
  <li><a href="#about" style="color:white;text-decoration:none">About</a></li>
</ul>
      <div class="right-nav">
        <span onclick="document.getElementById('login-modal').style.display='flex'" style="color: white; text-decoration: none; font-weight: bold; cursor: pointer;">Login</span>
        <span>Support</span>
        <a href="#contact" class="book-btn">Book Service</a>
      </div>
    </nav>
    <div class="hero-content" style="display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; height: 100%;">
      <p style="font-size: 1.3rem; color: #00e397; font-weight: bold;">#1 MULTI-SERVICE CENTER</p>
      <h1><span class="highlight">Ashok Enterprises</span><br>Service and <span>Support</span> Excellence</h1>
      <p>Simplify Your Work Today with Smarter, Faster Solutions</p>
      <a href="#services" class="cta-btn">Get Started Now</a>
    </div>
  </header>

  <section id="services" style="position: relative; z-index: 1;">
  <h2>🔹 Booking Services</h2>
  <ul>
    <li><i class="fa-solid fa-train"></i><a href="https://www.irctc.co.in/" target="_blank" rel="noopener">Railway Ticket Booking (IRCTC)</a></li>
    <li><i class="fa-solid fa-bus"></i><a href="https://www.redbus.in/" target="_blank" rel="noopener">Bus Ticket Booking (RedBus)</a></li>
    <li><i class="fa-solid fa-plane"></i><a href="https://www.goindigo.in/" target="_blank" rel="noopener">Flight Ticket Booking (IndiGo)</a></li>
  </ul>

  <h2>🔹 Banking Services</h2>
  <ul>
    <li><i class="fa-solid fa-fingerprint"></i><a href="https://uidai.gov.in/" target="_blank" rel="noopener">AEPS (UIDAI)</a></li>
    <li><i class="fa-solid fa-money-bill-transfer"></i><a href="https://paytm.com/" target="_blank" rel="noopener">Money Transfer (Paytm)</a></li>
    <li><i class="fa-solid fa-university"></i><a href="https://account-open.sbi/" target="_blank" rel="noopener">Bank Account Opening (SBI)</a></li>
    <li><i class="fa-solid fa-indian-rupee-sign"></i><a href="https://retail.onlinesbi.sbi/retail/login.htm" target="_blank" rel="noopener">Cash Deposit / SBI Portal</a></li>
    <li><i class="fa-solid fa-receipt"></i><a href="https://www.bankofbaroda.in/" target="_blank" rel="noopener">Balance Enquiry (BOB)</a></li>
    <li><i class="fa-solid fa-credit-card"></i><a href="https://www.rupay.co.in/" target="_blank" rel="noopener">Debit/Credit Card Services (RuPay)</a></li>
  </ul>

  <h2>🔹 Government Services</h2>
  <ul>
    <li><i class="fa-solid fa-id-card"></i><a href="https://www.pan.utiitsl.com/" target="_blank" rel="noopener">PAN Card</a></li>
    <li><i class="fa-solid fa-hard-hat"></i><a href="https://eshram.gov.in/" target="_blank" rel="noopener">E-Shram Card</a></li>
    <li><i class="fa-solid fa-heart-pulse"></i><a href="https://pmjay.gov.in/" target="_blank" rel="noopener">Ayushman Card</a></li>
    <li><i class="fa-solid fa-people-group"></i><a href="https://labour.gov.in/" target="_blank" rel="noopener">Labour Card</a></li>
    <li><i class="fa-solid fa-graduation-cap"></i><a href="https://scholarship.up.gov.in/" target="_blank" rel="noopener">Scholarship Form</a></li>
    <li><i class="fa-solid fa-landmark"></i><a href="https://edistrict.up.gov.in/" target="_blank" rel="noopener">Income/Caste/Domicile Certificate</a></li>
    <li><i class="fa-solid fa-file-signature"></i><a href="https://npscra.nsdl.co.in/" target="_blank" rel="noopener">Pension Yojana (NPS)</a></li>
  </ul>

  <h2>🔹 Utility Services</h2>
  <ul>
    <li><i class="fa-solid fa-bolt"></i><a href="https://www.uppclonline.com/" target="_blank" rel="noopener">Electricity Bill (UPPCL)</a></li>
    <li><i class="fa-solid fa-mobile-alt"></i><a href="https://www.jio.com/" target="_blank" rel="noopener">Mobile Recharge (Jio)</a></li>
    <li><i class="fa-solid fa-tv"></i><a href="https://www.airtel.in/dth/" target="_blank" rel="noopener">DTH Recharge (Airtel)</a></li>
    <li><i class="fa-solid fa-fire"></i><a href="https://my.ebharatgas.com/" target="_blank" rel="noopener">Gas Booking (Bharat Gas)</a></li>
    <li><i class="fa-solid fa-tint"></i><a href="https://jalboard.delhi.gov.in/" target="_blank" rel="noopener">Water Bill (Delhi Jal Board)</a></li>
    <li><i class="fa-solid fa-wifi"></i><a href="https://www.bsnl.co.in/" target="_blank" rel="noopener">Broadband Bill Payment (BSNL)</a></li>
    <li><i class="fa-solid fa-building-columns"></i><a href="https://www.nagarnigam.in/" target="_blank" rel="noopener">Municipal Tax Payment</a></li>
  </ul>
<div style="width: 100%; height: 150px; background: radial-gradient(circle, rgba(0,227,151,0.15) 10%, transparent 40%), radial-gradient(circle, rgba(0,227,151,0.1) 10%, transparent 40%); background-size: 15% 15%; animation: animateBg 20s linear infinite;"></div>

$1 id="contact" style="position: relative; z-index: 1;">
  <h2>📞 Contact Information</h2>
  <p><strong>Owner:</strong> <span class="highlight">Ashok Yadav</span></p>
  <p><strong>Mobile:</strong> <a href="tel:9761294444">9761294444</a></p>
  <p><strong>Email:</strong> <a href="mailto:ashokenterprises109@gmail.com">ashokenterprises109@gmail.com</a></p>
  <p><strong>Address:</strong> <span class="highlight">Ashok Enterprise</span> front on Radha Swami Aashram, Kalapur, Pilibhit Road, Bareilly</p>
  <p><strong>WhatsApp:</strong> <a href="https://wa.me/919761294444" target="_blank">Chat on WhatsApp</a></p>
  <p><strong>Google Map:</strong> <a href="https://www.google.com/maps" target="_blank">View Location</a></p>
</section>

<footer>
  <p>&copy; 2025 <span class="highlight">Ashok Enterprises</span>. All rights reserved.</p>
</footer>

<!-- Login Modal -->
<div id="login-modal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.8); z-index:9999; display:flex; justify-content:center; align-items:center;">
  <div style="background:#fff; padding:2rem; border-radius:10px; width:90%; max-width:400px; position:relative;">
    <h3 style="margin-bottom:1rem; color:#003f7f;">Login to Ashok Enterprises</h3>
    <input type="text" placeholder="User ID" style="width:100%; padding:10px; margin-bottom:10px;">
    <input type="password" placeholder="Password" style="width:100%; padding:10px; margin-bottom:10px;">
    <button style="width:100%; padding:10px; background:#00e397; border:none; font-weight:bold; cursor:pointer;">Login</button>
    <p style="margin-top:1rem; text-align:center;">
      Don't have an account? <span onclick="document.getElementById('signup-form').style.display='block';" style="color:#005baa; cursor:pointer; text-decoration:underline;">Sign up</span>
    </p>
    <span onclick="document.getElementById('login-modal').style.display='none'" style="position:absolute; top:10px; right:15px; font-weight:bold; cursor:pointer;">&times;</span>

    <!-- Signup Form (initially hidden) -->
    <div id="signup-form" style="display:none; margin-top:1rem;">
      <h4 style="margin-bottom:1rem; color:#003f7f;">Sign Up</h4>
      <input type="text" placeholder="Full Name" style="width:100%; padding:10px; margin-bottom:10px;">
      <input type="email" placeholder="Email Address" style="width:100%; padding:10px; margin-bottom:10px;">
      <input type="text" placeholder="Mobile Number" style="width:100%; padding:10px; margin-bottom:10px;">
      <button onclick="sendSignupEmail()" style="width:100%; padding:10px; background:#005baa; border:none; color:white; font-weight:bold; cursor:pointer;">Register</button>
    </div>
  </div>
</div>

<script>
function sendSignupEmail() {
  const name = document.querySelector('#signup-form input[placeholder="Full Name"]').value;
  const email = document.querySelector('#signup-form input[placeholder="Email Address"]').value;
  const phone = document.querySelector('#signup-form input[placeholder="Mobile Number"]').value;

  if (!name || !email || !phone) {
    alert('Please fill all fields.');
    return;
  }

  const mailtoLink = `mailto:ashokenterprises109@gmail.com?subject=New Signup from Website&body=Name: ${name}%0DEmail: ${email}%0DPhone: ${phone}`;
  window.location.href = mailtoLink;
}
</script>

<!-- About Section -->
<section id="about" style="padding: 2rem; background-color: rgba(255, 255, 255, 0.9); color: #000;">
  <h2>ℹ️ About <span class="highlight">Ashok Enterprises</span></h2>
  <p>Welcome to <span class="highlight">Ashok Enterprises</span>, your trusted one-stop service center located front of Radha Swami Aashram, Kalapur, Pilibhit Road, Bareilly. We offer a wide range of services including booking, banking, government documentation, and utility bill solutions with complete support.</p>
  <p>We are committed to delivering fast, reliable, and accurate service with a personal touch. For any assistance, feel free to contact us via phone or WhatsApp.</p>
</section>
