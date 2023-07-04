# 变更日志

本文档记载了自 2023-06-30 以来的所有变更。

## 2023-07-04

`Stable Diffusion web UI` 版本 [v1.4.0-RC-18-gecc10c11](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/v1.4.0-RC)

- 增加对 [ControlNet v1.1.228](https://github.com/Mikubill/sd-webui-controlnet/tree/b9e09db324e4bf18d3a107fa4bfda501aaf3f6b5) 常用预处理器的翻译
- 增补内建脚本名称的翻译
- 对 `GFPGAN` 和 `CodeFormer` 分别作了注解
- 简化部分文字过长的翻译
- 增加对 [Catppuccin Theme](https://github.com/catppuccin/stable-diffusion-webui) 的翻译

## 2023-07-03

`Stable Diffusion web UI` 版本 [v1.4.0-RC-18-gecc10c11](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/v1.4.0-RC)

- 更新和修正 [ControlNet](https://github.com/Mikubill/sd-webui-controlnet.git) 的翻译
- 区分同名翻译（注：仅在 [journey-ad/sd-webui-bilingual-localization](https://github.com/journey-ad/sd-webui-bilingual-localization) 双语翻译加持下生效）
- 更新 [README](README.md)

## 2023-07-02

`Stable Diffusion web UI` 版本 [v1.4.0-RC-18-gecc10c11](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/v1.4.0-RC)

- 更新翻译
- 增补部分通知信息的翻译
- 增补 [OpenPose Editor](https://github.com/fkunn1326/openpose-editor.git) 的翻译
- 更新 [README](README.md) 的“更新本地翻译”章节

## 2023-07-01

`Stable Diffusion web UI` 版本 [v1.4.0-RC-18-gecc10c11](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/v1.4.0-RC)

- 更新翻译
- 增补被遗漏项的翻译，主要是 [ControlNet](https://github.com/Mikubill/sd-webui-controlnet.git) 的文本
- 由于下载的本地化模板未包含全部需要翻译的语句，因此在本地翻译中添加了一些分类标识：
  - `____HINTS_IN_JAVASCRIPT/HINTS.JS` 在 *javascript/hints.js* 中的提示
  - `____LABELS_AND_PLACEHOLDERS_NOT_IN_LOCALIZATION_TEMPLATE_BUT_IN_*.PY` 不在本地化模板中，但在 **.py* 中的标签和占位符
  - `____OPTION_INFO_NOT_IN_LOCALIZATION_TEMPLATE_BUT_IN_*.PY` 不在本地化模板中，但在 **.py* 中的选项信息
  - `____DROPDOWN_INFO_NOT_IN_LOCALIZATION_TEMPLATE_BUT_IN_*.PY` 不在本地化模板中，但在 **.py* 中的选项信息
  - `____ADDITIONAL_INFO_NOT_IN_LOCALIZATION_TEMPLATE_BUT_IN_*.PY` 不在本地化模板中，但在 **.py** 中的其他信息
  - `____ADDITIONAL_INFO_NOT_IN_LOCALIZATION_TEMPLATE_BUT_IN_EXTENSIONS_*.PY` 不在本地化模板中，但在扩展 **.py** 中的信息
- 更新 [README](README.md)

## 2023-06-30

`Stable Diffusion web UI` 版本 [v1.4.0-RC-18-gecc10c11](https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/v1.4.0-RC)

- 首次提交
