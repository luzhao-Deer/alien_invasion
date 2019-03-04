![游戏界面](https://img-blog.csdnimg.cn/20190304091124999.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NhaXdlaWppYTAx,size_16,color_FFFFFF,t_70)

## 配置：

pygame版本 1.9.4
python版本 3.6.0
主文件为alien_invasion.py

基于 Eric Matthes 的《python编程：从入门到实践》编写。
扩展了一些功能。

## 游戏指南：

鼠标点击白色“Your Name”输入框，输入你的名字
点击“play”开始游戏

## 操作：

方向左右键控制移动
空格键发射子弹

每消灭一个敌人会获得一定积分(右上角显示)，随Level提高游戏难度会加大，
相应的击中奖励积分会增加，每累计一定积分可获得一点能量值。

右下角的Power值表示剩余能量值，有两种可选用途(每次均消耗1点能量)：
1. 按方向上键，获得5秒无敌状态，不会被敌人子弹击中
2. 按左Alt键，发射超级子弹，比普通子弹更大，且命中一个敌人后不会
    立刻消失，使用得当可消灭整列4个敌人

## 其他
游戏结束会显示5秒排行榜Top10, 期间不可操作，过后可再次点击Play重新开始
游戏。（没有注销系统，游戏期间无法更改用户名）
