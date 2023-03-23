<script>
export default {
    data() {
        return {
            headerNavList: [
                {
                    name: 'CHARACTERS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'COMICS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'MOVIES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'TV',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'GAMES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'COLLECTIBLES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'VIDEOS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'FANS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'NEWS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'SHOP',
                    link: '#',
                    target: '_self'
                }
            ]
        }
    }
}
</script>

<template>
    <div class="container-header">
        <div class="logo-header">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav-header">
            <ul>
                <li v-for="item in headerNavList">{{ item.name }}</li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
.container-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: white;
    height: 7.1875rem;
    padding: 0 20.625rem 0 20rem;
}

ul {
    display: flex;
    list-style: none;
}

ul>li {
    display: inline-block;
    margin-right: 1.875rem;
    height: 111px;
    line-height: 111px;
}

ul>li:hover {
    border-bottom: 4px solid #0282f9;
    cursor: pointer;
    color: #0282f9;
}
</style>