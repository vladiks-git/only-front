<template>
    <div class="employeers">
        <ul>
            <li>
                <One_employeer></One_employeer>
            </li>
            <li>
                <One_employeer></One_employeer>

            </li>
            <li>
                <One_employeer></One_employeer>

            </li>
            <li>
                <One_employeer></One_employeer>

            </li>
        </ul>
    </div>
</template>

<script>
    import One_employeer from "./one_employeer";
    export default {
        name: "employeers",
        components: {One_employeer}
    }
</script>

<style scoped>
    .employeers{
        width: auto;
        height: 450px;
        border: 1px solid black;
        background-image: url("https://99px.ru/sstorage/53/2019/04/tmb_258209_450620.jpg");
    }
    ul li{
        display: inline-block;
        margin-left: 50px;
        margin-right: 60px;
        margin-top: 50px;
    }
    ul{
        display: flex;
        justify-content: center;
        top: 50%;
    }
</style>