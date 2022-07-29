<template>
  <!-- FOOTER-SECTION START -->
        <footer class="footer-section">
            <div class="container">
                <div class="row g-5">
                    <div class="col-lg-3">
                        <div class="footer-links-content">
                            <img src="image/logo.png" alt="">
                            <div class="footer-links d-flex justify-content-between">
                            <div class="whatsapp"><i class="fa-brands fa-whatsapp"></i></div>
                            <div class="viber"><i class="fa-brands fa-viber"></i></div>
                            <div class="envelope"><i class="fa-solid fa-envelope"></i></div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="footer navigation">
                            <h1 class="footer-navigation-title">О компании</h1>
                            <ul class="footer-navigation-items">
                                <li><a href="#">Услуги</a></li>
                                <li><a href="#">Цены</a></li>
                                <li><a href="#">Отзывы</a></li>
                                <li><a href="#">Контакты</a></li>
                                <li><a href="#">Вакансии</a></li>
                                <li><a href="#">Соглашение о персональных данных</a></li>
                                <li><a href="#">Условия использования</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="footer navigation">
                            <h1 class="footer-navigation-title">Полезное</h1>
                            <ul class="footer-navigation-items">
                                <li><a href="#">Как работает наш сервис</a></li>
                                <li><a href="#">Как покупать с оператором</a></li>
                                <li><a href="#">Ответы на частые вопросы</a></li>
                                <li><a href="#">Популярные магазины</a></li>
                                <li><a href="#">Черный список магазинов</a></li>
                                <li><a href="#">Актуальные распродажи</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="footer-navigation">
                            <h1 class="footer-navigation-title">Спецпроекты</h1>
                            <ul class="footer-navigation-items">
                                <li><a href="#">50% на первую доставку</a></li>
                                <li><a href="#">Скидки для постоянных клиентов</a></li>
                                <li><a href="#">Реферальная программа</a></li>
                                <li><a href="#">Кэшбек Mr. Rebates и Rakuten</a></li>
                                <li><a href="#">Stop Fraud</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer-bottom-item">
                <p>© 2021 Okeypost . Все права защищены.</p>
            </div>
        </footer>
        <!-- FOOTER-SECTION END -->

</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");

    /* FOOTER-SECTION START */
    .footer-section {
        padding: 4rem;
        padding-bottom: 0;
    }
    .footer-links {
        margin-top: 3rem;
    }
    .footer-links img {
        display: block;
        margin-bottom: 3rem;
        width: 8rem;
    }
    .whatsapp {
        border-radius: 50%;
        border: 1px solid greenyellow;
        width: 4rem;
    }
    .whatsapp i {
        padding: 1rem;
        font-size: 1.7rem;
        color: greenyellow;
        display: block;
    }
    .viber {
        border-radius: 50%;
        border: 1px solid rebeccapurple;
        width: 4rem;
    }
    .viber i {
        padding: 1rem;
        font-size: 1.7rem;
        color: rebeccapurple;
        display: inline-block;
    }
    .envelope {
        border-radius: 50%;
        border: 1.5px solid #41B7E9;
        width: 4rem;
    }
    .envelope i {
        padding: 1rem;
        font-size: 1.7rem;
        color: #41B7E9;
        display: inline-block;
    }
    .footer-navigation {
        margin-bottom: 3rem;
        
    }
    .footer-navigation-title {
        font-weight: 700;
        font-size: 1.5rem;
        text-align: center;
    }
    .footer-navigation-items {
        width: 100%;
        margin: 0 auto;
    }
    .footer-navigation-items li {
        list-style: none;
    }
    .footer-navigation-items li a {
        text-decoration: none;
        color: #1F2428;
    }
    .footer-bottom-item {
        text-align: center;
        color: #1F2428;
        padding: 2rem;
        margin-top: 1.5rem;
        border-top: 1px solid #C0C9D7;;
    }
    /* FOOTER-SECTION END */


</style>