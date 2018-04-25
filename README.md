# signUp-and-signIn
```javascript
node server.js 8080
```
浏览器打开http://localhost:8080/sign_up，进入注册页面  
简单地验证是否输入邮箱，是否输入密码，验证输入两次密码是否相同  

浏览器打开http://localhost:8080/sign_in，进入登录页面  
简单地验证是否输入邮箱，是否输入密码，如果邮箱和密码能够与类似数据库里的对应，就跳转到主页, 利用cookie来把用户显示到主页上 

如果你没有注册，直接打开http://localhost:8080，会提示你先注册登录