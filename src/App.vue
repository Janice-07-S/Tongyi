<script>
import content from "@/components/content.vue";
import navTab from "@/components/navTab.vue";
import history from "@/components/history.vue";

export default {
  components: {
    history,
    navTab,
    content
  }
}
</script>

<template>
  <div id="ice-container" style="filter: blur(0px)">
    <div class="layout-bj">
      <div class="layout-nav" id="new-nav">
        <navTab/>
      </div>
      <div class="layout-content" id="new-content">
        <content/>
      </div>
    </div>
  </div>
</template>

<style>
#ice-container {
  height: 100vh;
}

#ice-container {
  overflow: hidden;
  transition: all 0.4s ease;
  width: 100vw;
}

.layout-bj {
  align-items: stretch;
  display: flex;
  flex-direction: row;
  position: relative;
  width: 100%;
  height: 100%;
  background: slateblue;
}


.layout-nav {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  height: 100%;

  overflow: hidden;
  padding-top: 35px;
  position: relative;
  width: 72px;
}

.layout-content {
 background-color:#ffffff;
  display: flex;
  overflow: hidden;
  position: relative;
  width: 100%;
  border-radius: 12px;
  flex:1;
  margin: 8px 8px 8px 0;
}

</style>