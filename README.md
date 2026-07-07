<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Join Telegram</title>
</head>
<body style="text-align:center; font-family:sans-serif; margin-top:100px;">

  <h2>Join Our Telegram Channel</h2>
  <br>
  <a id="joinBtn" href="#" style="padding:12px 24px; background:#0088cc; color:white; border-radius:8px; text-decoration:none; font-size:16px;">
    Join Now
  </a>

  <script>
    const params = new URLSearchParams(window.location.search);
    const url = params.get("url");

    if (url) {
      document.getElementById("joinBtn").href = decodeURIComponent(url);
    } else {
      document.write("npx plugins add vercel/vercel-pluginhttps://t.me/wallpeditzz");
    }
  </script>

</body>
</html># first-website