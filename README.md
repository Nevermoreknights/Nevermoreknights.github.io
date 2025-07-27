<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Age Verification</title>
  <style>
    #protected-content {
      display: none;
      text-align: center;
      margin-top: 20px;
    }
    #error-message {
      color: red;
      text-align: center;
      display: none;
    }
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 50px;
    }
  </style>
</head>
<body>

  <h1>Age Verification Required</h1>
  <p>Please confirm your age to continue:</p>

  <button onclick="verifyAge()">I'm 18 or Older</button>

  <div id="error-message">You must be at least 18 to view this content.</div>

  <div id="protected-content">
    <h2>Verified!</h2>
    <img src="your-image.jpg" alt="Protected Content" style="max-width: 80%;">
  </div>

  <script>
    function verifyAge() {
      const isOldEnough = confirm("Are you 18 years or older?");
      if (isOldEnough) {
        document.getElementById('protected-content').style.display = 'block';
        document.querySelector('button').style.display = 'none';
      } else {
        document.getElementById('error-message').style.display = 'block';
      }
    }
  </script>

</body>
</html>
