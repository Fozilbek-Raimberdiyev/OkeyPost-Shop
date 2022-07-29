<template>
   <!-- SUBSCRIBE-SECTION START -->
        <div class="subscribe-section">
            <div class="container">
                <div class="row align-items-center g-3">
                    <div class="col-md-6 col-lg-5">
                        <h1 class="subscribe-title">Подпишитеть и будьте в курсе всех скидок и акций магазинов Великобритании!</h1>
                    </div>
                    <div class="col-md-6 col-lg-4">
                        <div class="subscribe-input d-flex align-items-center">
                            <i class="fa-solid fa-envelope"></i>
                            <input type="text" placeholder="Введите ваш email">
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <button class="subscribe-btn btn">Подписаться</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- SUBSCRIBE-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");

/* SUBSCRIBE-SECTION START */
    .subscribe-section {
        background: linear-gradient(79.63deg, #5B52A3 1.08%, #40B8EA 100%);
        border-radius: 36px;
        padding: 2rem;
        margin-top: 8rem;
    }
    .subscribe-title {
        font-size: 1.8rem;
        color: #fff;
        font-weight: 700;
    }
    .subscribe-input {
        border-bottom: 1px solid #fff;
    }
    .subscribe-input i {
        margin-left: 0.5rem;
        color: #fff;
    }
    .subscribe-input input {
        outline: none;
        background: inherit;
        padding: 1rem 0.5rem;
        color: #fff;
        border: none;
    }
    .subscribe-input input::placeholder {
        color: #fff;
    }
    /* SUBSCRIBE-SECTION END */

</style>