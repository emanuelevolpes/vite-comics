<template>
    <div class="container-main">
        <section class="card">
            <div class="card-content">
                <h1>Content goes here</h1>
            </div>
        </section>
        <section class="shortcuts">
            <ul>
                <li>1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
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