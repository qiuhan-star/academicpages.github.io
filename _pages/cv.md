---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /Resume_Han_(Rachel)_QIU.pdf
---
You can access Rachel's latest C.V. [here](https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/assets/Resume_Han_(Rachel)_QIU.pdf). 

{% include base_path %}

继续尝试
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Collapsible List Example</title>
<style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .active, .collapsible:hover {
    background-color: #555;
  }

  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
  }

  .toggle-all {
    position: fixed;
    top: 10px;
    right: 10px;
  }
</style>
</head>
<body>

<button class="toggle-all">Toggle All</button>

<button class="collapsible">Education</button>
<div class="content">
  <p>* M.A. in Administration Management, Xiamen University, Sept. 2022 - Jun. 2025 (Expected)</p>
  <p>* B.A. in Public Administration, Hainan University, Sept. 2018 - Jun. 2022</p>
  <p>* B.S. in Public Service and Public Policy, Arizona State University, Sept. 2018 - May. 2022</p>
</div>

<button class="collapsible">Skills</button>
<div class="content">
  <p>Stata, SPSS, R, Python, QGIS, and ArcGIS;</p>
  <p>Office (Word, Excel, and PowerPoint)</p>
  <p>Adobe (PS, LR, AU, and PR)</p>
</div>

<button class="collapsible">Publications</button>
<div class="content">
  <!-- Publications content here -->
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Talks</button>
<div class="content">
  <!-- Talks content here -->
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Service and leadership</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<button class="collapsible">Work experience</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
    this.classList.toggle("active");
  });
}

// Function to toggle all collapsible content
function toggleAllContent(display) {
  for (i = 0; i < coll.length; i++) {
    var content = coll[i].nextElementSibling;
    content.style.display = display;
    coll[i].classList.toggle("active", display === "block");
  }
}

// Add click event listener to the toggle-all button
document.querySelector('.toggle-all').addEventListener('click', function() {
  var isAnyContentVisible = Array.from(coll).some(function(c) {
    return window.getComputedStyle(c.nextElementSibling).display === 'block';
  });
  toggleAllContent(isAnyContentVisible ? 'none' : 'block');
});
</script>

</body>
</html>




下面是第一次版本
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Collapsible List Example</title>
<style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .active, .collapsible:hover {
    background-color: #555;
  }

  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
  }
</style>
</head>
<body>

<button class="collapsible">Education</button>
<div class="content">
  <p>* M.A. in Administration Management, Xiamen University, Sept. 2022 - Jun. 2025 (Expected)</p>
  <p>* B.A. in Public Administration, Hainan University, Sept. 2018 - Jun. 2022</p>
  <p>* B.S. in Public Service and Public Policy, Arizona State University, Sept. 2018 - May. 2022</p>
</div>

<button class="collapsible">Skills</button>
<div class="content">
  <p>Stata, SPSS, R, Python, QGIS, and ArcGIS;</p>
  <p>Office (Word, Excel, and PowerPoint)</p>
  <p>Adobe (PS, LR, AU, and PR)</p>
</div>

<button class="collapsible">Publications</button>
<div class="content">
  <!-- Publications content here -->
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Talks</button>
<div class="content">
  <!-- Talks content here -->
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Service and leadership</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<button class="collapsible">Work experience</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>

</body>
</html>


失败版本

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Collapsible List Example</title>
<style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .active, .collapsible:hover {
    background-color: #555;
  }

  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
  }

  .toggle-all {
    position: fixed;
    top: 10px;
    right: 10px;
  }
</style>
</head>
<body>

<button class="toggle-all">Toggle All</button>

<button class="collapsible">Education</button>
<div class="content">
  <p>* M.A. in Administration Management, Xiamen University, Sept. 2022 - Jun. 2025 (Expected)</p>
  <p>* B.A. in Public Administration, Hainan University, Sept. 2018 - Jun. 2022</p>
  <p>* B.S. in Public Service and Public Policy, Arizona State University, Sept. 2018 - May. 2022</p>
</div>

<button class="collapsible">Skills</button>
<div class="content">
  <p>Stata, SPSS, R, Python, QGIS, and ArcGIS;</p>
  <p>Office (Word, Excel, and PowerPoint)</p>
  <p>Adobe (PS, LR, AU, and PR)</p>
</div>

<button class="collapsible">Publications</button>
<div class="content">
  <!-- Publications content here -->
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Talks</button>
<div class="content">
  <!-- Talks content here -->
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
</div>

<button class="collapsible">Service and leadership</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<button class="collapsible">Work experience</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}

// Function to toggle all collapsible content
function toggleAllContent(display) {
  for (i = 0; i < coll.length; i++) {
    var content = coll[i].nextElementSibling;
    content.style.display = display;
    coll[i].classList.toggle("active", display === "block");
  }
}

// Add click event listener to the toggle-all button
document.querySelector('.toggle-all').addEventListener('click', function() {
  var isAnyContentVisible = Array.from(coll).some(function(c) {
    return window.getComputedStyle(c.nextElementSibling).display === 'block';
  });
  toggleAllContent(isAnyContentVisible ? 'none' : 'block');
});
</script>

</body>
</html>