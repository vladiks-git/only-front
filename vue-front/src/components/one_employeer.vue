<template>
    <div>
        <img class="photo-empl" src="https://firelinks.ru/wp-content/uploads/2017/01/face.jpg">
        <h4>Name employeer</h4>
        <p>
            Ведение бизнеса это процесс по ходу, которого предприниматель сталкивается с миллионом разнообразных нюансов и вопросов прямо не связанных с его основной деятельностью.
        </p>
    </div>
</template>

<script>
    export default {
        name: "one_employeer"
    }
</script>

<style scoped>
    div{
        border: 5px solid  deepskyblue;
        height: 380px;
        width: 300px;
        border-radius: 10px;
        background-color: rgba(39, 58, 93, 0.9);
    }
    .photo-empl{
        width: 240px;
        height: 140px;
        border-radius: 7px;
        margin-top: 20px;
        position: relative;
        margin-left: 25px;
    }
    h4{
        display: flex;
        justify-content: center;
        margin-top: 15px;
        color: white;
    }
    p{
        word-wrap: break-word;
        margin: 15px;
        color: white;
    }
</style>