<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    /* CSS styles from the first part */
    #loginpage {
        position: relative;
        top: 300px;
    }
    .background {
        width: 430px;
        height: 480px;
        position: absolute;
        transform: translate(-50%, -50%);
        left: 50%;
        top: 50%;
    }
    .background .shape {
        height: 200px;
        width: 200px;
        position: absolute;
        border-radius: 50%;
    }
    .shape:first-child {
        background: linear-gradient(to left, #ff512f, #f09819);
        left: -60px;
        top: -110px;
    }
    form h3 {
        font-size: 32px;
        font-weight: 500;
        line-height: 42px;
        text-align: center;
    }
    label {
        display: block;
        margin-top: 30px;
        font-size: 16px;
        font-weight: 500;
    }
    input {
        display: block;
        height: 50px;
        width: 100%;
        background-color: rgba(225, 225, 255, 0.07);
        border-radius: 3px;
        padding: 0 10px;
        margin-top: 8px;
        font-size: 14px;
        font-weight: 300;
    }
    .shape:last-child {
        background: linear-gradient(to right, #ff512f, #f09819);
        right: -60px;
        bottom: -110px;
    }
    form {
        height: 400px;
        width: 1000px;
        background-color: rgba(255, 255, 255, 0.78);
        position: absolute;
        transform: translate(-50%, -50%);
        top: 80%;
        left: 50%;
        border-radius: 10px;
        backdrop-filter: blur(10px);
        border: 2px solid rgba(36, 184, 39, 0.994);
        box-shadow: 0 0 40px rgba(8, 7, 16, 0.6);
        padding: 50px 35px;
    }
    form * {
        font-family: "Poppins", sans-serif;
        color: #323030;
        letter-spacing: 0.5px;
        outline: none;
        border: none;
    }
    ::placeholder {
        color: #888484;
    }
    button {
        margin-top: 50px;
        width: 100%;
        background-color: #cdcbcb;
        color: #080710;
        padding: 15px;
        font-size: 18px;
        font-weight: 600;
        border-radius: 5px;
        cursor: pointer;
    }

    /* CSS styles from the second part */
    body {
        background-color: lightgreen;
    }

  </style>
</head>
<body>
  <main>
    <form id="loginpage">
      <h3>Log-In</h3>
      <label for="username">Username</label>
      <input type="text" placeholder="Email or Phone" id="username">
      <label for="password">Password</label>
      <input type="password" placeholder="Password" id="password">
      <button type="submit">Log-In</button>
    </form>
  </main>

  <!-- JavaScript part -->
  <script>
    document.getElementById('loginpage').addEventListener('submit', function(event) {
        event.preventDefault(); // Prevent form submission

        // Get the form data
        var username = document.getElementById('username').value;
        var password = document.getElementById('password').value;

        // Check if the entered username and password match the expected values
        if (username === 'user' && password === 'password') {
            alert('Login successful!');

            // Trigger the zoom-out animation
            var loginText = document.querySelector('h3'); // Assuming 'h3' contains the login text
            loginText.classList.add('zoom-out');

            // Redirect after the animation ends (1 second)
            setTimeout(function() {
                window.location.href = 'C:/Users/A_R_C/Desktop/website nature/NATURE/index (2).html'; // Update to the relative path
            }, 1000); // Match the timeout duration with the animation duration
        } else {
            alert('Invalid username or password. Please try again.');
        }
    });
  </script>

  <!-- External CSS from the second part -->
  <link rel="stylesheet" type="text/css" href="C:\Users\A_R_C\Desktop\website nature\NATURE\css.css">
</body>
</html>
