# AI-Career-Copilot

## AI智能求职助手 Agent

## 项目介绍

AI-Career-Copilot 是一款面向大学生和求职者的 AI 智能求职助手。

项目基于大语言模型（LLM）、Prompt Engineering、AI Agent 和 RAG 知识库技术，帮助用户完成岗位分析、简历优化、面试模拟以及职业规划等求职流程。

通过 AI Agent 对用户需求进行理解、任务拆解和内容生成，实现从岗位分析到求职准备的一站式辅助。

---

# 项目背景

随着 AI 技术快速发展，越来越多企业岗位开始关注候选人的 AI 应用能力。

但求职过程中，用户通常面临以下问题：

- 无法准确理解岗位 JD 中的核心能力要求；
- 简历内容与目标岗位匹配度不足；
- 缺少针对性的面试训练；
- 不知道如何规划 AI 技能学习路径。

因此设计 AI-Career-Copilot，通过大模型能力辅助用户提升求职效率。

---

# 核心功能

## 1. 岗位智能分析

用户输入目标岗位 JD。

AI 自动分析：

- 岗位核心职责；
- 技能要求；
- 技术关键词；
- 岗位能力模型；
- 用户匹配建议。


## 2. AI简历优化

用户输入个人简历。

AI 根据岗位要求进行分析：

- 简历匹配度评估；
- 项目经历优化；
- 技能补充建议；
- 简历表达优化。


## 3. AI面试模拟

根据目标岗位生成模拟面试流程：

- 专业问题生成；
- 面试追问；
- 回答评价；
- 优化建议。


## 4. AI职业规划

根据用户目标岗位：

生成：

- AI技能学习路线；
- 项目实践建议；
- 能力提升方向。

---

# 产品设计流程

用户需求分析

↓

岗位信息输入

↓

AI Agent任务规划

↓

Prompt调用

↓

知识库检索（RAG）

↓

大模型生成结果

↓

输出个性化建议

---

# 技术方案

## AI能力

- Large Language Model（LLM）
- Prompt Engineering
- AI Agent
- RAG Knowledge Base
- Workflow Automation


## 应用流程

用户输入岗位信息和个人经历后：

1. Agent理解用户需求；
2. 自动拆解任务；
3. 调用对应Prompt；
4. 检索相关知识；
5. 生成结构化结果。

---

# 项目亮点

- 将大模型能力应用于真实求职场景；
- 结合Prompt设计提升AI输出质量；
- 通过Agent实现多任务自动处理；
- 引入RAG知识库增强回答准确性；
- 按产品流程完成需求分析、方案设计和效果验证。

---

# 后续优化方向

- 增加更多职业知识库；
- 支持更多岗位类型分析；
- 增加用户反馈闭环；
- 优化Agent任务规划能力。
---

## 技术实现与快速开始

本项目不仅提供了完整的 AI 产品设计思路，还包含了可运行的核心代码与 RAG 知识库。

### 项目核心目录
- app/：包含 AI Agent 核心逻辑代码 (career_agent.py)。
- knowledge_base/：包含 RAG 检索增强生成所需的岗位知识库 (AI岗位知识.md)。
- docs/：完整的产品设计、Prompt 工程与 Agent 架构文档。

### 如何本地运行
如果你想亲自体验这个 AI Agent，请按照以下步骤操作：

1. 克隆仓库到本地
git clone https://github.com/你的用户名/AI-Career-Copilot.git
cd AI-Career-Copilot

2. 安装依赖
pip install -r requirements.txt

3. 配置 API Key
在你的电脑环境变量中设置 OPENAI_API_KEY。

4. 启动 AI Agent
python app/career_agent.py

 ![Agent 核心工作流](./docs/Img_2026_0715_180450.png) 