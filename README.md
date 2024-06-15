# Facebook_homepage
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Facebook - Log in or sign up</title>
  <link rel="shortcut icon" href="https://www.facebook.com/images/fb_icon_325x325.png" type="image/x-icon">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      width:auto;
      background-color: #f0f2f5;
    }
    .container {
      width: 350px; /* Set width */
      height: 300px;
      margin: 200px auto ;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      position: relative;
      left: 30%; /* Move to the right */
      transform: translateX(-50%); /* Center horizontally */
    }
    .logo img {
      width: 320px;
      height: 106px; /* Set the height */
      margin-bottom: 20px;
    }
    h2 {
        height: 76px; /* Set height */
        font-size: 24px;
        line-height: 28px;
        width: auto;
        margin-bottom: 20px;
      text-align: 50%; /* Align center */
    }
    form input[type="text"],
    form input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    form button[type="submit"],
    form button[type="button"] {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 4px;
      background-color: #4267B2;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
      margin-bottom: 10px; /* Added margin-bottom */
    }
    form button[type="submit"]:hover,
    form button[type="button"]:hover {
      background-color: #365899;
    }
    .forgot-password-container {
      text-align: center; /* Align container in center */
    }
    .forgot-password {
      font-size: 14px;
    }
    .create-page {
      margin-top: 20px;
      font-size: 14px;
      text-align: center; /* Align the text center */
    }
    .divider {
      margin-top: 10px;
      margin-bottom: 10px;
      border-top: 1px solid #ccc;
    }
    .create-page button[type="button"] {
      width: auto; /* Remove full width */
      background-color: #4CAF50; /* Green color */
      color: white;
      padding: 8px 8px; /* Adjust padding */
      border-radius: 4px;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s;
      font-size:17px;

    }
    .create-page button[type="button"]:hover {
      background-color: #45a049;
    }
    /* Adjusted CSS for the image container */
    .image-container {
      position: absolute;
      top: 40%;
      left: 10%; /* Aligned to the left */
      transform: translateY(-50%);
      padding: 10px;
    }
  </style>
</head>
<body>
  <!-- Image container -->
  <div class="image-container">
    <img src="https://static.xx.fbcdn.net/rsrc.php/y1/r/4lCu2zih0ca.svg" alt="Facebook Logo" width="320" height="106">
    <h2>Facebook helps you connect and share<br> with the people in your life.</h2>
  </div>
  <div class="container">
    <form>
      <input type="text" name="email" placeholder="Email address or phone number" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit">Log in</button>
      <div class="forgot-password-container">
        <a href="https://www.facebook.com/login/identify/?ctx=recover&ars=facebook_login&from_login_screen=0" class="forgot-password">Forgotten password?</a>
      </div>
      <div class="divider"></div> <!-- Division line -->
      <div class="create-page">
        <button type="button">Create new account</button>
      </div>
    </form>

  </div>
  <p style="text-align:center;margin-top: 28px; border-top:none;color: #1c1e21;font-family: SFProText-Regular, Helvetica, Arial, sans-serif;
    font-size: 14px;
    font-weight: normal;
    padding-top: 0;"><a href="https://www.facebook.com/pages/create/?ref_type=registration_form"><b>Create a page</a> for a celebrity, brand or business.</p>
</body>
</html>

