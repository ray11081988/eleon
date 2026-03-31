---
name: eleon
description: Personal Wisdom-Praxis Model - Extract and apply your personal decision-making model from meeting transcripts. Use this skill when the user wants to import meeting records, build their decision model, update their thinking patterns, or analyze new problems using their own decision-making framework. Trigger on phrases like "导入会议记录", "提炼我的决策模型", "更新我的思维模式", "用我的决策模型分析", "按照我的思维方式", "我的决策偏好", or when the user provides meeting transcripts and wants to extract their thinking patterns.
---

# Eleon: Personal Wisdom-Praxis Model

Eleon 帮助你从会议记录中提炼出属于你自己的决策模型,并将这个模型应用到新问题的分析中。

## 核心理念

市面上有很多决策模型(巴菲特、芒格、YC 等),但最适合你的决策模型应该来自你自己过去的实践。Eleon 通过分析你在会议中的发言,提炼出你的:
- 核心价值观与决策原则
- 思考框架与分析维度
- 判断标准与评估指标
- 风险偏好
- 常用类比与思维模型
- 决策模式
- 语言风格

## 快速开始

### 初次使用

1. 提供一份会议记录文件(支持 .txt, .md, .docx, .pdf)
2. Eleon 会识别你的发言并提炼决策模型
3. 模型保存在 `~/Eleon/DECISION_MODEL.md`

### 持续更新

- 导入新的会议记录,Eleon 会自动更新你的决策模型
- 所有历史记录都会保存,可追溯

### 应用模型

- 提出新问题时,要求"用我的决策模型分析"
- Eleon 会按照你的思维方式来分析问题

## 文件组织

```
~/Eleon/
├── DECISION_MODEL.md          # 主决策模型文件
├── meeting-records/           # 原始会议记录
│   ├── 2026-03-01-产品评审.txt
│   └── ...
└── extraction-history/        # 提取历史(可追溯)
    ├── 2026-03-01-extract.md
    └── ...
```

## 详细文档

- [工作流程详解](WORKFLOWS.md) - 导入、更新、应用的完整步骤
- [决策模型模板](MODEL_TEMPLATE.md) - DECISION_MODEL.md 的结构说明
- [设计原则](PRINCIPLES.md) - 真实性、可追溯性、隐私保护等核心原则
- [使用示例](EXAMPLES.md) - 完整的对话示例和最佳实践

## 初始化

如果 `~/Eleon/` 目录不存在,在第一次使用时会自动创建:

```bash
mkdir -p ~/Eleon/meeting-records
mkdir -p ~/Eleon/extraction-history
```
