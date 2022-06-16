# 步骤

```
npm init -y
npm i koa koa-static-cache koa-router koa-body
npm i -D nodemon
```


package.js中
```
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "nodemon app.js"
  },
```

新建app.js，public/index.html
在浏览器打开页面后，轮询获取用户数据。