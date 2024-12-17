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

<h2>Collapsible List Example</h2>
<p>Click on the buttons inside the box to expand/collapse the content.</p>

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
</div>

<button class="collapsible">Talks</button>
<div class="content">
  <!-- Talks content here -->
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



Education
======
* M.A. in Administration Management, Xiamen University, Sept. 2022 - Jun. 2025 (Expected)
* B.A. in Public Administration, Hainan University, Sept. 2018 - Jun. 2022
* B.S. in Public Service and Public Policy, Arizona State University, Sept. 2018 - May. 2022

Skills
======
* Stata, SPSS, R, Python, QGIS, and ArcGIS; ; 
* Office (Word, Excel, and PowerPoint)
* Adobe (PS, LR, AU, and PR)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Service and leadership
======
**Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.**

Work experience
======
**Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.**
