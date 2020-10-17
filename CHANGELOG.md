未发布版本:
- [ ] 支持 -random 双英雄
- [ ] 解决堵怪问题 => Trig_AttackCheck_Actions
=======
Changes 3.44:
[新增]
[更改]
- 开局基地物品购买间隔从 60s => 10s, 加快开局节奏
- BOSS平衡性调整
  - 深渊魔王
    - 取消重生物品
  - 阿尔萨斯[BOSS技能等级与极限难度相关,N4时为最高]
    - 神圣护甲(无敌)
      - CD 30s/35s/40s/45s => 50s/55s/60s/65s
- 优化了极限模式下结束闪电袭击的时机(打死深渊魔王后 => 开始打深渊魔王的时候)[此为同步原版3.33的更改]
- 优化了打死深渊魔王后开门较慢的问题
- 后期BOSS(深渊魔王, 四角的将领, 阿尔萨斯)开局无敌, 防止被提前打死, 导致无法触发后面的事件
[修复]
- 修复了阿尔萨斯BOSS传送技能的触发问题, 避免双英雄模式下出bug
- 修正了机枪的『克隆』技能描述
===========
QQ讨论群: 247044926
=======
Changes 3.43:
[新增]
[更改]
- 英雄技能平衡性调整
  - 基迦米(剑圣)
    - 镜像
      - 本体攻击力 50%/70%/85%/100% => 50%/65%/80%/85%
      - 所受伤害 200%/175%/150%/125% => 230%/210%/190%/170%
      - CD 15s/14s/13s/12s => 15s/13s/11s/10s
- 经验获取范围从3000 => 1900
- 取消之前镜像可共享神器光环的改动
- 镜像现在能接受装备/光环等的护甲加成了
- 微调双英雄模式换选英雄的CD
[修复]
- 修复了极限模式无闪电袭击的bug
- 修复了吉安娜的满级10级大招会添加到错误技能的bug
- 修正了剑圣的天赋技能『狂战士』描述
- 修正了 -info 命令中的错误翻译
===========
QQ讨论群: 247044926
=======
Changes 3.42:
[新增]
[更改]
- 优化了 -bt 命令, 现在会一次性买够书, 避免多人使用时可能会阻塞的问题
- 优化了双英雄模式选取英雄的流畅性, 现在切换英雄很流畅了
- 双英雄模式非当前英雄会无敌, 避免双英雄嘲讽卡怪的问题
[修复]
===========
QQ讨论群: 247044926
=======
Changes 3.41:
[新增]
[更改]
- 英雄技能平衡性调整
  - 基迦米(剑圣)
    - 镜像
      - 数量 3/4/5/6 => 2/3/4/5
      - 本体攻击力 65% => 50%/70%/85%/100%
      - 所受伤害 200% => 200%/175%/150%/125%
      - CD 3s => 15s/14s/13s/12s
  - 德鲁伊
    - 变熊
      - 降低攻击速度 => 加快攻击速度
      - 生命恢复描述有误, 取消生命恢复效果
  - 火枪手
    - 修正了『激光』技能描述
    - 补全其20级天赋技能未做完的部分
    - 火枪手升到20级后不会跌回1级重新升级, 且会自动学完所有技能
- 经验获取范围从1200 => 3000
- 资源交易量: 普通点击 500 => 1000; Ctrl点击 5000 => 50000
- 镜像可以共享神器的光环了(即在镜像旁边也能享受到光环的效果)
- 隐形单位也能共享神器的光环了(此处主要针对守望20级终极技能进行优化)
- 变形/变身后的单位也能共享神器的光环了
[修复]
===========
QQ讨论群: 247044926
=======
Changes 3.40:
[新增]
[更改]
- 优化了醉猫的『火神佑护』技能描述
[修复]
- 修复了醉猫的5级技能『火神佑护』描述与实际效果不符的bug(即护甲加成从200 => 100)
===========
QQ讨论群: 247044926
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
=======
Changes 3.34:
- 部分平衡性调整
  - 娜迦
    - 野兽幽魂: 快捷键改为G, 防止与20级群体传送大招的快捷键冲突
    - 10级大招: 更换了技能模板, 修复无技能图标的问题, 同时添加了技能描述文本
      - 技能效果: 降低周围敌人55%移速和25%攻速 => 降低周围敌人25%/45%移速和20%/35%攻速

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
- [x] Fixed bug: Arthas teleport bug in "Dual Hero Mode".
- [x] Fixed bug: Invulnerable units after "Final Wave" in "Extreme Mode".
- [x] Fixed bug: Player without a hero cannot select a hero after game level 1.
- [x] Fixed bug: Used "Tome of Knowledge" are not removed from game (tiny item model visible on map).
- [x] Fixed bug: Some ability icons displayed twice for "Mountain King" and "Tauren Chieftain".
- [x] Fixed bug: Sometimes heroes of some players are not revived.
