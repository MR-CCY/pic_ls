<template>
  <div class="home" >
  <h2 margin=-20px>11111</h2>
    <viewer :images="photo" > 
      <div  v-for="(src,index) in photo" :key="index.title" class="div_pic">
        <img :src="src.url" :onerror="errorImg" :title="src.title" class="pic_cls">
        <label>{{src.title}}</label>
      </div>
    </viewer> 
  </div>
</template>
<script>
export default {
  name :'home',
  data(){
    return{
      errorImg:'',
      url:'',
      photo:[
        {
          url:"https://i0.hdslb.com/bfs/article/39d5c32b1e9671be6cc0043bfa75c4458deb65d2.jpg@1320w_742h.webp",
          title:"111",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587321283186&di=02cfe620aae8f64b00b9916f908f17ff&imgtype=0&src=http%3A%2F%2Fwww.17qq.com%2Fimg_biaoqing%2F78690945.jpeg",
          title:"222",
        },
        {
          url:"https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3066108946,962098715&fm=26&gp=0.jpg",
          title:"333",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587321408870&di=6cde82d82406e9f45b573cda7d869703&imgtype=0&src=http%3A%2F%2Fbbs.vc52.cn%2Fdata%2Fattachment%2Fforum%2F201907%2F19%2F110015g7dz7kzesznpo9nd.jpg",
          title:"444",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"5555",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"666",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"777",
        },
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d11858112c8fcc3ce2d5d.jpg",
          title:"888",
        },
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d118ba12c8fcc3ce2d5d.jpg",
          title:"999",
        },
      ]
    }
  },
  methods:{}
 
}
</script>

<style >
.home {
    width: 110%;
    height: 120vh;
     background-image: -webkit-linear-gradient(top,rgb(196,228,253),rgb(255,255,255)); 
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale; 
    text-align: center;
    float:left;
    margin:-20px
    }
.pic_cls {
       width:400px;
       height:200px
}
.div_pic{
  width:400px;
  height:200px;
  margin-left: 3%;
  margin-top: 3%;
  float:left;
}
</style>