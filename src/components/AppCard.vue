<script>
export default {
    name: 'AppCard',
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <img :src="image" :alt="title">
        <h5>{{ this.title }}</h5>
    </div>
</template>

<style lang="scss" scoped>
.card {
    padding: 15px;
    flex-basis: 15%;
    margin-bottom: 2rem;

    img {
        display: block;
        max-width: 100%;
    }

    h5 {
        color: #fff;
        text-transform: uppercase;
        font-size: 0.8rem;
        font-weight: 500;
    }
}
</style>