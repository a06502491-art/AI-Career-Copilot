# AI Agent 架构设计

## 一、项目目标

AI-Career-Copilot 采用 Agent 架构，将传统聊天机器人升级为能够理解任务、拆解任务、调用知识库并生成结果的智能助手。

---

# 二、系统架构

用户输入

↓

Agent理解用户需求

↓

任务拆解(Task Planning)

↓

Prompt生成

↓

知识库检索(RAG)

↓

大语言模型推理

↓

结果生成

↓

用户反馈

---

# 三、Agent能力

## 岗位分析 Agent

输入：

岗位JD

输出：

- 岗位职责分析
- 技能关键词
- 能力要求
- 匹配建议

---

## 简历优化 Agent

输入：

用户简历

输出：

- 简历问题分析
- 项目经历优化
- 技能补充建议

---

## 面试模拟 Agent

输入：

目标岗位

输出：

- 面试问题
- 回答建议
- 面试评价

---

## 学习规划 Agent

输入：

目标岗位

输出：

- AI学习路线
- 推荐项目
- 能力成长建议

---

# 四、技术能力

Agent Framework

Prompt Engineering

Knowledge Base（RAG）

Large Language Model（LLM）

Workflow

---

# 五、后续优化

计划增加：

- 多Agent协作
- 用户长期记忆
- 自动任务规划
- MCP工具调用
- 外部API集成