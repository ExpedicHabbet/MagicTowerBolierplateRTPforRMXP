# RPGツクールXP用魔法の塔ボリエプレートランタイムパッケージ

[English](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README.md) |
[español](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/LEEME.md) |
[français](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/LISEZMOI.md) |
__日本語__ |
[русский](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README-RU.md) |
[中文](https://github.com/ExpedicHabbet/MagicTowerBolierplateRTPforRMXP/blob/main/README-ZH.md) |

RPGツクールXP用の魔法の塔ボリエプレート（魔塔样板）ランタイムパッケージ（RTP）です。

# インストールには？

**regedit**(レジストリエディタ)を実行し、**コンピュータ\HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Enterbrain\RGSS\RTP**（x86の場合は：コンピュータ\HKEY_LOCAL_MACHINE\SOFTWARE\Enterbrain\RGSS\RTP）に移動し、**MagicTower**という文字列値を作成し、**データ**値を**このRTPのアドレス**に変更します。

# 適用するには？

**Game.ini**を開いて、**RTP2**の値を**MagicTower**に変更します（RTP2=MagicTower）、または、

**Game.rxproj**を開いて、**ゲーム » RTPを選ぶ**を選択して、**RTP2**を**MagicTower**に変更します。
