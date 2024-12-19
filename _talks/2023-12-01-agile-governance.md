---
title: "Embracing Agile Governance: Cultivating Innovation and Addressing the Challenges of Generative Artificial Intelligence in Higher Education"
collection: talks
type: "Presenter at Journal of Asian Public Policy Special Issue Authors' Workshop"
permalink: /talks/2023-12-01-agile-governance
venue: "The Hong Kong University of Science and Technology (HKUST)"
date: 2023-12-01
location: "Hong Kong, China"
---
Captured in the moment, sharing insights at a recent research event. 📸
<img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-1.PNG" alt="Talk 2023-12-01-1" title="Talk 2023-12-01-1">
#Talk #AcademicLife



[News Report](https://mp.weixin.qq.com/s/EuHTxNFZpdGGEOrvOj-RPg)




<div id="homeCarousel">
  <div id="homeCarouselWrap">
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-1.PNG">
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-2.PNG">
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-3.PNG">
    <!-- Duplicate the images to create an infinite loop -->
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-1.PNG">
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-2.PNG">
    <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/talks/Talk-2023-12-01-3.PNG">
  </div>
</div>
<div id="modal">
  <span id="closeBtn">×</span>
  <img id="img2">
</div>

<style>
    body {
        display: grid;
        place-items: center;
        height: 100vh;
        margin: 0;
        overflow: hidden;
    }
    #homeCarousel {
        width: 300px;
        height: 1800px; /* Adjusted height */
        overflow: hidden;
        border: solid rgba(0, 0, 0, 0.1);
        position: relative;
    }
    #homeCarousel #homeCarouselWrap {
        display: flex;
        position: absolute;
        animation: move 55s linear infinite;
    }
    #homeCarousel #homeCarouselWrap>img {
        flex-shrink: 0;
        width: 400px;
        height: 300px; /* Adjusted height */
        cursor: pointer;
    }
    @keyframes move {
        0% {
            transform: translateX(0);
        }
        100% {
            transform: translateX(-2400px); /* 6 images * 400px width */
        }
    }
    #homeCarousel #homeCarouselWrap:hover {
        animation-play-state: paused;
    }
    #modal {
        position: fixed;
        z-index: 1;
        left: 0;
        top: -100%;
        width: 100%;
        height: 100%;
        overflow: auto;
        background-color: rgba(0, 0, 0, 0.9);
        transition-duration: 0.4s;
        text-align: center;
    }
    #img2 {
        width: 75%;
        max-height: 80%;
        display: block;
        margin: 0 auto;
    }
    #closeBtn {
        position: absolute;
        top: 5%;
        right: 2.5%;
        color: white;
        font-size: 40px;
        font-weight: bold;
        cursor: pointer;
    }
    @media(max-width: 400px) {
        #closeBtn {
            top: 0;
        }
    }
</style>

<script>
    document.getElementById('homeCarousel').addEventListener('click', function(e) {
      if(e.target.tagName === 'IMG') {
        var modal = document.getElementById('modal');
        modal.style.top = '0';
        modal.style.paddingTop = '12%';
        document.getElementById('img2').src = e.target.src;
      }
    });
    
    document.getElementById('closeBtn').addEventListener('click', function() {
      var modal = document.getElementById('modal');
      modal.style.top = '-100%';
      modal.style.paddingTop = '0';
    });
</script>
