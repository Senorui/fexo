> A minimalist design theme for Hexo.

> 一个极简主义设计的 Hexo 主题。

原作: https://github.com/forsigner/fexo

**此修改主题仅仅自用，发布到此以作备份**

**在此感谢原作者forsigner写出了这么优秀的主题!!!**

<a href="https://senorui.top/" target="_blank">Demo</a>
|
<a href="http://forsigner.com/2016/03/10/fexo-doc-zh-cn/" target="_blank">原文档</a>

**此修改版样式的布局大体上没变，但是细节方面变了很多很多；且对增加的功能均配置文件中做了配置选项，可选择关闭或者开启。**
**有任何疑问均可发邮件至：info<!-- >@. -->@<!-- >@. -->senorui<!-- >@. -->.<!-- >@. -->com**

全局：
1. 引入 font-awesome 样式
2. 加入小爱心图鼠标点击特效
3. 添加滚动条样式
4. 添加页面预加载
5. 增加支持PWA
6. 修改全站字体
7. 全站适配基于媒体查询的深色模式
8. 其他样式上的增改

![demo](/source/img/DBlog.webp)
![demo](/source/img/Blog.webp)

另本主题要求的必装插件：
- "hexo-deployer-git"：部署插件
- "hexo-search"：本主题搜索插件
- "hexo-wordcount"：<font color=red>文章字数阅读时长插件与文章页深度集合，请务必先安装好不然打不开文章页面</font>。

首页：
1. 首页导航添加图标样式
2. 增加底部的声明与备案号
3. 底部添加今日诗词
4. 添加中国天气网插件

![首页](/source/img/Blog.webp)

文章页：

1. 代码块复制功能

![copy](/source/img/copy.png)

2. 增加文章末尾自动添加版权声明功能

3. 修改了表格样式

![表格样式](/source/img/table.png)

以下样式来自: https://bestzuo.cn/posts/halo-beauty.htm

4. 引入有序标签

![有序标签](/source/img/youxu.png)

5. 引入多种样式的note标签（依赖font-awesome）

![note标签](/source/img/note.png)

用法

```html
<div class="note info">这里是 info 标签样式</div>

<div class="note info no-icon">这里是不带符号的 info 标签样式</div>

<div class="note primary">这里是 primary 标签样式</div>

<div class="note primary no-icon">这里是不带符号的 primary 标签样式</div>

<div class="note warning">这里是 warning 标签样式</div>

<div class="note warning no-icon">这里是不带符号的 warning 标签样式</div>

<div class="note danger">这里是 danger 标签样式</div>

<div class="note danger no-icon">这里是不带符号的 danger 标签样式</div>
```

6. 另一种风格的标签，包括小标签。

![note标签](/source/img/anote.png)
![note标签](/source/img/snote.png)

用法
```html
<p class='div-border green'>绿色</p>
<p class='div-border red'>红色</p>
<p class='div-border yellow'>黄色</p>
<p class='div-border grey'>灰色</p>
<p class='div-border blue'>蓝色</p>
## 小tag标签语法示例
<span class="inline-tag red">红色小标签</span>
<span class="inline-tag green">绿色小标签</span>
<span class="inline-tag blue">蓝色小标签</span>
<span class="inline-tag yellow">黄色小标签</span>
<span class="inline-tag grey">灰色小标签</span>
```

其他：
1. 关于页增加对本站的描述。

2. 关于页点击QQ跳转聊天，适配移动端(需要在source下的qq.html中将QQ号改为自己的)

3. 友链页新增一个小tip，告知如何好友获取本站的友链信息。

4. 删除了所有评论系统，若需要可查看原主题添加评论模块即可。

另附Valine评论的美化：

可阅读: https://senorui.top/posts/7bde.html
![评论](/source/img/last.png)

5. ~~由于原归档文章列表页面切换按钮样式有bug，我用`< . >`替换了此按钮。~~

此处现在原作者已经修复！可看bug[原因](https://github.com/forsigner/fexo/commit/71d0840ebe4768f1d94cf63aed1a84e7327a0111)



### Browser compatibility

- IE8+
- Firefox
- Chrome
- Safari
- Opera

### License

[MIT](LICENSE)