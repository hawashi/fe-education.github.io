<template>
  <!-- courses section starts  -->

  <section class="courses" id="courses">
    <h1 class="heading">our <span>courses</span></h1>

    <carousel class="swiper" :items-to-show="3" :loops="true">
      <div class="swiper-wrapper text-left">
        <slide class="swiper-slide slide">
          <img src="images/course-1.svg" alt="" />
          <h3>web development</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>

        <slide class="swiper-slide slide">
          <img src="images/course-2.svg" alt="" />
          <h3>digital marketing</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>

        <slide class="swiper-slide slide">
          <img src="images/course-3.svg" alt="" />
          <h3>science and biology</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>

        <slide class="swiper-slide slide">
          <img src="images/course-4.svg" alt="" />
          <h3>graphic design</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>

        <slide class="swiper-slide slide">
          <img src="images/course-5.svg" alt="" />
          <h3>teaching</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>

        <slide class="swiper-slide slide">
          <img src="images/course-6.svg" alt="" />
          <h3>engineering</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique,
            repellat!
          </p>
        </slide>
      </div>
      <template #addons>
        <!-- <Navigation /> -->
        <!-- <pagination class="swiper-pagination"></pagination> -->
        <Pagination />
      </template>
    </carousel>
  </section>

  <!-- courses section ends -->
</template>

<script>
// import carousel from "vue-owl-carousel";
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination } from "vue3-carousel";

export default {
  name: "CoursesEdu",
  components: {
    Carousel,
    Slide,
    Pagination,
  },
};
</script>
