<template>
  <div class="wrapper">
    <!-- HEADER SECTION START -->
        <header class="header">
            <div class="container">
                <nav class="navbar navbar-expand-lg bg-light fixed-top">
                    <div class="container-fluid">
                      <a class="navbar-brand my-logo" href="#">
                          <img src="@/assets/logo.png" alt="">
                      </a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span><i class="fa-solid fa-bars"></i></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav ms-auto mb-2 mb-lg-0 align-items-center">
                          <li class="nav-item my-nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Как покупать</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Распродажи</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Цены</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Помощь</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Бонусы</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Блог</a>
                          </li>
                          <li class="nav-item my-nav-item">
                            <a class="nav-link" href="#">Магазины</a>
                          </li>
                          <ul class="header-contact-menu d-lg-flex p-0 align-items-center ">
                              <li><a href="#">
                                  <img src="@/assets/sign.png" alt="sign">
                              </a></li>
                              <li><a class="btn-1 btn" href="#">Связаться с нами</a></li>
                          </ul>
                        </ul>
                      </div>
                    </div>
                  </nav>
            </div>
        </header>

          <!-- HEADER-MENU RESPONSIVE START -->
        <div class="offcanvas offcanvas-start" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasWithBothOptionsLabel">Backdrop with scrolling</h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <p>Try scrolling the rest of the page to see this option in action.</p>
            </div>
          </div>
        <!-- HEADER-MENU RESPONSIVE END -->
        
        <!-- HEADER SECTION END -->

         <!-- BANNER SECTION START -->
        <div class="banner">
            <div class="container">
                <div class="row align-items-center gx-5">
                    <div class="col-sm-6">
                        <div class="first-banner-left">
                            <h1 class="first-banner-title">Доставка товаров из Великобритании в Россию</h1>
                            <p class="firsr-banner-text">Начните экономить до 80% на шопинге. Регистрируйтесь в
                                OkeyPost, чтобы покупать со скидками в UK одежду, обувь, гаджеты известных брендов и
                                безопасно отправлять вещи в Россию.
                            </p>
                            <button class="firts-banner-btn btn">Получить адрес в UK</button>
                        </div>
                    </div>
                    <div class="col-sm-5">
                        <div class="first-banner-right">
                            <div class="first-banner-img text-end">
                                <img src="@/assets/illustration.png" alt="banner-img">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- BANNER SECTION END -->

        <!-- TAB-SECTION START -->
        <TabSection></TabSection>
        <!-- TAB-SECTION End -->

        <!-- AdvantageSection START -->
        <AdvantageSection></AdvantageSection>
        <!-- AdvantageSection -->

        <!-- SecondBanner START -->
        <SecondBanner></SecondBanner>
        <!-- SecondBanner -->

        <!-- DeliverySection START -->
        <DeliverySection></DeliverySection>
        <!-- DeliverySection -->

        <!-- FourStepSection START -->
        <FourStepSection></FourStepSection>
        <!-- FourStepSection -->

        <!-- ThirdBannerSection START -->
        <ThirdBannerSection></ThirdBannerSection>
        <!-- ThirdBannerSection -->

        <!-- HappyClientSection START -->
        <HappyClientSection></HappyClientSection>
        <!-- HappyClientSection -->

        <!-- FeedbackSection START -->
        <FeedbackSection></FeedbackSection>
        <!-- FeedbackSection -->

         <!-- YourAdresSection START -->
        <YourAdresSection></YourAdresSection>
        <!-- YourAdresSection -->

         <!-- SubscribeSection START -->
        <SubscribeSection></SubscribeSection>
        <!-- SubscribeSection -->

        <!-- FooterSection START -->
        <FooterSection></FooterSection>
        <!-- FooterSection -->


  </div>
</template>

<script>
import TabSection from "@/components/TabSection"
import AdvantageSection from "@/components/AdvantageSection"
import SecondBanner from "@/components/SeconBanner.vue"
import DeliverySection from "@/components/DeliverySection.vue"
import FourStepSection from "@/components/FourStepSection.vue"
import ThirdBannerSection from "@/components/ThirdBannerSection.vue"
import HappyClientSection from "@/components/HappyClientSection.vue"
import FeedbackSection from "@/components/FeedbackSection.vue"
import YourAdresSection from "@/components/YourAdresSection.vue"
import SubscribeSection from "@/components/SubscribeSection.vue" 
import FooterSection from "@/components/FooterSection.vue"



export default {
  components: {
    TabSection,
    AdvantageSection,
    SecondBanner,
    DeliverySection,
    FourStepSection,
    ThirdBannerSection,
    HappyClientSection,
    FeedbackSection,
    YourAdresSection,
    SubscribeSection,
    FooterSection
  }
}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    user-select: none;
}


.wrapper {
    width: 95%;
    margin: 0 auto;
    color: #2c3e50;
    margin-top: 60px;
    font-family: "Gilroy";
    overflow-x: hidden;
}
.btn {
    background: linear-gradient(90deg, #00C97B 0%, #00D981 96.96%);
    box-shadow: 0px 4px 4px rgba(1, 203, 124, 0.2);
    border-radius: 36px;
    color: #fff;
    margin-left: 0.5rem;
}


/* HEADER STYLES START */
.container-fluid {
    display: flex;
}
.nav-link {
    color: #000;
    font-weight: 500;
}
.header-contact-menu {
    list-style: none;
}
.header-contact-menu a {
    text-decoration: none;
    color: #fff;
    display: inline-block;
    margin: 0 1rem;
}


/* HEADER STYLES END */



/* FIRST-BANNER STYLES */

.banner {
    margin-top: 4rem;
    background: url("@/assets/fon.png");
    background-size: cover;
    border-radius: 2rem;
    padding: 3.5rem;
}
.first-banner-left {
    margin: 1rem 0;
}
.first-banner-right {
    margin: 1rem 0;
}

.first-banner-title {
    font-weight: 800;
    color: #fff;
}
.firsr-banner-text {
    font-weight: 300;
    font-size: 20px;
    color: #fff;
    margin-top: 0.5rem;
}
.firts-banner-btn {
    margin-top: 2.25rem;
}

.first-banner-img img {
    max-width: 100%;
}
@media screen and (max-width: 450px) { 
    .first-banner-title {
        font-size: 1.5rem;
        width: 100%;
        line-height: 1.5rem;
    }
    .firsr-banner-text {
        font-size: 1rem;
        line-height: 1.3rem;
    }
}
@media screen and (max-width: 992px) {
    .first-banner-title {
        font-size: 2rem;
        width: 100%;
        line-height: 2rem;
    }
    .firsr-banner-text {
        font-size: 0.8rem;
        line-height: 1.5rem;
    }
}
@media screen and (max-width: 620px) {
    .firts-banner-btn {
        max-width: 120%;
        display: block;
        margin: 0 auto;
    }
}

/* FIRST-BANNER STYLES END */

</style>
