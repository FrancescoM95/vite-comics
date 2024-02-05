<script>
export default {
    name: 'AppJumbo',
}
</script>

<template>
    <div class="jumbo">
        <div>
            <h3>CURRENT SERIES</h3>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.jumbo {
    height: 300px;
    background-image: url('../assets/img/jumbotron.jpg');
    background-position: top;
    background-size: cover;
    position: relative;

    div {
        padding: 10px 30px;
        color: #fff;
        background-color: #0282F9;
        position: absolute;
        bottom: 0;
        left: 13%;
        transform: translateY(+50%);
        font-size: 1.2rem;
    }
}
</style>