# remove_garbage_x_post_rule_cn

「垃圾推号大扫除」的防误伤强化版规则与脚本。

本项目用于屏蔽 X / Twitter 中文区常见垃圾黄推、引流号、博彩号、返佣号，同时尽量减少对正常用户的误伤，尤其是跨圈、日圈、病垢圈、LGBTQ 用户等常见命名方式。

## 文件说明

本仓库包含两部分：

```text
rules.json   防误伤强化版规则
script.js    修改版用户脚本
```

原 GreasyFork 脚本：

[垃圾推号大扫除 - Greasy Fork](https://greasyfork.org/zh-CN/scripts/573991-%E5%9E%83%E5%9C%BE%E6%8E%A8%E5%8F%B7%E5%A4%A7%E6%89%AB%E9%99%A4)

由于原脚本没有提供修改远程规则抓取地址的设置，本仓库额外提供了一份修改版 `script.js`，将默认远程规则改为本仓库的 `rules.json`。

## 推荐使用方式

推荐直接安装本仓库中的修改版脚本：

```text
https://raw.githubusercontent.com/Ce-daros/remove_garbage_x_post_rule_cn/main/script.js
```

规则文件地址：

```text
https://raw.githubusercontent.com/Ce-daros/remove_garbage_x_post_rule_cn/main/rules.json
```

如果已经安装了 GreasyFork 原版脚本，**先卸载原版**，再安装本仓库的修改版。

## 防误伤改动

本规则主要调整了原规则中容易误伤正常用户的泛化正则，尤其减少跨性别旗帜、日文假名、emoji作为用户名的正常 X 用户的误伤。


## 协议

原脚本基于 MIT 协议发布，本仓库的修改版 `script.js` 保留 MIT 协议。

本仓库仅为规则与脚本修改版，不是原 GreasyFork 脚本的官方版本。

## 注意

规则无法保证完全准确。垃圾账号格式会变化，正常用户的命名习惯也很多样。

如果遇到误伤或漏判，欢迎提交 issue 或自行修改 `rules.json`。
