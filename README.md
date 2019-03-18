# ClipBoardDictionary
This program monitors the clipboard of the system and translate the word from English to Chinese by YouDao api, especially designed for Students who are working under linux environment where there is no simple translater when you reading papers.

# 项目起源
本人即将成为一名Ph.D，现在在看一些关于强化学习，深度学习，机器学习，控制理论等方面的英文文献，经常会有一些单词不认识．

虽然屏幕取词的功能市面上很多优秀的翻译软件都已经集成了，例如有道词典．但是由于我操作系统或者驱动等一些问题（本人的开发环境为Manjaro），安装了有道词典之后，我无法使用屏幕取词功能，每次都需要复制到网页中查询．

每次切换到浏览器再切换回pdf阅读器，十分影响阅读体验．因此，我想着完成这么一个小工具，能够监控剪贴板中的内容，并且自动使用有道词典的api来进行翻译．将结果输出到终端中．

