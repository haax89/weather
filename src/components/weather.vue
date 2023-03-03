<template>
    <body>
        <div class="backgroungImg">
            <img src="../assets/Background.png">
        </div>

        <p class="textCity">Саранск</p>
        <div class="container">
            <img class="startImg" src="../assets/Component0.png" alt="ясно"> <p class="gradus">4°</p>
        </div>
       <p class="weather_0">Солнечно</p><br>

       <p class="days">По дням</p><br>

       <div class="container_2">
            <div class="countBlock block1">
                <p class="d1">Сегодня</p><br>
                <img class="weather_1" src="../assets/Component1.png" alt="ясно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block2">
                <p class="d1">Завтра</p><br>
                <img class="weather_2" src="../assets/Component2.png" alt="облачно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block3">
                <p class="d1">Ср 9</p><br>
                <img class="weather_3" src="../assets/Component3.png" alt="облачно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block4">
                <p class="d1">Чт 10</p><br>
                <img class="weather_4" src="../assets/Component4.png" alt="ясно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block5">
                <p class="d1">Пт 11</p><br>
                <img class="weather_5" src="../assets/Component5.png" alt="ясно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block6">
                <p class="d1">Сб 12</p><br>
                <img class="weather_6" src="../assets/Component1.png" alt="ясно"><br>
                <p>4°</p>
            </div>
            <div class="countBlock block7">
                <p class="d1">Вс 13</p><br>
                <img class="weather_7" src="../assets/Component5.png" alt="ясно"><br>
                <p>4°</p>
            </div>
        </div>

        <p class="info">Подробности</p>
        <hr class="line_1"> <hr class="line_2">

       <div class="container_3">
            <div class="info_1">По ощущениям<br> <p class="num_1">3°</p></div>
            <div class="info_2">Влажность<br><p class="num_2">73%</p></div>
            <div class="info_3">Давление<br><p class="num_3">750.00мм</p></div>
            <div class="info_4">Ветер<br>
                <div class="wind">
                <img class="direction" src="../assets/Frame.png"><p class="num_4">4м\с</p>
                </div>
            </div>
            <div class="info_5">Видимость<br><p class="num_5">10км</p></div>

            <div class="container_4">
            <div class="info_6">Восход
                <div class="sun_2">
                    <img class="sunrise" src="../assets/Frame1.png"><span class="time_1">7:23</span>
                </div>
            </div>
            <div class="info_7">Закат
                <div class="sun_2">
                    <img class="sunset" src="../assets/Frame2.png"><span class="time_2">18:42</span>
                </div>
            </div>
        </div>
       </div> 
    </body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

