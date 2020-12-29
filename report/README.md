## Chinese Chess

### 题目要求

**alpha-beta剪枝算法**

编写一个中国象棋博弈程序，要求用alpha-beta剪枝算法，可以实现人机对弈。棋局评估方法可以参考已有文献，要求具有下棋界面，界面编程也可以参考网上程序，但正式实验报告要引用参考过的文献和程序。

### 实现过程

首先我们构建象棋页面，这里我们使用了 go 语言中的 ebiten 库来构建我们的页面。

我们通过网络下载了有关中国象棋的棋盘、棋子以及音效这些资源，然后通过 ebiten 官方给出的 file2byteslice 工具将资源文件转化为对应的 []byte 数组，并且使用现有的轮子将这些资源放进map便于我们程序的使用。

### References

- [用Go写一个中国象棋](https://wangqianhong.com/tag/%e4%b8%ad%e5%9b%bd%e8%b1%a1%e6%a3%8b/)

-  IMPROVEMENT ON ALPHA-BETA SEARCH ALGORITHM IN CHINESE CHESS  YUE Jinpeng FENG Su(College of Information Science and Technology,Beijing Normal University,100875,Beijing,China)

