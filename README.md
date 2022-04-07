基于Waline的评论系统

[在此留言](https://comments.cicada000.work/)

HTML引入

```
<head>
  <script src="//cdn.jsdelivr.net/npm/@waline/client"></script>
</head>
<body>
  <div id="waline"></div>
  <script>
    Waline({
      el: '#waline',
      serverURL: 'https://comments.cicada000.work',
    });
  </script>
</body>
```
