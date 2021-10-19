<template>
    <button :style="{background: color}" class="btn">{{text}}</button>
</template>

<script>
export default {
    name: "HomePageBttn",
    props: {
        text: String,
        color: String
    }
}
</script>