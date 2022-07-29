<template>
   <!-- DELIVERY-SECTION START -->
        <div class="delivery-section">
            <div class="container">
                <div class="row">
                    <div class="col">
                        <div class="delivery-information">
                            <h1 class="delivery-title">OkeyPost удобная и быстрая доставка посылок из Великобритании
                            </h1>
                            <p class="delivery-text">OkeyPost удобная и быстрая доставка посылок из Великобритании </p>
                        </div>
                    </div>
                    <!-- <div class="col-6"></div> -->
                </div>
                <div class="delivery-select-section">
                    <div class="row">
                        <div class="col">
                            <div class="delivery-select-item">
                                <h1 class="delivery-select-title">Страна:</h1>
                                <div class="delivery-select-field">

                                    <select name="" id="">
                                        <option value="rus">Россия</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="delivery-select-item">
                                <h1 class="delivery-select-title">Город:</h1>
                                <div class="delivery-select-field">

                                    <input type="text" placeholder="Москва">
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="delivery-select-item">
                                <h1 class="delivery-select-title">Индекс:</h1>
                                <div class="delivery-select-field">

                                    <input type="text" placeholder="Введите индекс">
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="delivery-select-item">
                                <h1 class="delivery-select-title">Вес посылки:</h1>
                                <div class="delivery-select-field">

                                    <input type="text" placeholder="0,5">
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="delivery-select-item">
                                <h1 class="delivery-select-title">Дополнительные услуги:</h1>
                                <div class="delivery-select-field">

                                    <select name="" id="">
                                        <option value="choose">Выберите услуги</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                    </div>
                    <button class="delivery-select-btn btn">Рассчитать</button>
                </div>
                <div class="delivery-type">
                    <!-- <h1 class="delivery-type-headtitle">Варианты доставки:</h1> -->
                    <p class="delivery-type-top-title">Варианты доставки:</p>
                    <div class="delivery-type-items">
                        <div class="delivery-type-item d-md-flex align-items-center">
                            <div class="delivery-type-name">
                                <img src="@/assets/delivery-type-1.png" alt="">
                                <h1 class="delivery-type-title">Почта России</h1>
                            </div>
                            <div class="delivery-type-term d-flex justify-content-between flex-md-column">
                                <h1 class="term-title">Сроки:</h1>
                                <p class="term-days">10-14 дней</p>
                            </div>
                            <div class="delivery-type-price d-flex justify-content-between flex-md-column">
                                <h1 class="price-title">Стоимость доставки:</h1>
                                <p class="price-money">от £27.00</p>
                            </div>
                            <div class="delivery-type-total d-flex justify-content-between flex-md-column">
                                <h1 class="total-title">Итого:</h1>
                                <p class="total-money">£41.99</p>
                            </div>
                        </div>
                        <div class="delivery-type-item d-md-flex align-items-center">
                            <div class="delivery-type-name">
                                <img src="@/assets/delivery-type-2.png" alt="">
                                <h1 class="delivery-type-title">EMS ПОЧТА РОССИЯ</h1>
                            </div>
                            <div class="delivery-type-term d-flex justify-content-between flex-md-column">
                                <h1 class="term-title">Сроки:</h1>
                                <p class="term-days">9-12 дней</p>
                            </div>
                            <div class="delivery-type-price d-flex justify-content-between flex-md-column">
                                <h1 class="price-title">Стоимость доставки:</h1>
                                <p class="price-money">от £40.00</p>
                            </div>
                            <div class="delivery-type-total d-flex justify-content-between flex-md-column">
                                <h1 class="total-title">Итого:</h1>
                                <p class="total-money">£54.55</p>
                            </div>
                        </div>
                        <div class="delivery-type-item d-md-flex align-items-center">
                            <div class="delivery-type-name">
                                <img src="@/assets/delivery-type-3.png" alt="">
                                <h1 class="delivery-type-title">ПОЧТА РОССИИ МЕЛКИЕ ПАКЕТЫ</h1>
                            </div>
                            <div class="delivery-type-term d-flex justify-content-between flex-md-column">
                                <h1 class="term-title  d-flex justify-content-between flex-md-column">Сроки:</h1>
                                <p class="term-days">10-14 дней</p>
                            </div>
                            <div class="delivery-type-price  d-flex justify-content-between flex-md-column">
                                <h1 class="price-title">Стоимость доставки:</h1>
                                <p class="price-money">от £13.00</p>
                            </div>
                            <div class="delivery-type-total  d-flex justify-content-between flex-md-column">
                                <h1 class="total-title">Итого:</h1>
                                <p class="total-money">£90.50</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- DELIVERY-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");


    /* DELIVERY-SECTION START */

    .delivery-section {
        margin-top: 10rem;
    }
    .delivery-information {
        width: 100%;
        text-align: left;
        margin: 0 auto;
    }
    .delivery-title {
        font-weight: 700;
    }
    .delivery-text {
        margin-top: 1.25rem;
    }

    .delivery-select-item {
        margin-top: 3rem;
    }
    .delivery-select-title {
        font-size: 14px;
        font-weight: 700;
        height: 2rem;
    }
    .delivery-select-field {
        font-size: 16px;
    }
    .delivery-select-field select, input {
        padding: 10px 20px;
        padding-left: 0;
        width: 100%;
        border: none;
        border-bottom: 1px solid #222222;
        outline: none;
        height: 3rem;
    }
    .delivery-select-btn {
        margin-top: 2rem;
        border-radius: 1rem;
    }
    .delivery-type {
        margin-top: 9rem;
        margin-bottom: 20px;
    }
    .delivery-type-top-title {
        font-size: 1rem;
        color: #1F2428;
        margin: 0 auto;
        text-transform: uppercase;
        font-weight: 700;
    }
    .delivery-type-item {
        background: #FFFFFF;
        box-shadow: 0px 0px 70px rgba(138, 138, 138, 0.1);
        border-radius: 16px;
        padding: 0;
        margin: 20px 0;
    }
    .delivery-type-item > div {
        position: relative
    }
    .delivery-type-item > div::after {
        position: absolute;
        right: 0;
        top: 0;
        height: 100%;
        width: 1px;
        background: #C0C9D7;
        content: "";

    }
    .delivery-type-title {
        font-size: 1.5rem;
        margin: 0 0.5rem;
    }
    .delivery-type-name {
        flex-basis: 50%;
        display: flex;
        align-items: center;
        padding: 1rem;
        margin: 1.25rem 0;
        font-size: 1.5rem;
    }
    .delivery-type-name img {
        width: 2.5rem;
    }
    .delivery-type-term {
        flex-basis: 16%;
        padding: 0 1.5rem;
    }
    .term-title {
        font-weight: 400;
        font-size: 14px;
        line-height: 18px;
        color: #222222;
    }
    .term-days {
        font-weight: 700;
        font-size: 16px;
        line-height: 16px;
        color: #222222;
    }
    .delivery-type-price {
        flex-basis: 16%;
        padding: 0 1.5rem;
    }
    .price-title {
        font-weight: 400;
        font-size: 14px;
        line-height: 18px;
        color: #222222;
    }
    .price-money {
        font-weight: 700;
        font-size: 16px;
        line-height: 16px;
        color: #222222;
    }
    .delivery-type-total {
        flex-basis: 16%;
        padding: 0 1.5rem;
    }
    .total-title {
        font-weight: 400;
        font-size: 14px;
        line-height: 18px;
        color: #222222;
    }
    .total-money {
        font-weight: 700;
        font-size: 16px;
        line-height: 16px;
        color: #222222;
    }

    @media screen and (max-width: 768px) {
        .delivery-section > div > div  {
            display: flex;
            justify-content: space-between;
        }
        .delivery-select-item {
            justify-content: center;
        }
        .delivery-select-btn {
            align-self: flex-end;
        }
        .delivery-type {
            width: 100%;
        }
        .delivery-type-items {
            display: flex;
            flex-wrap: wrap;
            align-items: center !important;
            align-content: center !important

        }
        .delivery-type-item {
            margin-top: 3rem;
            display: block;
            flex-basis: 90%;
            padding: 2rem;
        }
        .delivery-type-top-title {
           display: none;

        }
    }
    /* DELIVERY-SECTION END */

</style>