<script>
import chatHeader from "@/components/chatHeader.vue";
import chatFunctionButton from "@/components/chatFunctionButton.vue";
import showMessage from "@/components/showMessage.vue";
import chatInput from "@/components/chatInput.vue";
export default {
components:{
  chatHeader,
  chatFunctionButton,
  showMessage,
  chatInput
},
  data(){
  return{
    isExpanded:false
  }
  },
methods:{
toggleContent(){
  this.isExpanded = !this.isExpanded
}
}
}
</script>

<template>
<div class="contentlayout">
  <div class="header"><chatHeader/></div>
  <div class="contentMessage"><showMessage/></div>
  <div class="functionButton"><chatFunctionButton/></div>
  <div class="chatInput"><chatInput/></div>
  <div class="root" style="display:block;"><p class="desc--o960OFCA">服务生成的所有内容均由人工智能模型生成，其生成内容的准确性和完整性无法保证，不代表我们的态度或观点</p></div>
</div>
</template>

<style >
.contentlayout{
  display: flex;
  flex: 1 1 0;
  width: 100%;
  height: 100%;
  position: relative;
  flex-direction: column;
  background-color: #ffffff;
  align-items: center;
}

.header{
  width: 100%;
  height: 70px;
  padding: 10px 10px 5px 10px;
  display: flex;
  align-items: center;
  position: relative;
}
.contentMessage{
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
  width: 98%;
}
.chatInput{
  width: 98%;
  height: 40px;
  margin-top: 5px;
  border: 2px solid #6a5bfa;
  border-radius: 15px;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  background: #fff;
  align-items: center;
}
.desc--o960OFCA{color: #8f91a8;
  font-size: 10px;
  height: 12px;
  line-height: 12px;
  margin: 0;
  overflow: hidden;
  text-align: center;
  text-overflow: ellipsis;
  white-space: nowrap;
  width: 100%;}
*div{
  box-sizing: border-box;
}
</style>