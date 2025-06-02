<script>
export default {}

</script>

<template>
  <div class="select3bj">
    <div class="card">
      <div class="cardPage">
        <div class="openQnwen">
          <div class="appButton">

          </div>
        </div>
      </div>
      <div class="cardPage">
      </div>
      <div class="cardPage">
      </div>
    </div>
  </div>
</template>

<style>
.select3bj{
  flex: 1;
  height: 100%;
  width: 100%;
}
.card{
  height: 100%;
  width: 216px;
  position: relative;
}
*div{
  box-sizing: border-box;
}
.cardPage{
  height: 100%;
  left: 0;
  position: absolute;
  top: 0;
  transition: opacity .4s ease,visibility .4s ease;
  width: 100%;
}
.openQnwen{
  background-image: url(https://img.alicdn.com/imgextra/i1/O1CN01wIGuko1UxWTwwzFu9_!!6000000002584-0-tps-432-384.jpg);
}
</style>