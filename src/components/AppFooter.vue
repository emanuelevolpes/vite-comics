<script>
export default {
    data() {
        return {
            footerNavList1: [
                'DC COMICS',
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Videos',
                'News'
            ],
            footerNavList2: [
                'DC COMICS',
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Videos',
                'News',
                'TV',
                'Games',
                'Videos',
                'News'
            ],
            footerNavList3: [
                'DC COMICS',
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games'
            ],
            footerNavList4: [
                'DC COMICS',
                'Characters',
                'Comics'
            ],
            socialList: [
                {
                    src: '../../public/img/footer-facebook.png'
                },
                {
                    src: '../../public/img/footer-periscope.png'
                },
                {
                    src: '../../public/img/footer-pinterest.png'
                },
                {
                    src: '../../public/img/footer-twitter.png'
                },
                {
                    src: '../../public/img/footer-youtube.png'
                },
            ]
        }
    }
}
</script>

<template>
    <!-- <div class="background-footer-top"></div> -->
    <div class="container-footer-top">
        <section class="footer-nav">
            <ul class="footer-nav-list">
                <li v-for="items in footerNavList1">{{ items }}</li>
                <li v-for="items in footerNavList4">{{ items }}</li>
            </ul>
            <ul class="footer-nav-list">
                <li v-for="items in footerNavList2">{{ items }}</li>
            </ul>
            <ul class="footer-nav-list">
                <li v-for="items in footerNavList3">{{ items }}</li>
            </ul>
        </section>
        <div class="footer-logo">
            <img src="../../public/img/dc-logo-bg.png" alt="logo">
        </div>
    </div>
    <div class="container-footer-bottom">
        <div><button>SIGN-UP NOW!</button></div>
        <ul class="social">
            <li>FOLLOW US</li>
            <li v-for="items in socialList">
                <img :src="items.src" alt="">
            </li>
        </ul>
    </div>
</template>

<style scoped>
.container-footer-top {
    height: 370px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: gray;
    padding: 0 20rem;
    background-image: url('../public/img/footer-bg.jpg');
}

.footer-nav {
    display: flex;
    justify-content: space-between;
    align-items: start;
}

.footer-nav-list {
    list-style: none;
    color: white;
}

.footer-nav-list>li {
    display: block;
    margin-bottom: .625rem;
}

.footer-logo {
    height: 370px;
}

.footer-logo>img {
    height: 370px;
    width: 550px;
    object-fit: cover;
}

.container-footer-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #303030;
    padding: 1.875rem 20rem;
}

.container-footer-bottom>div>button {
    background-color: #303030;
    border: 2px solid #0282f9;
    padding: 15px;
    color: white;
}

.social {
    display: flex;
    align-items: center;
    list-style: none;
}

.social>li {
    display: inline-block;
    margin-right: 1.25rem;
    color: #0282f9;
}
</style>