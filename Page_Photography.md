---
layout: page
title: Photography
subtitle: Capturing the Beauty.
---
<section class="demo">
  <button class="next">Next</button>
  <button class="prev">Previous</button>
  <div class="container">
    <div style="display: inline-block;">
      <img src="/img/PhotoGallery/金丝桃.jpeg"/>
    </div>
    <div>
     <img src="/img/PhotoGallery/WechatIMG38.jpeg"/>
    </div>
    <div>
      <img src="/img/PhotoGallery/蜘蛛絲上的露珠.jpeg"/>
    </div>
    <div>
      <img src="/img/PhotoGallery/WechatIMG39.jpeg"/>
    </div>
  </div>
</section>

<div class="explanation">
  Life is full of beauty. All you need is the eyes to spot it!
</div>

.container {
  max-width: 400px;
  background-color: black;
  margin: 0 auto;
  text-align: center;
  position: relative;
}
.container div {
  background-color: white;
  width: 100%;
  display: inline-block;
  display: none;
}
.container img {
  width: 100%;
  height: auto;
}

button {
  position: absolute;
}

.next {
  right: 5px;
}

