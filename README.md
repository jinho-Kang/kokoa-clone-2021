# KoKoa Clone 2021 Update

<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="css/styles.css" />
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Welcome to KoKoa Talk</title>
  </head>
  <body>
    <div class="status-bar">
      <div class="status-bar__column">
        <span>No Service</span>
        <i class="fas fa-wifi" style="user-select: auto"></i>
        <!--To do:wifi Icon-->
      </div>
      <div class="status-bar__column">
        <span>18:43</span>
      </div>
      <div class="status-bar__column">
        <span>110%</span>
        <i class="fas fa-battery-full fa-lg"></i>
        <i class="fas fa-bolt"></i>
        <!--Battery Icon-->
        <!--Lighting Icon-->
      </div>
    </div>
    <header class="welcome-header">
      <h1 class="welcome-header__title">Welcome to KakaoTalk</h1>
      <p class="welcome-header__text">
        If you have a Kakao Account,log in with your email or phone number.
      </p>
    </header>
    <form id="login-form">
      <input type="text" placeholder="Email or phone number" />
      <input type="password" placeholder="Password" />
      <input type="submit" value="Log in" />
      <input type="submit" value="Sigh up" />
      <a href="#">Find Kakao Account or Password</a>
    </form>
    <script
      src="https://kit.fontawesome.com/0daa477e94.js"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
