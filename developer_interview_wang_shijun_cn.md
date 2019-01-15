Mixin Network有很多开发者，我们将持续的采访他们，了解他们的故事，希望他们的故事能对开发者有帮助。
本期开发者的 github地址是 https://github.com/wangshijun
## 开发者大赛
mixin开发者大赛正在进行中，javascript, python, ruby, php, go程序员都可以来赢30万大奖。

大赛地址活动地址 http://mixin.one/events/hackathon

开发者入门文档 https://mixin-network.gitbook.io/mixin-network-cn

## 访谈正文

> 能否介绍一下你自己？

我是王仕军，JS 全栈工程师，2017 年接触区块链，通过 Coursera 上面的 CryptoCurrency 课程搞懂了区块链技术之后，对区块链技术非常看好。我工作之余也会写写技术文章，可能很多人已经通过下面这些渠道接触过我：

* 知乎专栏[《前端周刊》](https://zhuanlan.zhihu.com/feweekly)作者，高质量技术[视频教程](http://47.104.23.85/courses)作者；
* 掘金小册[《用 npm script 打造超溜的前端工作流》](http://t.cn/REb5oGv) 和[《写给前端工程师的以太坊智能合约+DApp开发入门》](http://t.cn/RuxYGUZ)作者，所写的都是我非常感兴趣的领域；
* GitHub 主页：https://github.com/wangshijun ；

> 你是什么时候开始学习编程？

本科大二的时候开始学习编程，大概 2007 年的样子，当时校内网特别的流程，让我着迷的是在个人主页上加上各种代码能让页面变的与众不同、更加炫酷，于是我就开始学习和研究背后的技术，而从那之后就再也没有玩过校内网了。从 CSS、HTML 开始，再到 JS、PHP，再到最后用 JS 做前端、后端、后台、客户端的端到端开发，算上来已经折腾快 10 年了，编码对我来说是件非常有乐趣的事情。

> 你日常使用的编程软件是哪些？比如 IDE，debugger

随着技术的进步，我常用的编程软件也在慢慢进化，当然最钟情的就是 VIM 了，简洁高效，不管在什么现代编辑器里面，我都会启用 VIM 模式，当然现在的主 IDE 是 VSCode。调试工具就比较多了：网络调试用 Charles，页面调试用 Chrome Dev Tools，API 调试用 Postman，IDE 本身也自带了非常强大的调试功能。

> 你日常使用的硬件是哪些？

最常用的硬件就是 15 寸的 Mac Book Pro，从 2013 年开始使用之后就喜欢上了，并且安利身边的不少工程师朋友入手，当然大尺寸显示器在做前端开发的时候也是必不可少的，再配上机械键盘，开发体验就非常棒了。

> 你是什么时候，从哪个渠道知道 mixin network？

Mixin Network 项目 2017 年底就听说了，随后就定期关注这个项目，从最开始的 Messenger，到后来的 Developer Dashboard。

> 是什么原因促使你花时间写 nodejs 的库？

- 首先，软件正在吞噬这个世界，而 JS 正在吞噬软件，前半句毫无疑问，后半句可能有些夸张，但是应用层西越来越多在用 JS 开发，从 GitHub 语言统计来看，JS 开发者数量最近几年也是高速增长的状态，Mixin 或者说任何一个平台项目都需要一个容易上手并且好用的 JS SDK 才能获得更得开发者的青睐；
- 其次，Mixin 社区已经有 [mixin-node](https://github.com/virushuo/mixin-node) 可以用，但是里面对 Mixin Network 能力的封装不够全面，在易用性、代码风格、测试上面也有不少改进的空间。

> 你从什么时候开始学习和使用现在这个语言来写 mixin network 上的库

就像上面说的，我学习和使用 JS 有接近 9 年的历史，不过 [mixin-node-client](https://github.com/wangshijun/mixin-node-client) 项目初始化是在 2018 年上半年，当时我准备做个 Mixin Bot，[mixin-node](https://github.com/virushuo/mixin-node) 基本能 work，但是大量的接口调用代码还是得自己封装，就萌生了封装个对 JS 开发者更好用的 SDK 的想法，当时测试网还没有官宣上线，我忙其他事情把这个就暂时搁置了。

> 写这个库的过程中，有什么特别的感受？

在 Mixin Network 作为区块链应用开发平台，足够开放，在其上开发应用，特别像开发微信小程序或者微信服务号，开发者的迁移成本会非常低。

> 做这个库有什么收获，有没有收入？

坦白的说开发 [mixin-node-client](https://github.com/wangshijun/mixin-node-client) 没有金钱上的收入，但是怎么设计一个冗余代码比较少的 SDK，怎么在 SDK 中把平台能力做合理的拆分这些思考都让我收益良多，此外，作为半个区块链开发者，我非常期望能用自己的力量推动区块链技术的普及和应用。

> 对于 Mixin Network 有什么建议？

不光有 Mixin Network 的社区技术论坛，还需要有个地方能把社区的代码都组织起来，降低代码贡献者、新进入开发者的成本，比如做的相当成功的 React 项目，除了官方组织之外还有个 React Community 组织，这样项目会更有生命力。

> 你自己对于数字资产在未来的应用有什么看法？

这里我就借用 Ryan Sean Adams 的观点来说明我的看法：Software has eaten mail, commerce, maps, servers, taxis, Blockbuster, payments, photos, games, hotels, songs. Money is next on it's list!
