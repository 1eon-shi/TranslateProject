[#]: collector: (lujun9972)
[#]: translator: (zhs852)
[#]: reviewer: ( )
[#]: publisher: ( )
[#]: subject: (Take a break at the Linux command line with Nyan Cat)
[#]: via: (https://opensource.com/article/18/12/linux-toy-nyancat)
[#]: author: (Jason Baker https://opensource.com/users/jason-baker)
[#]: url: ( )

在 Linux 命令行中观看 Nyan Cat 来稍适休息
======
> 你甚至可以在终端里欣赏彩虹猫。

![](https://opensource.com/sites/default/files/styles/image-full-size/public/uploads/linux-toy-nyancat.png?itok=eg1aEmBw)

今天是《Linux 命令行小玩具介绍》的第六天。在本系列文章中，我们将会探索一些娱乐用途（甚至有时完全没用）的 Linux 命令行小玩具。所有我们介绍的小玩具都是开源的。

也许你会问，他们都很独特吗？是的。不过，他们对你是否独特，我就不知道了。但是，我们相信你应该能在这系列文章结束之前找到至少一个好玩的玩具。

从[昨天的选题][1]继续：我们谈到了猫和彩虹。不过，在 Linux 命令行下有更有趣的彩虹和猫结合的程序吗？答案是肯定的。

我们不妨看看之前可以在命令行中使用 Nyan Cat 的方式吧。意料之中，2011 年发布的 [Nyan Cat][2] 可以用 **nyancat** 呈现在终端中。你想念这只曾火遍网络的 Nyan Cat 吗？看看下面这个视频记录吧，我会等你看完的。

<https://www.youtube.com/embed/QH2-TGUlwu4>

现在，让我们在终端中重新感受这个令人惊奇的体验吧。**Nyancat** 包正在很多地方被分发（比如 Arch、Debian、Gentoo、Ubuntu 等等…），不过我的系统（Fedora）没有，但是我们仍然可以很轻松地从源码编译它。事实上，我们只需要一行命令就能做完所有工作：

```
git clone https://github.com/klange/nyancat.git && cd nyancat && make && cd src && ./nyancat
```

这直接为我带来了一个 Nyan Cat 体验，甚至还有个计时器来显示我享受 “Nyan Cat 魔法”的时间。

![](https://opensource.com/sites/default/files/uploads/linux-toy-nyancat-animated.gif)

你可以在 [GitHub][3] 上找到 **nyancat** 的源码，它正以 [NCSA 许可证][4] 开源。

命令行版本的 Nyan Cat 可在[这个公共 Telnet 服务器上访问][5]（或者 [netcat][6] 也行），所以理论上来说你不必安装它。不过不幸的是，由于带宽限制，该服务器目前已经被关闭了。尽管如此，在各种老设备上连接老 Telnet 服务器上运行 Nyan Cat 的[照片][5]还是值得一看的，说不准你还会萌生搭建一个能让大家连接的公共服务器的想法呢（如果你真的搭建了，请务必告知作者，万一他们可能会向公众分享呢？）。

你想让我介绍一下你最喜爱的命令行玩具吗？请在原文下留言，作者会考虑介绍的。

瞧瞧我们昨天介绍的小玩意：[用 lolcat 为你的 Linux 终端增添些许色彩][1]。明天再来看我们的下一篇文章吧！

--------------------------------------------------------------------------------

via: https://opensource.com/article/18/12/linux-toy-nyancat

作者：[Jason Baker][a]
选题：[lujun9972][b]
译者：[zhs852](https://github.com/zhs852)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://opensource.com/users/jason-baker
[b]: https://github.com/lujun9972
[1]: https://opensource.com/article/18/12/linux-toy-lolcat
[2]: https://en.wikipedia.org/wiki/Nyan_Cat
[3]: https://github.com/klange/nyancat
[4]: http://en.wikipedia.org/wiki/University_of_Illinois/NCSA_Open_Source_License
[5]: http://nyancat.dakko.us/
[6]: http://netcat.sourceforge.net/
