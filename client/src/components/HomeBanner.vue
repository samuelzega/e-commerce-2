<template>
  <div class="bannerNya">
    <div class="block">
      <el-carousel height="70vh">
        <el-carousel-item v-for="item in 4" :key="item">
          <h3 class="small">{{ item }}</h3>
        </el-carousel-item>
      </el-carousel>
    </div>
  </div>
</template>

<style scoped>
.bannerNya {
  margin: 3vh 5vw;
}

.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 150px;
  text-align: center;
  margin: 0;
}

.el-carousel__item:nth-child(3) {
  background: url('https://www.marshallmusic.co.za/wp-content/uploads/2015/11/1.png');
  background-repeat: no-repeat;
  background-size: 100vw 70vh;
}

.el-carousel__item:nth-child(4) {
  background: url('https://cdn05.zipify.com/9kSBzwqaCmoim949HF6kEhTfK24=/fit-in/2048x0/1c5bcf0aa2a14f3e83b051b0c85ac709/big-music-sale_facebook-feeds-ads.jpg');
  background-repeat: no-repeat;
  background-size: 100vw 70vh;
}

.el-carousel__item:nth-child(5) {
  background: url('https://www.edmtunes.com/wp-content/uploads/2019/05/miami-gallery-2019-31-1600x1066.jpg');
  background-repeat: no-repeat;
  background-size: 100vw 70vh;
}

.el-carousel__item:nth-child(6) {
  /* https://20trendingwallpapers.com/wp-content/uploads/2019/09/studio-wallpaper_3581717-1024x576.jpg */
  background: url('https://20trendingwallpapers.com/wp-content/uploads/2019/09/studio-wallpaper_3581717-1024x576.jpg');
  background-repeat: no-repeat;
  background-size: 100vw 70vh;
}
</style>
