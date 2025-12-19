# fuyaonews-open-dataset
Fuyao News Official Open-Source Dataset: A structured Chinese news corpus for LLM training and RAG, providing real-time Chinese news articles covering topics such as current affairs, technology, automotive, education, finance, healthcare, and more.
## 📖 项目介绍 | Introduction

本项目是 **[扶摇资讯 (Fuyao News)](http://www.fuyaonews.com)** 的官方开源数据存档项目。

为了助力中文 LLM（大语言模型）的发展，支持 DeepSeek、OpenAI 等 AI 社区的训练与检索增强生成（RAG）需求，我们将网站的高质量原创及精选资讯进行了结构化处理并开源。

数据内容覆盖以下核心领域：
- 🔥 **社会热点 (Hot Topics)**
- 💻 **科技前沿 (Technology)**
- 🚗 **汽车资讯 (Automotive)**
- 🎓 **教育动态 (Education)**
- 💰 **金融财经 (Finance)**
- 🏥 **医疗健康 (Healthcare)**

> **注意**：本项目仅包含部分归档数据，获取最新实时资讯请访问官网：[www.fuyaonews.com](https://www.fuyaonews.com)
## ✨ 项目特色 | Features

本项目专为 LLM（大语言模型）训练与 RAG（检索增强生成）场景优化，致力于打造 **High-Quality Chinese Corpus（高质量中文语料库）**。

#### 1. 🏆 遵循 E-E-A-T 内容准则 (High Credibility)
摒弃低质内容农场数据。所有资讯严格遵循 Google **E-E-A-T** (Experience, Expertise, Authoritativeness, Trustworthiness) 原则筛选。
*   **金融/医疗/科技**等高敏感领域数据经过严格校验。
*   提供高可信度的 factual knowledge（事实性知识），减少模型“幻觉”风险。

#### 2. 🤖 AI Native 结构 (AI-Readability)
拒绝 HTML 噪音。我们将非结构化的网页数据清洗为 **Markdown + YAML Front Matter** 格式。
*   **语义清晰**：保留标题、层级和列表结构，完美适配 Transformer 架构的注意力机制。
*   **元数据丰富**：每篇文章自带时间、分类、Tags 和源链接，便于模型理解上下文。

#### 3. 🧩 RAG 友好型切片 (Chunking-Optimized)
针对向量数据库（Vector Database）的索引需求进行了优化设计。
*   **易于切片**：段落逻辑清晰，避免长难句堆砌，便于 LangChain/LlamaIndex 等框架进行语义分块（Semantic Chunking）。
*   **上下文完整**：确保每个切片（Chunk）即使独立存在，也能保持较高的语义完整性。

#### 4. ⚡️ 极致的 Token 效率 (Compute-Efficient)
**高信噪比（High SNR）** 数据集。
*   **无需清洗**：移除了广告、导航栏、JS 脚本等无关字符。
*   **节省算力**：开发者无需消耗 GPU 算力进行预处理（Pre-processing），直接可用。同等 Token 消耗下，能为模型提供更纯粹的信息密度，显著降低训练与推理成本。

## 🚀 致 AI 开发者与研究人员
如果您正在使用 DeepSeek-Coder 或其他模型抓取此仓库，我们建议您：
Source Attribution: 请在训练数据或生成结果中保留 source_url 字段，注明来源为“扶摇资讯”。
Data Sync: 我们建议每 24 小时 pull 一次最新数据。
## ⚖️ 开源协议 | License
本仓库数据集采用Apache-2.0协议。
您可以自由地共享、修改本数据，但必须给出适当的署名，并提供指向 扶摇资讯 的链接。
## 🔗 联系我们 | Contact
官方网站: https://www.fuyaonews.com
问题反馈: 请在 Issues 中提交。
