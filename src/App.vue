<template>
  <h1>{{ message }}</h1>
</template>

<script>
import HelloWorld from '~/components/HelloWorld' // 컴포넌트 연결 예시

export default {
    components: { 
    HelloWorld //컴포넌트 연결 예시
  },
  data(){
     components:{
    HelloWorld
    }
    return{
      message: 'Hello Vue!'
    }
  }
}
</script>