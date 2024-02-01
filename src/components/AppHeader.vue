<script>
export default {
    name: 'AppHeader',
    data: () => ({
        navLinks: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]
    }),
    methods: {
        changeActiveLink(index) {
            // Imposta l'elemento corrente su false per tutti gli elementi
            this.navLinks.forEach((link, i) => {
                link.current = i === index;
            });
        },
    }
}
</script>

<template>
    <header class="container">
        <figure>
            <img src="../assets/img/dc-logo.png" alt="Logo DC" id="logo">
        </figure>
        <nav>
            <ul>
                <li v-for="(link, i) in navLinks" :key="i" :class="{ 'active': link.current }" @click="changeActiveLink(i)">
                    <a :href="link.url">{{ link.text }}</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    height: 100px;
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
    height: 100%;
}

a {
    text-decoration: none;
    text-transform: uppercase;
    font-family: 'Open Sans Condensed', sans-serif;
    color: #1C1C1C;
    font-weight: 900;
    padding: 35px 0;
}

.active a {
    color: #0282f9;
    border-bottom: 4px solid #0282f9;
}
</style>