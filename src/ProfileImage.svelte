<style>
@keyframes glitch_effect {
  0% {
    opacity: 1;
    transform: none;
  }
  33% {
    transform: none;
    filter: invert(0%);
  }
  33.3% {
    opacity: 1;
    transform: skewY(20deg) translate(8px, 6px);
    filter: invert(100%);
  }
  33.6% {
    opacity: 0;
    transform: skewY(-10deg) translate(-10px, -10px);
  }
  33.9% {
    opacity: 1;
    transform: none;
    filter: invert(0%);
  }
  41% {
    opacity: 1;
  }
  41.4% {
    opacity: 0;
  }
  41.8% {
    opacity: 1;
  }
  42.2% {
    opacity: 0;
  }
  42.6% {
    opacity: 1;
  }
  66% {
    transform: none;
    filter: invert(0%);
  }
  66.3% {
    opacity: 1;
    transform: skewX(5deg) translate(-4px, 10px);
    filter: invert(100%);
  }
  66.6% {
    opacity: 0;
    transform: skewX(-7deg) translate(4px, -6px);
  }
  66.9% {
    opacity: 1;
    transform: none;
  }
  77% {
    transform: none;
  }
  77.3% {
    transform: skewY(10deg) translate(10px, -6px);
  }
  77.6% {
    transform: skewY(-22deg) translate(-5px, 8px);
    filter: invert(100%);
  }
  77.9% {
    transform: none;
    filter: invert(0%);
  }
  100% {
    opacity: 1;
    transform: none;
    filter: invert(0%);
  }
}

.profile {
  text-align: center;
  padding: 4rem 0;
}
.glitch {
  animation: glitch_effect 1.5s infinite;
}
.profile-image {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 20%;
}
</style>

<div class="profile glitch">
  <img src="/haruta.JPG" alt="" class="profile-image" />
</div>
