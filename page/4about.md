---
layout: page
title: About
permalink: /about/
icon: heart
type: page
---

* content
{:toc}

## 关于我

<iframe src="https://githubbadge.appspot.com/gaohaoyang?s=1" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder="0"></iframe>

## 联系我

* GitHub：[manzogong](https://github.com/manzogong)
* email：1033070204@qq.com
* [Weibo](http://weibo.com/)
* [豆瓣](https://www.douban.com/people/)

## 友情链接

[羡辙杂俎](http://zhangwenli.com/blog) \| [Anotherhome](https://www.anotherhome.net) \| [Reverland](http://reverland.org/) \| [ZhiLi](http://lizhipower.github.io/) \| [Aralic](http://aralic.github.io/) \| [zchen9](http://www.chen9.info/) \| [薛彬XueBin](http://axuebin.com/blog/) \| [TBOOX](http://www.tboox.org/cn/) \|  [Ling](http://linglinyp.com/)

## Comments

{% include comments.html %}

<h2 id="comments">Comments</h2>

<div id="gitalk-container"></div>
<link rel="stylesheet" href="/css/gitalk.css" />

<script src="/js/gitalk.min.js"></script>

<script>
const gitalk = new Gitalk({
  clientID: '73946dc1d9e2276ad0da',
  clientSecret: '12a3cb94361ba3ebc6ecb68cf80d592bfaa8106d',
  repo: 'tboox.github.io',
  owner: 'waruqi',
  admin: ['waruqi'],
  id: location.pathname,      
  language: 'en',
  distractionFreeMode: false  
})
gitalk.render('gitalk-container')
</script>
