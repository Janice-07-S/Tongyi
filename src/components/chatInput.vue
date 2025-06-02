<script>
export default {}

</script>

<template>
  <div class="option">
   <span role="img" class="anticon">
     <svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use
         xlink:href="#extend-upload-line"></use></svg>
   </span>
  </div>
  <input type="text" placeholder="遇事不解问通义" class="chatinput">
  <button class="send">

  </button>
</template>

<style scoped>
.option{
  align-items: center;
  background: #fff;
  cursor: pointer;
  display: flex
;
  height: 43px;
  justify-content: center;
  margin-right: 14px;
}
.anticon{
  fill: currentColor;
}
.chatinput {
  width: 100%;
  height: 100%;
  border: none;
  outline: none;
  flex: 1;
}
.send{
  background: #d6d5de;
  border-radius: 50%;
  width: 30px;
  height: 30px;
  border: none;
margin-right: 10px;
}
</style>