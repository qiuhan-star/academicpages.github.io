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
    opacity: 0;
    position: absolute;
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
  }

  .fa-moon, .fa-sun {
    color: #f1c40f;
    position: absolute;
    left: 5px;
  }

  .fa-sun {
    left: unset;
    right: 5px;
  }

  .checkbox:checked + .checkbox-label .fa-moon {
    display: none;
  }

  .checkbox:not(:checked) + .checkbox-label .fa-sun {
    display: none;
  }

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
