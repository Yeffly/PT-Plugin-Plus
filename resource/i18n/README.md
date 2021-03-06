# 关于多语言
> 多语言环境正在构建中，现阶段正在努力将中文翻译为英文，需要各位英文达人参与翻译、复核，待英文文案可用后，将作为其他语言的源文件以供翻译。

## 如何参与英文翻译？
- 您可以通过以下方式来参与
  - 通过在线翻译的方式来参与，欢迎加入：https://www.transifex.com/ronggang/pt-plugin-plus-dev
  - 直接以 `git` 方式更新本目录下的 `en.json` 文件；

## 多语言文案更新流程
- 中文词汇增加 -> 提交至 `transifex` 的 `dev` 项目 -> 翻译为英文 -> 复核 -> 转为正式文案 -> 翻译为其他语言

## 如何测试已翻译的新语言
- 更新助手至 `v1.0.9` 之后的版本；
- 进入助手配置页面；
- 点击右下角的 `切换语言` -> `临时添加新语言` ；
- 选择已经翻译好的语言文件，如：`zh-TW.json` ；
- 如果格式正确，应该就可以看到新的语言内容了；
- 如果是通过 `transifex` 在线翻译的，可以从 `transifex` 下载已翻译好的文件进行测试；
- 使用该方式添加的语言文件仅本次生效，浏览器重启后恢复到默认状态；