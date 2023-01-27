# Elecphi

## 简介

如题，用 js/canvas 还原 Phi&#103;ros 游戏画面，属于个人兴趣项目，仅用于学习和测试；

本程序最初是为了能让我在带触屏的电脑(二合一,~~希沃~~)上体验到~~完整~~能玩的Phi****；

游玩部分代码为 [@飞机上的长电视](https://space.bilibili.com/484759721 "苦逼初中洛天依(划掉)一个,没大事别找我") 在 [@lchz&#104;3473](https://space.bilibili.com/274753872)/[sim-phi](https://www.github.com/lchzh3473/sim-phi) 的基础上改编而成，与 [Phi&#103;ros](https://www.taptap.com/app/165287) 游戏本体和[厦门鸽游网络有限公司](http://www.pigeon-games.cn)无关；

**禁止**发布(公开)在此程序的基础上进行的任何**改编**后的程序,其他方面与 sim-phi 基本一致；

不提供游戏本体安装包及逆向工具/教程，也不提供谱面下载；

现阶段**禁止**向任何人提供能直接访问 Elecphi 及项目的网址和 Elecphi 安装包；

### 兼容性

本程序(电脑端)基于 Electron 框架构建,不用(过多)考虑兼容性问题

以下为本人(作者)做过测试的平台及其兼容情况:
| 系统 | 版本 | 兼容性 |
| --- | --- | --- |
| macOS (Electron) | Ventura(13 Beta 22A5331f) | 完美 |
| Windows (Electron) | 11 (22000) | 完美 |
| Windows (Electron) | 10 LTSC 2021 | 完美 |
| HarmonyOS 2 华为浏览器 | ? | 勉强 |
| Chrumium 系桌面端浏览器 | 100+ | 完美 |
| Safari on macOS | 16.1 (18614.2.1.1.1) | 较好 |
| UOS (Electron) | 20 | 完美 |
| Edge on Android | 108 | 勉强 |
| Kiwi Browser | 108 | 断触严重 |

### 联系作者
Tip:本人作为苦逼初中~~洛天依~~(ge ji)一个,时间十分宝贵.如没有**极其重要**的事请不要直接联系作者,优先在`GitHub`提出Issue.

联系方式详见[小破站](https://longtvonairplane.github.io "Tip:不是B站")首页右侧边栏

### 界面

#### 结算
![结算](./readme/ranking_0.0.11.png)


## 即将更新
### 大饼
#### 未完成
- 允许在曲目选择页面选择上传自定义谱面(zip格式/文件夹)
- 允许通过在曲目选择界面使用`HTML5 File API`将(zip)文件直接拖入窗口以游玩自定义谱面

## 版本号更新日志

### [0.0.14] - 2023/01/27
#### 改变
- 将游玩界面曲目信息显示在画面顶端
- Autoplay时不显示连击数,原acc处显示`AUTOPLAY`,并使用绿色判定线
- 使用全新暂停菜单

### [0.0.12] - 2022/12/27
#### 新内容
- 采用更好的~~全新~~架构,选歌界面不再需要等待即可进入,且没有了内存溢出的世纪难题
- 统计游玩时的断连次数,并在结算页面显示
#### 优化
- `Flick`判定与滑动速度挂钩

### [0.0.11] - 2022/10/05
#### 新内容
- 全新的结算界面
#### 优化
- 结算页面曲目名称显示大小,减小溢出可能性
#### 修复
- 按住`Hold`时移动会导致断连
