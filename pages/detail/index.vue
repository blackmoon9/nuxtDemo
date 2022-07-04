<template>
  <div>
    <h2>收到的id为：
      <span style="color: red;">
        {{$route.params.id}}
      </span>
    </h2>
  </div>
</template>

<script>
export default {
  name: 'profile'
}
</script>
