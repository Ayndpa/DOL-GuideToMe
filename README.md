# GuideToMe 模组

## 简介

**GuideToMe** 是一个为 DOL（Degrees of Lewdity）游戏设计的模组，旨在为玩家提供更多与 NPC 嘴部互动的选项，例如引导 NPC 嘴部进行操作。

## 功能

- 添加了新的互动选项，允许玩家引导 NPC 嘴部到特定位置，同时允许玩家推开NPC的嘴。

## 文件结构

- **boot.json**: 模组的配置文件，定义了依赖项和功能模块。
- **actions-hands-left.twee**: 定义左手相关的互动逻辑。
- **actions-hands-right.twee**: 定义右手相关的互动逻辑。
- **actions-hands-pull.twee**: 定义从 NPC 身上移开嘴部的逻辑。
- **effects.twee**: 定义互动效果和结果。

## 安装方法

1. 下载Release中的最新版本的模组文件。
2. 使用ModLoader加载模组

## 依赖项

- **TweeReplacer** (版本 ^1.2.0)
- **ReplacePatcher** (版本 ^1.0.0)

## 注意事项

- 本模组可能与其他修改 NPC 行为的模组存在兼容性问题，请在安装前备份游戏存档。
- 如果在使用过程中遇到问题，请检查 `boot.json` 中的调试选项是否启用，并报告错误信息。