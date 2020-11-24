<template>
  <div>
    <v-container id="hero">
      <v-row>
        <div class="align-self-md-center col-sm-6 col-md-4 col-12">
          <h1 class="hero-title">
            Welcome to <br /> Total Master
          </h1>
          <p class="hero-text">
            ロレム・イプサム（Lorem
            Ipsum）は、印刷・組版業界の要するにダミーテキストです。ロレム・イプサム
            は、1500年代から業界標準のダミーテキストでした。
          </p>
          <v-btn class="mb-5 primary--text" flat rounded depressed outlined large >
            <span> メールアドレスを記入 </span>
            <v-icon aria-hidden="true" class="notranslate right mdi mdi-send" style="transform: rotate(-45deg);"></v-icon>
          </v-btn>
          <br />
          <v-btn class="primary" depressed rounded large>
            <span>申し込み</span>
          </v-btn>
        </div>
        <div class="text-right col-sm-6 col-md-8 col-12">
          <img src="~/assets/img/hero.png" alt="" class="hero-image">
        </div>
      </v-row>
    </v-container>

    <v-container id="our-services">
      <div class="d-none d-lg-block">
        <img class="bg-left" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDIzLjAuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA5NDMuNyA2MTguOSIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgOTQzLjcgNjE4Ljk7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KCS5zdDB7ZmlsbDp1cmwoI1NWR0lEXzFfKTt9Cjwvc3R5bGU+CjxsaW5lYXJHcmFkaWVudCBpZD0iU1ZHSURfMV8iIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNjA5LjExODIiIHkxPSI2ODMuMTczNCIgeDI9IjM3NC44NzgyIiB5Mj0iLTIyLjYzNDgiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgLTEgMCA1MzcuOTczKSI+Cgk8c3RvcCAgb2Zmc2V0PSIwIiBzdHlsZT0ic3RvcC1jb2xvcjojRjNGN0ZGIi8+Cgk8c3RvcCAgb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojREVFRUZFIi8+CjwvbGluZWFyR3JhZGllbnQ+CjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0yNC40LDE0MS4zQzg1LjgsNzAuOCwyMDcsMTYyLDM4Mi42LDEyMkM1MzQuNyw4Ny41LDU0My40LTQuNCw2NjUsMC4yYzg4LjgsMy4zLDE4NS41LDU0LjYsMjM4LjcsMTQzLjkKCWM1OC42LDk4LjUsMzcuMywxOTguNywzMS4zLDIyMy4xYy0yNi43LDEwOS4xLTEwNiwxNjYuNy0xMzQsMTg2LjNjLTExNS4yLDgxLTI0NC42LDY2LjgtMzA2LjYsNjBDMjYxLjQsNTg3LjksMTIsNDIxLjYsMC44LDI0MC43CglDLTAuNiwyMTctMy4zLDE3My4xLDI0LjQsMTQxLjN6Ii8+Cjwvc3ZnPgo=" alt="">
      </div>
      <div class="d-none d-lg-block">
        <img class="bg-right" src="~/assets/img/vector-element.svg" alt="">
      </div>
      <h1 class="section-title">弊社のサービス</h1>
      <hr style="margin: 15px auto 30px; width: 55px; border: 2px solid black; border-radius: 5px;" >
      <p class="section-description">あなたに最適な選択をご提供します。ロレム・イプサム印刷・組版業界のダミーテキストです。ロレム・イプサムは、1500年代に無名の印刷業者が活字のゲラををスクランブルにして活字見本帳を作って以来、業界の標準的なダミーテキストとなっています。</p>
      <div class="row">
        <div class="d-flex col-sm-4 col-12">
          <v-card flat class="card" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
            <div class="card-icon">
              <img height="90" src="~/assets/img/service-search-icon.svg" alt="">
            </div>
            <div class="card-title">仕事を探す</div>
            <div class="card-description">
            今すぐ仕事を見つけます。 ロレム・イプサム
            とは、要するに印刷・組版業界のダミーテキストです。
          </div>
          </v-card>
        </div>
        <div class="d-flex col-sm-4 col-12" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
          <v-card class="card">
            <div class="card-icon">
              <img height="90" src="~/assets/img/service-job-icon.svg" alt="">
            </div>
            <div class="card-title">仕事を申し込む</div>
            <div class="card-description">
              今すぐお仕事をTotal Masterに応募できます。
              ここには多くの求人があります。
            </div>
          </v-card>
        </div>
        <div class="d-flex col-sm-4 col-12" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
          <v-card class="card">
            <div class="card-icon">
              <img height="90" src="~/assets/img/service-consult-icon.svg" alt="">
            </div>
            <div class="card-title">相談する</div>
            <div class="card-description">
              無料で信頼できる専門家と相談し、最高の助言が得られます。
            </div>
          </v-card>
        </div>
      </div>
      <div class="text-center my-10">
        <v-btn to="/services" class="font-weight-bold primary--text" depressed flat outlined rounded large>
          <span>さらに詳しく</span>
        </v-btn>
      </div>
    </v-container>

    <v-container id="about-us">
      <div class="row">
        <div class="text-right col-sm-6 col-12">
          <img class="about-us-image" src="~/assets/img/construction-company.png" alt="">
        </div>
        <div class="align-self-md-center d-flex justify-end col-sm-6 col-12">
          <div class="brief-about-us">
            <h1 class="about-us-title">企業情報</h1>
            <hr style="margin: 15px 0px 30px; width: 55px; border: 2px solid black; border-radius: 5px;">
            <p class="about-us-description">
              あなたに最適な選択をご提供します。ロレム・イプサム印刷・組版業界のダミーテキストです。ロレム・イプサムは、1500年代に無名の印刷業者が活字のゲラををスクランブルにして活字見本帳を作って以来、業界の標準的なダミーテキストとなっています。
            </p>
            <v-btn to="/company-about-us" depressed flat outlined rounded large class="primary--text">
              <span>さらに詳しく</span>
            </v-btn>
          </div>
        </div>
      </div>
    </v-container>

    <v-container id="benefits">
      <div class="benefits-intro">
        <div class="d-none d-lg-block">
          <img class="bg-left" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDIzLjAuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA5NDMuNyA2MTguOSIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgOTQzLjcgNjE4Ljk7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KCS5zdDB7ZmlsbDp1cmwoI1NWR0lEXzFfKTt9Cjwvc3R5bGU+CjxsaW5lYXJHcmFkaWVudCBpZD0iU1ZHSURfMV8iIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNjA5LjExODIiIHkxPSI2ODMuMTczNCIgeDI9IjM3NC44NzgyIiB5Mj0iLTIyLjYzNDgiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgLTEgMCA1MzcuOTczKSI+Cgk8c3RvcCAgb2Zmc2V0PSIwIiBzdHlsZT0ic3RvcC1jb2xvcjojRjNGN0ZGIi8+Cgk8c3RvcCAgb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojREVFRUZFIi8+CjwvbGluZWFyR3JhZGllbnQ+CjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik0yNC40LDE0MS4zQzg1LjgsNzAuOCwyMDcsMTYyLDM4Mi42LDEyMkM1MzQuNyw4Ny41LDU0My40LTQuNCw2NjUsMC4yYzg4LjgsMy4zLDE4NS41LDU0LjYsMjM4LjcsMTQzLjkKCWM1OC42LDk4LjUsMzcuMywxOTguNywzMS4zLDIyMy4xYy0yNi43LDEwOS4xLTEwNiwxNjYuNy0xMzQsMTg2LjNjLTExNS4yLDgxLTI0NC42LDY2LjgtMzA2LjYsNjBDMjYxLjQsNTg3LjksMTIsNDIxLjYsMC44LDI0MC43CglDLTAuNiwyMTctMy4zLDE3My4xLDI0LjQsMTQxLjN6Ii8+Cjwvc3ZnPgo=" alt="">
        </div>
        <div class="d-none d-lg-block">
          <img class="bg-right" src="~/assets/img/vector-element.svg" alt="">
        </div>
        <h1 class="section-title">Benefits</h1>
        <hr style="margin: 15px auto 30px; width: 55px; border: 2px soild black; border-radius: 5px;" >
        <p class="section-description">
          あなたに最適な選択をご提供します。ロレム・イプサム印刷・組版業界のダミーテキストです。ロレム・イプサムは、1500年代に無名の印刷業者が活字のゲラををスクランブルにして活字見本帳を作って以来、業界の標準的なダミーテキストとなっています。
        </p>
      
        <div class="row">
          <div class="d-flex col-sm-4 col-12">
            <v-card class="card">
              <div class="card-icon">
                <img height="90" src="~/assets/img/service-search-icon.svg" alt="">
              </div>
              <div class="card-title">Quick Job Matching</div>
              <div class="card-description">
                今すぐ仕事を見つけます。 ロレム・イプサム
                とは、要するに印刷・組版業界のダミーテキストです。
              </div>
            </v-card>
          </div>
          <div class="d-flex col-sm-4 col-12">
            <v-card class="card">
              <div class="card-icon">
                <img height="90" src="~/assets/img/service-job-icon.svg" alt="">
              </div>
              <div class="card-title">履歴書を無料でホスト</div>
              <div class="card-description">
                今すぐ仕事を見つけます。 ロレム・イプサム
                とは、要するに印刷・組版業界のダミーテキストです。
              </div>
            </v-card>
          </div>
          <div class="d-flex col-sm-4 col-12">
            <v-card class="card">
              <div class="card-icon">
                <img height="90" src="~/assets/img/service-consult-icon.svg" alt="">
              </div>
              <div class="card-title">リモートオンライン面接</div>
              <div class="card-description">
                今すぐ仕事を見つけます。 ロレム・イプサム
                とは、要するに印刷・組版業界のダミーテキストです。
              </div>
            </v-card>
          </div>
        </div>
        <div class="text-center my-10">
          <v-btn class="font-weight-bold primary--text" depressed flat outlined rounded large to="/benefits">
              <span>さらに詳しく</span>
          </v-btn>
        </div>
      </div>
      <div id="customer-voice" class="pt-3">
        <div v-swiper:mySwiper="swiperOption" style="margin-bottom: 50px">
          <div class="swiper-wrapper">
            <div class="swiper-slide" style="width: 1161px; margin-right: 20px">
              <v-card class="slide-card">
                <h2 class="slide-title">建設エンジニアから</h2>
                <hr class="title-underline">
                <div class="row">
                  <div class="pa-0 col-sm-6 col-12">
                    <div class="slide-profile">
                      <div class="slide-avatar">
                        <v-img style="width: 100%" src="https://avataaars.io/?avatarStyle=Transparent&topType=LongHairCurvy&accessoriesType=Round&hairColor=Black&facialHairType=Blank&clotheType=BlazerShirt&eyeType=Happy&eyebrowType=Default&mouthType=Smile&skinColor=Light" />
                      </div>
                      <div class="customer-info">
                        <div class="customer-name">Name</div>
                        <div class="customer-position">Position</div>
                      </div>
                    </div>
                  </div>
                  <div class="pa-0 align-self-center col-sm-6 col-12">
                    <div class="customer-said">
                      <p>
                        「Total
                        Masterは、建設技術者として自分が情熱を注ぐ適切で高賃金の仕事を見つけるのに役立つプラットフォームです。」
                      </p>
                    </div>
                  </div>
                </div>
              </v-card>
            </div>
          </div>
          <div class="swiper-pagination swiper-pagination-bullets swiper-pagination-clickable swiper-pagination-bullets-dynamic" style="width: 80px">
            <span class="swiper-pagination-bullets" tapindex="0" role="button" aria-label="Go to slide 1"></span>
          </div>
          <div class="swiper-button-prev" tabindex="0" role="button" aria-label="Previous slide"></div>
          <div class="swiper-button-next" tabindex="0" role="button" aria-label="Next slide"></div>
        </div>

        swiper
      </div>
    </v-container>
  
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'
import { swiper, swiperSlide } from 'vue-awesome-swiper'

