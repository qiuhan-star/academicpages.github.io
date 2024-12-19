<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Theme Switcher</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<style>
  * { box-sizing: border-box; }

  body {
    font-family: "Montserrat", sans-serif;
    background-color: #fff;
    transition: background 0.2s linear;
  }

  body.dark {
    background-color: #292c35;
  }

  body.dark h1, body.dark .support a {
    color: #fff;
  }

  .checkbox {
    display: none;
  }

  .checkbox-label {
    background-color: #111;
    width: 50px;
    height: 26px;
    border-radius: 50px;
    position: fixed;
    top: 20px;
    right: 20px;
    padding: 5px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .fa-moon, .fa-sun {
    color: #f1c40f;
    transition: transform 0.2s linear;
  }

  .fa-moon {
    position: absolute;
    left: 2px;
  }

  .fa-sun {
    position: absolute;
    right: 2px;
  }

  .checkbox:checked + .checkbox-label .fa-moon {
    transform: translateX(-100%);
  }

  .checkbox:not(:checked) + .checkbox-label .fa-sun {
    transform: translateX(100%);
  }

  .ball {
    background-color: #fff;
    width: 22px;
    height: 22px;
    border-radius: 50%;
    position: absolute;
    top: 2px;
    transition: transform 0.2s linear;
  }

  .checkbox:checked + .checkbox-label .ball {
    transform: translateX(26px);
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
    <div class="ball"></div>
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
