# Nevermoreknights.github.io
I need to install the Claspo (https://claspo.io) script on our site

Paste this script only once on every page of your website – right before the closing </body> tag:
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

Alternative ways to install the script:
https://support.claspo.io/en/collections/5041998-user-guides-and-instructions
