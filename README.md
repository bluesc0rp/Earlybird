Earlybird
=========
<ul>
  <li><b>语言：</b>C++</li>
  <li><b>开发平台：</b>VS2012  windows</li>
  <li><b>引擎：</b>cocos2dx3.0 beta2</li>
</ul>

<p>小鸟的头撞水管上了，我的头撞键盘上了。对不起言归正传，这里是我和我的同伴所组建的游戏个人游戏开发小组OiteBoys为了学习游戏制作和cocos2d-x而仿制的flappy bird cocos2d-x 3.0beta2版的C++源代码。</p>

<p>游戏已经完成，我们打算将我们制作这款游戏的过程通过博客的形式公开，让跟多的人参与到游戏制作中，同时我们也欢迎各位Fork我们的代码，给我们的代码挑刺，发布issue，和我们一起体会游戏制作的乐趣。</p>

Early Bird开发博客大纲
=================

1.	<a href="http://blog.csdn.net/kantian_/article/details/21161299" target="_blank">就这么开始--开发环境的搭建素材的准备，以及素材精灵读取类AtlasLoader的设计。</a>
2.	<a href="http://blog.csdn.net/kantian_/article/details/21184609" target="_blank">未雨绸缪—Loading界面的写法</a>
3.	<a href="http://blog.csdn.net/kantian_/article/details/21226239" target="_blank">玄关是必要的—游戏欢迎界面的创建，以及Menu的简单应用</a>
4.	英雄都是孤独的？--小鸟单例类的设计以及小鸟类的设计
5.	千层饼的智慧—谈谈游戏主场景的分层以及最简单的背景层的实现
6.	SM？控制和被控制的欲望—游戏控制层的设计以及控制层和游戏层的关系
7.	终于要来正戏了—游戏层的设计和小鸟的加入
8.	物理世界的美妙—游戏层的物理属性的设置
9.	让马里奥大叔来搬水管—在游戏层加入水管
10.	对不起，我的数学老师是体育老师兼职的—游戏中所用到的数字类封装
11.	布告栏中的玄机—游戏状态层的设计与实现
12.	我才不会告诉你我硬盘的秘密呢—游戏存储和金币闪光实现
13.	就要结束了吗—Android交叉编译以及后继

<p style='color:red'>博客还在建设中，我们会在博客一篇完成是同步加上博客链接，预计在一周左右会全部完成</p>

游戏截图
=================
基本高仿游戏，素材均来自原版，版权归原作者所有，此仅供学习之用:)<br/>
<img src="https://github.com/OiteBoys/Earlybird/blob/master/Earlybird/Resources/image/Screenshot_2014-03-08-15-04-15.png?raw=true" width="300" height="450"/><br/>
<img src="https://github.com/OiteBoys/Earlybird/blob/master/Earlybird/Resources/image/Screenshot_2014-03-08-15-04-19.png?raw=true" width="300" height="450"/><br/>
<img src="https://github.com/OiteBoys/Earlybird/blob/master/Earlybird/Resources/image/Screenshot_2014-03-08-15-04-23.png?raw=true" width="300" height="450"/><br/>
<img src="https://github.com/OiteBoys/Earlybird/blob/master/Earlybird/Resources/image/Screenshot_2014-03-08-15-05-19.png?raw=true" width="300" height="450"/>


游戏下载
=================
下载地址：<a href="http://pan.baidu.com/s/1qW6mqio">点击下载</a><br/>
二维码：<br/>
![alt tag](https://github.com/OiteBoys/Earlybird/blob/master/Earlybird/Resources/image/1257355888.png?raw=true)

注意
=================
代码忽略了cocos2dx的库，你可以在cocos2dx官方下载的库直接拷贝到/Earlybird下下载地址：<a href="http://cdn.cocos2d-x.org/cocos2d-x-3.0beta2.zip">cocos2d-x-3.0beta2</a>
用下面代码随意创建一个项目
<pre><code>
$ cd cocos2d-x
$ ./setup.py
$ source FILE_TO_SAVE_SYSTEM_VARIABLE
$ cocos new mygame -p com.your_company.mygame -l cpp -d /home/mygame
$ cd /home/mygame
</code></pre>
将新建的项目中的cocos2d文件夹拷贝到Earlybird/即可
库太大了，上传各种不方便，望体谅


版权声明
=================
该游戏创意和素材的所有权归原作者所有，本程序仅供学习使用

