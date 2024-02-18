<template>
  <div class="menu">
    <a>Home</a>
    <a>About</a>
    <a></a>
  </div>
  <img alt="Vue logo" src="./assets/logo.png">
  <div> 
    <h4  style="color:purple">oodfd샵</h4>
    <h2> {{products[0]}}</h2>  
    <p> xx만원</p>
    <div>
      <h5>{{products[1]}}</h5>
    <p>30만원</p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      //여기다 다 짱박으면된다 단, object 자료형식으로!
      //데이터 저장시켜놨다 배열로. 꺼내쓰려면?
      products : ['역삼동원룸',"천호동원룸",'마포구원룸']
    }
  },
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.menu{
  background: darkslateblue;
  padding: 15px;
  border-radius:5px;
}
</style>
