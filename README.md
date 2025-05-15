# Animated-Login-Page
A sleek and futuristic animated login page crafted with modern web technologies. Featuring smooth transitions, interactive elements, and a visually captivating UI, this page offers a dynamic user experience. Ideal for projects requiring an elegant and responsive login interface.

#HTML Code
<!DOCTYPE html>
<head>
  <title>Link CSS to HTML</title>
  <link rel="stylesheet" href="style.css"
</head>
<body>
    <form class="box" action="Hello.html" method="post">
      <h1>Login</h1>
      <input type="text" name="" placeholder="Username">
      <input type="password" name="" placeholder="Password">
      <input type="submit" name="" value="Login">
    </form>
</body>


#CSS CODE
body{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background: #232121;
}

.box{
    width: 300px;
    padding: 20px;
    position: absolute;
    top: 50%;
    left: 50%;
    color: white;
    transform: translate(-50%,-50%);
    background: #191919;
    text-align: center;
    border-radius: 14em;
    box-shadow: 5px 5px 50px 50px rgba(252, 5, 5, 0.699);
    animation: animateBg 5s linear infinite;
}

   @keyframes animateBg{
      100%{
      filter: hue-rotat(360deg);
      }
}

.box input{
     border: 0;
     background: none;
     display: block;
     margin: 20px auto;
     text-align: center;
     border: 3px solid #0399fd;
     padding: 14px 10px;
     width: 200px;
     outline: none;
     color: white;
     border-radius: 24px;
     transition: 0.25s;
}

.box input[type="text"]:focus,.box input[type="password"]:focus{
     width: 280px;
     border-color:#84fb6b;
}

.box input[type="submit"]{
     border: 0;
     background: none;
     display: block;
     margin: 20px auto;
     text-align: center;
     font-size: 100%;
     border: 3px solid #04fb6b;
     padding: 14px 40px;
     outline: none;
     color: white;
     border-radius: 24px;
     transition: 0.25s;
     cursor: pointer;
}

.box input[type="submit"]:hover{
  background:#04fb6b;
}
