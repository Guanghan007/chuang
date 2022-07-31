# 实验

小组成员

成员一：
姓名：王逸腾
学号：202000460123
Git账户名称：Guanghan007

成员二：
姓名：孟冲
学号：202000460047
Git账户名称：mengchong0

成员三:
姓名：隋佩杭
学号：202000460064
Git账户名称：renxia1739

所做项目


项目一：

项目名称：research report on MPT

项目简介：默克尔树（Merkle树）又叫哈希树，是区块链数据存储运用到的一个重要的技术算法。

简单来说，哈希树（默克尔树）中，每个节点都标有一个数据块的加密哈希值。哈希树可以用来验证任何一种在计算机中和计算机之间存储、处理和传输的数据。它们可以确保在点对点网络中数据传输的速度不受
影响，数据跨越自由的通过任意媒介，且没有损坏，也没有改变。

完成人：王逸腾、隋佩杭、孟冲

代码说明：在CPP文件中有说明

运行截图：![图片](https://user-images.githubusercontent.com/109494359/182005215-8b308e11-38eb-48ef-97b2-3cd4f804bff8.png)
![图片](https://user-images.githubusercontent.com/109494359/182005221-aab41e60-150b-4043-92e3-c8f00831f558.png)

贡献说明：

王逸腾：负责编写主要代码，查找有关论文

孟冲：负责网上查找相关资料，完成前缀树、默克尔树、结构设计和一些基本操作的实现

隋佩杭：负责优化、校对代码，以及提供在不同设备上运行的结果对比


项目二：

项目名称：implement the naïve birthday attack of reduced SM3

项目简介：生日攻击其实是一个概率的问题，也就是说一个看起来很难发生的事情，事实上它发生的概率却很大。这种主观上和事实上的概率差距，让随机攻击成功的几率变的更高，这样的攻击就叫做生日攻击。这里是将生日攻击运用在SM的破解上。

完成人：王逸腾、隋佩杭、孟冲

代码说明：在CPP文件中有说明

运行截图：![图片](https://user-images.githubusercontent.com/109494359/182005253-b1367497-516c-49a1-90fe-7a7deb697154.png)

贡献说明：

王逸腾：查询资料，了解SM3原理，提供SM3代码

孟冲：利用网络查询资料，在SM3的基础上实现生日攻击找出有效碰撞

隋佩杭：编写部分函数，审核与整理代码，优化掉影响程序性能的冗余代码，最后测试与运行


项目三：

项目名称：implement the Rho method of reduced SM3

项目简介：rho的攻击方法正如其名，主要是通过不断地生成哈希值并保持前后的联系，最后生成一个环后即找到相应的碰撞。首先是成环的过程，这里的f函数用的2*x+1。

完成人：王逸腾、隋佩杭、孟冲

代码说明：大部分注释已在代码中说明

运行截图：
![图片](https://user-images.githubusercontent.com/109494359/182005293-9eefca48-26a5-41e1-a6c8-27544fab2b33.png)

贡献说明：

王逸腾：掌握rho的具体方法，提出代码思路

孟冲：查询利用python实现的SM3加密算法，代码测试与运行

隋佩杭：编写主要代码，通过控制不同输入bit长度重复测试运行时间（8，16，24bit）


项目四

项目名称：optimazation of SM3

项目简介：基于原SM3代码，通过快速实现消息扩展、预计算常量T、调整压缩函数的结构、以及优化函数中间变量的生成流程对SM3的实现进行优化。

完成人：王逸腾、隋佩杭、孟冲

代码说明：大部分注释已在代码中说明

运行截图：![图片](https://user-images.githubusercontent.com/109494359/182005308-363750af-04ad-4c18-968c-3f58e5b92db4.png)

贡献说明：

王逸腾：提出优化思路与方案

孟冲：网上查询相关资料，实现SM3以及代码审核

隋佩杭：编写主要代码，针对压缩函数（以及内循环）进行主要的优化，并将完成度表示并输出
