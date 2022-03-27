<template>
<!--  注意大括号的位置 -->
  <h1>{{  result }}</h1>
</template>
<script>
export default {
  name:'CounterResult',
  props:{
    result: Number
  }
}
</script>
