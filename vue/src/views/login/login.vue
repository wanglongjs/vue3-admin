<template>
  <div class="cotnent">
    <div class="login">
      <el-input placeholder="请输入内容" v-model="input10" clearable></el-input>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
        input10:''
    };
  }
};
</script>

<style lang="scss" scoped>
.login {
  background-color: rgb(7, 88, 88);
  height: 100vh; //可视区窗口比例来处理
}
</style>