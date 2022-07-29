<template>
  <!-- FEEDBACKS-SECTION START -->
        <div class="feedbacks-section">
            <div class="container">
                <h1 class="feedbacks-section-title">Отзывы и цитаты блогеров:</h1>
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="feedbacks-section-item d-lg-flex align-items-center">
                        <div class="feedbacks-section-img">
                            <img src="@/assets/feedback-1.png" alt="">
                        </div>
                        <div class="feedbacks-section-content">
                            <h1 class="feedbacks-section-person">NIKOLAY S</h1>
                            <p class="feedbacks-section-rate">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </p>
                            <p class="feedbacks-section-feedback">Ваша доставка самая быстрая и дешёвая!!!</p>
                            <div class="feedbacks-section-date">
                                <h1 class="feedbacks-date-title">Дата:</h1>
                                <p class="feedbacks-date-value">16 Ноября 2021</p>
                            </div>
                            <div class="feedbacks-section-addres">
                                <h1 class="feedbacks-addres-title">Город:</h1>
                                <p class="feedbacks-addres-value">Санкт-Петербург</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="feedbacks-section-item d-lg-flex align-items-center justify-content-between">
                        <div class="feedbacks-section-img">
                            <img src="@/assets/feedback-2.png" alt="">
                        </div>
                        <div class="feedbacks-section-content">
                            <h1 class="feedbacks-section-person">DMITRIY D</h1>
                            <p class="feedbacks-section-rate">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </p>
                            <p class="feedbacks-section-feedback">Пуховик Levi’s c eBay. Всё приехало быстро и целым.</p>
                            <div class="feedbacks-section-date">
                                <h1 class="feedbacks-date-title">Дата:</h1>
                                <p class="feedbacks-date-value">16 Ноября 2021</p>
                            </div>
                            <div class="feedbacks-section-addres">
                                <h1 class="feedbacks-addres-title">Город:</h1>
                                <p class="feedbacks-addres-value"> Москва</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="feedbacks-section-item d-lg-flex align-items-center justify-content-between">
                        <div class="feedbacks-section-img">
                            <img src="@/assets/feedback-3.png" alt="">
                        </div>
                        <div class="feedbacks-section-content">
                            <h1 class="feedbacks-section-person">VLADIMIR E</h1>
                            <p class="feedbacks-section-rate">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </p>
                            <p class="feedbacks-section-feedback">Огонь, как всегда! Отдельное спасибо за доп.упаковку, часики от Apple пришли в простом бумажном пакете )</p>
                            <div class="feedbacks-section-date">
                                <h1 class="feedbacks-date-title">Дата:</h1>
                                <p class="feedbacks-date-value">16 Ноября 2021</p>
                            </div>
                            <div class="feedbacks-section-addres">
                                <h1 class="feedbacks-addres-title">Город:</h1>
                                <p class="feedbacks-addres-value">Санкт-Петербург</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="feedbacks-section-item d-lg-flex align-items-center justify-content-between">
                        <div class="feedbacks-section-img">
                            <img src="@/assets/feedback-4.png" alt="">
                        </div>
                        <div class="feedbacks-section-content">
                            <h1 class="feedbacks-section-person">Оксана</h1>
                            <p class="feedbacks-section-rate">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </p>
                            <p class="feedbacks-section-feedback">Очень быстро, надежно! Как всегда большое спасибо за работу!</p>
                            <div class="feedbacks-section-date">
                                <h1 class="feedbacks-date-title">Дата:</h1>
                                <p class="feedbacks-date-value">16 Ноября 2021</p>
                            </div>
                            <div class="feedbacks-section-addres">
                                <h1 class="feedbacks-addres-title">Город:</h1>
                                <p class="feedbacks-addres-value">Odintsovo</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <button class="feedbacks-section-btn btn">Все отзывы</button>
            </div>
        </div>
        <!-- FEEDBACKS-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");


 /* FEEDBACKS-SECTION START */
    .feedbacks-section {
        margin-top: 5rem;
    }

    .feedbacks-section-title {
        font-weight: 800;
        font-size: 36px;
        color: #1F2428;
        margin-bottom: 3rem;
    }
    .feedbacks-section-item {
        background: #FFFFFF;
        box-shadow: 0px 0px 70px rgba(138, 138, 138, 0.1);
        border-radius: 16px;
        margin: 1rem;
    }
    .feedbacks-section-content {
        padding: 1rem 2rem;
    }
    .feedbacks-section-person {
        font-size: 18px;
        color: #1F2428;
        font-weight: 700;
    }
    .feedbacks-section-rate i {
        color: #FFA009;;
    }
    .feedbacks-section-feedback {
        font-weight: 300;
        font-size: 16px;
        color: #1F2428;
        margin-bottom: 3.5rem;
        height: 5rem;
        line-height: 1.2rem;
    }
    .feedbacks-section-date {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .feedbacks-date-title {
        font-weight: 700;
        font-size: 14px;
        color: #1F2428;
        
    }
    .feedbacks-date-value {
        font-weight: 300;
        font-size: 14px;
        color: #1F2428;
    }
    .feedbacks-section-addres {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .feedbacks-addres-title {
        font-weight: 700;
        font-size: 14px;
        color: #1F2428;
    }
    .feedbacks-addres-value {
        font-weight: 300;
        font-size: 14px;
        color: #1F2428;
    }
    .feedbacks-section-btn {
        margin-top: 3rem;
    }

    @media screen and (max-width: 768px) {
        .feedbacks-section-img {
            height: 80%;
        }
        .feedbacks-section-img img {
            width: 100%;
            height: 20rem;
        }
        .feedbacks-section-btn {
            width: 50%;
            margin: 0 auto;
            display: block;
        }
    }
    @media screen and (max-width: 450px) {
        .feedbacks-section-img img {
            width: 100%;
            height: 15rem;
        }
        .feedbacks-section-btn {
            width: 50%;
            margin: 0 auto;
            display: block;
        }
        .feedbacks-section-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
    }
    @media screen and (max-width: 350px) {
        .feedbacks-section-img img {
            width: 100%;
            height: 10rem;
        }
    }
    
    /* FEEDBACKS-SECTION END */
</style>