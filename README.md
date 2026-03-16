想法缘由：每次右边显示未读红点都要点进去然后点击已读，再单击ok，太麻烦了，这个是在原本NodeSeek X脚本插件的基础上增加了一键已读的功能，主界面一键已读无需更多步骤即可消除红点
感谢下面两位原作者：
NodeSeek X的原作者的插件地址：
https://greasyfork.org/zh-CN/scripts/479426-nodeseek-x
NodeSeek/DeepFlood 全部已读增强版的原作者的插件地址：
https://greasyfork.org/zh-CN/scripts/520759-nodeseek-deepflood-全部已读增强版
当前效果

![image](https://cdn.nodeimage.com/i/EWpWW5WVlb4sh48KP4PPUtGHJiYqYHuF.png)

![image](https://cdn.nodeimage.com/i/lq4mMZZZZZKR0WmDE2RdKafmUs5TzFWC.png)
如何自定义按钮位置：
代码搜索【绝对定位小徽章，完全不占布局空间】
改这两个就行了，一个上下一个左右

```
bottom:-25px;right:-50px
```
