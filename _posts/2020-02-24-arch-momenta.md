---
layout:     post
title:      "Momenta Challenge比赛小记"
subtitle:   " \"与无人驾驶的第一次亲密接触\""
date:       2020-02-24 22:00:00
author:     "Groxyu"
header-img: "img/post-momenta.jpg"
catalog: true
tags:
    - 生活
    - Meta
---

> “Archive之青春的记录 —— 来自于2018年，纠结的我顶着毕业的压力不务正业~”

这段时间了解到了LJQ的人生经历，佩服到无以复加，决心一定要做一个不再限制自己的人。随后开始自学机器学习，学习Python。由于有一些基本基础，所以学起来倒也不是特别困难。后来的半年沉迷于天池上的机器学习大数据竞赛，最好的时候通过leakage data特征，也拿到了前20的成绩（但还是没有奖励啊！摔）。

那么再往前一步，带着小半年的经历后，就是需要找一个实习/线下封闭式比赛的渠道了，带着之前找工作的简历开始疯狂投有没有在暑假期间进行的AI相关的活动。投了很多CAMP，夏令营都被拒绝了，但后续的offer也到到来得很整齐：一个蓝火计划、一个Momenta的Challenge，还有8月多凑数的水会一则。突然感觉自己又繁忙了起来。。

![](/img/Newimg/momenta-offer.jpg)
<center><font size=2>"请忽略我的那篇在同一时间被接收的的水会一则"</font></center>

最后一番斟酌之后，放弃了教育部的蓝火计划，决定参加Momenta的MC world。事实证明，这是一个无比正确的选择。

Momenta第一次见面会定在七月初，那天下着瓢泼大雨，抵达公司后互相进行自我介绍，随后签实习的劳动合同（免费提供硬件、服务器让你进行比赛，免费提供三餐，居然还给发钱，真的良心！）。随后找到队友组队后便和大家开始了一段奇妙的旅程。同队的有清华大二的冯昊、清华大三的余唯民，北航大二的闫坤，北邮研一的刘帅，再加上我这个老头子= =。最开始以为我是最老的那一个，然而发现其它队里PhD也不少，只是我们队太过年轻。开发和比赛的场地都在清华的信息楼里，所以之后的20天，我和队友都一起穿梭于公司和清华之间（为了取饭）。

比赛的内容大致就是机器人足球赛，一个小球，敌我两个机器人，双方球门。规则是普通球赛的简化规则。视觉算法和控制算法主要是冯昊、余唯民和闫坤在搞，主要用来识别小球，球门，并进行测距等工作，以及小车后续的射门的运动轨迹。我和刘帅主要提供turtlebot和RoS的底层API供调用（小车运动的API、传感器等等）。

![](/img/Newimg/momenta-playground.png)
<center><font size=2>"比赛和调试用的场地"</font></center>

比赛期间，每天都为着同一个单纯的目标奋斗，每一个小功能做出来后都会无比开心。公司提供免费三餐零食，还有技术讲座，创始人交流会。

![](/img/Newimg/momenta-dinnertalk.png)
<center><font size=2>"Momenta Dinnertalk，主要是公司内大牛做技术分享"</font></center>

![](/img/Newimg/momenta-ren.png)
<center><font size=2>"公司CTO Shaoqin Ren，浑身发光的男人（忽略旁边的憨憨一枚）"</font></center>

队友们都很厉害，虽然被选为队长，然而论技术我可能是最菜的那一个（视觉什么完全不懂）= =，但也一直秉持着为团队贡献自己最大的力量而努力。最后的结果虽然表面上不太理想，但其实主要还是由于实际场地的不确定性太大，个人觉得我们小车的控制逻辑以及灵活性上是不逊于其它任何队伍的。在这段时间也收获到了非常非常多的东西，非常幸运可以认识其它四位队友，希望之后能有工作上再次合作的机会，生活上一起玩耍的机会。

![](/img/Newimg/momenta-tsinghua.jpg)
<center><font size=2>"你见过凌晨三点的清华吗？"</font></center>

总结这次比赛，收获到了很多，感悟到了很多。首先是翔哥说的那一句，当你的在一个封闭的环境中只专注一件事情的时候，你的效率会变得难以想象的高。其它事情何尝不是如此呢。真的很幸运Momenta提供了这样一个机会，让我们可以心无旁骛地提升和学习；第二是来自队友闫坤，在取饭的过程中聊天，说学生的身份真的很方便，在很多很多事情/技术活动上都有优惠也很方便，。只可惜我已经快要毕业了才认识到这个事情，感觉之前浪费了好多的学生时光= =但从现在开始，要更多更多更多地突破自己的小圈（先毕业吧啊！）。