export default {
  data () {
    return {
      banners: [ '~/assets/img/service-consult-icon.svg', '~/assets/img/service-job-icon.svg', '~/assets/img/service-search-icon.svg' ],
      swiperOption: {
        pagination: {
          el: '.swiper-pagination'
        },
        // some swiper options...
      }
    }
  },
  mounted() {
    setTimeout(() => {
      this.banners.push('~/assets/img/hero.png')
      console.log('banners update')
    }, 3000)
    console.log(
      'This is current swiper instance object', this.mySwiper, 
      'It will slideTo banners 3')
    this.mySwiper.slideTo(3, 1000, false)
  },
  components: {
    // Logo,
    // VuetifyLogo
    swiper,
    swiperSlide
  },
}
</script>

<style lang="stylus">
.hero-title{
    font-size: 48px;
    font-weight: 700;
}

.hero-image {
    width: 100%;
    height: auto;
}

@media only screen and (min-width: 960px)
  .hero-image {
     width: auto;
      height: 400px;
  }

#our-services {
    margin-top: 50px;
    margin-bottom: 50px;
    position: relative;
}

.bg-left{
    position: absolute;
    height: 650px;
    top: 165px;
    left: -495px;
}

.bg-right {
    position: absolute;
    right: -40px;
    bottom: 100px;
}

