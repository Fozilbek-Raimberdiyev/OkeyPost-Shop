<template>
  <!-- HAPPY-CLIENTS-SECTION START -->
        <div class="happy-clients-section">
            <div class="container">
                <h1 class="happy-clients-title">120 000 довольных клиентов в России уже сделали свой выбор</h1>
                <p class="happy-clients-text">За последний год десятки тысяч наших клиентов заказали товары из Англии и
                    оставили 19 633 отзыва</p>
                <div class="row">
                    <div class="col-lg-4">
                        <div class="happy-clients-item">
                            <img src="@/assets/clients-1.png" alt="">
                            <h1 class="happy-clients-item-title">Больше не значит дороже</h1>
                            <p class="happy-clients-item-text">С ростом веса посылки цена за каждые 0.5 кг уменьшается в
                                прогрессии.</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="happy-clients-item">
                            <img src="@/assets/clients-2.png" alt="">
                            <h1 class="happy-clients-item-title">Быстрая обработка посылок</h1>
                            <p class="happy-clients-item-text">Посылка обрабатывается не дольше 48 часов после
                                поступления на склад.</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="happy-clients-item">
                            <img src="@/assets/clients-3.png" alt="">
                            <h1 class="happy-clients-item-title">SMS-уведомления</h1>
                            <p class="happy-clients-item-text">Отслеживайте весь процесс с помощью sms-уведомлений.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- HAPPY-SECTION-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");


    /* HAPPY-CLIENTS-SECTION START */

    .happy-clients-section {
        margin-top: 8rem;

    }
    .happy-clients-title {
        font-size: 36px;
        line-height: 40px;
        color: #1F2428;
        width: 60%;
        font-weight: 700;
    }
    .happy-clients-text {
        font-weight: 300;
        font-size: 20px;
        line-height: 36px;
        color: #1F2428;
        width: 55%;
    }
    .happy-clients-item {
        background: #FFFFFF;
        box-shadow: 0px 0px 70px rgba(138, 138, 138, 0.1);
        border-radius: 16px;
        padding: 2rem;
    }
    .happy-clients-item img {
        width: 3rem;
    }
    .happy-clients-item-title {
        margin-top: 2rem;
        font-weight: 700;
        font-size: 1.1rem;
        line-height: 10px;
        color: #1F2428;
        height: 2rem;
    }
    .happy-clients-item-text {
        font-weight: 300;
        font-size: 16px;
        line-height: 16px;
        color: #1F2428;
    }

    @media screen and (max-width: 992px) {
        .happy-clients-title {
            width: 100%;
            text-align: center;
        }
        .happy-clients-text {
            width: 100%;
            text-align: center;
        }
      }


    /* HAPPY-CLIENTS-SECTION END */

</style>