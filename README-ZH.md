# RPG Maker XP用魔塔样板运行时库组件

[English](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README.md) |
[español](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/LEEME.md) |
[français](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/LISEZMOI.md) |
[日本語](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README-JA.md) |
[русский](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README-RU.md) |
__中文__ |

用于RPG Maker XP的魔塔样板运行时库组件（RTP）。

# 如何安装？

运行**regedit**（注册表编辑器），进入**计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Enterbrain\RGSS\RTP**（32位：计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Enterbrain\RGSS\RTP），创建字符串值，名称为**MagicTower**，然后更改**数据**值为**该RTP地址**。

# 如何应用？

打开**Game.ini**，更改**RTP2**的值为**MagicTower**（RTP2=MagicTower），或

打开**Game.rxproj**，选择**游戏 » 选择RTP**，更改**RTP2**到**MagicTower**。
