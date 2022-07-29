<template>
  <!-- FOUR-STEP-SECTION START -->
        <div class="four-step-section">
            <div class="container">
                <h1 class="four-step-headtitle">4 простых шага для ваших покупок в Великобритании </h1>
                <div class="row">
                    <div class="col">
                        <div class="four-step-item">
                            <img src="@/assets/four-step-1.png" alt="">
                            <h1 class="four-step-title">вы ВЫБИРАЕТЕ ТОВАР</h1>
                            <p class="four-step-text">в английском магазине, оплачиваете и указываете адрес склада
                                OkeyPost</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="four-step-item">
                            <img src="@/assets/four-step-2.png" alt="">
                            <h1 class="four-step-title">ПОКУПКИ ПРИХОДЯТ НА СКЛАД</h1>
                            <p class="four-step-text">и появляются в вашем личном кабинете на нашем сайте</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="four-step-item">
                            <img src="@/assets/four-step-3.png" alt="">
                            <h1 class="four-step-title">ОТПРАВЛЯЕМ ИХ К ВАМ ДОМОЙ</h1>
                            <p class="four-step-text">в надежной упаковке, по выгодной цене и очень быстро</p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="four-step-item">
                            <img src="@/assets/four-step-4.png" alt="">
                            <h1 class="four-step-title">ЗАБИРАЕТЕ
                                свою ПОСЫЛКУ</h1>
                            <p class="four-step-text">в пункте выдачи, на почте или с курьером</p>
                        </div>
                    </div>
                </div>
                <h3 class="four-step-subtitle">Не хотите разбираться самостоятельно, наши мастера шопинга с радостью
                    купят все товары за вас.</h3>
                <button class="four-step-btn btn">Быстрая покупка</button>
            </div>
        </div>
        <!-- FOUR-STEP-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");

  /* FOUR-STEP-SECTION START */
    .four-step-section {
        margin-top: 13rem;
    }
    .four-step-headtitle {
        font-size: 3rem;
        line-height: 3rem;
        color: #1F2428;
        font-weight: 700;
        width: 50%;
        margin-top: 14px;
    }
    @media screen and (max-width: 768px) {
        .four-step-headtitle {
            width: 100%;
            font-size: 1.8rem;
            line-height: 2rem;
            margin: 0 auto;
            text-align: center;
        }
        .four-step-text {
            width: 100%;
            padding: 0;
            margin: 0;
        }
        .four-step-item {
            margin: 0 auto;
        }
        .four-step-title {
            font-size: 22px;
            width: 100% !important;
            display: block;
            margin: 0 auto;
            text-align: center;
        }
        .four-step-title {
            width: 100%;
        }
        .four-step-subtitle {
            display: block;
            width: 100% !important;
            margin: 0 auto;
            text-align: center;
        }
        .four-step-btn {
            width: 50%;
            margin: 0 auto;
            display: block;
        }
    }
    @media screen and (max-width: 576px) {
        .four-step-item {
            width: 90%;
        }
        .four-step-text {
            width: 90%;
            padding: 0;
            margin: 0;
            font-size: 0.8rem;
        }
    }
    .four-step-title {
        font-weight: 700;
        font-size: 20px;
        line-height: 24px;
        text-transform: uppercase;
        color: #1F2428;
        height: 50px;
        width: 80%;
    }
    .four-step-item {
        width: 250px;
    }
    .four-step-item img {
        width: 100%;
    }
    .four-step-text {
        font-size: 14px;
        line-height: 30px;
        color: #1F2428;
    }
    .four-step-subtitle {
        font-size: 20px;
        line-height: 1.5rem;
        color: #1F2428;
        width: 65%;
        margin-top: 1.8rem;
    }
    .four-step-btn {
        margin-top: 2rem;
    }
    /* FOUR-STEP-SECTION END */


</style>