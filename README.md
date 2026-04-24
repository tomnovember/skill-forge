# Skill Forge

一套用对话驱动AI训练的开发框架。上传到Claude Project，通过自然语言对话，将AI从通用助手训练为特定专业领域的专家。

## 它是什么

Skill Forge是一组方法论文件，定义了从需求分析、知识库构建、流程设计、质量门禁到测试验证的完整Skill开发路径。

核心理念：你不需要是领域专家，你需要知道什么叫好。

## 文件结构

| 文件 | 职责 |
|------|------|
| `instruction.txt` | 总控指令，上传到Claude Project的Custom Instructions |
| `core-rules.md` | 铁律体系与核心规则 |
| `skill-dev.md` | Skill设计与打磨的完整流程 |
| `quality.md` | 质量标准与检查机制 |
| `methods.md` | 信息检索、事实校验、经验积累方法论 |
| `expression.md` | 表达质量、可信度分层、降级处理 |
| `diagnostics.md` | 问题诊断框架 |
| `project.md` | 项目管理规范 |
| `aesthetic-standard.md` | 审美标准 |
| `visual-design.md` | 视觉设计决策逻辑 |

## 怎么用

1. 在Claude中创建一个新的Project
2. 将`instruction.txt`的内容粘贴到Project的Custom Instructions
3. 将其余`.md`文件作为Knowledge Files上传
4. 开始对话，告诉它你要训练哪个领域的Skill

## 实际案例

用Skill Forge从零训练了一个股权税务架构分析Skill，耗时6小时，覆盖13种交易类型、35条法条、9个争议口径。

详见：[equity-tax-skill](链接)

## 许可

本项目采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 许可协议。允许学习、修改、分享，禁止商业使用。

## 作者

唐梦 (TANG Meng)
