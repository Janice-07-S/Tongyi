<script>
import chatHeader from "@/components/chatHeader.vue";
import chatFunctionButton from "@/components/chatFunctionButton.vue";
export default {
components:{
  chatHeader,
  chatFunctionButton
}
}
</script>

<template>
<div class="contentlayout">
  <div class="header"><chatHeader/></div>
  <div class="showMessage"></div>
  <div class="functionButton"><chatFunctionButton/></div>
  <div class="chatInput"></div>
</div>
</template>

<style scoped>
.contentlayout{
  display: flex;
  flex: 1 1 0%;
  height: 100%;
  position: relative;
  flex-direction: column;
  background-color: #f7f8fc;
}
.header{
  background-color: white;
  width: 100%;
  height: 35px;
  padding: 10px 10px 5px 10px;
  display: flex;
}
.showMessage{
  width: 100%;
  flex: 1;
  padding: 0 10px 15px 10px;
  display: flex;
  justify-content: center;
}
.functionButton{
    padding-top: 10px;
    display: flex;
  flex-direction: row;
}
.chatInput{
  width: 100%;
  height: 40px;
  margin-top: 5px;
  border: solid #6a5bfa;
  border-radius: 15px;
  display: flex;
  overflow: hidden;
  background: #fff;
  padding: 5px;
}
</style>