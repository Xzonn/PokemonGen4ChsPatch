# 《宝可梦》第四世代字库扩容补丁

本项目用于对《宝可梦》第四世代游戏的字库进行扩容，以支持更多的汉字和符号。本补丁不包含汉化文本，如需汉化文本请使用 **[《宝可梦》第四世代汉化修正补丁](https://github.com/Xzonn/PokemonChineseTranslationRevise)**。

## 使用方法
### `arm9.bin` 补丁

1. 提取 `arm9.bin`，可使用 [ndstool](https://github.com/devkitPro/ndstool) 或 [CrystalTile2](https://www.romhacking.net/utilities/818/)。**注意：《心金／魂银》的 `arm9.bin` 被压缩过，需要对其进行解压缩。可使用 [ndspy](https://github.com/RoadrunnerWMC/ndspy) 或 CrystalTile2 自带的解压功能。**
2. 根据游戏版本和语言版本导航到对应的目录下，并对前一步提取的 `arm9.bin` 应用相应的 IPS 补丁，可使用 [Lunar IPS](https://www.romhacking.net/utilities/240/) 或 [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/)。
3. 将 `arm9.bin` 重新导入游戏 ROM，可使用 ndstool 或 CrystalTile2。**注意：如果对《心金／魂银》的 `arm9.bin` 重新压缩，可能需要同步修改 [arm9.bin 中存储的文件大小](https://github.com/Xzonn/PokemonChineseTranslationRevise/issues/16)。**

### 字体补丁

（二者选其一）

1. 根据游戏版本和语言版本导航到对应的目录下，采用 [NitroPatcher](https://github.com/Xzonn/NitroPatcher) 应用相应的 XZP 补丁。
2. 也可使用 [PCTRTools](https://github.com/Xzonn/PCTRTools) 自行创建字体并导入，但请确保使用 [《宝可梦》第四世代汉化修正补丁所用的码表](https://github.com/Xzonn/PokemonChineseTranslationRevise/blob/master/files/CharTable.txt)。

## 效果预览

![游戏截图](assets/images/screenshot-D.png) ![游戏截图](assets/images/screenshot-Pt.png) ![游戏截图](assets/images/screenshot-HG.png)

## 参见
- [基于 pret 项目的《宝可梦 钻石／珍珠》汉化](https://xzonn.top/posts/Pokemon-DP-Chinese-Localization-Based-on-Pret-Project.html)
