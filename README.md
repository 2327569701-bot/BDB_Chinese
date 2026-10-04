# BDB 简体中文汉化 V2

为 **Kerbal Space Program 1** 的 **Bluedog Design Bureau（BDB）** 制作的独立简体中文汉化附属项目。

**本仓库只提供汉化文件，不包含 BDB 本体，也不是 BDB 官方发行版。** 请先从官方项目安装 BDB 及其所需依赖，再安装本汉化包。

**[BDB 官方项目](https://github.com/CobaltWolf/Bluedog-Design-Bureau) · [BDB 官方下载](https://github.com/CobaltWolf/Bluedog-Design-Bureau/releases)**

## 下载汉化包

前往 **[Releases（发行版）](https://github.com/2327569701-bot/BDB_Chinese/releases/latest)**，下载 **BDB_Chinese.zip**。压缩包已整理好安装目录，只包含本项目的汉化文件和说明。

## 汉化内容

- 零件名称、制造商与零件说明，已完成所依据版本中 1,292 条完整简介的翻译。
- 构型、涂装、子型号和右键菜单选项，补充了大量菜单与提示说明的汉化，并修正了此前只翻译一部分的说明。
- SAF 整流罩的筒段数量、透明／开合状态、自动展开高度及展开动作。
- B9 零件信息面板，以及 BDB 的动态状态、中继信息窗口和设置选项。
- 科学实验名称及部分实验结果。
- 中文搜索关键词，同时保留英文搜索词。

保留 Kane、Sarnus、Bossart 等 BDB 系列名称和真实发动机型号，方便对照原项目的教程与飞船文件。汉化只改变显示文字，不改变零件性能或游戏玩法。

部分科学实验结果仍保持英文；其他模组额外加入的内容也可能需要单独适配。

## V2 更新与性能说明

V2 重点完善了 **零件右键操作窗口（PAW，Part Action Window）** 及其构型选择菜单、子选项和提示说明的汉化，包括 SAF 整流罩操作、B9 零件信息面板，以及 BDB 的动态状态和部分独立窗口。

可配置的文字通过 ModuleManager 汉化补丁覆盖；由程序生成的界面文字，则由本包自带的独立 UI 汉化插件在运行时处理显示内容。**不修改、替换或重新编译 BDB、B9PartSwitch、SAF 的原始 DLL。** 汉化包包含自己的插件 DLL，只负责显示文字，不改变内部 ID、零件参数或模拟逻辑。

V2 开发初期，拖拽时重复处理整艘飞船、频繁搜索场景对象及反复刷新窗口，造成了严重的额外开销。现已减少重复处理、缓存界面控件并限制刷新频率。

**经维护者本人本次人工测试，拖拽火箭时的卡顿已经消失，未再观察到此前的性能拖累。** 这一结果仅适用于本次测试环境和操作，不代表所有界面及模组组合都已验证。运行时 UI 汉化仍可能带来一定性能开销，也不排除其他环境下出现问题；如果遇到卡顿或界面异常，欢迎附上复现步骤、模组版本和日志反馈。

## 安装

本汉化依据 **BDB v1.14.0** 制作，菜单汉化针对 **KSP 1.12.5**。请使用简体中文游戏语言。

1. 按照 [BDB 官方说明](https://github.com/CobaltWolf/Bluedog-Design-Bureau) 安装 BDB 及其所需依赖。
2. 从 **[最新发行版](https://github.com/2327569701-bot/BDB_Chinese/releases/latest)** 下载 **BDB_Chinese.zip**，然后解压。
3. 退出游戏，将解压得到的 **BDB_Chinese** 文件夹复制到游戏的 **GameData** 文件夹中。
4. 将游戏语言设为简体中文，再启动游戏。

安装后的目录应为 `Kerbal Space Program/GameData/BDB_Chinese`。只复制这一层文件夹，不要把整个下载的仓库文件夹放进去。

更新时，请先移除旧的 `GameData/BDB_Chinese`，再复制新版。卸载时删除这个文件夹即可，无需改动 BDB 本体。

## 问题反馈

如果发现漏译、译文不准确或显示异常，欢迎在本仓库的 **Issues** 中反馈。请尽量附上零件名称、截图，以及使用的 BDB 版本。

## 致谢与许可

感谢 **Matthew（CobaltWolf）Mlodzienski** 及所有 BDB 贡献者创造了这个模组。原版内容、名称及相关权利归原作者所有。

本项目的翻译与改编文本遵循原作的 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** 许可：转载请注明来源，不得用于商业用途，衍生作品须以相同许可分享。

本仓库不分发 BDB 的模型、贴图、音效或程序文件；获取原版模组请前往 **[Bluedog Design Bureau 官方项目](https://github.com/CobaltWolf/Bluedog-Design-Bureau)**。
