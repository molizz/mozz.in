---
layout: post
title: 花了2天时间，终于实现了免费天气短信！
published: true
author: moli
comments: true
date: 2010-02-25 12:02:37
tags:
    - 免费
    - 免费天气短信
    - 免费短信
    - 天气预告
    - 电信邮件
    - 移动邮件
    - 联通邮件
categories:
    - works
    - other
    - life
permalink: /archives/947.html
---
[][1]是否记得移动公司提供的 天气提醒服务? 是的，每个月收费5元。我其实也想出这5元钱，毕竟不多，但还是算了，节约出5元钱跟女朋友发50条短信好多哦（_过些日子，莫粒将编写一个手机java程序，实现低流量的免费短信！敬请期待_）！所以，对于消费并不多的朋友，这将节约些银子~ 本功能还在测试ing，主要还在测试 是否能每日准时收到短信！在没有任何PHP编程基础的情况下，楞是编写了几百行代码。。累&#8230;

说了这么多，如何免费收到天气短信呢？

首先，我们知道移动/联通/电信 均提供 相应的电子邮件服务（注册邮件均免费！除了某些特殊服务需要缴费，但我们避免了，就不会收费的，虽然他们名声很臭，但还不至于得罪几百万客户！）, 相比其他的电子邮件, 他们提供一个很好的功能,那就是如果有新邮件, 他**会将邮件的内容发送到 客户的手机上, 并,这是免费的!**所以我们利用这一点,为我们服务,毕竟,我们每个月缴的话费中**90%是他们的利润啊!**

打开本博客的 **菜单 -》 服务 -》 查询天气，或者直接[点击这个][2]****进入网址，**然后填写你的 移动/联通/电信 的邮件账户.

并填写上你的**所在城市，**即可！

为了保证短信能顺利到达你的邮箱（这样他们才会发短信给你），你最好在邮件里**设置**好白名单 如移动的邮件：

[][3]

这样，我们发送过来的邮件就不会被当成垃圾邮箱(因为如果我们的用户量很大，频繁发送邮件的话，会遭到他们的封锁的)，加入白名单后，邮件就畅通无阻了。

 [1]: http://mymoli.cn/wp-content/uploads/2010/02/freemoblie.jpg
 [2]: http://mymoli.cn/mini/weather/
 [3]: http://mymoli.cn/wp-content/uploads/2010/02/baimingdan.jpg