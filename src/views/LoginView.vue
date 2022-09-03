<template>
  <div class="login_container">
    <div class="login_box">
      <div class="avatar_box">
        <img src="../assets/iu.jpg" alt="logo" />
      </div>
      <div>
          <!-- 表单, ELE, UI组件按需导入 -->
          <el-form class="login_from" label-width="80px">
            <el-form-item label="登录名">
              <el-input placeholder="请输入登录名"></el-input>
            </el-form-item>git 
            <el-form-item label="密码">
              <el-input placeholder="请输入密码"></el-input>
            </el-form-item>
            <el-form-item>
                <el-button type="primary">登录</el-button>
                <el-button type="info">取消</el-button>
            </el-form-item>
          </el-form>
        </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.login_container {
  background-color: aquamarine;
  height: 100%;
}

.login_box {
  width: 450px;
  height: 300px;
  background-color: #fff;
  border-radius: 5px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);

  .avatar_box {
    height: 130px;
    width: 130px;
    padding: 10px;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);

    img {
      width: 100%;
      height: 100%;
      border-radius: 35%;
    }
  }

  .login_from {
    position: absolute;
    bottom: 0;
    width: 100%;
    padding: 0 20px;
    box-sizing: border-box;
  }
}
</style>