.section-title {
    font-size: 24px;
    font-weight: 700;
    text-align: center;
}

@media only screen and (min-width: 600px)
  .section-title {
    font-size: 36px;
  }

.section-description {
    max-width: 950px;
    color: #7d7987;
    margin: 0 auto;
    font-size: 16px;
    text-align: center;
}

@media only screen and (min-width: 600px)
 .section-description {
    font-size: 18px;
    margin-bottom: 50px;
  }

.card {
    border-radius: 20px;
    padding: 15px;
    box-shadow: 10px 40px 50px rgba(229,233,246,.4)!important;
}

.card .card-title {
    color: #000;
    font-size: 24px;
    line-height: 56px;
    font-weight: 700;
}

.card .card-icon {
    text-align: left;
}

.card .card-description {
    font-size: 16px;
}

@media only screen and (min-width: 600px)
  .card {
    padding: 40px;
  }

#about-us {
    margin-top: 100px;
    margin-bottom: 50px;
    position: relative;
}

@media only screen and (min-width: 960px)
  #about-us {
    padding-top: 50px;
    padding-bottom: 50px;
  }

.about-us-image {
    width: 100%;
    height: auto;
}

@media only screen and (min-width: 960px)
  .about-us-image {
    width: auto;
    height: 400px;
  }

