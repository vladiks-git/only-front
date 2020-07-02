<template>
    <div class="content">
        <div class="r-content">
            <img class="img-cl" src="https://img.gazeta.ru/files3/721/10450721/RR-pic905-895x505-57650.jpg">
            <div class="discription ds">
                В купе соблюдены все принципы работы Rolls-Royce — филигранно выверенное соотношение высоких технологий и ручной сборки, безудержная роскошь и свобода самовыражения с помощью персонализации, элегантность и внутренняя сила. Он, как и его «собрат» Phantom, движется тихо, плавно, как будто летя в нескольких миллиметрах над трассой.
            </div>
            <div class="con-dis ds">
                Rolls-Royce Wraith определенно создан для водителя, недаром в его рекламной кампании снялся гонщик Дженсен Баттон. Автомобиль «сосредоточен» на движении и быстрой, но контролированной езде. Он существенно отличается от модели Ghost, хоть капот у него похожий, удлиненный, и в целом купе внешне немного напоминает четырехдверный седан. Автомобиль удивляет дизайнерской смелостью — фэстбэков с такими характерными, покатыми линиями среди современных машин практически нет.

                Характеристики и конструктивные особенности модели позволяют смело входить в виражи, утолщенный руль четко передает водителю информацию о положении передних 20-дюймовых колес. Благодаря обновленной пневмоподвеске автомобиль стал стремительнее, дорога на резких поворотах ощущается сильнее, но оптимизированная динамика не навредила знаменитой плавности хода Rolls-Royce.
            </div>
        </div>
        <div class="answ">
            <div class="cl-con"><answers></answers></div>
            <div class="cl-con"><answers></answers></div>
            <div class="cl-con"><answers></answers></div>
        </div>
    </div>
</template>

<script>
    import Answers from "./answers";
    export default {
        name: "content2",
        components: {Answers}
    }
</script>

<style scoped>
    .content{
        width: auto;
        height: 700px;
        background-color: indianred;
        margin-top: 55px;
    }
    .r-content{
        width: 875px;
        height: 600px;
        margin-top: 30px;
        margin-left: 50px;
        float: left;
    }
    .img-cl{
        height: 240px;
        width: 465px;
        margin-top: 50px;
        margin-left: 35px;
        float: left;
        border-radius: 3px;
    }
    .discription{
        margin-top: 45px;
        margin-left: 15px;
        height: 240px;
        width: 320px;
        float: left;
        word-wrap: break-word;
    }
    .con-dis{
        float: left;
        height: 250px;
        width: 800px;
        margin-left: 35px;
        margin-top: 10px;
    }
    .ds{
        color: white;
    }
    .answ{
        float: left;
        margin-top: 80px;
        margin-left: 100px;
    }
    .cl-con{
        margin-bottom: 40px;
    }
</style>