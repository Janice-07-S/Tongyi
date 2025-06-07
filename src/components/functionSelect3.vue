<script>
export default {}

</script>

<template>
  <div class="select3bj">
    <div class="card">
      <div class="card1">
        <div class="appButton">
          <div class="fun3-logo">
            <span class="text">x</span>
            <div class="fun3-text">
              <span class="text">体验Qwen3</span>
            </div>
          </div>
        </div>
      </div>
      <div class="card2">
      </div>
      <div class="card3">
      </div>
    </div>
  </div>
</template>

<style>
.select3bj {
  flex: 1;
  height: 100%;
  width: 100%;
}

.card {
  height: 100%;
  width: 216px;
  position: relative;
}

* div {
  box-sizing: border-box;
}


.card1 {
  position: absolute;
  width: 216px;
  height: 190.667px;
  background-image: url(../../public/icon/p1.png);
  background-size: contain;
  animation: slideAnimation 12s infinite;
  animation-delay: 0s;
}

.appButton {
  height: 32px;
  width: 160px;
  border-radius: 15px;
  background: #f1f0fd;
  position: absolute;
  z-index: 20;
  left: 0;
  top: 145px;
  bottom: 0;
  right: 0;
  margin: auto;
  display: flex;
  flex-direction: row;
  gap: 5px;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  animation: ease;

}

.appButton:hover {
  color: #6a5bfa;
}

.fun3-logo {
  display: flex;
  align-items: center;
}

.fun3-text {
  display: flex;
  align-items: center;
}

.text {
  font-size: 14px;
  font-weight: 600;

}

.card2 {
  position: absolute;
  width: 216px;
  height: 190.667px;
  background-image: url(../../public/icon/p2.jpg);
  background-size: contain;
  animation: slideAnimation 12s infinite;
  animation-delay: 4s;

}

.card3 {
  position: absolute;
  width: 216px;
  height: 190.667px;
  background-image: url(../../public/icon/p3.jpg);
  background-size: contain;
  animation: slideAnimation 12s infinite;
  animation-delay: 8s;
}

@keyframes slideAnimation {
  0%{
    opacity: 1;
    visibility: visible;
  }
  33%{
    opacity: 1;
    visibility: visible;
  }
  34%{
    opacity: 0;
    visibility: hidden;
  }
  100%{
    opacity: 0;
    visibility: hidden;
  }
}
</style>