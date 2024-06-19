- 👋 Hi, I’m @Huud-tech
- 👀 I’m interested in HTML development
- 🌱 I’m currently learning how to create a website
- 💞️ I’m looking to collaborate on my first website
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Huud-tech/Huud-tech is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<h1>hello world</h1>
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>FORM</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body{
      font-family: Arial, Helvetica, sans-serif;
      background: #344a72;
      color: #fff;
      line-height: 1.8;
    }
    a {
      text-decoration: none;
    }
    #container {
      margin:30px auto;
      max-width: 400px;
      padding: 20px;
    }
    .head {
      background: #fff;
      padding: 15px 25px;
      color: #333;
    }
    .head h3,
    .head p {
      text-align: center;
      background: #49c1a2;
    }
    .head .body {
      margin-top: 20px
    }
    .head .body label {
      display: block;
      color: #666;
    }
    .head .body input {
      width: 100%;
      padding: 10px;
      border: #ddd 1px solid;
      border-radius: 10px
    }
    .head button {
      display: block;
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      background: #49c1a2;
      color: #fff;
    }
    .head .bottom {
      font-size: 13px;
      text-align: center;
    }
    .footer {
      text-align: center;
      margin-top: 10px;
    }
    .footer a {
      color: greenyellow;
     }
  </style>
</head>

<body>
  <div id="container">
    <div class="head">
        <h3>Sign Up</h3>
        <p>Fill in the form</p>

    <div class="body">
  <form>
    <label>First name</label>
    <input type="text" name="name" placeholder="First name"><br>
    <label>Last name</label>
    <input type="text" name="name" placeholder="Second name"><br>
    <label>Email</label>
    <input type="text" name="name" placeholder="@gmai.com"><br>
    <label>Password</label>
    <input type="password" name="password" placeholder="password"><br>
    <label>Confirm Password</label>
    <input type="password" name="password" placeholder="confirm password"><br>
    <button>Sign Up</button><br>
    <div class="bottom">
       By clicking the Sign Up button, you agree on our <a href="#">Terms & condition</a> and <a href="#">Privacy policy</a>
    </div>
    </div>
    </div>
    <div class="footer">
      Already have an account?<a href="#">Login Here</a>
    </div>
  </form>
   </div>
</body>

</html>
