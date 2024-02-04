# rime 中文/日本語/English 输入方案

## 简介

本项目为自用许久的 linux 端 rime 输入法配置，包含中文、日文、英文输入方案。

中文输入方案基于 [rime-cloverpinyin](https://github.com/fkxxyz/rime-cloverpinyin)

英文输入方案基于 [rime-easy-en](https://github.com/BlindingDark/rime-easy-en)

日文输入方案基于 [rime-japanese](https://github.com/gkovacs/rime-japanese)

修复了 cloverpinyin 的若干 bug，表情符号输入、部分字音错误等。觉得它的词库仍然不够全面，于是整合了 sogou 的所有词库，制作成了大小 300M 的 sogouall.dict.yaml

将 rime-easy-en 整合到了 cloverpinyin 中，并增加了日语输入方案

## 使用

下载本项目的[Release](https://github.com/xororz/rime-zh_en_jp/releases)，解压到你使用的输入法的配置文件夹，重启输入法即可。

先按<kbd>F4</kbd>再按数字<kbd>3</kbd>可以切换 中文/日本語 输入法方案。

Windows 用户慎用，印象中在 Windows 上的尝试没有成功过。

## 最佳实践

fcitx/fcitx5 可以使用输入法皮肤，改善使用体验。

使用类似 Dropbox 的软件，修改 installation.yaml 配置同步文件夹，以便在多台电脑上使用相同的输入法配置，并积累个人词库。
