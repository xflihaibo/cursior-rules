
---
description: 
globs: api/**.ts,api/**.js,**.api.ts,**.api.js
alwaysApply: false
---
** 入参要求
    - header中必须设置auth,值为当前登录后保存的toke值
    - 请求的参数使用json格式,就算是参数为空,也需要使用{}来代替
** http请求
    - 请求方式默认是post,除非有明确要求
** 返参
    - 后端统一返回的参数为json对象,格式如下
    {
        "error":0,
        "body": object,
        "message":''
    }

error=0,表示没有任何异常
error=500,表示系统异常,需要弹出系统异常的错误
error=401,表示需要登录
error 其它值,表示业务异常,直接弹出message内容
body是一个对象
** 设计一个通用函数来处理后端API返回值,所有的API文件都都是用这个通用函数
