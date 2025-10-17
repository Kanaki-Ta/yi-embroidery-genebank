# 彝绣视觉基因库 | Yi-Embroidery Visual Gene Bank

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

*一个开源的、为AI与数字艺术提供动力的彝族刺绣文化基因库。*

*An open-source visual gene bank of Yi ethnic embroidery, powered for AI and digital art.*

---

项目简介 | Project Introduction

本项目旨在将历史悠久的彝族刺绣文化，特别是**南华彝绣**的经典视觉符号，转化为数字时代的“创意基因”。

我们系统性地为每个核心纹样（如火焰纹、马缨花、虎头纹）建立了“视觉身份档案”，包含其**标准化的AI提示词（Prompt）** 与**文化释义**。这使得设计师、艺术家和开发者能够像调用“代码库”一样，精准、轻松地在AI绘画、数字艺术和创意设计中运用这些文化元素，推动传统文化的现代化传承与创新。

This project aims to translate the timeless visual symbols of Yi ethnic embroidery, especially from **Nanhua Yi Embroidery**, into "creative genes" for the digital age.

基因库内容 | What's in the Gene Bank?

目前，基因库包含以下纹样的完整档案（持续更新中）：
- **火焰纹 | Flame Pattern**: 象征光明、热情与勇敢。
- **马缨花 | Azalea Pattern**: 象征母爱、生命与自然。
- **虎头纹 | Tiger Head Pattern**: 象征力量、威严与守护。

每个纹样的“基因档案”包含：
- **纹样名称**（中英文）
- **文化寓意**（中英文）
- **标准化Prompt**（中英文关键词，适用于主流AI绘画工具）
- **视觉范例**（由AI生成的多种风格化图像）


 快速开始 | Quick Start

您可以通过以下几种方式使用本基因库：

1.  **用于AI绘画（推荐）**：
    - 复制`/prompts`目录下您感兴趣的纹样Prompt。
    - 将其输入到如`Midjourney`, `Stable Diffusion`, `可灵` 等AI绘画工具中。
    - **强烈建议**结合图生图功能，并上传本库`/images/references`中的纹样图，以获得最佳效果。

2.  **示例：生成赛博朋克风格的火纹**
prompt

（可直接在AI工具中使用）

火焰纹，燃烧的，漩涡状，红与黑，彝绣图案，赛博朋克风格，霓虹发光，电路板纹理

Flame pattern, burning, swirling, red and black, Yi embroidery, cyberpunk style, neon glow, circuit board texture


项目结构 | Project Structure

Yi-Embroidery-GeneBank/

│

├── README.md          # 项目说明文件（本文件）

├── LICENSE            # 开源许可证文件

│

├── /docs              # 详细文档

│   └── 纹样文化释义.md    # 纹样的详细文化背景

│

├── /prompts           # 核心：提示词库

│   ├── flame_pattern_prompts.md

│   ├── azalea_pattern_prompts.md

│   └── tiger_pattern_prompts.md

│

├── /images            # 图像资源

│   ├── /references    # 原始纹样参考图

│   └── /generated     # AI生成的风格化范例

│

└── /metadata          # 元数据（供开发者使用）

└── patterns.csv   # 纹样信息的结构化数据


 如何贡献 | How to Contribute

我们热烈欢迎任何形式的贡献！您可以：
- **新增纹样**：提交新的彝绣纹样及其基因档案。
- **优化Prompt**：提供效果更好的提示词。
- **纠正释义**：完善纹样的文化背景描述。
- **扩展应用**：分享您基于本基因库创作的艺术作品。

**贡献流程**：
1. Fork 本仓库。
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)。
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)。
4. 推送到分支 (`git push origin feature/AmazingFeature`)。
5. 开启一个Pull Request。


开源许可证 | Open Source License

本项目采用 **知识共享署名 4.0 国际 (CC BY 4.0)** 许可证。

这意味着您可以自由地：
- **共享** — 在任何媒介以任何形式复制、发行本作品。
- **演绎** — 修改、转换或以本作品为基础进行创作。

只要你遵守许可协议条款，许可人就无法收回你的这些权利。

**简单来说，只需注明原作者（即本项目）的出处，您甚至可以用于商业用途。**

## 致谢 | Acknowledgments

- 感谢南华彝绣传承人们的卓越技艺与智慧。
- 灵感来源于所有致力于用科技传承文化的开拓者。


联系我们 | Contact

- 如有问题或建议，请在 [GitHub Issues](https://github.com/AizenGinutako/yi-embroidery-genebank/issues) 中提出。
- 项目维护者：[@Aizen Ginutako](https://github.com/AizenGinutako)
- 作者电邮：2406851083@qq.com / 13554754853@163.com

---

如果这个项目对您有帮助，请给它一个⭐️星标支持！

