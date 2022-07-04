<template>
  <div class="home">
    <ul>
      <li>
        <nuxt-link :to="{name:'about'}"> about</nuxt-link>
       
      </li>
      <li>
        <nuxt-link :to="{name:'profile'}">profile</nuxt-link>
      </li>
       <li>
        <nuxt-link :to="{name:'detail',params:{id:3314}}">查看详情3314</nuxt-link>
      </li>
      <li>
        <a href="/detail/1157">查看详情1157</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style scoped>
  .home ul{
    display: flex;
  }
  .home ul li{
    background-color: aqua;
    margin: 20px;
    border: 2px solid red;
    font-size: 24px;
  }


</style>