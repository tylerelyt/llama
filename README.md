# LLaMA实践指南

<div align="center">
  <img src="https://github.com/user-attachments/assets/049efcd7-5b47-4933-b55a-02ec90b98489" alt="logo" height="500">
</div>

本仓库包含与 **LLaMA 模型系列**相关的代码示例、练习和工具，旨在提供动手学习的机会，帮助理解前沿的机器学习和人工智能应用。

## 简介

**LLaMA 实践指南** 仓库提供了一个结构化的学习方式，用于掌握和实现最先进的人工智能概念。每个章节或模块都包括代码示例、练习和文档，以加深理解并加速实用技能的构建。

**注意：** 本仓库会定期更新，请持续关注以获取最新的改进和内容。

| 主题分类        | 课程名称                                         | 难度     | 推荐练习顺序 |
|-----------------|------------------------------------------------|:--------:|:------------:|
| 对话与推理能力   | 揭示 LLaMA 3 对话能力的奥秘                   | 简单     |      1       |
| 对话与推理能力   | 如何善用 LLaMA 3 长文本处理能力？              | 简单     |      2       |
| 对话与推理能力   | LLaMA 3 的应用探索：指令跟随的最佳实践         | 中等     |      3       |
| 对话与推理能力   | LLaMA 3 的思考之道：思维链的源流与应用         | 中等     |      4       |
| 对话与推理能力   | 如何通过提示词获得上下文学习能力？             | 中等     |      5       |
| 对话与推理能力   | 多轮推理应用：对话系统与自动化任务建模         | 中等     |      6       |
| 思维与增强能力   | 如何运用 LLaMA 3 的思维链实现频率增强？        | 中等     |      7       |
| 思维与增强能力   | 多轮推理的搜索增强：技术与实践                 | 困难     |      8       |
| 思维与增强能力   | 多轮推理的反馈增强：提升准确性的策略           | 困难     |      9       |
| 检索增强        | RAG 检索增强全景                              | 简单     |     10       |
| 检索增强        | 如何借助 LLaMA 3 赋能索引构建？               | 中等     |     11       |
| 检索增强        | 利用 RAG 提升 LLaMA 问答系统的准确性          | 困难     |     12       |
| 检索增强        | 如何评估 LLaMA 3 的检索增强效果？             | 中等     |     13       |
| 检索增强        | 展望未来：LLaMA 3 检索增强的潜力              | 中等     |     14       |
| 智能体系统      | LLaMA 3 的开源语言智能体方案                  | 中等     |     15       |
| 智能体系统      | 如何实现多智能体协作？                        | 困难     |     16       |
| 智能体系统      | 多智能体实战：构建一个多智能体系统             | 困难     |     17       |
| 多模态与具身智能 | Vision 多模态模型：智能文档处理技术升级        | 困难     |     18       |
| 多模态与具身智能 | LLaMA 3 的具身智能体潜力                      | 困难     |     19       |


## 环境配置

为顺利运行代码示例，请确保您的环境符合以下要求：

- **Python 版本**：3.x
- **依赖项**：通过以下命令安装所需的依赖项：

```bash
pip install -r requirements.txt
```

建议使用虚拟环境进行依赖管理：

```bash
# 使用 venv
python3 -m venv env
source env/bin/activate  # Windows 用户使用 `env\Scripts\activate`

# 使用 conda
conda create --name myenv python=3.x
conda activate myenv
```

## 代码结构

本仓库的组织结构如下：

```
├── chapter1/        # 第 1 章代码
│   ├── example1.py  # 该章的示例代码
│   └── exercise1.py # 该章的练习代码
├── chapter2/        # 第 2 章代码
│   ├── ...
├── requirements.txt # 依赖文件
└── README.md        # 仓库文档
```

## 使用方法

每个章节文件夹包含反映对应概念的代码文件。运行这些文件以探索并理解关键主题。

示例：

```bash
# 进入第 1 章并运行示例脚本
cd chapter1
python example1.py
```

## 常见问题

1. **如何获取最新更新？**  
   - 定期使用 `git pull` 拉取最新代码和资源。

2. **运行代码时遇到错误怎么办？**  
   - 确保已按文档配置环境并安装了所有依赖项。  
   - 如果问题仍然存在，请查看对应章节的 README 文件或提交 issue。

## 贡献指南

欢迎为本仓库做出贡献！以下是贡献流程：

1. Fork 本仓库。
2. 创建新分支（`git checkout -b feature-branch`）。
3. 提交更改（`git commit -m 'Add new feature'`）。
4. 推送到新分支（`git push origin feature-branch`）。
5. 创建 Pull Request。

## 贡献者

<a href="https://github.com/tylerelyt/LLaMA-in-Action/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tylerelyt/LLaMA-in-Action" />
</a>

## Star 变化趋势

[![Stargazers over time](https://starchart.cc/tylerelyt/LLaMA-in-Action.svg?variant=adaptive)](https://starchart.cc/tylerelyt/LLaMA-in-Action)

## 许可证

本仓库使用 **知识共享署名-非商业性使用-相同方式共享 4.0 国际（CC BY-NC-SA 4.0）** 许可协议授权。  
许可证适用于标记为 `v0.0.1` 及后续版本的内容。详情请查看 [LICENSE](LICENSE) 文件。

## 课程介绍

本仓库是 [极客时间 LLaMA 高级课程](https://time.geekbang.org/column/intro/100828301) 的配套资源。它包含实用的示例代码、练习和补充材料，以辅助课程内容的学习。材料按章节或模块组织，与课程结构保持一致。

**注意：** 仓库内容会随课程的进展持续更新，请定期查看以获取最新资源。