body {
    background-image: url(../assets/Background.png);
    font-family: 'Roboto';
    color: rgb(255, 255, 255);
    background-size: cover;
    background-repeat: no-repeat;
}
.textCity {
    text-align: center;
    color: white;
    font-size: 25px;
    font-family: 'Roboto';
    color: white;
        margin-right: 0px;
        margin-left: 0px;
        margin-top: 15px;
        margin-bottom: 0px;
    position: absolute;
    top: 15px;
    bottom: 0px;
    left: 0px;
    right: 0px; 
}
.container {
    display: flex;
    align-items: center;
    justify-content: center;
}
.startImg {
    height: 80px;
    width: 80px;
    position: absolute;
    top: 70px;
    bottom: 0px;
    left: 45%;
    right: 0px;
}
.gradus {
    text-align: center;
    font-size: 60px;
    color: white;
    font-family:'Roboto';
    position: absolute;
    top: 25px;
    bottom: 0px;
    left: 100px;
    right: 0px; 
}
.weather_0 {
    text-align: center;
    font-size: 20px;
    color: white;
    font-family: 'Roboto';
   position: absolute;
   top: 135px;
   bottom: 0px;
   left:0px;
   right:0px;
}
.days {
    color: white;
    padding-left: 30px;
    font-size: 20px;
    font-family: 'Roboto';
    position: absolute;
    top: 230px;
    bottom: 0px;
    left: 30px;
    right: 0px; 
}
.container_2 {
    display: flex;
    padding-left: 30px;
    padding-right: 30px;
    justify-content: space-between;
    justify-items: flex-start;
    position: absolute;
    top: 280px;
    bottom: 100px;
    left: 50px;
    right: 0px;

}
.countBlock {
    margin: 0px;
    border-radius: 10px;
    font-size: 18px;
    width: 160px;
    height: 168px;
}
.d1 {
    margin: 0px;
    padding: 0px;
}
.block1 { 

}
.weather_1 {
    height: 40px;
    width: 40px;
}
.block2 {

}
.weather_2 {
    height: 40px;
    width: 40px;
}
.block3 {

}
.weather_3 {
    height: 40px;
    width: 40px;
}
.block4 {

}
.weather_4 {
    height: 40px;
    width: 40px;
}
.block5 {

}
.weather_5 {
    height: 40px;
    width: 40px;
}
.block6 {
}
.weather_6 {
    height: 40px;
    width: 40px;
}
.block7 {


}
.weather_7 {
    height: 40px;
    width: 40px;
}
.info {
    position: absolute;
    top: 480px;
    bottom: 50px;
    left: 30px;
    right: 0px; 
    color: white;
    padding-left: 30px;
    font-size: 20px;
    font-family: 'Roboto';
}
.line_1 {
    position: absolute;
    top: 530px;
    bottom: 90px;
    left: 0px;
    right: 0px; 
    padding-left: 5px;
    width: 30%;
    height: 0px;
    margin-right: 5px;
    margin-left: 55px;
    margin-top: 0px;
    margin-bottom: 1px;
}
.line_2 {
    position: absolute;
    top: 530px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
    padding-left: 5px;
    width: 20%;
    height: 0px;
    margin-right: 5px;
    margin-left: 630px;
    margin-top: -2px;
    margin-bottom: 1px;
}
.info_1 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    color: white;

    position: absolute;
    width: 50px;
    height: 66px;
    left: 70px;
    top: 540px;
    padding:0;
    margin:0;
}
.num_1 {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 23px;
    display: flex;
    align-items: center;
    color: #FFFFFF;
    padding:0;
    margin:0;
}
.info_2 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    color: white;

    position: absolute;
    width: 100px;
    height: 66px;
    left: 217px;
    top: 540px;
    padding:0;
    margin:0;
}   
.num_2 {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 23px;
    display: flex;
    align-items: center;
    color: #FFFFFF;
    padding:0;
    margin:0;
}
.info_3 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    color: white;

    position: absolute;
    width: 100px;
    height: 66px;
    left: 70px;
    top: 620px;
    padding:0;
    margin:0;
} 
.num_3 {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 23px;
    display: flex;
    align-items: center;
    color: #FFFFFF;
    padding:0;
    margin:0;
}
.info_4 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    color: white;

    position: absolute;
    width: 70px;
    height: 66px;
    left: 217px;
    top: 620px;
    padding:0;
    margin:0;
}
.num_4 {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 23px;
    display: flex;
    align-items: center;
    color: #FFFFFF;
    padding:0;
    margin:0;
}
.direction {
    height: 12px;
    width: 12px;
    margin-right: 20px; 
}
.wind {
    display:flex;
    align-items:center;
    justify-content: center;  
}
.info_5{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 16px;
    color: white;

    position: absolute;
    width: 70px;
    height: 66px;
    left: 364px;
    top: 540px;
    padding:0;
    margin:0;
}
.num_5{
    font-family: 'Roboto';
    font-style: normal;
    font-size: 23px;
    display: flex;
    align-items: center;
    color: #FFFFFF;
    padding:0;
    margin:0; 
}
.container_4 {
    display: flex;
    min-height: 140px;
    width: 200px;
    text-align: left;
    flex-wrap: wrap;
    margin-left: 64px;
    margin-bottom: 92px;
        position: absolute;
        top: 540px;
        bottom: 0px;
        left: 565px;
        right: 0px;
}
.info_6 {  
    width: 120px;
    height: 70px;
    display: flex;
}
.sunrise {
    margin-top: 10px;
    margin-right: 10px;
    width: 30px;
    height: 30px;
}
.info_7{
    width: 120px;
    height: 70px;
    display: flex;
}
.sunset {
    margin-top: 10px;
    margin-right: 10px;
    width: 30px;
    height: 30px;
}
</style>
