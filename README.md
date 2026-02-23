<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
    }

    .login-box {
      width: 300px;
      margin: 100px auto;
      padding: 25px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      text-align: center;
    }

    input {
      width: 100%;
      padding: 8px;
      margin: 8px 0;
    }

    button {
      width: 100%;
      padding: 8px;
      background-color: #4CAF50;
      color: green;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>Login</h2>
    <form>
      <label>Username:</label>
      <input type="text" placeholder="Enter username">

      <label>Password:</label>
      <input type="password" placeholder="Enter password">

      <button type="submit">Login</button>
    </form>
  </div>

</body>
</html>
