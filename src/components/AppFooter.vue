<template>
    <div class="container-footer-top">
        <section class="footer-nav">
            <ul class="footer-nav-list">
                <li>
                    <h4>DC COMICS</h4>
                </li>
                <li>1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
                <li>6</li>
                <li>7</li>
            </ul>
            <ul class="footer-nav-list">
                <li>
                    <h4>DC COMICS</h4>
                </li>
                <li>1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
                <li>6</li>
                <li>7</li>
            </ul>
            <ul class="footer-nav-list">
                <li>
                    <h4>DC COMICS</h4>
                </li>
                <li>1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
                <li>6</li>
                <li>7</li>
            </ul>
        </section>
        <div class="footer-logo"></div>
    </div>
    <div class="container-footer-bottom">
        <div><button>SIGN-UP NOW!</button></div>
        <ul class="social">
            <li>FOLLOW US</li>
            <li>1</li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
            <li>5</li>
        </ul>
    </div>
</template>

<style scoped>
.container-footer-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: gray;
    padding: 0 20rem;
}

.footer-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-nav-list {
    list-style: none;
    color: white;
}

.footer-nav-list>li {
    display: block;
    margin-bottom: .625rem;
}

.container-footer-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #303030;
    padding: 1.875rem 20rem;
}

.social {
    display: flex;
    list-style: none;
}

.social>li {
    display: inline-block;
    margin-right: 1.25rem;
    color: white;
}
</style>