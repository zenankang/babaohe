# 本仓库说明

某游戏过程中遇到的小问题，写个工具模拟出解法。

# 使用方法

下载babaohe.exe程序并打开，[下载地址](https://github.com/zenankang/babaohe/releases/download/babaohe/babaohe.exe)

根据提示输入游戏初始状态，即可计算出解决方案并进行低级可视化展示。

展示过程中使用键盘A、D按键进行进度前后控制，使用R回到程序初始状态。

![微信图片_20231220041806](https://github.com/zenankang/-/assets/38875641/af0ab1db-3a1e-4bc9-899e-144a9b1a9713)

若遇到输入不合法或无解，程序会回到初始状态。

![image](https://github.com/zenankang/-/assets/38875641/390a5f6e-d714-4db6-98c9-808ae9bb28de)

# 代码说明

1、解答部分逻辑使用了BFS搜索，所得解法既是游戏总移动距离最短解决方案。

2、输出可视化界面由于基于windows控制台，十分简陋，勉强可视。

3、代码编写和编译运行工具为codeblocks 20.03 (MinGW) 系统为 win10
