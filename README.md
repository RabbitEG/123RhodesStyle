# 123 罗德岛：纯分析版

这是一个只发布分析文字、索引数据、提示词记录和评估笔记的公开仓库。

仓库不包含《123罗德岛！？》的官方原图、整页图、裁剪图、contact sheet 或其他视觉复制作物。原始素材来自鹰角网络官方漫画页面：[123罗德岛！？](https://comic.hypergryph.com/terra-historicus/comic/6253)。官方素材的版权、角色、商标及其他权利仍归相应权利人所有；本仓库不授予任何使用官方素材的许可。

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
