---
permalink: /theme-switcher/
title: "Theme Switcher"
author_profile: true
---
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Theme Switcher</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap">
<style>
  * { box-sizing: border-box; }

  body {
    font-family: "Montserrat", sans-serif;
    background-color: #fff;
    display: flex;
    justify-content: center;
    transition: background 0.2s linear;
  }

  body.dark { background-color: #292c35; }

  body.dark h1, body.dark .support a { color: #fff; }

  .checkbox {
    opacity: 0;
    position: absolute;
  }

  .checkbox-label {
    background-color: #111;
    width: 50px;
    height: 26px;
    border-radius: 50px;
    position: relative;
    padding: 5px;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .fa-moon { color: #f1c40f; }

  .fa-sun { color: #f39c12; }

  .checkbox-label .ball {
    background-color: #fff;
    width: 22px;
    height: 22px;
    position: absolute;
    left: 2px;
    top: 2px;
    border-radius: 50%;
    transition: transform 0.2s linear;
  }

  .checkbox:checked + .checkbox-label .ball {
    transform: translateX(24px);
  }
</style>
</head>
<body>

<h1>Light/Dark Toggle<br>Button</h1>

<div>
  <input type="checkbox" class="checkbox" id="checkbox">
  <label for="checkbox" class="checkbox-label">
    <i class="fas fa-moon"></i>
    <i class="fas fa-sun"></i>
    <span class="ball"></span>
  </label>
</div>

<script type="text/javascript">
  const checkbox = document.getElementById("checkbox");
  checkbox.addEventListener("change", () => {
    document.body.classList.toggle("dark");
  });
</script>

</body>
</html>
