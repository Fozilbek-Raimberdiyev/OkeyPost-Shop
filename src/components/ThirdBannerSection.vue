<template>
   <!-- THIRD-BANNER-SECTION START -->
        <div class="third-banner-section">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-5">
                        <div class="third-banner-left-item">
                            <img src="@/assets/third-banner.png" alt="">
                        </div>
                    </div>
                    <div class="col-lg-7">
                        <div class="third-banner-right-item">
                            <h1 class="third-banner-right-item-title">Виртуальный тур по нашему складу в реальном
                                времени</h1>
                            <p class="third-banner-right-item-text">Вы можете всегда посмотреть на нашу слаженую работу
                                на складе</p>
                            <button class="third-banner-right-item-btn btn">Попробовать</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- THIRD-BANNER-SECTION END -->
</template>

<script>
export default {

}
</script>

<style> 
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");




    /* THIRD-BANNER-SECTION START */

.third-banner-section {
    background: url("@/assets/fon.png");
    background-size: cover;
    border-radius: 2rem;
    margin-top: 8rem;
}
.third-banner-left-item {
    margin-top: 2rem;
    margin-bottom: 1rem;
}
.third-banner-left-item img {
    width: 100%;
    height: 100%;
}
.third-banner-right-item {
    margin-top: 3rem;
    margin-bottom: 2rem;
}
.third-banner-right-item-title {
    font-weight: 800;
    font-size: 2.8rem;
    line-height: 56px;
    color: #FFFFFF;
}
.third-banner-right-item-text {
    margin-top: 1.3rem;
    font-weight: 400;
    font-size: 1.1rem;
    line-height: 30px;
    color: #FFFFFF;
}
.third-banner-right-item-btn {
    margin-bottom: 1rem;
}
@media screen and (max-width: 992px) {
    .third-banner-right-item-title {
        width: 100%;
        text-align: center;
        font-size: 2rem;
        line-height: 2rem;
    }
    .third-banner-right-item-text {
        line-height: 1rem;
        font-weight: 300;
        text-align: center;
    }
    .third-banner-right-item-btn {
        width: 50%;
        display: inline-block;
        display: block;
        margin: 0 auto;
    }
}
    /* THIRD-BANNER-SECTION END */

</style>