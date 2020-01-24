<template>
    <div class="boots-link">
        <div class="boots-link-contents">
            <h1>Boots your link today </h1>
            <button class='boot-link-btn'>Get Started</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'BootsLink',
        props: {
            msg: String,
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 25px 0 0;
    }
    ul {
        list-style-type: none;
        padding-top: 25px;

    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }

</style>