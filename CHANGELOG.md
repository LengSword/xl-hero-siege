未发布版本:
- [ ] 支持 -random 双英雄
=======
Changes 3.39:
[新增]
- 添加回原版被替换的原版本英雄(兽王以及幻影猎手), 并补上原汉化者未翻译完的技能描述
- 添加原版3.32中的新英雄: 德鲁伊
[更改]
- 再次调整了下读取界面里的帮助文本
- 删除了原作者遗留下的某几处的憨批检测, 避免可能会导致无法初始化和强度无法提升的问题
[修复]
- 修复了石头人的嘲讽技能描述错误的问题
===========
QQ讨论群: 247044926
=======
Changes 3.38:
[新增]
[更改]
[修复]
- 修复了特殊事件无法触发的bug
===========
QQ讨论群: 247044926
=======
Changes 3.37:
[新增]
[更改]
- 在强度提升后仍可使用 -random 命令选择英雄
[修复]
- 修复了2000杀敌数特殊事件可能会与山丘事件同时触发的bug
- 修复了火枪手天赋技能无描述的问题
- 修复了部分英雄的食物一开始会占用5人口的问题(应该)
===========
QQ讨论群: 247044926
=======
Changes 3.36:
[新增]
[更改]
- F9指令说明更新与优化
[修复]
- 修复了F9任务文本错位的bug
===========
QQ讨论群: 247044926
=======
Changes 3.35:
[新增]
- 新增全开/关门命令: -owa / -cwa => 就是把全部门都开了/关了
- 玩家2也可以使用 -fog 命令
[更改]
- 补上之前忘记记录的一个修改: 攻击城堡暂停 1分钟 => 5秒
- 大法在打全体镜像时会删除对应镜像的反魔法护盾技能, 使得大法在高难度下具有可玩性
- 大法天赋技能 CD5秒 => 10秒, 持续时间90秒 => 60秒
[修复]
- 修复了可以在100W特殊事件使用-bt命令的bug
- 修复了4分钟一次的特殊怪数量不足的bug
- 修复了有时某些玩家的英雄死亡不会复活的bug
- 修复了使用食物记录特殊怪杀敌数会影响到收入的bug
===========
QQ讨论群: 247044926

https://mubu.com/doc/47nH6XS-KsM
点这查看 『 新手入门与进阶文档(教程) 』 ，另外欢迎进群讨论和补充
=======
Changes 3.34:
- 部分平衡性调整
  - 娜迦
    - 野兽幽魂: 快捷键改为G, 防止与20级群体传送大招的快捷键冲突
    - 10级大招: 更换了技能模板, 修复无技能图标的问题, 同时添加了技能描述文本
      - 技能效果: 降低周围敌人55%移速和25%攻速 => 降低周围敌人25%/45%移速和20%/35%攻速4

=======
Changes 3.33:
- 修复了100W特殊事件无怪物刷新的bug
- 部分平衡性调整
  - 地穴领主(小强)
    - 尖刺外壳: 反弹伤害 1%/2%/3%/4% => 1%/2%/4%/6%
  - 战争傀儡(石头人)
    - 天赋技能: 改为防御技能, 开启后可减免35%的穿刺伤害(即龙, 刺客等单位的攻击)和魔法伤害(更改的原因是: 原天赋技能实际上原汉化者未进行任何修改, 是个完全无用的技能!)
    - 投石: 伤害 600/800/1000/1600 => 600/1200/1800/3500
    - 荆棘光环: 反弹伤害 1%/2%/3%/4% => 1%/2%/4%/6%
    - 嘲讽: 释放CD 15s/0s/0s/0s => 15s/12s/10s/8s; 影响区域 500/600/700/800 => 500/700/900/1100
    - 10级大招(宁静): 治疗生命值 每秒100点/400点 => 每0.5秒100点/400点
    - 20级大招: 溅射15% => 30%; 范围175 => 300
  - 恐惧魔王
    - 荒芜光环: 修复了还会加快魔法回复的问题
=======
Changes 3.33:
- Added a new item "Scepter of Mastery" with "Banish" to increase spell damage on single targets.
- Added "Storm", "Earth" and "Fire" as alternative models for "Sorceress", "Tauren Chieftain" and "Blood Mage" (selection: one-click 1 of the 3 heroes then press the down-arrow on keyboard).
- Fixed bug: Level 20 Ability is not added to "Druid of the Clow" in "Bear Form".

Changes 3.32:
- Added the commands -random and -repick for "Dual Hero Mode".
- New hero "Druid of the Claw".
- [x] Own "Wave Kills" and "Wave Kills" of current leadder are displayed in "food counter".
- [x] Significantly improved map loading.
- Added the command "-random 100".
- Retriggerd hero selection system.
- Improved the abilities of some dark heroes.
- Removed "Blink" from "Boots of Speed" because of abuse.
- Removed the pausing of player units that attacks castle.
- Fixed bug: Arthas teleport bug in "Dual Hero Mode".
- [x] Fixed bug: Invulnerable units after "Final Wave" in "Extreme Mode".
- [x] Fixed bug: Player without a hero cannot select a hero after game level 1.
- [x] Fixed bug: Used "Tome of Knowledge" are not removed from game (tiny item model visible on map).
- [x] Fixed bug: Some ability icons displayed twice for "Mountain King" and "Tauren Chieftain".
- [x] Fixed bug: Sometimes heroes of some players are not revived.
