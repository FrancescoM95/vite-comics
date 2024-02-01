<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <header>
        <figure>
            <img src="../assets/img/dc-logo.png" alt="Logo DC" id="logo">
        </figure>
        <nav>
            <ul>
                <li><a href="#">characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li><a href="#">collectibles</a></li>
                <li><a href="#">videos</a></li>
                <li><a href="#">fans</a></li>
                <li><a href="#">news</a></li>
                <li><a href="#">shop</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

#logo {
    height: 70px;
    width: 70px;
}

ul {
    list-style-type: none;
    display: flex;
    gap: 30px;
}

a {
    text-decoration: none;
    text-transform: uppercase;
    color: #1C1C1C;
    font-size: 0.8rem;
    font-weight: 600;
    padding: 30px 0;
}
</style>