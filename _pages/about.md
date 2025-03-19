---
permalink: /about/
title: ""
---
## About Me
Hi, I'm **Mees Lindhout**, 24 years old, and I have a background in Aviation Operations (*BSc*) and Digital Driven Business (*MSc*). I live in the center of the Netherlands and I'm passionate about new technology and aviation. I enjoy being outside in nature and I love to travel and explore new places. Want to connect? Feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/meeslindhout/). I'm always looking for new opportunities to learn and grow :wink:. 

## Hobbies
In my free time, I enjoy a variety of hobbies. Here are a few of my favorites:  
:rowboat: Rowing  
:running: Running  
:camera_flash: Photography  

### A Glimpse of My Travel Photography
<div class="slideshow-container">
  <div class="slide">
    <img src="/assets/images/photo_slider_about/01_Japan.jpg" alt="Photo 1" style="width:100%">
    <div class="text-overlay">Osaka, Japan 1 | 4</div>
  </div>
  <div class="slide">
    <img src="/assets/images/photo_slider_about/02_Vancouver.jpg" alt="Photo 2" style="width:100%">
    <div class="text-overlay">Vancouver Library Square 2 | 4</div>
  </div>
  <div class="slide">
    <img src="/assets/images/photo_slider_about/03_Aviation.jpg" alt="Photo 3" style="width:100%">
    <div class="text-overlay">WestJet Hangar at Calgary Airport 3 | 4</div>
  </div>
  <div class="slide">
    <img src="/assets/images/photo_slider_about/04_Austria.jpg" alt="Photo 4" style="width:100%">
    <div class="text-overlay">Badgastein valley in Austria 4 | 4</div>
  </div>
</div>
Explore a selection of moments captured on my journeys around the globe.  
{: .text-center}

<style>
.slideshow-container {
  position: relative;
  max-width: 100%;
  margin: auto;
  overflow: hidden;
}

.slide {
  display: none;
  position: relative;
}

.text-overlay {
  position: absolute;
  bottom: 5%;
  left: 50%;
  transform: translateX(-50%);
  background-color: rgba(0, 0, 0, 0.5);
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  font-size: 16px;
}

.fade {
  animation: fadeEffect 3s infinite;
}

@keyframes fadeEffect {
  0%, 100% { opacity: 0; }
  50% { opacity: 1; }
}
</style>

<script>
let currentSlide = 0;
const slides = document.querySelectorAll(".slide");

function showSlides() {
  slides.forEach((slide, index) => {
    slide.style.display = index === currentSlide ? "block" : "none";
  });
}

function changeSlide(direction) {
  currentSlide = (currentSlide + direction + slides.length) % slides.length;
  showSlides();
}

// Automatically change slides every 3 seconds
setInterval(() => changeSlide(1), 3000);

// Show the first slide initially
showSlides();
</script>
