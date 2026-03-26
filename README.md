# 🪞 Symmeme Generator

一个纯前端的图片对称处理工具，专为生成对称表情包（Symmetrical Memes）设计。支持自定义对称轴位置和方向，可部署在 Cloudflare Pages 上，无需后端服务器，所有处理均在本地浏览器完成，保护用户隐私。

[![GitHub stars](https://img.shields.io/github/stars/fangbm/symmeme-generator?style=social)](https://github.com/fangbm/symmeme-generator)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/fangbm/symmeme-generator/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Cloudflare%20Pages-orange)](https://pages.cloudflare.com/)
[![Tech](https://img.shields.io/badge/tech-HTML5%20Canvas-green)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

🔗 **在线演示**: [https://symmeme-generator.pages.dev](https://symmeme-generator.pages.dev) (示例链接)

## ✨ 功能特性

- **双向对称模式**：支持左半边→右半边、右半边→左半边两种镜像方向
- **自定义对称轴**：滑块调节对称轴位置（1%-99%），实时预览红线标注
- **智能拉伸填充**：自动拉伸镜像内容填满目标区域，无透明间隙
- **性能优化**：拖动时仅更新参考线，释放鼠标后才渲染，避免卡顿
- **文字水印**：支持添加自定义文字，可调节位置、大小、颜色和字体
- **多格式导出**：支持 PNG（无损）、JPEG、WebP 格式下载
- **隐私保护**：纯本地处理，图片不会上传到任何服务器
- **响应式设计**：支持桌面端和移动端使用

## 🚀 快速开始

### 本地使用

1. 克隆仓库
   ```bash
   git clone https://github.com/fangbm/symmeme-generator.git
   cd symmeme-generator
