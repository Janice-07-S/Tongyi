<script>
import functionSelect2 from "@/components/functionSelect2.vue";
import functionSelect3 from "@/components/functionSelect3.vue";
import functionSelect1 from "@/components/functionSlect1.vue";
export default {
  components:{
    functionSelect1,
    functionSelect2,
    functionSelect3
  }
}

</script>

<template>
  <div class="contentMessagebj">
    <div class="messageFolder">
      <div class="prompt">
        <img class="logo-01"
             src="https://img.alicdn.com/imgextra/i4/O1CN01EfJVFQ1uZPd7W4W6i_!!6000000006051-2-tps-112-112.png"
             alt="logo">
        <div class="prompt-text">
          <b class="text-1">我是通义，你的实用AI助手</b>
          <div class="text-2">我可以帮你做这些事情</div>
        </div>
      </div>
      <div class="functionSelect">
        <div class="funcommon1 f1 funCommoneffect"><functionSelect1/></div>
        <div class="funcommon1 f2 funCommoneffect"><functionSelect2/></div>
        <div class="funcommon1 f3 funCommoneffect"><functionSelect3/></div>
      </div>
    </div>
  </div>
</template>

<style>
.contentMessagebj{
  flex:1;
  width:100%;
  height: 100%;
  display: flex;
  justify-content: center;
  overflow: auto;
}
.messageFolder {
  width: 872px;
  height: 308px;
  height: auto;
  display: flex;
  flex-direction:column;
  overflow: hidden;
}

.prompt {
  width: 100%;
  height: 64px;
  display: flex;
  justify-content: flex-start;
  flex-direction: row;

}

.logo-01 {
  border-radius: 20px;
  box-shadow: 0 14px 28px 0 rgba(111, 107, 238, .16);
  height: 56px;
  margin-right: 20px;
  width: 56px;
}

.functionSelect {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 10px;
  margin-top: 32px;

}
.funcommon1{
  border: 1px solid #fff;
  border-radius: 16px;
  box-sizing: border-box;
  height: 192px;
  opacity: 1;
  overflow: hidden;
  padding: 16px;
  width: auto;
}

.funCommoneffect{
  background: radial-gradient(49% 49% at 23% 90%, rgba(213, 242, 255, .15) 0, rgba(51, 192, 253, 0) 100%), radial-gradient(122% 122% at 94% -6%, rgba(237, 241, 255, .6) 0, rgba(247, 248, 252, .6) 100%);
}
</style>