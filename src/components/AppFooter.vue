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
                                    <li>Terms Of Use</li>
                                    <li>Privacy policy (New)</li>
                                    <li>Ad Choices</li>
                                    <li>Advertising</li>
                                    <li>Jobs</li>
                                    <li>Subscriptions</li>
                                    <li>Talent Workshops</li>
                                    <li>CPSC Certificates</li>
                                    <li>Ratings</li>
                                    <li>Shop Help</li>
                                    <li>Contact Us</li>
                                </ul>
                            </div>
                            <div class="cols-3">
                                <h3>Sites</h3>
                                <ul>
                                    <li>DC</li>
                                    <li>MAD Magazine</li>
                                    <li>DC Kids</li>
                                    <li>DC Universe</li>
                                    <li>DC Power Visa</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="cols-2">
                        <figure>
                            <img src="../assets/img/dc-logo-bg.png" alt="Logo DC bg" id="logo-footer">
                        </figure>
                    </div>
                </div>
            </div>
        </div>
        <div id="footer-bottom">
            <div class="container">
                <div class="row">
                    <div class="cols-2">
                        <button role="button">SIGN-UP NOW!</button>
                    </div>
                    <div class="cols-2 d-flex">
                        <h2>FOLLOW US</h2>
                        <ul id="social">
                            <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
                            <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
                            <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="you tube"></a></li>
                            <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
                            <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    color: #fff;

    h3 {
        text-transform: uppercase;
        margin-bottom: 15px;
    }

    li {
        cursor: pointer;
    }
}

#footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 320px;
    overflow: hidden;
    padding: 30px 0;

    ul {
        list-style-type: none;
        font-size: 0.75rem;
        line-height: 1.1rem;
        margin-bottom: 15px;
        color: #7A7B79;
    }
}

.row {
    display: flex;
    gap: 50px;

    .cols-2 {
        flex-basis: 50%;
        height: 100%;
    }
}

#logo-footer {
    max-width: 100%;
    transform: translate(0, -25%);
}

#footer-bottom {
    height: 80px;
    line-height: 80px;
    background-color: #303030;

    .row {
        align-items: center;
    }
}

#social {
    display: flex;
    gap: 15px;
    list-style-type: none;

    img {
        height: 30px;
    }

    h2 {
        color: #0282f9;
        font-size: 1.2rem;
    }
}

.d-flex {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 30px;
}

button {
    padding: 10px;
    background-color: transparent;
    color: #fff;
    border: 2px solid #0282f9;
    cursor: pointer;
}
</style>