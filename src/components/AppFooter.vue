<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div id="footer-top">
            <div class="container">
                <div class="row">
                    <div class="cols-2">
                        <div class="row">
                            <div class="cols-3">
                                <h3>Dc comics</h3>
                                <ul>
                                    <li>Characters</li>
                                    <li>Comics</li>
                                    <li>Movies</li>
                                    <li>TV</li>
                                    <li>Games</li>
                                    <li>Videos</li>
                                    <li>News</li>
                                </ul>

                                <h3>Shop</h3>
                                <ul>
                                    <li>Shop dc</li>
                                    <li>Shop dc collectibles</li>
                                </ul>
                            </div>
                            <div class="cols-3">
                                <h3>Dc</h3>
                                <ul>
                                    <li>Characters</li>
                                    <li>Comics</li>
                                    <li>Movies</li>
                                    <li>TV</li>
                                    <li>Games</li>
                                    <li>Videos</li>
                                    <li>News</li>
                                    <li>News</li>
                                    <li>News</li>
                                    <li>News</li>
                                    <li>News</li>
                                </ul>
                            </div>
                            <div class="cols-3">
                                <h3>Sites</h3>
                                <ul>
                                    <li>Characters</li>
                                    <li>Comics</li>
                                    <li>Movies</li>
                                    <li>TV</li>
                                    <li>Games</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="cols-2">
                        <figure>
                            <img src="../assets/img/dc-logo-bg.png" alt="Logo DC bg">
                        </figure>
                    </div>
                </div>
            </div>
        </div>
        <div id="footer-bottom">
            <div class="container">

            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    color: #fff;
}

#footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 300px;
    overflow: hidden;
    padding: 15px 0;
}

#footer-bottom {
    height: 100px;
}

.row {
    display: flex;
    gap: 50px;
}

.cols-2 {
    flex-basis: 50%;
    height: 100%;
    padding-top: 20px;
}

img {
    max-width: 100%;
    transform: translate(0, -28%);
}

h3 {
    font-size: 0.9rem;
    text-transform: uppercase;
    margin-bottom: 15px;
}

ul {
    list-style-type: none;
    font-size: 0.75rem;
    line-height: 1rem;
    margin-bottom: 15px;
    color: #7A7B79;
}

li {
    cursor: pointer;

}
</style>