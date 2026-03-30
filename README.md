# FigureArrowTool | 学术论文 SVG 矢量箭头生成器 🏹

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

**FigureArrowTool** 是一款专为科研工作者打造的纯前端、轻量级 SVG 矢量箭头生成工具。无论是用于电气工程架构图、虚拟电厂调度流程图，还是 ICPIES 等国际顶会的学术宣讲 PPT，本工具都能帮助你快速生成符合学术规范、数学上绝对平滑且支持符号标注的高质量矢量箭头。

## ✨ 核心特性

* **📐 极致的几何控制**：支持单/双向箭头切换，精准调节总体长度、弯曲程度（Bend）、箭头大小、箭身及颈部宽度。
* **📝 学术级文字标注**：
  * 内置基础 **LaTeX 符号解析**（输入 `\alpha`, `\Delta` 等自动转换为 Unicode 字符）。
  * 支持自由调整文字字体（Times New Roman, Arial 等）、大小、沿曲线位置及垂直偏移。
  * 文字方向可自适应翻转，支持加粗与斜体。
* **🎨 丰富的色彩与渐变**：支持自定义主体颜色，内置多种渐变模式（尾部渐隐、头部渐隐、两端渐隐、纯色），提升图表高级感。
* **🖼️ 描图辅助 (Trace)**：支持上传本地图片作为底层参考图，可调节透明度与缩放比例，方便临摹现有文献中的复杂拓扑结构。
* **💾 多场景导出方案**：
  * **导出 PPT 专用格式 (SVG)**：采用混合渲染技术（文字转 PNG 嵌入 SVG），彻底解决矢量图导入 Office PPT 后字体排版错乱、公式乱码的痛点。
  * **纯矢量 SVG**：保留完整路径和 `<textPath>`，适合导入 Adobe Illustrator 或 Visio 进行二次编辑。
  * **高清 PNG**：支持 3 倍超采样导出，背景透明，直接可用。

## 🚀 在线体验 (Live Demo)

👉 **[点击这里访问 FigureArrowTool 在线版] (https://chihirolkj.github.io/academic-arrow-tool/)**

## 💻 本地运行

本项目为 100% 纯前端单文件项目，**零依赖，无需安装任何环境或脚手架**。

1. 克隆或下载本仓库到本地。
2. 双击打开 `index.html`（原 `箭头生成器.html`）即可在任何现代浏览器中运行。

## 🛠️ 技术栈

* **核心**：HTML5 + CSS3 + Vanilla JavaScript (原生 JS)
* **矢量渲染**：DOM API 动态构建与操纵 `<svg>` 标签
* **曲线计算**：基于数学几何映射实现直箭头的弯曲变形（Warp Point）
* **无后端**：所有图像生成、Base64 转换与下载均在浏览器本地完成，确保科研数据与底图隐私安全。

## 👨‍💻 作者

**Liu Kaijun** *(如有改进建议或 Bug 反馈，欢迎提交 Issue 或 Pull Request！)*

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 协议开源，你可以自由地将本工具生成的箭头用于你的学术论文、毕业设计或商业演示中。
