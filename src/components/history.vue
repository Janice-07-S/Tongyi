<script>
import history1 from "@/components/history1.vue";
import history2 from "@/components/history2.vue";

export default {
  components: {
    history1,
    history2,
  }
}
</script>

<template>
  <div class="history-layout">
    <div class="historyBj">
      <div class="first">
        <history1/>
      </div>
      <div class="second">
        <history2/>
      </div>
      <div class="last"></div>
    </div>
  </div>

</template>
<style>
.history-layout {
  width: 260px;
  height: 100%;
  position: relative;
  transition: width 0.4S;

}

.historyBj {
  display: flex;
  flex-direction: column;
  border-right: 1px solid rgba(237, 239, 245, .45);
  height: 100%;
  width: 260px;
  padding: 24px 0;
  justify-content: space-between;
}

.first {
  width: 260px;
  height: 24px;
  padding: 10px 0;
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: nowrap;
}

.second {
  width: 260px;
  padding: 0 10px;
  flex: 1;
  justify-content: center;
}

.last {
  width: 260px;
  height: 24px;
  border-top: 1px solid rgba(237, 239, 245, .45);
  padding: 10px 0;
  justify-content: center;
}
</style>