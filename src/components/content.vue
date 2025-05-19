<script>
import history from "@/components/history.vue";
import ChatContent from "@/components/chatContent.vue";

export default {
  components: {ChatContent, history},
  data() {
    return {
      newMessage: '',
      showMessage:'',
    }
  },
  methods: {
    sendMessage() {
      this.showMessage = this.newMessage;
    }
  }
}
</script>

<template>
  <div class="chat-window">
    <history/>
    <chat-content/>
<!--    <div class="chat-header">-->

<!--    </div>-->
<!--    <div class="chat-content">-->
<!--      <div id="showMessage" class="content">-->
<!--        {{ showMessage }}-->
<!--      </div>-->
<!--    </div>-->

<!--    <div class="chat-input">-->
<!--      <input class="input" type="text" v-model="newMessage" placeholder="输入消息...">-->
<!--      <button class="button" @click="sendMessage">发送</button>-->
<!--    </div>-->
  </div>
</template>

<style>
.chat-window {
  flex-direction: row;
  height: 100%;
  width: 100%;

  background-color: #f7f8fc;
  display: flex;
  overflow: hidden;
}

.chat-content {
  display: flex;
  flex-grow: 1;
  padding: 10px;
}
.content{
  flex:1;
  background:white;
  overflow: auto;
}




.input {
  border-style: none;
  outline: none;
  flex-grow: 8;
  font-size: 25px;

}

.button {
  border: none;
  font-size: 12px;
  font-weight: bold;
  width: 50px;
  border-radius: 50%;
  background: #999999;
  color: white;
}


</style>
