
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Instagram Landing Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fafafa;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }
    .container {
      text-align: center;
      background: #fff;
      padding: 40px;
      border: 1px solid #dbdbdb;
      border-radius: 8px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
    }
    .logo {
      font-size: 36px;
      font-weight: bold;
      color: #262626;
      margin-bottom: 20px;
    }
    input {
      display: block;
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #dbdbdb;
      border-radius: 4px;
    }
    button {
      width: 100%;
      padding: 10px;
      background: #3897f0;
      color: #fff;
      border: none;
      border-radius: 4px;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background: #2878c8;
    }
    .footer {
      margin-top: 20px;
      font-size: 14px;
      color: #8e8e8e;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo">Instagram</div>
    <input type="text" placeholder="Phone number, username, or email">
    <input type="password" placeholder="Password">
    <button>Log In</button>
    <div class="footer">
      Don’t have an account? <a href="#">Sign up</a>
    </div>
  </div>
</body>
</html>
