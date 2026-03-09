# LLM Emotional Support Agent
**Emotional Interaction · Supportive Dialogue · Human-Centered AI Communication**  
**情感交互｜支持型对话｜以人为中心的 AI 沟通设计**

## Overview | 项目简介

This project explores how an LLM-based emotional support agent can provide accessible, low-pressure, and privacy-aware conversational support for users experiencing stress, anxiety, loneliness, or emotional overwhelm.

Rather than replacing licensed therapists, this system is designed as an early-stage emotional support interface: a safe space for users to open up, reflect on feelings, and receive empathetic responses in a more private and less intimidating way.

本项目探索了一个基于大语言模型（LLM）的情感支持 Agent，如何为处于压力、焦虑、孤独或情绪负担中的用户提供一种更低门槛、更具隐私感、更加以人为中心的对话支持体验。

它并不试图替代专业心理咨询师，而是作为一个早期情绪支持入口，让用户能够在更私密、压力更低的情境下表达情绪、整理想法，并获得具有支持感的回应。

---

## Background | 项目背景

Mental health support is often limited by:
- high consultation costs
- limited scheduling availability
- hesitation to open up to other people
- privacy concerns around sensitive emotions

This project asks:

**Can an AI agent create a supportive, emotionally aware, and privacy-conscious conversation experience while respecting safety boundaries?**

心理支持服务往往受到以下限制：
- 咨询费用较高
- 预约时间有限
- 用户可能不愿意向他人表达脆弱情绪
- 对隐私与敏感表达存在顾虑

因此，这个项目希望回答的问题是：

**一个 AI Agent 是否能够在尊重安全边界的前提下，提供更有支持感、更懂情绪、也更重视隐私的对话体验？**

---

## Product Goals | 产品目标

- Design a supportive and non-judgmental conversational experience
- Lower the barrier for users to express vulnerable emotions
- Explore prompt and persona strategies for emotionally appropriate responses
- Detect high-risk signals such as self-harm or suicide intent
- Enable privacy-aware escalation through anomaly alerts instead of exposing full conversation content

- 设计具有支持感和非评判感的对话体验
- 降低用户表达脆弱情绪的门槛
- 探索 Prompt 与 Persona 策略对情绪支持型回复的影响
- 识别自残、自杀倾向等高风险信号
- 通过异常提醒而非暴露完整内容的方式实现隐私友好的升级机制

---

## Key Features | 核心功能

- Multi-turn emotional support dialogue
- Context-aware conversation memory
- Knowledge-enhanced supportive response generation
- Emotionally aligned persona and tone control
- Safety trigger and escalation logic
- Privacy-aware abnormal risk alerting

- 多轮情感支持对话
- 上下文感知与对话记忆
- 知识增强的支持型回复生成
- Persona 与语气控制
- 安全触发与升级逻辑
- 隐私友好的异常风险提醒

---

## Safety Design | 安全机制设计

This project is not a diagnostic or treatment tool.

When the system detects possible signals of self-harm, suicide intent, or emotional crisis, it shifts from regular supportive conversation to a safer response mode. This includes:
- emotionally stabilizing responses
- stronger encouragement to seek human help
- warning prompts for crisis situations
- backend anomaly alerts without exposing the full conversation by default

本项目不是诊断工具，也不是治疗工具。

当系统检测到可能涉及自残、自杀倾向或严重情绪危机的表达时，它会从普通支持型对话切换到更安全的响应模式，包括：
- 更稳定情绪的回应方式
- 更明确地建议寻求人类帮助
- 面向危机情境的警示提示
- 默认不上传完整聊天内容，而仅发送异常风险提示到后台系统

---

## Tech Stack | 技术栈

- Python
- LangChain
- RAG
- Prompt Engineering
- Persona Design
- Next.js
- Tailwind CSS
- Supabase

---

## My Role | 我的角色

- Product concept definition
- User pain point framing
- Emotional interaction design
- Prompt and persona strategy design
- Dialogue flow design
- Safety escalation logic
- Prototype testing and iteration

- 产品概念定义
- 用户痛点分析
- 情感交互设计
- Prompt 与 Persona 策略设计
- 对话流程设计
- 安全升级逻辑设计
- 原型测试与迭代优化

---

