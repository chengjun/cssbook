# 使用 docsify.js搭建在线图书！ 🔥

特点：纯粹Github网页端操作

STEP 1.  Fork然后修改settings
- pages --- branch 部分，将/(root)改为/docs

STEP 2. 需要修改index.html文件当中的assets部分的链接
- 我的repo名为cssbook
- 将assets前面添加 /cssbook/assets/

```html
<link rel="stylesheet" href="/cssbook/assets/css/vue.css">
<link rel="stylesheet" href="/cssbook/assets/css/gitalk.css">
<script src="/cssbook/assets/js/md5.js"></script>
<script src="/cssbook/assets/js/docsify.min.js"></script>
<script src="/cssbook/assets/js/gitalk.min.js"></script>
<script src="/cssbook/assets/js/docsify-pagination.min.js"></script>
<script src="/cssbook/assets/js/zoom-image.js"></script>
<script src="/cssbook/assets/js/prism-bash.js"></script>
<script src="/cssbook/assets/js/prism-java.min.js"></script>
```

