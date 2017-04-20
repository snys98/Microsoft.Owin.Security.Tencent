# This is a third party login extension of Microsoft.AspNet.Identity

##Usage:

Add below code to asp.net mvc5 project App_Start/Startup.Auth.cs

app.UseQQConnectAuthentication(appId: "***",appSecret: "*****");

app.UseWeChatAuthentication(appId: "***",appSecret: "*****");

##About

The origin repo is https://github.com/momyh/Microsoft.Owin.Security.Solution. It's been out of date and the owner shows no interest of updating this project. So I opened this repo.

