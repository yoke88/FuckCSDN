# FuckCSDN
去除csdn广告、代码复制需要登录、代码折叠隐藏等限制

## 食用方式
1. 在chrome、edge、firefox等浏览器中安装ublock origin扩展，在ublock Origin控制面板中的静态规则中加入下面内容

``` text

blog.csdn.net##.article_content:style(height:unset !important;overflow:unset !important)
blog.csdn.net##.hide-article-box:remove()
blog.csdn.net##.signin:remove()
blog.csdn.net##.hide-preCode-box:remove()
blog.csdn.net##code:style(user-select: unset !important;height:unset !important;)
blog.csdn.net##.set-code-hide:style(user-select: unset !important;height:unset !important;)
blog.csdn.net###content_views pre:style(user-select: unset !important)
blog.csdn.net###asideNewNps

! 左右边栏，需要去掉的取消注释 !开头为注释行。
! blog.csdn.net##.asideHotArticle

! 百度推荐的CSDN站内文章

! blog.csdn.net##.insert-baidu-box

```




