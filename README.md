# 123 罗德岛：纯分析版

这是一个只发布分析文字、索引数据、提示词记录和评估笔记的公开仓库。

仓库不包含《123罗德岛！？》的官方原图、整页图、裁剪图、contact sheet 或其他视觉复制作物。原始素材来自鹰角网络官方漫画页面：[123罗德岛！？](https://comic.hypergryph.com/terra-historicus/comic/6253)。官方素材的版权、角色、商标及其他权利仍归相应权利人所有；本仓库不授予任何使用官方素材的许可。

## 来源与加工流程

1. 原始研究材料是《123罗德岛！？》的官方原图漫画；本公开仓库不再分发这些图片。
2. GPT6-Astra Medium 模型对本地保存的全部官方原图漫画进行了完整浏览和风格分析，形成视觉规律、分类标签、精选参考坐标以及生成测试基线。
3. GPT5.6-Luna Max 模型在上述分析结果的基础上进行二次整理和加工，移除图片资产，统一为公开版目录结构，并将需要本地复核的文件改写为 `private_assets/...` 相对路径。

因此，本仓库是“**GPT6-Astra Medium 模型分析，GPT5.6-Luna Max 模型整理加工**”的纯分析记录，不是鹰角网络官方项目，也不代表其立场。

## 核心成果

本项目最核心的分析成果是 [`analysis/style_bible.md`](analysis/style_bible.md)。它将 GPT6-Astra Medium 对全部官方原图漫画的观察，经过 GPT5.6-Luna Max 的归纳、筛选和二次加工，凝结为一份可直接用于创作约束、风格复核和后续测试的视觉与叙事规范。如果只阅读一个文件，请从这份风格规范开始。

## 内容

- `analysis/`：风格规范、分类结果、样本清单和精选参考的文字化索引。
- `prompts/`：原创测试场景的提示词记录。
- `tests/`：生成测试的文字记录、漂移分析和历史基线。
- `private_assets/`：仅作为本地工作区的相对路径约定，公开版故意不放入源图或衍生图片。

## 相对路径约定

清单中的路径均以仓库根目录为基准，例如：

```text
private_assets/source/123罗德岛_官方原图/001_阿米娅篇/01.jpg
private_assets/derived/overview/01.jpg
private_assets/derived/contact_sheets/core.jpg
private_assets/derived/reference_crops/core_026_p1.png
private_assets/outputs/01_library.png
```

这些路径只用于记录本地分析时的对应关系，目标文件不会随公开仓库提交。需要在本地复核时，可按 `private_assets/*/README.md` 的说明放置文件；`.gitignore` 会阻止这些素材被误提交。

## 使用边界

本仓库的原创文字和代码未附带开放转载许可，除非另有说明。不要将仓库中的分析结论理解为对官方图像、角色或商标的授权，也不要用仓库中的路径索引替代原图发布。

本项目是视觉分析记录，不是鹰角网络官方项目，也不代表其立场。
