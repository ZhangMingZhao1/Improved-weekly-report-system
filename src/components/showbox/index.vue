<template>
  <div class="showBox">
    <el-card class="box-card">
    <div slot="header" class="clearfix">
        <span>周报</span>
        <el-button style="float: right; padding: 3px 0" type="text">操作按钮</el-button>
    </div>
    <div v-for="o in 4" :key="o" class="text item">
        {{'列表内容 ' + o }}
    </div>
    </el-card>
  </div>
</template> 

<script>
export default {
  name: 'ShowBox',
  props: {
    // msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .text {
    font-size: 14px;
  }

  .item {
    margin-bottom: 18px;
  }

  .clearfix:before,
  .clearfix:after {
    display: table;
    content: "";
  }
  .clearfix:after {
    clear: both
  }

  .box-card {
    width: 100%;
  }
</style>
