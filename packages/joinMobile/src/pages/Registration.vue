<template>
  <div style="width: 95%; margin: 0 auto">
    <n-card size="small">
      <form>
        <label for="sid">学号:&nbsp;</label>
        <input type="text" id="sid" name="sid" placeholder="请填写学号" />
        <br />
        <br />
        <label for="sname">姓名:&nbsp;</label>
        <input type="text" id="sname" name="sname" placeholder="请填写姓名" />
        <br />
        <br />
        <label for="sex">性别:&nbsp;</label>
        <select name="sex" id="sex">
          <option value="male">男</option>
          <option value="female">女</option>
        </select>
        <br />
        <br />
        <label for="smajor">专业:&nbsp;</label>
        <input type="text" id="smajor" name="smajor" placeholder="请填写专业" />
        <br />
        <br />
        <label for="sphone">手机号码:&nbsp;</label>
        <input type="text" id="sphone" name="sphone" placeholder="请填写手机号码" />
        <br />
        <br />
        <label for="sqq">qq:&nbsp;</label>
        <input type="text" id="sqq" name="sqq" placeholder="请填写qq" />
        <br />
        <br />
        <label for="semail">电子邮箱：&nbsp;</label>
        <input type="text" id="semail" name="semail" placeholder="请填写电子邮箱" />
        <br />
        <br />
        <label for="sgroup">意向小组:&nbsp;</label>
        <select name="sgroup" id="sgroup">
          <option value="web">网站组</option>
          <option value="be">程序设计组</option>
        </select>
        <br />
        <br />
        <label for="sdepartment">意向部门（可选）:&nbsp;</label>
        <select name="sdepartment" id="sdepartment">
          <option value="xc">宣传部</option>
          <option value="wl">外联部</option>
        </select>
        <br />
        <br />
        <label for="w3review">用一段简短的文字描述你自己！</label>
        <textarea id="w3review" name="w3review" rows="4" cols="50" placeholder="正如你所看到的，我是一个非主流。"></textarea>
      </form>
    </n-card>
  </div>
</template>
<script setup lang="ts">
import { NCard } from "naive-ui";
</script>

<style scoped>
input {
  border: 0;
  border-bottom: 1px solid black;
  outline: none;
  background-color: rgba(0, 0, 0, 0);
  width: 100%;
  -webkit-appearance: none;
}

select {
  border: 0;
  border-bottom: 1px solid black;
  outline: none;
  width: 100%;
  font-family: 楷体;
  background-color: white;
  color: rgb(169, 169, 169);
}

textarea {
  border: 0;
  border-bottom: 1px solid black;
  outline: none;
  width: 100%;
  font-family: 楷体;
}

.n-card {
  box-shadow: 0px 0px 42px #d6cfcf;
  border-radius: 4px;
  margin-top: 5px;
  margin-bottom: 10px;
}
</style>
