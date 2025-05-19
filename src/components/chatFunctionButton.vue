<script>
export default {}
</script>

<template>
    <div class="fun hoverContainer-fun">
      <div class="fun-icon"><img src="https://img.alicdn.com/imgextra/i2/O1CN01Fi1EBN1OAcUwPAk7e_!!6000000001665-2-tps-40-40.png" alt="图标" class="imgShow"></div>
      <div>深度思考</div>
    </div>
    <div class="fun hoverContainer-fun">
      <div class="fun-icon"><img src="https://img.alicdn.com/imgextra/i2/O1CN01wBtZmR1HXnE3ifqo0_!!6000000000768-2-tps-40-40.png" alt="图标" class="imgShow">
      </div> 分析研究</div>
    <div class="fun hoverContainer-fun">
      <div class="fun-icon">
      <img src="https://img.alicdn.com/imgextra/i2/O1CN01g8YVRn2803grrl1lG_!!6000000007869-2-tps-40-40.png" alt="图标" class="imgShow">
      </div>
        连网搜索</div>
</template>

<style scoped>
.fun{
  background-color: #fff;
  border: 1px solid #e8eaf2;
  border-radius: 9999px;
  color: #585a73;
  cursor: pointer;
  font-size: 14px;
  height: 36px;
  overflow: hidden;
  transition:0.3s ease;
  width: 116px;

}
.fun-icon{
  display: flex;
  align-items: center;
}
.hoverContainer-fun{
  align-items: center;
  display: flex;
  justify-content: center;
}
.imgShow{
  width: 20px;
  height: 20px;
}
</style>