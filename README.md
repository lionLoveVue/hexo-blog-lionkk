## :sunny:hexo-blog-lionkk

<p align="center"> <a href="https://yangchaoyi.vip" target="_blank" rel="noopener noreferrer"><img width="100" src="https://Chocolate1999.github.io/img/avatar.png" alt="Blog logo"></a> </p>

<p align="center">
<img src="https://camo.githubusercontent.com/87301d019d7f5fd66e4186fcf2f7e7a2276fd9f1/68747470733a2f2f7472617669732d63692e636f6d2f736877323031382f736877323031382e6769746875622e696f2e737667" alt="Build Status" data-canonical-src="https://travis-ci.comChocolate1999/hexo-blog-lionkk.svg" style="max-width:100%;">
<a href="http://hits.dwyl.com/Chocolate1999/hexo-blog-lionkk"><img src="http://hits.dwyl.com/Chocolate1999/hexo-blog-lionkk.svg" alt="HitCount"></a><a href="https://www.gnu.org/licenses/"> <img src="https://img.shields.io/github/license/Chocolate1999/hexo-blog-lionkk.svg" alt="License"></a><a href="https://github.com/Chocolate1999/hexo-blog-lionkk/network"> <img src="https://img.shields.io/github/forks/Chocolate1999/hexo-blog-lionkk.svg" alt="GitHub forks"></a> <a href="https://github.com/Chocolate1999/hexo-blog-lionkk/stargazers"> <img src="https://img.shields.io/github/stars/Chocolate1999/hexo-blog-lionkk.svg" alt="GitHub stars"></a></p>

>This is my personal blog repository. <a href="https://yangchaoyi.vip/">https://yangchaoyi.vip/</a> Now,it is open for everyone to download and modify. If it can help you to build your blog or you like the repo, could you give me a star ! Thank you!

目前是已经在做开源的准备了，当然还有一些优化项和功能增加后续在慢慢更新，请小伙伴们关注<a href="https://github.com/Chocolate1999/hexo-blog-lionkk">本仓库</a>，点个star即可，然后记得关注`readme`的动态更新，添加的特性与教程都会与代码同步更新。为了回馈开源，这不是生成后的网页文件，是您可以直接使用的源码，您只需要把博客相关信息换成您自己的就可以部署了，对于新手或者不懂编程的小伙伴来说，简直是福音，极大简化了您构建博客的工作量和复杂度，每个人都可以下载并修改成自己喜欢样式！如果你有修改想法，欢迎PR！最后，我们还是给这个开源小项目取个名字吧，由于本人狮子座（单身，苦笑），而且微信公众号名字也是取名：`小狮子前端Vue`，由于并不是自己开发的主题，起名就不添加`theme`了，那就叫 `hexo-blog-lionkk`。<<<<<<a href="https://github.com/Chocolate1999/hexo-blog-lionkk">源代码下载</a>>>>>>

**博客基于`Hexo`框架搭建，用到`hexo-theme-butterfly`主题,并在此基础之上做了很多修改，修复了一些bug，增加了一些新的特性和功能，博客演示：<a href="https://yangchaoyi.vip/">yangchaoyi.vip</a>。**


**简单使用方法：**

 1. `star` 本项目仓库 ^ o ^
 2. 安装<a href="https://git-scm.com/downloads">Git</a>, 安装<a
    href="https://nodejs.org/en/">nodeJS</a>
 3. 你可以直接`fork`一份源码到你的仓库，`clone`到本地
 4. 在本地博客仓库运行`npm install`命令安装依赖包
 5. 修改配置信息，改成自己的信息
 6. 运行命令`hexo clean`（清除生成文件），`hexo g`（生成网页）， `hexo s`（本地预览），`hexo d`（部署）

<a href="https://yangchaoyi.vip/posts/520520/">教程：【源码开放】Hexo+Github 博客butterfly 和 matery 主题 搭建完全教程【整理】</a>

有什么问题可以在文章最后评论区**留言和讨论**，当然，欢迎点击文章最后的打赏按键，请博主一杯冰阔乐，笑～

>最后，如果项目和教程对你有所帮助或者你看见了还算比较喜欢，欢迎给我star，谢谢您！

## :loudspeaker:公告

2020年4月25日 2点 已经把`hexo-blog-lionkk`博客搭建起来了，目前版本是已经够用了，关于新加入的特性可以参考下文内容。部分没有实现的功能，在教程里面也已提供详细的文档，你可以直接`clone`下来，随你 `DIY`，形成你的博客风格。

<a href="https://www.bilibili.com/video/BV1qe411s7Y5">叮咚~ 关于博客搭建教程的视频介绍</a>

v1.0.0版本已经发布

## :partly_sunny:特性
`hexo-theme-butterfly `是基于 <a href="https://github.com/Molunerfinn">Molunerfinn</a> 的<a href="https://github.com/Molunerfinn/hexo-theme-melody"> hexo-theme-melody</a> 的基础上进行开发的。

:pencil:	作者: <a href="https://github.com/jerryc127/hexo-theme-butterfly">JerryC</a>

:memo:PS：<a href="https://github.com/shw2018/hexo-blog-fly">参考书写风格</a>

**原主题特性：**

