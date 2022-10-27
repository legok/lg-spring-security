### 核心功能
1. 用户认证
2. 用户授权

SpringSecurity本质是一个过滤器链,有很多过滤器

1. FilterSecurityInterceptor:是一个方法级的权限过滤器， 基本位于过期链的最底部
2. ExceptionTranslationFilter:是一个异常过滤器，用来处理在认证授权过程中跑出的异常
3. UsernamePasswordAuthenticationFilter:对/login的POST请求做拦截，检验表单中用户名，密码





如果github push不成功可以执行下边这两个命令

git config --global --unset http.proxy

git config --global --unset https.proxy


