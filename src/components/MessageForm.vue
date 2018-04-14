<template>
  <div class="form">
    <input v-model="msg" />
    <br />
    <label>{{msg}}</label>
  </div>
</template>
<script>
  export  default {
    name: "Message Form",
      data(){
        return{
          msg: "",
        }
      }
  }
</script>
