**注意:所有指令都是在聊天框中输入!**

##### 如何开始比赛
1. 第一个进去的人输入`.setup`进行初始化设置(特别是双方人数设定)
2. 其余人进入游戏，并且所有人输入`.ready`进行准备
3. 如果双方人数都达到最大值且都准备，则进行地图投票
4. 投票完毕后进入新的地图，所有人再输入`.ready`进行准备
5. 静候比赛开始吧！

*如果双方人数不均衡，先让一个人退出，等到了第$5$步时候再进入服务器*


##### 皮肤修改相关指令
[插件地址 - weapon](https://github.com/kgns/weapons/tree/v1.7.1)
[插件地址 - 手套](https://github.com/kgns/gloves)
- `!ws`     修改武器皮肤
- `!glove`  修改手套(可能需要重生后才生效)

##### 比赛插件pubSetup相关指令
[插件地址 - PubSetup](https://github.com/splewis/csgo-pug-setup)
- `.setup`, begins the setup phase and sets the pug leader
- `.10man`, an alias of setup with 5v5, captains, and a mapvote   快捷设置5v5对战
- `.ready`
- `.notready`
- `.pause` requests a pause (which takes effect next freezetime)  暂停
- `.unpause` request an unpause                                   取消暂停
- `.start` starts the game if auto-live has been disabled
- `.capt` gives the pug leader a menu to select captains          给队长菜单用来选择队员
- `.rand` selects random captains                                 随机选择队员
- `.leader` gives a menu to change the game leader                改变队长
- `.endgame` force ends the game safely (only the leader can do this, note that this resets the leader to nobody) 投票结束比赛
- `.forceend force ends the game without a confirmation menu 强制结束比赛
  
以下4个为拼刀胜利后的指令
- `.stay` chooses to stay after winning a knife round         保持原队伍
- `.swap` chooses to swap after winning a knife round         交换队伍
- `.ct` chooses to start on ct after winning a knife round    到ct队伍
- `.t` chooses to start on ct after winning a knife round     到t队伍
