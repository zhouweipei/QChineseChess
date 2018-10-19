# QChinessChess

QChinessChess 是一个 Qt 实现的网络对战象棋游戏。提供保存/加载棋局、计时、认输等功能。

![新游戏](img/newgame.png)

Notes:

- 无论是新游戏还是加载残局，都默认开局的一方是红方（即：若是新游戏，则一定是开局者先走；若是从残局加载，则开局者执红，谁先走视残局文件而定）。

- 在游戏进行的过程中，任何一方都可以在自己走子/对方走字的时候选择认输/保存残局。保存残局不会影响游戏进程。

有关软件设计的内容，参见 `readme.pdf` 。