基于Waline的评论系统

HTML引入

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
