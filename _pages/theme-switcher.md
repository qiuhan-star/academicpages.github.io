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
<style>
  :root {
    --color-background: #1b1b1b; /* 暗色背景 */
    --color-text: #fff; /* 暗色文字 */
    --color-background-light: #fff; /* 亮色背景 */
    --color-text-light: #0b1016; /* 亮色文字 */
  }

  body {
    background-color: var(--color-background-light);
    color: var(--color-text-light);
    transition: background-color 0.3s, color 0.3s;
  }

  body.dark-mode {
    background-color: var(--color-background);
    color: var(--color-text);
  }
</style>
</head>
<body>

<button onclick="toggleTheme()">切换主题</button>

<script>
  function toggleTheme() {
    let html = document.querySelector('html');
    if (html.classList.contains('dark-mode')) {
      html.classList.remove('dark-mode');
    } else {
      html.classList.add('dark-mode');
    }
  }
</script>

</body>
</html>
