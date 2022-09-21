<template>
  <div style="margin: 20px;">
    <el-input v-model="input" placeholder="请输入内容"></el-input>

    <div>
      <el-date-picker
          v-model="testValue"
          type="datetime"
      ></el-date-picker>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        input: 'Hello Element UI!',
        testValue: null
      };
    }
  };
</script>
