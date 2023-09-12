# RizPS-Reborn (RZPR)
# 废弃警告
### 这是一个已被废弃的项目，除非你要考古不然请不要使用它，这个项目中充斥着各种杂乱的代码导致我们不得不进行重写，新的项目叫[RizServer](https://github.com/osp-project/RizServer)，它将带着RizPS-Reborn的使命继续前行

## 项目介绍
由Grasscutter原班人马献上，RizPS-Reborn（简称为RZPR）是针对 **某款简约风全屏判定音乐游戏** 的服务端重实现，为简洁而生，一个文件夹，拷贝即走，兼容多种系统，无需任何额外依赖，无需安装数据库，支持多用户，使用Rust编写

RizPS-Reborn可实现让你无任何限制地随意畅玩这款游戏。RizPS-Reborn的名称中虽然包含RizPS，但它与RizPS这个已经被DMCA的项目不存在任何关系与关联，RizPS-Reborn是一款全新 **从0开始编写** 的开源项目

## 功能实现
[x] 完全模拟**某款简约风全屏判定音乐游戏**的发行商的SDK

[x] 完全模拟**某款简约风全屏判定音乐游戏**的游戏服务端（甚至速度更快，因为官服是nodejs + express，我们使用Rust）

[x] 成绩保存与修改、支持多用户

[x] 使用WebPanel进行便捷的远程管理

[ ] 离线更新与自定义下发bundle（在做了在做了，我们只需要解决cridata的问题）

[ ] catalog动态调控

## 运行要求
***RizPS-Reborn目前仅支持游戏客户端的港澳台版本，请注意这点***

RizPS-Reborn的运行本身并没有任何特殊要求，只需要一台运行Windows操作系统的电脑，若您正在使用MacOS或Linux，也可以自行下载源代码进行编译运行

但RizPS-Reborn需要与 **某款简约风全屏判定音乐游戏** 建立连接后才能发挥其作用，并且为了让游戏与RizPS-Reborn连接，您也需要对您自己的手机进行些许 **系统级** 的修改。为了做出这些修改，如果您正在使用iOS，那么您必须拥有一个未被Apple进行任何限制的Apple ID；若您正在使用Android，则 **必须拥有root权限**，并确保根目录和System分区可写。

## 使用教程

查看RizPS-Reborn的Docs: [Click Here](https://osp-project.github.io/RizPS-Reborn-Docs)
