# 关于处理器你需要知道的每件事

[![][b]][b]
```
   我们的手机 ，主机以及笔记本电脑已经成长得如此的成熟 ，以至于它们进化成为我们的一部分 ，而不只是一种设备 。
   在应用和软件的帮助下 ，处理器执行许多任务 。我们是否曾经想过是什么给了这些软件这样的能力 ？它们是如何执行他们的逻辑的 ？它们的大脑在哪 ？
   我们知道 CPU 或者是处理器是那些需要处理数据和执行逻辑任务设备的大脑 。
``
[![cpu image][1]][1]
```
    在处理器的深处有那些不一样的概念呢 ？ 它们是如何进化的 ？ 一些处理器是如何做到比其他处理器更快的 ？ 我们来看看关于处理器的主要术语并且它们是如何影响处速度的 ？
```
## 架构
```
    处理器有不同的架构 ，你一定偶遇过不同种类的那种你说它们是 64 位或 32 位的程序 ，其中的意思是程序支持特定的处理器架构 。
    如果一颗处理器是 32 位的架构 ，意味着这颗处理器能够在一个处理周期内处理一个 32 位的数据 。同理可得 ，64 位的处理器能够在一个周期内处理一个 64 位的信息 。
    你可以使用的 RAM 大小决定于处理器的架构 ，你可以使用的 RAM 总量为处理器架构的幂指数 。
    16 位架构的处理器 ，仅仅有 64 kb 的 RAM 使用 。32 位架构的处理器 ，最大可使用的 RAM 是 4 GB ，64 位架构的处理器的可用 RAM 是 16 Exa-Byte 。
```
## 内核
```
    在电脑上 ，核心是基本的处理单元 。核心接收指令并且执行指令 。越多的核心带来越快的速度 。把核心当成工厂里的工人 ，越多的工人使工作能够越快的完成 。另一方面 ，工人越多 ，你所付出的薪水也就越多 ，工厂也会越拥挤 ；相对于核心来说 ，越多的合兴消耗更多的能量 ，比核心少的 CPU 更容易发热 。
```
## 时钟速度
[![CPU CLOCK SPEED][2]][2]
```
    GHZ 是 GigaHertz 的简写 ，Giga 意思是 Billon ，Hertz 意思是一秒有几个周期 ，2 GHZ 的处理器意味着处理器一秒能够执行 2 百万个周期 。
    也被作为 `频率` 或者 `时钟速度` 被熟知 。这项数值越高 ，CPU的性能越好 。
```
## CPU 缓存
```
    CPU 缓存是处理器内部的一块小的存储单元 ，用来存储一些内存 。不管如何 ，我们都需要执行一些任务 ，数据需要从 RAM 传递到 CPU ，CPU 的工作速度远快于 RAM ，CPU 在大多数时间是在等待从 RAM 传递过来的数据 ，而此时 CPU 是处于空闲状态的 。为了解决这个问题 ，RAM 持续的向 CPU 缓存发送数据 。一般的处理器会有 2 ~ 3 M 的 CPU 缓存 。高端的处理器会有 6 M CPU 缓存 ，越大的缓存 ，意味着处理器更好 。
```
## 印刷工艺
```
    晶体管的大小就是处理器平板印刷的大小 ，尺寸通常是纳米 ，更小的尺寸意味者更好的兼容性 。这允许你更多的核心 ，更小的面积 ，更小的能量消耗 。
    这最新的 Intel 处理器有 14 nm 的印刷工艺 。
```
## 热功耗设计
```
    代表这电池的能量 ，单位是瓦特 。在全核心激活以基本频率来处理 Intel 模式 ，高复杂度的负载是一种浪费处理器的行为 。
    所以 ，越低的热功耗设计 ，对你越好 。一个低的热功耗设计不仅更好的利用电池能量 ，而且产生更少的热量 。
```
[![battery][3]][3]
```
    桌面版本的处理器通常消耗更多的能量 ，热功耗消耗的能量能够在 40% 以上 ，相对应的移动版本只有不到桌面版本的 1/3 。
```
## 内存支持
```
    我们已经提到了处理器的架构是如何影响到我们能够使用的内存总量 。这样我们只掌握了正确的理论 。在实际的应用中 ，RAM 的总量对于处理器的规格来说是足够我们使用的 ，由处理器规格详细规定 ，也包含支持的 DDR 版本的内存 。
```
[![RAM][4]][4]

## 超频
```
    前面我们讲过时钟频率 ，超频是程序强迫 CPU 执行更多的周期 。游戏玩家经常会使他们的处理器超频 ，以此来获得更好的性能 。这样确实回增加速度 ，但也会增加消耗的能量 ，产生更多的热量 。
    一些高端的处理器允许超频 ，如果我们想让一个不支持超平的处理器超频 ，我们需要在主板上安装一个新的 BIOS 。
    这样通常下回成功 ，但这种情况是不安全的 ，也是不被建议的 。
```
## 超线程
```
   如果对特定的处理需要添加核心是不合适的 ，那么超线程回建立一个虚拟核心 。
   当我们说双核处理器有超线程 ，这个双核处理器有两个物理核心和两个虚拟核心 ，在技术上讲 ，一个双核处理器拥有四核核心 。
```
## 结论
```
    一个处理器有许多相关的数据 ，这是对数字设备来说是最重要的部分 。我们在选择设备时 ，我们应该在脑海中仔细的检查处理器在上面提到的数据 。
    时钟速度 ，核心数 ，CPU 缓存 ，以及架构是比重最大的数据 。印刷尺寸以及热功耗设计比重要小一些 。
    仍然有疑惑 ？ 欢迎评论 ，我会尽快回复的 。
```

--------------------------------------------------------------------------------

via: http://www.theitstuff.com/processors-everything-need-know

作者：[Rishabh Kandari][a]
译者：[singledo](https://github.com/singledo)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://www.theitstuff.com/author/reevkandari
[b]:http://www.theitstuff.com/wp-content/uploads/2017/10/processors-all-you-need-to-know.jpg
[1]:http://www.theitstuff.com/wp-content/uploads/2017/10/download.jpg
[2]:http://www.theitstuff.com/wp-content/uploads/2017/10/download-1.jpg
[3]:http://www.theitstuff.com/wp-content/uploads/2017/10/download-2.jpg
[4]:http://www.theitstuff.com/wp-content/uploads/2017/10/images.jpg
[5]:http://www.theitstuff.com/wp-content/uploads/2017/10/processors-all-you-need-to-know.jpg
