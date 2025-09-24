> 这里存放小组的一些合适的, 有趣的, Geek的探索和想法, 不限于技术, 产品, 思考, 生活, 
只要你愿意去折腾, 感兴趣, 我们一定能够把它们搞定, 大家可以自由组队一起研究, 一起分享。
> 这个其实经过这么多届的发展最终我发现，这个列表才是我们组底层能力的学习方向，也是咱们组的立组之本。

![feynman](https://github.com/Prithvirajbilla/build-your-own-x/raw/master/feynman.png)

---
# Contributer: Jin、Peterpan0927 、吕栋梁、李虹均、赵谦诚
# Finish List(recruiting): 

## 0x00. 初衷
简而言之, 如同组名一样, 我们要有探索精神, 折腾精神, 对疑难问题不妥协, 能写出高质量的技术分析, 提出独到的的见解, 多去创造而不是去搬运, 并且得有一定造轮子的能力

其次, 我们的例会分享, 应该尽可能有个**目标**, 这里的ideal就是帮大家细化一个具体的方向, 然后大家边研究可以边分享, 成长更快

尤其是技术领域, `Just Do it ~`

## 0x01. TODO List
目前列出大体探索点, 和对应参考难度(1~5星难度递增), 之后可以再分类别排列

### A. 技术研究
#### 1. 网络
1. HTTP2的设计, 变化, 优点, 考虑等.  (3星, TODO)
2. 科学上网的几种途径, 全面的体系了解 (3星, TODO)
3. VPN的工作机制和原理 (TODO)
4. ARP断网攻击(1星，TODO) [参考](https://www.52pojie.cn/thread-1787140-1-1.html)
5. 实现全协议隧道通信（3星，TODO）

#### 2. 前端
2. [Hexo](https://github.com/hexojs/hexo)的结构研究(4星, TODO)
3. [Hexo](https://github.com/hexojs/hexo)的性能分析(5星, TODO)
4. 如何编写自己的Hexo主题 (3星, TODO)
5. npm/yarn 包管理工具的原理和设计 (3星, TODO)
6. 如何参与开源, 融入开源社区 (2星, TODO)
7. 如何编写VSCode插件 (3星, TODO)
8. 实现一个markdown编辑器 (4星, TODO)
9. 前端智能化原理，如imgcook，确实很难，看学习到哪个程度了(5星，TODO)
10. 跨平台技术，flutter，electron等从应用到原理。（2星——5星，TODO）

#### 3. 服务端
1. Nginx的设计, 结构, 特点, 使用 (3星, TODO)
2. Nginx源码阅读 (5星, TODO)
2. Nginx性能相关优化和原理, 需细化拆分 (5星. TODO)
3. yum/apt 包管理工具的原理和设计 (3星, TODO)
4. Git的整体设计和数据结构 (4星, TODO)
4. 自己动手实现一个简版Database (4星, TODO)
5. Cache的设计, CPU如何与内存通信,  (4星, TODO)
6. 分布式三驾马车论文阅读和分享 (4星, TODO)
   - 分布式计算之Map-Reduce
   - 分布式存储之BigTable
   - 分布式文件系统之GFS
7. Socks5和HTTP代理的区别 (3星, TODO)
8. 分布式架构的设计和演变 (4.5星, TODO)
9. Linux下的网络编程 (3.5星, TODO)
10. EXT4-文件系统的设计与实现 (4.5星, TODO)
11. Unix/Linux内核学习 (5星, TODO)
12. 虚拟化与容器技术 (5星, TODO)
13. vim插件个性化拓展（3星，TODO）
	- 一个已经整理好的拓展包他做了哪些拓展？（可以参考代码随想录的PowerVim）
	- 自己模仿拓展方式再做个性化拓展

#### 4. 安全
- 破解植物大战僵尸（0.5星，TODO）[参考](https://bbs.kanxue.com/thread-278259.htm)
- 探索EDR的原理并尝试写免杀木马（4星，TODO）[参考1](https://synzack.github.io/Blinding-EDR-On-Windows/) [参考2](https://web.archive.org/web/20221126182533/https://pre.empt.dev/posts/maelstrom-edr-kernel-callbacks-hooks-and-callstacks/)
- ShadowSocks/ShadowSocksR/SSRR的研究和分析 (4.5星, TODO)
   - 服务端 (5星, TODO)
   - 客户端 (4.5星, TODO)
- V2Ray的研究, 对比SS, 实践和测试 (3星, TODO)
- 伪装HTTPS的[GFW-Trojan](https://github.com/trojan-gfw/trojan) (5星, TODO)
   - [上手使用](https://trojan-tutor.github.io/2019/04/10/p41.html) (2星, TODO)
   - 结构分析 (3星, TODO)
   - 源码阅读 (5星, TODO)
- KMS激活 (3星, TODO)
  - 大体的原理, 和单机的各种实践区别 (3星, TODO)
  - 实践: 让Lab都能安全优雅的使用KMS (3星, TODO)
- Android Xposed相关 (4.5星, TODO)
  - 整体框架结构, 原理, 来龙去脉 (3星, TODO)
  - Hook机制, Android启动机制学习 (4星, TODO)
  - 动手实现一个Xposed上的Hook-Demo (3星, TODO)
  - 动手实现一个Xposed上的Hook-App, 比如模拟定位器 (5星, TODO)
- iOS越狱开发相关（4.5星，TODO）
	- 越狱原理，越狱后的获得新的权限有哪些？（4星，TODO）
	- 了解各种Hook框架（CydiaSubstrate...）及其原理（dylib注入），尝试去diy系统的功能，比如修改通知栏界面样式（4星，TODO）
	- 尝试用Theos开发应用插件，普通版：增添一个button或新功能，加强版：破解一个小的付费app（5星，TODO）
- 抓包和分析包的上手使用 (3.5星, TODO)
- 栈溢出的历史发展过程，攻防演变，如Canary等mitigation及绕过（5星，TODO）

#### 5. 编程思想
1. 并发编程的前世今生, 背景了解 (3.5星, TODO)
2. 并发编程的几种经典模型 (4.5星, TODO)
3. 程序性能优化（4星,TODO）
	- 算法逻辑层面如何去做（对具体的实现做归纳，整理通用流程，如并行化流程等）
	- 物理层面优化如何去做（如何合理利用各类硬件？寄存器、多级缓存等）
3. 函数式编程之Scheme入门 (3星, TODO)
4. 如何在Python/Java中使用C/C++库 (4星, TODO)
5. JVM的内存管理, 对象的生命周期 (4.5星, TODO)
6. 简版JVM的设计与实现 (5星, TODO)
7. 竞态问题(线程安全)相关 (4星, TODO)
8. λ演算, λ与函数式编程 (4星, TODO)
9. 程序语言中不同锁的实现原理 (5星, TODO)
10. 更安全还是更黑暗 ---- RUST语言的入门 (4星, TODO)
11. JVM字节码相关 (5星, TODO)
    - 字节码注入, 动态修改字节码背景了解 (2星, TODO)
    - 字节码的设计和意义, 常见的字节码含义 (3星, TODO)
    - Arthas的使用和具体问题定位 (2星, TODO)
    - Arthas整体结构, 核心命令实现原理(源码阅读) (4.5星, TODO)
    - JIT的设计和实现 (4.5星, TODO)
12. C++中函数调用的内存模型，可以参考《深入理解C++对象模型》（4.5星， TODO）

### B. 产品思考

*TODO*

## 0x02. 其他
文档每个组内的同学, 都应该来不断完善, 或者再进行细分. 目前只是抛砖引玉, 写个简版

---

### 推荐资料:
1. [Build your own X -Github](https://github.com/Prithvirajbilla/build-your-own-x)
2. [软件架构设计专栏-zhihu](https://zhuanlan.zhihu.com/kls-software-arch-world)
3. [高性能计算学习路线·如果想玩的话](https://heptagonhust.github.io/HPC-roadmap/)
4. [System Design 学习路径](https://www.v2ex.com/t/897568)
