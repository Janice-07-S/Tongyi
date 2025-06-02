<script>
export default {}

</script>

<template>
<div class="fun1bj">
  <b class="title">效率工具</b>
  <div class="fun-1">
    <div class="fun-1-1">
      <img src="https://img.alicdn.com/imgextra/i4/O1CN01C6MZ7t1GbAWytkIXX_!!6000000000640-2-tps-288-288.png" alt="logo" style="width: 40px;height: 40px;">
      <div class="smallTitle">实时记录</div>
    </div>
    <div class="fun-1-1">
      <img src="https://img.alicdn.com/imgextra/i4/O1CN01hwL8fs208Hse9T2f6_!!6000000006804-2-tps-288-288.png" alt="logo" style="width: 40px;height: 40px;">
      <div class="smallTitle">PPT创作</div>
    </div>
    <div class="fun-1-1">
      <img src="https://img.alicdn.com/imgextra/i2/O1CN01NWr3Kq1LsBK06yKIz_!!6000000001354-2-tps-288-288.png" alt="logo" style="width: 40px;height: 40px;">
      <div class="smallTitle">阅读助手</div>
    </div>
    <div class="fun-1-1">
      <img src="https://img.alicdn.com/imgextra/i4/O1CN01QWc6r61hdS8FwyCds_!!6000000004300-2-tps-288-288.png" alt="logo" style="width: 40px;height: 40px;">
      <div class="smallTitle">AI笔记</div>
    </div>
  </div>
</div>
</template>

<style>
.fun1bj{
  height: 100%;
  width: 100%;
  flex:1;
  display: flex;
  flex-direction: column;
}
.title{
  width: 100%;
  height: 24px;
  margin-bottom: 10px;
  vertical-align:center;

}
.fun-1{
  flex: 1;
  display: flex;
  flex-direction: row;
  gap:15px;
  height: 112px;
}
.smallTitle{
  font-size: 12px;
  font-weight: 600;

}
.fun-1-1{
  align-items: center;
  background: #fff;
  border: none;
  border-radius: 12px;
  box-sizing: border-box;
  cursor: pointer;
  display: flex;
  flex-direction: column;
  gap: 12px;
  height: 112px;
  justify-content: center;
  padding: 8px 12px;
  position: relative;
  transition: .2s ease;
  width: 84px;
}
*div{
  box-sizing: border-box;
}
</style>