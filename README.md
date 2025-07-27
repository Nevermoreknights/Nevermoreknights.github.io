<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Responsive Image</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
    }
    .responsive-image {
      width: 100vw;      /* Full viewport width */
      height: 100vh;     /* Full viewport height */
      object-fit: contain; /* Keep aspect ratio, contain within window */
      display: block;
    }
  </style>
</head>
<body>


  <img src="https://i.postimg.cc/fbdbT6Y9/Fulu-Profile-inwork-3-1.png" alt="Expanding Image" class="responsive-image">

<script>
    !function (t, e, c, n) {
        var s = e.createElement(c);
        s.async = 1, s.src = 'https://scripts.claspo.io/scripts/' + n + '.js';
        var r = e.scripts[0];
        r.parentNode.insertBefore(s, r);
        var f = function () {
            f.c(arguments);
        };
        f.q = [];
        f.c = function () {
            f.q.push(arguments);
        };
        t['claspo'] = t['claspo'] || f;
    }(window, document, 'script', 'BE7E9464A52A4D7BB1FAA1A24589E3E2');
</script><script>claspo('init');</script>
</body>
</html>
