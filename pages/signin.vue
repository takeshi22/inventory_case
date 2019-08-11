<template>
  <div class="container">
    <div class="inner_block">
      <div class="mail_text"><input type="email" name="email" v-model="email"></div>
      <div class="pass_text"><input type="password" name="password" v-model="password"></div>
      <button v-on:click="regist">登録</button>
    </div>
  </div>
</template>

<script>


export default {
  data(){
    return{
      email: '',
      password: ''
    }
  },
  methods:{
    regist(){

    }
  }
}
</script>

<style lang="scss" scoped>
.container{
  text-align: center;
}
input,
button{
  border: none;
  outline: none;
  appearance: none;

  background: rgba(148, 122, 109, 0.2);
}
</style>
