<script>
import history from "@/components/history.vue";
import ChatContent from "@/components/chatContent.vue";

export default {
  components: {ChatContent, history},
  data() {
    return {
      newMessage: '',
      showMessage: '',
    }
  },
  methods: {
    sendMessage() {
      this.showMessage = this.newMessage;
    }
  }
}
</script>

<template>
  <div class="layout-history">
    <div>
    <history/>
    </div>
    <span class="fun-button">
    </span>
  </div>
  <div class="chat-window">
    <chat-content/>
  </div>
</template>

<style>
.layout-history{
  display: flex;
  flex-direction: row;
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
  position: absolute;
  right: -22px;
  top: 50%;
  transform: translate(0px, -22px) rotateY(0deg);
  width: 22px;
  height: 44px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  z-index: 11;
}

.fun-button svg {
  fill: var(#c8cad9);
}

</style>
