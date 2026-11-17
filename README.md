# tech-image-gen

使用 ImageGen 生成或修改政务云、政府信息化方案中的技术架构图、流程图、协同关系图和数据关系图的 Codex 技能。

## 安装

在 Codex 中使用 `$skill-installer`，指定仓库 `isunky/tech-image-gen`、路径 `.` 和技能名称 `tech-image-gen`。也可以运行安装器的 `install-skill-from-github.py --repo isunky/tech-image-gen --path . --name tech-image-gen`。技能依赖 Codex 的 `$imagegen` 技能；修改 Word 文档时还需要可用的文档处理技能。

## 使用

在 Codex 中调用 `$tech-image-gen`，提供需要转换的文字、ASCII 图、现有图片或文档，并说明希望表达的主体及关系。

技能默认使用黑白灰工程制图风格，核对图中文字和箭头关系；如需将图片插入文档，请在请求中说明。

## 许可

参见 [LICENSE](LICENSE)。
