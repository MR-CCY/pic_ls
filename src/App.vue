<template>
  <div class="home" >
  <h2>11111</h2>
    <viewer :images="photo" > 
      <div  v-for="(src,index) in photo" :key="index.title" class="div_pic">
        <img :src="src.url"  width="400px" height="200px" :onerror="errorImg" :title="src.title" >
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
      photo:[
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"111",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"1221",
        },
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"1331",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
         {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
        {
          url:"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1587143659339&di=6db09620fc85d041f0ef1819c8ef8f6a&imgtype=0&src=http%3A%2F%2Fd.hiphotos.baidu.com%2Fzhidao%2Fpic%2Fitem%2Ff9dcd100baa1cd11d1185816ba12c8fcc3ce2d5d.jpg",
          title:"aaaa",
        },
      ]
    }
  },
  methods:{}
 
}
</script>

<style >
.home {
    width: 100%;
    height: 120vh;
     background-image: -webkit-linear-gradient(top,rgb(196,228,253),rgb(255,255,255)); 
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale; 
    text-align: center;
    float:left;
    }
.pic_cls {
    margin-left: 10px;
    margin-top: 30px;
       width:400px;
       height:200px
}
.div_pic{
  width:400px;
  height:200px;
  background-color: brown;
  margin-left: 40px;
  margin-top: 30px;
  float:left;
}
</style>