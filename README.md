<div align="center">

<style>
@keyframes slideLeft {
  0% { transform: translateX(100%); }
  100% { transform: translateX(-100%); }
}

@keyframes slideRight {
  0% { transform: translateX(-100%); }
  100% { transform: translateX(100%); }
}

.slider-left {
  white-space: nowrap;
  display: inline-block;
  animation: slideLeft 10s linear infinite;
  font-size: 24px;
  font-weight: bold;
}

.slider-right {
  white-space: nowrap;
  display: inline-block;
  animation: slideRight 10s linear infinite;
  font-size: 18px;
  color: gray;
}
</style>

<div style="overflow: hidden; width: 100%;">
  <div class="slider-left">
    Hi there, I'm Omid Habibi 👋
  </div>
</div>

<br>

<div style="overflow: hidden; width: 100%;">
  <div class="slider-right">
    Software Engineer | Full Stack Developer | AI Researcher
  </div>
</div>

</div>
