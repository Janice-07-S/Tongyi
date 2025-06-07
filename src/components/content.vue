<script>
import history from "@/components/history.vue";
import ChatContent from "@/components/chatContent.vue";

export default {
  components: {ChatContent, history},
  data() {
    return {
      newMessage: '',
      showMessage: '',
      isHistoryVisible: true,
    }
  },
  methods: {
    sendMessage() {
      this.showMessage = this.newMessage;
    },
    toggleContent() {
      this.isHistoryVisible = !this.isHistoryVisible;
    }
  }
}
</script>

<template>
  <div class="layout-history" :class="{collapsed: !isHistoryVisible}" v-show="isHistoryVisible">
    <div>
      <history/>
    </div>
  </div>
  <button class="fun-button" @click="toggleContent">
    <span>{{ isHistoryVisible ? '<' : '>' }}
    </span>
  </button>
  <div class="chat-window">
    <chat-content/>
  </div>
</template>

<style>
.layout-history {
  width: 260px;
  height: 100%;
  display: flex;
  flex-direction: column;
  transition: width 0.4s ease;
  overflow: hidden;
  position: relative;
}

.layout-history.collapsed {
  width: 0;

}

.chat-window {
  flex-direction: row;
  height: 100%;
  width: 100%;
  background-color: #ffffff;
  display: flex;
  overflow: hidden;
}

.fun-button {
  background: #e0dfff;
  width: 22px;
  height: 44px;
  display: inline;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  z-index: 11;
  font-size: 24px;
  border: none;
}

.fun-button svg {
  fill: var(#c8cad9);
}

</style>
