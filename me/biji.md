### docsify 攻克尝试

> 官方网址：https://docsify.js.org/#/zh-cn/more-pages

---

### 1. 定制侧边栏  🔥

> 参考教程：https://www.jianshu.com/p/cfd0d4009cff

```javascript
// 首先配置 loadSidebar 选项,这一步也是修改index.html文件的配置：
<script>
  window.$docsify = {
    loadSidebar: true
  }
</script>
```

```md
<!-- 创建 _sidebar.md -->
* [首页](/)
```

---

### 2. 服务器渲染（SSR） 🔥

> 官方参考项目：https://github.com/docsifyjs/docsify-ssr-demo

`问题❓` 这里用到了一个知识点：`now` ，这个是什么东西

```HTML
<p>你好</p>
<h1>你好</h1>
<img src="http://pic29.nipic.com/20130601/12122227_123051482000_2.jpg">
```