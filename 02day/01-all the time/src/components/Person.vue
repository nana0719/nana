<template>
  <div class="person">
      <div class="lmn-top">
            <div class="bg">
                
            </div>
      </div>
  </div>
</template>

<script>
export default {
  name:"Person"
};
</script>

<style lang="scss">
    .lmn-top{
        width:100%;
        height:580px;
        position: relative;
        overflow: hidden;
    }
    .bg{
        width:140%;
        height:300px;
        background: #eb6100;
        border-radius:50%;
        position: absolute;
        left: -98px;
        top: -160px;
    }
</style>