![verified-seal](https://github.com/user-attachments/assets/e1c38fba-bec4-4bd8-ae2b-aa3d4e0827b2)
Initialize this repository with:
[ ] Add a README file ← THIS IS THE BOX!
[ ] Add .gitignore
[ ] Choose a license
[<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Solar Power Investment</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: url('https://images.unsplash.com/photo-1599982202375-e2c92f09c4db?auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      text-align: center;
    }
    .container {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 40px;
      max-width: 600px;
      margin: 100px auto;
      border-radius: 12px;
    }
    h1 {
      color: #ffcc00;
      margin-bottom: 10px;
    }
    p {
      font-size: 18px;
      margin-bottom: 20px;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: #ffcc00;
      color: #000;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
      margin: 10px;
    }
    .verified {
      margin-top: 20px;
      font-size: 14px;
      color: #00ff99;
    }
    .footer {
      margin-top: 40px;
      font-size: 13px;
      color: #ccc;
    }
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 10px 16px;
      border-radius: 50px;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Solar Power Investment</h1>
    <p>Earn Daily Income from Clean Energy. Join Thousands of Investors Nationwide.</p>
    <a href="signup.html" class="btn">Sign Up</a>
    <a href="login.html" class="btn">Log In</a>

    <div class="verified">
      ✅ Verified by: Central Bank of Nigeria · EFCC · NERC
    </div><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Signup – Solar Power Investment</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('https://images.unsplash.com/photo-1606761567284-f3bba4cd6532?auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }
    .signup-container {
      background: rgba(0,0,0,0.7);
      max-width: 400px;
      margin: 100px auto;
      padding: 30px;
      border-radius: 10px;
      text-align: left;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    input[type="text"],
    input[type="password"],
    input[type="tel"] {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: none;
      border-radius: 5px;
    }
    button {
      width: 100%;
      padding: 10px;
      background-color: #ffcc00;
      border: none;
      border-radius: 5px;
      font-weight: bold;
    }
    label {
      font-size: 14px;
    }
    .footer {
      margin-top: 20px;
      font-size: 13px;
      text-align: center;
      color: #ccc;
    }
    .recaptcha, .verified {
      margin-top: 10px;
      font-size: 13px;
      color: #00ff99;
    }
  </style>
</head>
<body>
  <div class="signup-container">
    <h2>Create Account</h2>
    <form action="dashboard.html" method="GET" onsubmit="return validateForm()">
      <label>First Name</label>
      <input type="text" required />

      <label>Middle Name</label>
      <input type="text" />

      <label>Last Name</label>
      <input type="text" required />

      <label>Phone Number</label>
      <input type="tel" required />

      <label>Password</label>
      <input type="password" required />

      <label>Referral Code (Optional)</label>
      <input type="text" />

      <label>
        <input type="checkbox" required />
        I agree to the <a href="#">Terms & Conditions</a>
      </label>

      <div class="recaptcha">🔒 reCAPTCHA Verified</div>
      <div class="verified">✅ Verified by CBN · EFCC · NERC</div>

      <button type="submit">Sign Up</button>
    </form>

    <div class="footer">
      Already have an account? <a href="login.html" style="color:#ffcc00;">Login</a>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login – Solar Power Investment</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('https://images.unsplash.com/photo-1592890288335-0c55c1a66e2f?auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }
    .login-container {
      background: rgba(0,0,0,0.7);
      max-width: 400px;
      margin: 100px auto;
      padding: 30px;
      border-radius: 10px;
      text-align: left;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    input[type="tel"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: none;
      border-radius: 5px;
    }
    button {
      width: 100%;
      padding: 10px;
      background-color: #ffcc00;
      border: none;
      border-radius: 5px;
      font-weight: bold;
    }
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dashboard – Solar Power</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #111, #222);
      color: white;
    }
    .dashboard {
      max-width: 700px;
      margin: 50px auto;
      padding: 20px;
      background: #1a1a1a;
      border-radius: 10px;
    }
    h2 {
      color: #ffcc00;
      text-align: center;
    }
    .info-box {
      background: #2a2a2a;
      padding: 15px;
      border-radius: 10px;
      margin: 10px 0;
    }
    .info-box span {
      font-weight: bold;
      color: #00ff99;
    }
    .nav {
      display: flex;
      justify-content:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Solar Products – Solar Power</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #111, #222);
      color: white;
    }
    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
    }
    h2 {
      color: #ffcc00;
      text-align: center;
    }
    .product {
      background: #1e1e1e;
      border: 1px solid #444;
      border-radius: 10px;
      padding: 20px;
      margin: 15px 0;
    }
    .produc
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Make Payment – Solar Power</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #111, #222);
      color: white;
      padding: 30px;
    }
    .container {
      max-width: 500px;
      background: #1e1e1e;
      margin: 50px auto;
      padding: 20px;
      border-radius: 10px;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: none;
    }
    label {
      font-size: 14px;
    }
    button {
      width: 100%;
      padding: 10px;
      background: #ffcc00;
      color: black;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .bank-info {
      background: #2a2a2a;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 5px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Make Your Investment Payment</h2>

    <div class="bank-info">
      <strong>Pay
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin Panel – Solar Power</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      padding: 20px;
    }
    .login-box, .admin-panel {
      max-width: 600px;
      background: #1e1e1e;
      margin: 50px auto;
      padding: 20px;
      border-radius: 10px;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: none;
    }
    button {
      padding: 10px 15px;
      background: #ffcc00;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    .section {
      margin-top: 30px;
    }
    label {
      font-size: 14px;
    }
    .payment-box {
      background: #2a2a2a;
      padding: 15px;
      border-radius: 8px;
      margin: 10px 0;
    }
  </style>
</head>
<body>

<div class="login-box" id="loginBox">
  <h2>Admin Login</h2>
  <input type="password" id="adminPass" placeholder="Enter admin password" />
  <button onclick="loginAdmin()">Login</button>
</div>

<div class="admin-panel" id="adminPanel" style="display: none;">
  <h2>Welcome, Admin</h2>

  <div class="section">
    <h3>Set Account Details</h3>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Withdrawal – Solar Power</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #000000, #1f1f1f);
      color: white;
      padding: 30px;
    }
    .container {
      max-width: 500px;
      margin: 50px auto;
      padding: 20px;
      background: #1a1a1a;
      border-radius: 10px;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: none;
    }
    button {
      width: 100%;
      padding: 10px;
      background: #ffcc00;
      color: black;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .alert {
      background: #ff4444;
      padding: 15px;
      border-radius: 6px;
      text-align: center;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

<div class="container" id="withdrawalBox">
  <h2>Withdraw Your Earnings</h2>

  <div id="approvalCheck"></div>

  <form id="withdrawForm" onsubmit="submitWithdraw(); return false;" style="display: none;">
    <input type="text" id="bank" placeholder="Bank Name" required />
    <input type="text" id="accountName" placeholder="Account Name" required />
    <input type="text" id="accountNumber" placeholder="Account Number" required />
    <input type="number" id="amount" placeholder="Amount (₦)" required />
    <button type="submit">Submit Withdrawal</button>
  </form>
</div>

<script>
  // Check if payment is approved first
  const data = JSON.parse(localStorage.getItem("userPayment") || "{}");

  if (!data.approved) {
    document.getElementById("approvalCheck").innerHTML = `
      <div class="alert">
        🚫 You cannot withdraw yet.<br>
        Your payment has not been approved by the admin.
      </div>
    `;
  } else {
    document.getElementById("approvalCheck").innerHTML = `
      ✅ Payment Approved! You can now request withdrawal.
    `;
    document.getElementById("withdrawForm").style.display = "block";
  }

  function submitWithdraw() {
    const request = {
      bank: document.getElementById("bank").value,
      accountName: document.getElementById("accountName").value,
      accountNumber: document.getElementById("accountNumber").value,
      amount: document.getElementById("amount").value,
      date: new Date().toLocaleString()
    };

    alert("Withdrawal request submitted successfully! It will be reviewed.");
    console.log("User Withdrawal:", request);
    window.location.href = "dashboard.html";
  }
</script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Income Log – Solar Power</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #0f0f0f, #1a1a1a);
      color: white;
      padding: 30px;
    }
    .container {
      max-width: 600px;
      margin: auto;
      background: #1f1f1f;
      padding: 20px;
      border-radius: 10px;
    }
    h2 {
      text-align: center;
      color: #ffcc00;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      padding: 10px;
      border-bottom: 1px solid #444;
      text-align: left;
    }
    th {
      background: #2a2a2a;
      color: #ffcc00;
    }
    tr:nth-child(even) {
      background: #292929;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Daily Income Log</h2>
    <table>
      <thead>
        <tr>
          <th>Date</th>
          <th>Amount Earned (₦)</th>
        </tr>
      </thead>
      <tbody id="logTable">
        <!-- Logs will go here -->
      </tbody>
    </table>
  </div>

  <script>
    // Fake daily earning data for preview
    const earningsPerDay = 250; // Normal user; change to 600 for VIP
    const days = 10;
    const tbody = document.getElementById("logTable");
    for (let i = 0; i < days; i++) {
      const date = new Date();
      date.setDate(date.getDate() - i);
      const row = `<tr><td>${date.toDateString()}</td><td>₦${earningsPerDay}</td></tr>`;
      tbody.innerHTML += row;
    }
  </script>
</body>
</html>

    <img src="verified-seal.png" alt="Verified Seal" width="100" style="margin-top: 10px;">
  </div>

  <div class="footer">
    📍 Powered by Solar Energy Nigeria HQ | support@solarpower.ng
  </div>

  <a class="whatsapp-btn" href="https://wa.me/2348000000000?text=Hello+Solar+Support" target="_blank">
    💬 Chat Support
  </a>
</body>
</html>