@media only screen and (min-width: 960px)
  #about-us {
    padding-top: 50px;
    padding-bottom: 50px;
  }

@media only screen and (min-width: 960px)
  #about-us .about-us-image {
    width: auto;
    height: 400px;
  }

 @media only screen and (min-width: 960px)
  #about-us .brief-about-us {
    max-width: 450px;
  } 

@media only screen and (min-width: 960px)
  #about-us .about-us-title {
    font-size: 36px;
  }

.benefits-intro {
    position: relative;
}

.slide-card {
    padding: 60px;
    border-radius: 24px;
    background: linear-gradient(191.49deg,#67c3f3 9.05%,#5a98f2 76.74%);
}

@media only screen and (min-width: 600px)
  .slide-card {
    padding: 60px;
  }

.slide-card .slide-title {
    text-align: center;
    font-size: 24px;
    font-weight: 700;
    color: #fff;
}

@media only screen and (min-width: 600px)
  .slide-card .slide-title {
    text-align: left;
    font-size: 36px;
}

.title-underline {
    margin: 15px 0 30px;
    width: 55px;
    border: 2px solid #fff;
    border-radius: 5px;
}

.slide-profile {
    display: flex;
    flex-flow: row;
}

.slide-avatar {
    overflow: hidden;
    align-self: center;
    width: 140px;
    height: 140px;
    margin-bottom: 15px;
    border-radius: 50%;
    box-shadow: 0 0 0 5px #fff;
    background-color: #65c9ff;
}

@media only screen and (min-width: 600px)
  .slide-card .slide-profile .slide-avatar {
    overflow: hidden;
    width: 140px;
    height: 140px;
    margin-right: 28px;
}

.customer-info {
    color: #fff;
    align-self: center;
}

.slide-card .slide-profile .customer-info {
    color: #fff;
    align-self: center;
}

@media only screen and (min-width: 600px)
  .slide-card .slide-profile .customer-info {
    color: #fff;
    align-self: center;
}

.slide-card .slide-profile .customer-info .customer-name {
    font-size: 24px;
}

@media only screen and (min-width: 600px)
  .slide-card .slide-profile .customer-info .customer-name {
    font-size: 24px;
}

.slide-card .slide-profile .customer-info .customer-position {
    font-size: 18px;
}

@media only screen and (min-width: 600px)
  .slide-card .customer-said, .slide-card .slide-profile .customer-info .customer-position {
    font-size: 18px;
}

.slide-card .customer-said {
    font-size: 16px;
    color: #fff;
}

@media only screen and (min-width: 600px)
  .slide-card .customer-said, .slide-card .slide-profile .customer-info .customer-position {
    font-size: 18px;
  };

.swiper-button-next, .swiper-button-prev {
    position: absolute;
    top: 50%;
    width: 27px;
    height: 44px;
    margin-top: -22px;
    z-index: 10;
    cursor: pointer;
    background-size: 27px 44px;
    background-position: 50%;
    background-repeat: no-repeat;
}


</style>