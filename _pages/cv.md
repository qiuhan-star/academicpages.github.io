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
<!-- Service and leadership content here -->
  <ul>{% for post in site.services reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
</div>

</div>

<button class="collapsible">Work experience</button>
<div class="content">
  <p>Hello, this page is currently being updated and is expected to be ready by December 22, 2024. Thank you for your patience.</p>

**Hangzhou Basic Interior Design & Construction Co., Ltd.** (Zhejiang, China)

**Head of Data Planning Department** (Full-time)

**Duration:** Jun. 2023 - Sep. 2023
- Spearheaded the collection and synthesis of data from internal databases and market research reports, utilizing statistical methods to ensure data accuracy and relevance.
- Expertly managed and organized data using Excel, creating spreadsheets with formulas and pivot tables to streamline data analysis and improve data integrity.
- Crafted comprehensive reports and infographics, and presented findings via PowerPoint to simplify complex data for team comprehension.
- Delivered strategic data interpretations, leveraging statistical models to forecast trends and inform executive decision-making, resulting in more informed and data-driven strategic planning sessions.

**Assistant to the Chief Financial Office** (Full-time)

**Duration:** Jun. 2022 - Aug. 2022
- Supported the CFO in managing the company’s financial operations, ensuring compliance with financial policies and procedures.
- Analyzed financial data, identifying trends and quantifiable improvement areas within financial statements, budgets, and cash flow projections.
- Contributed to monthly financial reporting, leveraging analytical skills to present clear, data-driven insights.
- Assisted in the management of accounts payable and receivable, enhancing payment efficiency and cash flow through targeted quantitative strategies.

**Zhejiang Yiming Food Co., Ltd**  (Zhejiang, China)

**Executive Assistant to the COO and CFO** (Full-time Intern)

**Duration:** Dec. 2021 - Apr. 2022
- Optimized COO’s schedule by planning itineraries and coordinating meetings.
- Assisted COO in strategic planning, leading to the development of public relations strategies.
- Supported CFO in budgeting and cost control, analyzing financial data to inform strategic financial decisions and optimize resource allocation within the company.
- Assisted the CFO in executing comprehensive market research and analysis, facilitating informed strategic financial planning and decision-making.

**National Survey Research Center (NSRC) at Renmin University of China** (Online)

**Telephone Interviewer** (Part-time Intern)

**Duration:** Mar. 2021 - Dec. 2021
- Conducted telephone interviews for high-impact surveys, including a national study on the comprehensive effects of the COVID-19 pandemic and a nationwide employment survey of 2021 university graduates.
- Maintained a 98% accuracy rate in collecting over 200 detailed survey samples, contributing to the reliability of research findings.
- Effectively engaged with a diverse range of respondents, employing communication strategies to overcome objections and secure valuable insights for high-impact studies.
- Utilized quantitative methods to ensure the representativeness and generalizability of the collected data.


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