- 简单漂亮，文章内容美观易读
- <a href="https://material.io/">Material Design</a> 设计
- 增加了广告插入，与文章模块同类型
- 夜间模式和浅色模式切换
- 简体和繁体的切换
- 支持本地搜索`local_search`
- 响应式设计，博客在桌面端、平板、手机等设备上均能很好的展现
- 首页轮播文章及每天动态切换 `Banner` 图片
- 时间轴式的归档页
- 文章摘要自动节选功能
- 集成图片大图查看模式
- 可自定义的数据的友情链接页面
- 支持文章置顶和文章打赏
- 百度和谷歌推送
- 支持 `MathJax` 和 `katex`
- `TOC` 目录
- 提供默认 `404` 页面
- 可设置复制文章内容时追加版权信息
- 可设置阅读文章时做密码验证
- 阅读模式和公告栏展示
- <a href="https://gitalk.github.io/">Gitalk</a>、<a href="https://imsun.github.io/gitment/">Gitment</a>、<a href="https://valine.js.org/">Valine</a> 和 <a href="https://disqus.com/">Disqus</a> 评论模块
- 集成了<a href="http://busuanzi.ibruce.info/">不蒜子统计</a>、谷歌分析（`Google Analytics`）、百度分析（`Baidu Analytics`）、腾讯分享（`Tencent Analytics`）和文章字数统计等功能
- 支持在首页的音乐播放和视频播放功能
- 更多内容请观赏博客演示：<a href="https://yangchaoyi.vip/">yangchaoyi.vip</a>

**增加的工作或特性(未打钩的是已做但还没更新到源码的):**

 - [x] 修改原主题样式，开启加载动画
 - [x]  增加媒体页面
 - [x] 增加聚宝盒页面
 - [x] 增加微语页面
 - [x] 增加清单页面
 - [x] 增加留言板页面
 - [x] 增加友链页面
 - [x] 增加关于页面
 - [x] 修改公告栏语句
 - [x] 增加今日诗词，`loop`
 - [x] 增加网页运行时间与不蒜子统计
 - [x] 更改原本未显示的`Github`图标
 - [x] 添加默认头像，保持旋转
 - [x] 更改默认字体，博客名称，首尾背景图
 - [x] 页面底部 `footer` 跳动的心
 - [ ] 添加访客地图
 - [x] 添加Pixiv 日榜
 - [x] 添加日历
 - [x] 添加哔哩哔哩番剧页面插件
 - [x] 添加卡通人物（看板娘）
 - [x] 地址栏添加 `abbrlink`
 - [x] 添加 `Gallery` 相册图库
 - [x] 豆瓣插件（`movie`、`book`、`game`）
 - [ ] 友链界面加入自定义文字
 - [ ] 友链链接区块加入一行小字
 - [ ] Valine添加博主标签及评论微信、QQ通知
 - [ ] 文章尾部投票打星系统
 - [ ] 添加聚宝盒页面
 - [x] 添加首页导航
 - [x] 添加音乐 `music` 页面
 - [ ] `Gitalk`、`Valine` 双评论系统切换
 - [ ] 随机文章跳转
 - [ ] 加入 `steam` 游戏库界面
 - [ ] 持续更新...
## :pushpin:贡献
本仓库已经为您搭建好了博客框架，极大地简化了您构建博客的工作量和复杂度，每个人都可以下载并修改成自己喜欢样式！如果你有修改想法，`fork`本仓库，欢迎PR！

## :golf:排版

笔记内容按照 <a href="https://mazhuang.org/wiki/chinese-copywriting-guidelines/">中文文案排版指北</a>进行排版。


## :rainbow:总结

 **神奇の沟通**

- 沟通是<font color=red> **传递**</font> 沟通是<font color=red> **交流**</font>
- 沟通是<font color=red> **分享**</font> 沟通是<font color=red> **智慧**</font>
- 沟通是<font color=red> **友谊**</font> 沟通是<font color=red> **力量**</font>

" **<font color=chocolate>认识自我、超越自我</font>** " 是沟通的最高境界

- 当你在项目中感觉所要学习的人和事越来越多时，说明你在 **<font color=chocolate>成长</font>** 。
- 当你感觉要责怪的人和事越来越少时，说明你在 **<font color=chocolate>成熟</font>** 。
- 当你在项目中不断获得了友谊和朋友时，说明你将取得项目的 **<font color=chocolate>成功</font>** 。

人们能够记住的东西有如下规律：
- **听到**的内容的 <font color=chocolate>5%</font>
- **读过**的内容的<font color=chocolate>10%</font>
- **见过**的内容的 <font color=chocolate>30%</font>
- **讨论过**的内容的 <font color=chocolate>50%</font>
- **亲自做**的内容的 <font color=chocolate>75%</font>
- **教给别人**所做过的事情的 <font color=chocolate>90%</font>


因此，我觉得我如果把我学过的知识开源也是一件有意义的事情，你读完本篇文章后，你学会了搭建博客，你得到了好处，我呢，因为这篇文档，也让自己受益颇多，将知识梳理的同时，也对这件事情记忆深刻了，这难道不是双赢的局面嘛。所以，赶快给本仓库点个star吧，<a href="https://github.com/Chocolate1999/Front-end-learning-to-organize-notes">传送门：小狮子前端の学习笔记</a>。请博主一杯冰阔乐，笑～

>更多详情教程，强烈推荐阅读我写的：<a href="https://yangchaoyi.vip/posts/520520/">【源码开放】Hexo+Github 博客butterfly 和 matery 主题 搭建完全教程【整理】</a>

有什么问题可以在文章最后评论区**留言和讨论**，当然，欢迎点击文章最后的打赏按键，请博主一杯冰阔乐，笑～

>最后，如果项目和教程对你有所帮助或者你看见了还算比较喜欢，欢迎给我star，谢谢您！

## :name_badge:License

<a href="http://www.apache.org/licenses/LICENSE-2.0">Apache License 2.0</a>
