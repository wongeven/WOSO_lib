---
name: WOSO_lib
name_cn: 女足知识库
description: "世界女足知识库，覆盖19本全球经典专著精华内容，支持对话式查阅。涵盖美国、欧洲、亚洲顶级球员与教练的真实故事。触发词：女足、女子足球、女足球员、女足教练、世界杯、球员自传"
category: sports
tags: [women's football, soccer, 足球, 传记, leadership, sports psychology]
author: Wang Yifan
version: "2.0"
shareable: true
---

# WOSO_lib | 世界女足知识库

> **版本说明**：本版本为可分享版，所有内容均已内嵌，无需原始书籍文件即可使用。
> 版权说明：所有笔记内容均为作者原创摘要/复述，非原文照搬，符合合理使用原则。

---

## 📚 概述

本技能提供对 **19本全球女足经典专著** 精华内容的访问能力。

涵盖范围：
- 🇺🇸 **美国**：Mia Hamm、Abby Wambach、Megan Rapinoe、Carli Lloyd、Hope Solo 等传奇
- 🇪🇺 **欧洲**：Emma Hayes、Sarina Wiegman、Christine Sinclair、Leah Williamson 等名帅与球星
- 🌍 **全球**：Marta、孙雯、Beth Mead 等各国代表人物
- 🇨🇳 **中国**：韩端、孙雯等中国女足传奇

用户可以通过对话方式询问关于女足历史、球员、教练、战术、运动心理等各类话题。

---

## 📖 知识库文件索引

### 美国 / 北美球员自传（10本）

| 书名 | 作者 | 笔记文件 | 核心主题 |
|------|------|---------|---------|
| The National Team | Caitlin Murray | `notes/the_national_team_notes.md` | 美国女足内部史，平等薪酬斗争 |
| A Completely Different Game | Emma Hayes | `notes/emma_hayes_notes.md` | 领导力哲学，"杀死独角兽" |
| Forward | Abby Wambach | `notes/forward_notes.md` | 成瘾与康复，脆弱的力量 |
| One Life | Megan Rapinoe | `notes/one_life_notes.md` | 同工同酬，社会活动主义 |
| Go for the Goal | Mia Hamm | `notes/go_for_the_goal_notes.md` | 技术教学+团队哲学 |
| When Nobody Was Watching | Carli Lloyd | `notes/carli_lloyd_notes.md` | 16分钟帽子戏法，极致自律 |
| Solo: A Memoir of Hope | Hope Solo | `notes/solo_notes.md` | 门将的孤独，争议与伟大 |
| Lioness | Beth Mead | `notes/lioness_notes.md` | 母亲患癌，欧洲杯金靴 |
| Chase Your Dreams | Julie Ertz | `notes/chase_your_dreams_notes.md` | 年轻球员励志，信仰与坚持 |
| Raised a Warrior | Susie Petruccelli | `notes/raised_a_warrior_notes.md` | 球员到教练的转型，平权 |

### 欧洲 / 国际球员自传（4本）

| 书名 | 作者 | 笔记文件 | 核心主题 |
|------|------|---------|---------|
| Playing the Long Game | Christine Sinclair | `notes/sinclair_notes.md` | 加拿大传奇，奥运金牌，团队高于个人 |
| What It Takes | Sarina Wiegman | `notes/what_it_takes_notes.md` | 荷兰→英格兰，包容性领导力 |
| You Have the Power | Leah Williamson | `notes/leah_williamson_notes.md` | 英格兰队长，10条人生法则 |
| Under the Lights | Gwendolyn Oxenham | `notes/under_the_lights_notes.md` | 普通球员生存状态，全球视角 |

### 综合 / 战术 / 历史（5本）

| 书名 | 作者 | 笔记文件 | 核心主题 |
|------|------|---------|---------|
| Soccerwomen | Gemma Clarke | `notes/soccerwomen_notes.md` | 全球女足百科全书，30+人物 |
| Everything Your Coach Never Told You | Dan Blank | `notes/everything_your_coach_never_told_you_notes.md` | 心智训练，脏活累活 |
| How to Win | Dr. Kate Hays | `notes/how_to_win_notes.md` | 运动心理学，科学训练法 |
| Champions of Women's Soccer | Ann Killion | `notes/champions_notes.md` | 22位传奇，FIFA梦之队 |
| 风雨玫瑰 | 韩端 | `notes/han_duan_notes.md` | 中国前锋，体制内成长 |

---

## 🔀 智能路由规则

根据用户问题，自动定位相关笔记文件：

### 按主题

| 问题类型 | 加载文件 |
|---------|---------|
| 询问**特定球员**（孙雯/Marta/Sinclair等） | 对应笔记文件 + `champions_notes.md` |
| 询问**教练/领导力** | `emma_hayes_notes.md` + `what_it_takes_notes.md` |
| 询问**运动心理/成功学** | `how_to_win_notes.md` + `everything_your_coach_never_told_you_notes.md` |
| 询问**美国女足整体历史** | `the_national_team_notes.md` |
| 询问**中国女足/铿锵玫瑰** | `champions_notes.md`（孙雯章节）+ `han_duan_notes.md` |

### 按球员

| 球员 | 加载文件 |
|------|---------|
| Abby Wambach | `forward_notes.md` |
| Mia Hamm | `go_for_the_goal_notes.md` |
| Megan Rapinoe / 同工同酬 | `one_life_notes.md` |
| Carli Lloyd | `carli_lloyd_notes.md` |
| Hope Solo | `solo_notes.md` |
| Christine Sinclair | `sinclair_notes.md` |
| Beth Mead | `lioness_notes.md` |
| Emma Hayes | `emma_hayes_notes.md` |
| Sarina Wiegman | `what_it_takes_notes.md` |
| Leah Williamson | `leah_williamson_notes.md` |
| **孙雯** | `champions_notes.md`（Sun Wen章节）+ `han_duan_notes.md` |
| Marta | `champions_notes.md`（Marta章节）|
| Julie Ertz | `chase_your_dreams_notes.md` |
| 韩端 | `han_duan_notes.md` |

---

## 💬 使用方式

### 示例对话

**问："对比欧美女足的不同"**
→ 加载 `the_national_team_notes.md` + `emma_hayes_notes.md` + `what_it_takes_notes.md`，综合回答

**问："Emma Hayes的领导力哲学是什么"**
→ 加载 `emma_hayes_notes.md`，回答"杀死独角兽"核心理念

**问："为什么Beth Mead在欧洲杯表现那么好"**
→ 加载 `lioness_notes.md`，重点讲母亲的故事和Sarina Wiegman的信任

**问："孙雯和韩端的故事"**
→ 加载 `champions_notes.md`（孙雯部分）+ `han_duan_notes.md`，中西对比

---

## 📝 回答规范

1. **语言**：用中文回答，引用时注明出处（书名）
2. **风格**：用自己的话复述，不是原文照搬
3. **结构**：先给结论/核心观点，再展开故事，最后总结启示
4. **情感**：适当展现故事的感染力，但不要过度煽情
5. **诚实**：不确定的内容不要编造，说明"书中记载..."

---

## 📌 版权说明

本知识库的所有摘要笔记均为 **原创复述内容**，非原书原文引用。目的是帮助用户快速了解书籍精华，而非提供书籍全文访问。

如需深入学习某本书，建议购买原版支持作者。

---

*最后更新：2026-05-14 | WOSO_lib v2.0 可分享版*
