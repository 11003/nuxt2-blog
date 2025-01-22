## 使用项目

```bash
# 淘宝源
$ npm config set registry https://registry.npmmirror.com/

# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
```

## 效果

🌙 深色模式

![](https://s2.loli.net/2023/03/27/siQgh4YmeMK96Hn.png)

## 更改自己的接口地址

进入`nuxt.config.js`里面

必须要和 [thinkphp-blogphp](https://github.com/11003/thinkphp-blogphp) 配合

```
env: {
   APP_BASE_API: '你的域名'
}
```

## 如果遇到了问题

请移动到 [我的博客]([http://blog.musclewiki.cn/search/nuxt](https://liuhai.work/search?q=nuxt)) ，里面记录了踩 Nuxt 的坑
