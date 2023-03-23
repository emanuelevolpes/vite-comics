<script>
export default {
    data() {
        return {
            shortcutsList: [
                {
                    logo: '../assets/img/buy-comics-digital-comics.png',
                    name: 'DIGITAL COMICS'
                },
                {
                    logo: '../assets/img/buy-comics-merchandise.png',
                    name: 'DC MERCHANDISE'
                },
                {
                    logo: './assets/img/buy-comics-subscriptions.png',
                    name: 'SUBSCRIPTION'
                },
                {
                    logo: '../assets/img/buy-comics-shop-locator.png',
                    name: 'COMICS SHOP LOCATOR'
                },
                {
                    logo: '../assets/img/buy-dc-power-visa.svg',
                    name: 'DC POWER VISA'
                },
            ]
        }
    }
}
</script>

<template>
    <div class="container-main">
        <section class="card">
            <div class="card-content">
                <h1>Content goes here</h1>
            </div>
        </section>
        <section class="shortcuts">
            <ul>
                <li v-for="item in shortcutsList">
                    <img :src="item.logo" alt="logo-shortcuts">
                    <p>{{ item.name }}</p>
                </li>
            </ul>
        </section>
    </div>
</template>

<style scoped>
.card-content {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: black;
    height: 8.125rem;
    color: white;
}

.shortcuts {
    display: flex;
    background-color: #0282f9;
    justify-content: center;
    align-items: center;
}

.shortcuts>ul {
    display: flex;
    list-style: none;
    color: white;
}

.shortcuts>ul>li {
    display: inline-block;
    padding: 1.875rem 3.125rem;
}
</style>