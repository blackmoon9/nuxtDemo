<template>
  <div>
    <h2>id收到的id为：
      <span style="color: red;">
        {{$route.params.id}}
      </span>
    </h2>
  </div>
</template>

<script>
export default {
  name: 'profile',
  validate({params}){
    return params.id === '1157'
  }
}
</script>
