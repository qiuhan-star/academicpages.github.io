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

<style>
  .modal {
    display: none; 
    position: fixed; 
    z-index: 1; 
    left: 0;
    top: 0;
    width: 100%; 
    height: 100%; 
    overflow: auto; 
    background-color: rgba(0,0,0,0.9);
  }

  .modal-content {
    margin: 10% auto; 
    display: block; 
    width: 80%; 
    max-width: 700px;
  }

  .mySlides {
    display: none;
  }
  
  .cursor {
    cursor: pointer
  }
  
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    padding: 16px;
    margin-top: -50px;
    color: white;
    font-weight: bold;
    font-size: 20px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
  }
  
  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }
  
  .prev:hover, .next:hover {
    background-color: rgba(0,0,0,0.8);
  }
  
  /* 添加 .hover-shadow 样式 */
  .hover-shadow {
    transition: transform .3s;
  }
  
  .hover-shadow:hover {
    transform: scale(1.05);
  }
</style>

<div id="gallery">
  <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-1.PNG" onclick="openModal();currentSlide(1)" class="hover-shadow">
  <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-2.PNG" onclick="openModal();currentSlide(2)" class="hover-shadow">
  <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-3.PNG" onclick="openModal();currentSlide(3)" class="hover-shadow">
</div>

<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">

    <!-- 第一张图片的幻灯片 -->
    <div class="mySlides">
      <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-1.PNG">
    </div>

    <!-- 第二张图片的幻灯片 -->
    <div class="mySlides">
      <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-2.PNG">
    </div>

    <!-- 第三张图片的幻灯片 -->
    <div class="mySlides">
      <img src="https://raw.githubusercontent.com/qiuhan-star/hanrachelqiu.github.io/master/images/Talk-2023-12-01-3.PNG">
    </div>

    <!-- 下一张/上一张 控件 -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function openModal() {
  document.getElementById("myModal").style.display = "block";
}

function closeModal() {
  document.getElementById("myModal").style.display = "none";
}

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display
