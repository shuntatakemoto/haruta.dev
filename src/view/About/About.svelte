<style>
main {
  font-family: "Comic Sans MS", "Marker Felt";
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: 80px 240px 1fr 1fr 80px;
  gap: 16px;
}
main h1 {
  grid-row: 1/2;
  grid-column: 3/4;
}
.about-text {
  grid-row: 2/3;
  grid-column: 3/8;
}
.love-image {
  object-fit: cover;
  border-radius: 8%;
  margin: 0 auto;
}
.love-image1 {
  grid-row: 3/4;
  grid-column: 3/4;
}
.love-image2 {
  grid-row: 3/4;
  grid-column: 4/5;
}
.love-image3 {
  grid-row: 3/4;
  grid-column: 5/6;
}
.love-image4 {
  grid-row: 3/4;
  grid-column: 6/7;
}
.love-image5 {
  grid-row: 4/5;
  grid-column: 3/4;
}
.love-image6 {
  grid-row: 4/5;
  grid-column: 4/5;
}
.love-image7 {
  grid-row: 4/5;
  grid-column: 5/6;
}
.love-image8 {
  grid-row: 4/5;
  grid-column: 6/7;
}

@media screen and (max-width: 959px) {
  .love-image {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 8%;
    margin: 0 auto;
  }
}

@media (max-width: 480px) {
  main {
    grid-template-columns: repeat(16, 1fr);
    grid-template-rows: 80px 240px 1fr 1fr 1fr 1fr 80px;
    gap: 12px;
  }
  main h1 {
    grid-row: 1/2;
    grid-column: 2/16;
  }
  .about-text {
    grid-row: 2/3;
    grid-column: 2/16;
  }
  .love-image {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 8%;
    margin: 0 auto;
  }
  .love-image1 {
    grid-row: 3/4;
    grid-column: 2/9;
  }
  .love-image2 {
    grid-row: 3/4;
    grid-column: 9/16;
  }
  .love-image3 {
    grid-row: 4/5;
    grid-column: 2/9;
  }
  .love-image4 {
    grid-row: 4/5;
    grid-column: 9/16;
  }
  .love-image5 {
    grid-row: 5/6;
    grid-column: 2/9;
  }
  .love-image6 {
    grid-row: 5/6;
    grid-column: 9/16;
  }
  .love-image7 {
    grid-row: 6/7;
    grid-column: 2/9;
  }
  .love-image8 {
    grid-row: 6/7;
    grid-column: 9/16;
  }
}
</style>

<main>
  <h1>About</h1>
  <div class="about-text">
    <p>
      I'm haruta. A graduate student at Kagoshima University majoring in
      computer science.
    </p>
    <p>I'm interested in Web Frontend.</p>
    <p>These are the ones I love.</p>
    <p>
      (Pet dog, Chinatown, Taiwan Mixed Noodle, Curry, Crio, Yachiyoden, Hassen,
      Takakiya)
    </p>
  </div>
  <img
    src="/love-image1.png"
    width="180"
    height="180"
    alt=""
    class="love-image love-image1" />
  <img
    src="/love-image2.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image2" />
  <img
    src="/love-image3.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image3" />
  <img
    src="/love-image4.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image4" />
  <img
    src="/love-image5.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image5" />
  <img
    src="/love-image6.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image6" />
  <img
    src="/love-image7.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image7" />
  <img
    src="/love-image8.jpg"
    width="180"
    height="180"
    alt=""
    class="love-image love-image8" />
</main>
