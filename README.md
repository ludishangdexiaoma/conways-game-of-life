游戏玩法：
生命游戏在一个无限的二维网格上进行，每个格子代表一个细胞，有两种状态：存活（黑色）或死亡（白色）。下一代细胞的状态由当前周围8个邻居的状态决定，规则如下：
出生（Birth）
如果一个死亡细胞周围 恰好有3个存活细胞，则下一代中该细胞变为存活（繁殖）。
存活（Survival）
如果一个存活细胞周围 有2或3个存活细胞，则下一代中它继续保持存活。
孤独死亡（Underpopulation）
如果一个存活细胞周围 存活细胞少于2个，则下一代中它会死亡（孤立）。
过度拥挤死亡（Overpopulation）
如果一个存活细胞周围 存活细胞超过3个，则下一代中它会死亡（拥挤）。
所有细胞的状态更新是同步进行的，下一代的状态完全由当前状态决定。

所有权：L.ming
