# 10mississippi
10Mississippi 是一款基于 [wepy](https://tencent.github.io/wepy/) 框架开发的音乐文学类小程序。

原本是自己想要有一个能够推荐自己喜欢的音乐而做小程序，没想到临到快做完的时候突然发现微信开放平台个人账户是没办法发布和音乐有关的小程序的。内心崩溃之余还是决定开源，本来也不是什么特别高端的小程序，能给大家在实际开发中带来一点点灵感就很满意了。

PS：喜欢的话，希望能给这个项目点个star，谢谢！！

## 小程序截图

<img src="https://raw.githubusercontent.com/wiki/getatny/10mississippi/1.png" width="300"></img>
<img src="https://raw.githubusercontent.com/wiki/getatny/10mississippi/2.png" width="300"></img>
<img src="https://raw.githubusercontent.com/wiki/getatny/10mississippi/3.png" width="300"></img>
<img src="https://raw.githubusercontent.com/wiki/getatny/10mississippi/4.png" width="300"></img>
<img src="https://raw.githubusercontent.com/wiki/getatny/10mississippi/5.png" width="300"></img>

## 如何运行
该小程序使用 [wepy](https://tencent.github.io/wepy/) 框架敏捷开发，不同于原生微信小程序开发，该框架引入了webpack对代码和资源进行打包。所以首先你需要确保你的电脑上已经安装了Node。

强烈推荐你安装wepy-cli，并通过wepy-cli创建新项目，之后将本项目内容覆盖新建项目中的src文件夹。运行以下代码：

```
    wepy build --watch
```

之后打开微信小程序开发工具，加载该项目即可看到小程序运行效果。

