<template>
  <section class="app-shot-one" id="screens">
    <div class="container-fluid">
      <div class="block-title text-center">
        <p>Project Screenshots</p>
        <h3>Checkout Our recent project projects</h3>
      </div><!-- /.block-title -->

      <div class="app-shot-one__carousel">
        <swiper :options="swiperOptions">

          <swiper-slide>
        <div class="item">
          <img src="/asset/recent-project/work-1..png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-2..png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-3..png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-3.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-4.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-5.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-6.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/images/recent-project/work-7.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
          <swiper-slide>
        <div class="item">
          <img src="/assets/recent-project/work-8.png" alt="Awesome Image" />
        </div><!-- /.item -->
          </swiper-slide>
        </swiper>

      </div><!-- /.app-shot-one__carousel owl-theme owl-carousel -->
    </div><!-- /.container-fluid -->
  </section>
</template>


<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'
  export default {
    name: "Screenshots",
    components: {
      Swiper,
      SwiperSlide
    },
    directives: {
      swiper: directive
    },
    data() {
      return {
        swiperOptions: {
          slidesPerView : 5,
          loop: true,
          speed: 1000,
          spaceBetween : 20,
          autoplay: {
            delay: 3000,
            disableOnInteraction: false
          },
          pagination: {
            el: '.swiper-pagination',
            type: 'bullets',
            clickable: true
          },

          // Responsive breakpoints
          breakpoints: {
            1024:{
              slidesPerView : 5
            },
            768:{
              slidesPerView : 2
            },
            640:{
              slidesPerView : 2
            },
            320:{
              slidesPerView : 1
            }
          }
        }
      }
    },
  }
</script>

<style scoped>

</style>
