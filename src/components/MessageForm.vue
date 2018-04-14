<template>
  <div class="form">
    <input v-model="msg" />
    <button @click="addMessage">Add</button>
    <br />
    <ul>
      <li v-for="(message, id) in listMessage" v-bind:key="id">{{message}}</li>
    </ul>
    <label>{{msg}}</label>
  </div>
</template>
<script>
  export  default {
    name: "Message Form",
      data(){
        return{
          listMessage: [],
          msg: "",
        }
      },
      methods: {
        addMessage(){
          if(this.msg !== "reza"){
            this.listMessage.push(this.msg);
          }
          this.msg = "";
        }
      }
  }
</script>
