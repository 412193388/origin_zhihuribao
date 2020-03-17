<h1>原生DOM实现知乎日报API</h1>
<br>
<h2>页面结构</h2>
<ul>
  <li>页面顶栏是知乎日报的标题和logo</li>
  <li>页面左栏是知乎日报每天的推送，包括标题和图片</li>
  <li>当左栏滚动至底部时更新文章，更新更多的文章在下面，实现无限滚动的效果</li>
  <li>页面右栏是将用户点击选择文章后，讲文章的内容展示到右栏</li>
</ul>
<h2>应用到的技术</h2>
<ul>
  <li>采用flex弹性布局</li>
  <li>使用伪类对滚动条进行隐藏</li>
  <li>采用ajxa查询知乎日报的api，对json数据进行处理并且应用数据进行页面更新</li>
  <li>使用了事件监听来监听滚动条的动态</li>
</ul>
<h2>效果图</h2>
<img src="https://github.com/412193388/origin_zhihuribao/blob/master/xiaoguotu.png">
