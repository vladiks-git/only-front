<template>
    <div class="title-c">
       <h2>Created by Ershov Vladislav</h2>
    </div>
</template>

<script>
    export default {
        name: "title-company"
    }
</script>

<style scoped>
    .title-c{
        height: 170px;
        width: auto;
    }
    h2{
        text-align: center;
        line-height: 5em;
        color: burlywood;
        animation: pulsate 2s linear infinite;
    }
    @keyframes pulsate {
        0%{
            color:burlywood
        }
        50%{
            color: grey;
        }
        75%{
            color: black;
        }
        100%{
            color: burlywood;
    }
    }
</style>