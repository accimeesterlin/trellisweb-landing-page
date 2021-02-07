<template>
  <section class="banner-one" id="home">

    <img src="/assets/images/shapes/banner-shape-1-1.png" class="banner-one__bg-shape-1" alt="">
    <div class="banner-one__bg">

    </div><!-- /.banner-one__bg -->
    <div class="container">
      <!-- <a href="https://www.youtube.com/watch?v=Kl5B6MBAntI" class="mediabox banner-one__video video-popup"><i
        class="fa fa-play"></i></a>/.banner-one__video -->
      <div class="banner-one__moc">
        <img src="/assets/images/browser.svg" class="wow fadeInUp"
             data-wow-duration="1500ms" alt="">
      </div><!-- /.banner-one__moc -->
      <div class="row">
        <div class="col-lg-7">
          <div class="banner-one__content">
            <div class="mc-form__response"></div><!-- /.mc-form__response -->
            <h3>We build, enhance and elevate your software.</h3>
            <p>We’re your software development partner.</p>
            <a href="#" class="thm-btn banner-one__btn"><span>Discover More</span></a>
            <!-- /.thm-btn banner-one__btn -->
          </div><!-- /.banner-one__content -->
        </div><!-- /.col-lg-7 -->
      </div><!-- /.row -->
    </div><!-- /.container -->
  </section>
</template>

<script>

    export default {
      name: "Banner",
      mounted() {
        MediaBox('.mediabox', { rel: '0' });
      }

    }
</script>

<style scoped>

</style>
