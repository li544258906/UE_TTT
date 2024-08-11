# UE_TTT
1.项目文件基于Unreal Engine5.1.1，项目文件位于master分支
2.实现了井字棋游戏的双人对战和人机对战
3.游戏内容文件路径为/Game/StarterContent/TTT

备注：
1. 其中人机对战的AI是基于随机选取空位下棋的方式（没有接入真实ai去运算下棋策略，没有使用Minimax算法的原因是无法控制其下棋策略的难度）。
2. 分为两个关卡，一个TicTacToe_Game为下棋关卡，一个TTT_MainMenu是游戏选择界面关卡， 游戏启动关卡为TTT_MainMenu。
3. 游戏逻辑用蓝图实现。
4. 项目中为了实现跨关卡传递参数，使用了自己的GameInstance，对应的蓝图类为TTT文件夹下的 MyGameInstance。
