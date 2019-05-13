利用游戏Bug刷装备
==================================================

通过备份sharedstash.bin复制装备
--------------------------------------------------

原理:

共享存储箱中的物品信息保存在 ``C:\Users\username\OneDrive\Documents\my games\runic games\torchlight 2\save\sharedstash.bin`` 文件中.
而人物物品栏中的物品信息保存在 ``charactername_{uuid}.restore`` 文件中.

操作:

将打到的暗金装备放到共享存储箱中. 然后返回游戏主界面 (保存游戏). 备份 ``sharedstash.bin`` 文件到其他位置. 进入游戏, 将共享存储箱中的物品取出来. 将备份的 ``sharedstash.bin`` 文件拷贝回去. 这样共享存储箱中的物品就乘2了.


通过备份charactername_{uuid}.restore文件无限刷Boss
--------------------------------------------------

操作:

在打Boss之前 (传送之前), 保存游戏, 并将 ``charactername_{uuid}.restore`` 文件备份到其他位置. 杀死Boss后回城, 将战利品放入共享存储箱. 然后恢复 ``charactername_{uuid}.restore`` 文件. 就可以再次杀Boss了.
