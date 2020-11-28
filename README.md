<h1 align="center">X Hero Siege 3.30 修正重制版</h1>

<p align="center">
<a href="./CHANGELOG.md">更新日志</a> |
<a href="https://shimo.im/docs/JYc6w8RkwJjgHCrp/">在线更新日志(石墨文档)</a> |
<a href="https://mubu.com/doc/47nH6XS-KsM">地图入门文档(幕布)</a>
</p>

<p align="center">这是一张经典的魔兽RPG图, 此版本根据XHS吧主汉化原版3.30的基础上进行二次开发</p>

## 二次开发

### 工具需求

- [YDWE](http://www.ydwe.net/download.html)
- [Visual Studio Code](https://code.visualstudio.com/)
- w3xlni(**项目已内置目前最新版2.7.2**)

### 具体步骤

1. 克隆此项目到你的本地(或下载项目的压缩包)
2. 安装YDWE(已安装可跳过)
3. 安装VSCode(已安装可跳过)
4. 使用VSCode打开此项目
5. 安装VSCode扩展 `jass.jass`
6. 已配置好各项`运行任务`
   1. 运行`Release-运行`/`Debug-运行` --> 调试运行地图
   2. 部署`部署` --> 会使用 `slk` 优化地图后自动改名成 `X_Hero_Siege_{当前版本号}.w3x`
7. 编辑触发请修改 `war3map.j` 文件, 改物编数据则修改 `table` 目录下的文件

## 项目基本结构

```
X Hero Siege 3.30 修正重制版
 ├── map
 │   ├── war3map.doo
 │   ├── war3map.j          // 触发脚本文件
 │   ├── war3map.mmp
 │   ├── war3map.shd
 │   ├── war3map.w3c
 │   ├── war3map.w3e
 │   ├── war3map.w3r
 │   ├── war3map.wpm
 │   ├── war3map.wts
 │   ├── war3mapskin.txt
 │   └── war3mapUnits.doo
 ├── releases               // 地图部署发布目录
 ├── resource               // 资源目录
 ├── table                  // 数据相关文件(物编/导入/地图信息等)
 └── tools                  // 工具目录(无需变动)
```

## 捐赠支持

开发维护不易, 如果你喜欢我对这地图的更新, 可以给我赏几个钱.😀

微信扫码赞赏:

![微信赞赏码](images/wechat_pay.jpg)

### 捐赠感谢名单

-  **郑**  - ￥33
