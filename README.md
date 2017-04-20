# Microsoft.Owin.Security.Solution is the asp.net mvc5 solution extentions for china developer

this solution is the Microsoft.Owin.Security extention,is extention the china qq and weixin login with asp.net identity

Usage:
Add below code to asp.net mvc5 project App_Start/Startup.Auth.cs

app.UseQQConnectAuthentication(appId: "***",appSecret: "*****");

app.UseWeChatAuthentication(appId: "***",appSecret: "*****");

The origin repo is https://github.com/momyh/Microsoft.Owin.Security.Solution. It's been out of date and the owner shows no interest of updating this project. So I opened this repo.

