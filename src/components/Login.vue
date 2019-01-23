<template>
    <div class = "main">
        <div class="error"></div>
        <div class = "top-title">信用钱包欢迎您</div>
        <div class = "main-style">
            <input type="text" class="mobile inp main-style-input"  placeholder="请输入手机号">
            <div class="cha fr">&Chi;</div>
        </div>
        <div class = "main-style fl">
            <div class= "verify-left fl">
                <input type="text" class="verify inp main-style-input" placeholder="请输入短信验证码">
            </div>
            <div class = "verify-right fr verify-bnt">获取验证码</div>
        </div>
        <div class="clean"></div>
        <div class="read">注册代表您同意 <a href="https://baidu.com" class="red">《信用钱包用户协商》</a></div>
        <div class = "btn">注册/登录</div>
        <div class="bottom fr"><a href="passwordLogin.html">密码登录</a></div>
    </div>
</template>

<script>
export default {
    name: 'Login',
}
</script>

<style >

</style>
