<template>
  <!-- ADVANTAGE-SECTION START -->
        <div class="advantage-section">
            <div class="container">
                <div class="row">
                    <div class="col-md-3">
                        <div class="advantage-item d-flex align-items-center text-center">
                            <img src="@/assets/advantage-1.png" alt="">
                            <p class="advantage-title">Экономия до 70%</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="advantage-item d-flex align-items-center text-center">
                            <img src="@/assets/advantage-2.png" alt="">
                            <p class="advantage-title">Только подлинная продукция</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="advantage-item d-flex align-items-center text-center">
                            <img src="@/assets/advantage-3.png" alt="">
                            <p class="advantage-title">Оперативная доставка</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="advantage-item d-flex align-items-center text-center">
                            <img src="@/assets/advantage-4.png" alt="">
                            <p class="advantage-title">Огромный выбор товаров</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- ADVANTAGE-SECTION END -->
</template>

<script>
export default {

}
</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css");


  /* ADVANTAGE-SECTION START */

    .advantage-section {
        margin-top: 11.5rem; 
        padding: 15px 0;
    }
    .advantage-section > div {
        background: #FFFFFF;
        box-shadow: 0px 0px 70px rgba(138, 138, 138, 0.1);
        border-radius: 16px;
    }
    .advantage-section > div > div > div {
        border-right: 1px solid #C0C9D7;
    }
    .advantage-section > div > div > div:last-child {
        border-right: none;
    }
    .advantage-item {
        padding: 0 10px;
    }

    .advantage-title {
        margin: 0 10px;
        font-weight: 700;
    }


    /* ADVANTAGE-SECTION END */
</style>