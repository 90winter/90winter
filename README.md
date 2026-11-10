# 你好，我是 90winter（BH3RIJ）

平时用 AI 做一些 CATIA 和 Windows 小工具，也喜欢业余无线电。

代码由 AI 实现。我主要提需求、试用工具，再根据结果慢慢调整。运行方法和目前的限制都记在各项目的 README 里。

## 做过的小工具

| 项目 | 解决的问题 |
| --- | --- |
| [CATIA BOM 导出](https://github.com/90winter/catia-bom-export-by-caa) | 将 CATIA V5 的多实体零件导出为带缩略图的 Excel BOM。通过 CAA 测量体积、表面积和质心，按测量值归并重复实体，再用 C++ OpenXML 写入报表。[下载 Windows 便携版](https://github.com/90winter/catia-bom-export-by-caa/releases/tag/v2.0.0) |
| [MediaCompressor](https://github.com/90winter/MediaCompressor) | 在 Windows 上批量压缩图片和视频，按拍摄时间整理输出。视频使用 FFmpeg 和 NVIDIA NVENC，并在开始处理前实际编码一帧，检查显卡和驱动是否可用。 |
| [CatiaToolsDemo](https://github.com/90winter/CatiaToolsDemo) | 用 VB.NET 和 COM 后期绑定为 CATIA V5 实体着色，可根据体积、面积或重心生成可重复的配色。目前已验证 Windows 编译，CATIA 实机验证待完成。 |
