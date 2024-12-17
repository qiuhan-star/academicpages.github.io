---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Welcome to Rachel's Homepage</title>
<style>
    /* CSS样式 */
    body, html {
        height: 100%;
        margin: 0;
        overflow: hidden; /* 隐藏滚动条 */
    }

    #overlay {
        background: #333; /* 覆盖层的背景颜色 */
        color: white;
        width: 100%;
        height: 100%;
        position: fixed; /* 使覆盖层固定在视口中 */
        top: 0;
        left: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 1000;
        transition: transform 0.5s ease-in-out; /* 动画过渡效果 */
    }

    .content {
        text-align: center;
    }

    #main-content {
        display: none; /* 初始时隐藏主页内容 */
        opacity: 0; /* 初始时不透明度为0 */
        transition: opacity 1s ease-in-out; /* 动画过渡效果 */
    }
</style>
</head>
<body>

<div id="overlay">
    <div class="content">
        <h1>Welcome</h1>
        <p>Click anywhere to enter Rachel's homepage</p>
    </div>
</div>

<div id="main-content">
    <!-- 这里是你的主页内容 -->
    <h1>This is the homepage</h1>
    <p>Welcome to Rachel's website</p>
</div>

<script>
    // JavaScript脚本
    document.getElementById('overlay').addEventListener('click', function() {
        var overlay = this;
        var mainContent = document.getElementById('main-content');

        // 开始动画
        overlay.style.transform = 'translateX(-100%)'; // 拉开覆盖层
        overlay.style.opacity = '0'; // 使覆盖层透明

        setTimeout(function() {
            overlay.style.display = 'none'; // 隐藏覆盖层
            mainContent.style.display = 'block'; // 显示主页内容
            setTimeout(function() {
                mainContent.style.opacity = 1; // 渐显主页内容
            }, 50); // 稍微延迟渐显效果
        }, 500); // 确保动画时间与CSS中定义的过渡时间一致

        // 解除body的overflow隐藏，允许滚动
        document.body.style.overflow = 'auto';
    });
</script>
</body>
</html>



My name is Han Qiu (Rachel, 邱涵). Driven by a passion for social justice and a personal dedication to making a difference, I am deeply committed to advancing public interest and welfare, always eager to contribute to charitable causes and promote community well-being.

I am a rigorously trained Master’s student in Public Administration at the [School of Public Affairs](https://spa.xmu.edu.cn/), [Xiamen University](https://www.xmu.edu.cn/), under the guidance of [Professor Wenxuan Yu](https://spa.xmu.edu.cn/info/1237/3095.htm).

I received a B.S. degree in Public Service & Public Policy from [Arizona State University](https://www.asu.edu/) (2022) and a B.A. degree in Public Administration from [Hainan University](https://www.hainanu.edu.cn/) (2022), where I was mentored by [Professor Haiying Lin](https://haitc.hainanu.edu.cn/cslm/jzyg/szdw/xzgl.htm).

My research interests are broadly lie in the areas of public finance, public and nonprofit management, digital government, government transparency, information technology and politics, and environmental policy.

I am actively seeking research opportunities and PhD positions for Fall 2025. If you are looking for a dedicated and self-motivated candidate, please DO contact me at rachel.hanqiu@gmail.com!
<br><br>

🌟 Interesting Sharing 🌟
======
As I was weighing the decision to pursue a PhD, I stumbled upon a phenomenal game -- the [**PhD Simulator**](https://research.wmz.ninja/projects/phd/index.html)! I'm eager to spread the word. For a deeper dive into the details, [**Click Here**](game-details.html).
<br><br>

🔥🔥 Latest News
======
<span style="color: #888888;">**[NOV. 2024]**</span> 🎉 **Academic Achievement:** *My Research Paper Earns College Acclaim!* >> [**Read More**](https://mp.weixin.qq.com/s/2TYL9l8GGay93hLLRQBzYw)

<span style="color: #888888;">**[DEC. 2023]**</span> 🚀 **Academic Milestone:** *Making My Debut at the International Academic Conference, Featured in College Broadcast!* >> [**Read More**](https://mp.weixin.qq.com/s/EuHTxNFZpdGGEOrvOj-RPg)

<span style="color: #888888;">**[DEC. 2023]**</span> 🗨️ **Academic Salon:**</span> *Delighted to Share My Research Insights within the College Community!* >> [**Read More**](https://mp.weixin.qq.com/s/dn-2_kHyLDbNC0hQ042xEw)

<span style="color: #888888;">**[May 2022]**</span> 🎓 **I've graduated!** *Summa Cum Laude Achievement with Heartfelt Thanks to My Supporters!* 🌟👩‍🎓

**Show more...**
<br><br>

Research Interest
======
## **The Evolution of My Research Interests**
Reflecting on my previous academic journey, it may seem broad in scope, but I see it as a natural evolution of my interests within the field of public policy and administration. My passion for exploration has been the compass guiding my studies, and the experiences I’ve gathered have greatly enriched my understanding and perspectives. Therefore, I would like to offer a more detailed account of how my research interests have evolved, in the hope that this will help you know me better.

**During my undergraduate studies**, my focus was on <u>local government responsiveness, transparency, and message strategy</u>. My role as a <u>research assistant</u> allowed me to delve into the realms of <u>collaborative governance and public service provision</u>. It was also during this time that my passion for <u>environmental and sustainability policies</u>, particularly in the area of <u>river and water governance</u>, was ignited through my participation in extracurricular activities and volunteer work. Furthermore, my undergraduate experience was enriched by social practice research, which cultivated a strong interest in services designed for the elderly. This research underscored the importance of tailoring public policies to meet the unique needs of this demographic. Through these diverse experiences, I learned the importance of aligning public policy with the specific needs of different community segments, a lesson that has been central to my academic and professional growth.

**In graduate school**, my attention turned to <u>government transparency (both administrative and fiscal transparency), performance management, digital governance, AI policy, and environmental policies (climate change and energy just transition)</u>. My research and exploration of AI, especially generative AI, revealed its potential to streamline public sector operations and improve policy effectiveness. However, I also became aware of the double-edged nature of technology, understanding its potential to disrupt, for instance, higher education and its challenges for public administration. This realization has led me to understand the critical necessity of integrating critical thinking and ethical considerations into our policies and practices in our rapidly evolving era.
<br><br>

📅 **Coming Soon**
======
The narrative continues. ✨ **Mark your calendars for December 22** when the full story unfolds. 🌟 Your patience is greatly appreciated!


