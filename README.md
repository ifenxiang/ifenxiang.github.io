# ifenxiang.github.io
i分享


123

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
  <script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>

<script>
const gitalk = new Gitalk({
  clientID: 'Ov23liGYWFHbbq39bY7l',
  clientSecret: '443c92236c1a3bd2af8ff53017a907dd393348cd',
  repo: 'airports',      // The repository of store comments,
  owner: 'ifenxiang',
  admin: ['ifenxiang'],
  id: location.pathname,      // Ensure uniqueness and length less than 50
  distractionFreeMode: false  // Facebook-like distraction free mode
})

gitalk.render('gitalk-container')

</script>
