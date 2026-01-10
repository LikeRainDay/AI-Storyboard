# Claude Skills 项目技能库 🎯

欢迎使用本项目的 Claude Skills！这里包含了专为本项目定制的 AI 助手技能。

> 📖 **官方文档**：[Claude Code Skills 使用指南](https://code.claude.com/docs/en/skills)

## 📚 当前可用的 Skills

|          Skill           |           目录           |                     功能说明                     |               触发词                |
| :----------------------: | :----------------------: | :----------------------------------------------: | :---------------------------------: |
| 🎬 **AI Cinematography** |   `ai-cinematography/`   | 将故事转化为分镜脚本，生成文生图和图生视频提示词 |  故事、剧本、分镜、AI 视频、文生图  |
| 🎨 **Midjourney Prompt** | `midjourney-gen-prompt/` |    为 Midjourney、DALL·E 3 生成优质图像提示词    | Midjourney、DALL·E、AI 绘画、提示词 |
|  ✈️ **Travel Planner**   |        `travel/`         |     智能旅游规划，自动分析出发地与目的地差异     |     旅游、旅行、攻略、行程规划      |
|   📊 **SWOT Analysis**   |         `swot/`          |   企业 SWOT 模型分析（优势、劣势、机会、威胁）   |  SWOT、战略分析、企业分析、竞争力   |
|   📋 **Task Manager**    |     `task-manager/`      |    GitHub Issues 任务管理，支持多 Agent 协作     |  任务管理、GitHub Issues、gh issue  |
| ⛽️ **Company Analysis** |   `company-analysis/`    |    专业公司分析，财报分析、行业研究、投资建议    |    公司分析、财报分析、行业研究     |

## 🔧 如何使用 Skills

### 自动激活

Claude 会根据您的问题和提到的关键词自动选择合适的 Skill。只需像平常一样提问即可！

### 手动激活

如果您想明确使用某个 Skill，可以直接提到 Skill 的名称或相关功能。

## 📖 Skills 开发指南

### 目录结构

每个 Skill 都有自己的目录，包含：

```
skill-name/
├── SKILL.md          # 必需：技能定义和说明文档
├── reference.md      # 可选：详细参考文档
├── examples.md       # 可选：扩展示例
└── scripts/          # 可选：辅助脚本
```

### 创建新 Skill

1. 在 `.claude/skills/` 目录下创建新文件夹
2. 遵循命名规范（小写字母 + 连字符）
3. 创建 `SKILL.md` 文件，包含 YAML frontmatter：

```yaml
---
name: skill-name
description: 详细描述技能功能和使用场景
---
```

4. 重启 Claude Code 以加载新 Skill

## 🎯 最佳实践

1. **一个 Skill 一个能力**：保持 Skill 专注，不要创建"万能 Skill"
2. **清晰的描述**：在 `description` 中包含触发关键词
3. **具体的示例**：提供真实可用的示例
4. **中文友好**：本项目 Skills 优先使用中文

## 📝 贡献指南

如果您想添加新的 Skill：

1. 确保 Skill 对项目有价值
2. 遵循目录结构和命名规范
3. 编写清晰的文档
4. 提供使用示例

---

**需要帮助？** 查看各 Skill 目录下的 `SKILL.md` 文件，或向 Claude 提问。

**最后更新**：2026-01-10
