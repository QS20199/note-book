# plugin / build.vender

看起来有点不好区分

plugin应该是单纯配置哪些模块是需要在Vue实例化之前运行的

build.vender是配置哪些模块要提取到vender.bundle.js(公共包)里

# 渲染模式 spa / universal

https://zh.nuxtjs.org/api/configuration-mode

spa就是不启用服务端渲染, 服务只提供js资源, DOM渲染在客户端

universal是启用服务端渲染

针对页面设置"不启用JS"可以看出区别