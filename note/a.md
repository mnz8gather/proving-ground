最新版本的主流浏览器确实已经禁止在 HTTP 环境下进行密码回填

```
<!-- 在表单上禁用 -->
<form autocomplete="off">
    <!-- 在具体输入框上禁用 -->
    <input type="password" autocomplete="off">
    
    <!-- 更明确的禁用方式 -->
    <input type="password" autocomplete="new-password">
</form>
```