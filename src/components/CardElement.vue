<script>
export default {
    name: 'Card',
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <div><img :src="img" alt=""></div>
        <h4>{{ title }}</h4>
    </div>
</template>