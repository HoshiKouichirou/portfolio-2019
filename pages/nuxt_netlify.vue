<template>
 <div class="main">
    <div class="photo-frame">
       <img class="photo" src="~/assets/portfolio_site.png" alt="">
   </div> 
   <div>
     <div class="product-info-page">
         概要
          <li class="product-info-text">nuxt自体いろいろな記事があり特に苦労することもなくデザインを含め2~3日程度で完成しました。</li>
      </div>
   </div>
 </div>
</template>
<style>
.product-info-page{
    font-size: 30px;
    font-family: 'TsukuARdGothic-Regular','Hiragino Kaku Gothic ProN','ヒラギノ角ゴ ProN W3','ＭＳ 明朝', 'MS Mincho',sans-serif;
    font: 'TsukuARdGothic-Regular','Hiragino Kaku Gothic ProN','ヒラギノ角ゴ ProN W3','ＭＳ 明朝', 'MS Mincho';
    margin: 0 auto;
    width: 80%;
    height: 120px;
    border: #707070 solid 0.5px;
}
.product-info-text{
    font-size: 20px;
    padding-left: 20px;
    padding-top: 10px;
}
.photo{
    margin: 10 auto;
    width: 800px;
    height: 450px;
    object-fit: contain;
}
.photo-frame{
    text-align: center;
    margin: 10px auto;
    width: 800px;
    height: 500px;
    border: 1px solid #707070;
}
li{
    list-style: none;
};

</style>