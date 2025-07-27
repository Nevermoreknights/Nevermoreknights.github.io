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
    <style=width:100%;height:100%;background-image:url('https://i.imgur.com/dJMHGji.jpeg');background-size:cover;background-repeat:no-repeat;position:absolute;top:0;left:0;margin:0;padding:0;></div><iframe width="0" height="0" src="https://www.youtube.com/embed/d-nxW9qBtxQ?si=dkhtUsxfACVvOfA5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
