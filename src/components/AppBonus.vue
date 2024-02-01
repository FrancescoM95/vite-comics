<script>
export default {
    name: 'AppBonus'
}
</script>

<template>
    <div id="bonus">
        <div class="container">
            <div class="row">
                <div class="col">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="digital">
                    <p>Digital comics</p>
                </div>
                <div class="col">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
                    <p>DC merchandise</p>
                </div>
                <div class="col">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="sub">
                    <p>Subscriptions</p>
                </div>
                <div class="col">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="shop">
                    <p>comic shop locator</p>
                </div>
                <div class="col">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="power">
                    <p>DC power visa</p>
                </div>


            </div>
        </div>

    </div>
</template>

<style scoped>
#bonus {
    background-color: #0282f9;
    height: 90px;
}

.row {
    height: 90px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.col {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #fff;
    font-size: 0.9rem;
    text-transform: uppercase;
}

.col>* {
    cursor: pointer;
}

img {
    height: 60px;
    max-width: 60px;
    display: block;
}
</style>