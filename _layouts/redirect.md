---
# Mr. Green Jekyll Theme (https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme)
# Copyright (c) 2022 Mr. Green's Workshop https://www.MrGreensWorkshop.com
# Licensed under MIT

layout: util/compress
---
<!DOCTYPE html>
<html lang="en-US">
  <meta charset="utf-8">
  <title>Redirecting&hellip;</title>
  <link rel="canonical" href="{{ page.redirect.to }}">
  <script>location="{{ page.redirect.to }}"</script>
  <meta http-equiv="refresh" content="0; url={{ page.redirect.to }}">
  <meta name="robots" content="noindex">
  <h1>Redirecting&hellip;</h1>
  <a href="{{ page.redirect.to }}">Click here if you are not redirected.</a>
  <script src="https://scytedtvstudios.statuspage.io/embed/script.js"></script>
</html>