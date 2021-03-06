# 学习XCB并翻译 [XCB网站][link-XCB]

## 项目起因

我在大学里的专业为软件工程专业, 我很喜欢编程, 但是在刚迈入大学的时候, 还什么都不懂, 只能是学校开什么课我就上什么课, 然后其他时间就打游戏:). 慢慢的我开始接触到了C语言, 在老师的课堂上, 我学会了怎么将源码生成可执行程序, 于是 `Hello World!` 就这样出现在了我的电脑屏幕上的一个黑白框中(控制台), 这一刻我就感觉到我喜欢上它了. 经过一段时间的学习, 我深深的喜欢上了这门语言, 可以说除了玩游戏, 上课, 睡觉, 吃饭的其他时间我都在与C语言打交道. 慢慢的书上的知识我大多数都会了, 我便想写一个小游戏出来(我很喜欢玩游戏:) ), 有了想法那就行动呗, 经过几天的构思, 编写, 优化, 我成功的写出了我人生中自己创造的游戏: 贪吃蛇. 但是写得很烂, 功能不全(只有蛇头没有蛇身, 能够生成随机的食物...). 但是这也给了我极大的自豪感和增加了我的好奇心, 我于是有了更多的想法, 我很好奇我还能用C语言干些什么更酷的事情, 比如说不在控制台里边运行的程序. 由于我很喜欢游戏, 于是便上网上搜索了怎么用C语言开发游戏. 经过海量的搜索, 我知道了库, 能用一些C语言的库来进行开发带可绘制的窗口. 由于实验室的一些因素, 我学了第一个C/C++库 `OpenCV` , 买了本书, 边学边实践, 算是入门了这个库. 出于兴趣, 我便产生了一个念头: 用这个库来开发一个带窗口的游戏. 在暑假的时候, 奋斗了几天, 我的第一个彩色的窗口游戏就这么诞生了: 扫雷. 经过了一年的积累, 我知道我未来要干什么了: 开发游戏. 同时在这个时候我能够快速的从网上找到我需要的信息, 发现了不能用 `OpenCV` 来做游戏, 于是我又去寻找并学习了 `OpenGL` . 还是通过书籍以及网络, 我渐渐的会用 `OpenGL` 来画点东西了, 学习 `OpenGL` 的路程极为坎坷, 但是多亏 [这个(LearnOpengl-CN)][link-learnopengl-cn] 网站的帮助, 我从中学到了很多的东西. 在使用 `OpenGL` 进行开发的项目中, 无一例外我都使用了另一个库 [GLFW][link-GLFW] , 但是随着更加深入的学习和使用, 我遇到了很多的问题, 我便去看了 `GLFW` 的源码, 一看才发现除了少部分内容看不懂, 其他的都能看懂. 我便想自己从底层开始写一个库, 经过很长时间的学习事件, 我实现了 `Windows` 平台上的库, 考虑到跨平台, 便想去学 `Linux`上的窗口方面的C/C++库, 经过查阅资料, 我知道了两个库: `Xlib` 和 `xcb` , 经过比较, 我选择了 `xcb`, 于是便有了这个项目.

## 目标读者

* 对XCB库感兴趣的编程爱好者

## 文档撰写风格

* 链接均放在文章底部, 以引用方式出现在文章中.
* 文章中的链接均用空格进行前后填充.
* 标点符号后均有空格.


[link-XCB]: https://xcb.freedesktop.org/
[link-learnopengl-cn]: https://learnopengl-cn.github.io/
[link-GLFW]: https://www.glfw.org/