<template>
   <!-- SECOND-BANNER SECTION START -->
        <div class="second-banner-section">
            <div class="row g-5 align-items-center">
                <div class="col-lg-5">
                    <div class="second-banner-item">
                        <img src="@/assets/banner2.png" alt="">
                    </div>
                </div>
                <div class="col-lg-7">
                    <div class="second-banner-item">
                        <h1 class="second-banner-title">Поручите нашим мастерам шопинга оформить заказы в английских
                            магазинах и освободите время для более важных дел.</h1>
                        <p class="second-banner-text">Такой способ покупки также подойдёт, если магазин принимает только
                            английские карты.</p>
                        <button class="second-banner-btn btn">Попробовать</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- SECOND-BANNER SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");



    /* SECOND-BANNER-SECTION START */

    .second-banner-section {
        padding: 3rem;
        background: url("@/assets/fon.png");
        background-size: cover;
        border-radius: 2rem;
        margin-top: 10rem;
    }

    .second-banner-item {
        margin: 0 auto;
    }
    .second-banner-item img {
        max-width: 100%;
    }

    .second-banner-title {
        font-size: 2rem;
        font-weight: 700;
        color: #fff;
    }
    .second-banner-text {
        font-weight: 300;
        font-size: 20px;
        color: #fff;
        margin-top: 0.8rem;
    }
    .second-banner-btn {
        margin-top: 2rem;
    }
    @media screen and (max-width: 450px) {  
        .second-banner-title {
            font-size: 1.5rem;
            line-height: 1.5rem;
            text-align: center;
        }
        .second-banner-text {
            font-size: 1.2rem;
            line-height: 1.5rem;
            text-align: center;
        }
    }
    @media screen and (max-width: 768px) {
        .second-banner-title {
            font-size: 1.5rem;
            line-height: 1.5rem;
            text-align: center;
        }
        .second-banner-text {
            font-size: 1rem;
            line-height: 1.5rem;
            text-align: center;
        }
        .second-banner-btn {
            width: 100%;
            margin: 0 auto;
            display: block;
        }
        .second-banner-item img {
            width: 55%;
            margin: 0 auto;
            display: block;
        }
    }
    /* SECOND-BANNER-SECTION END */

</style>