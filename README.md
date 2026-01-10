# Claude Code Skills 项目 🤖✨

一个基于 Claude Code 的专业 AI 技能库项目，集成了多个实用的 AI 助手技能，帮助您提升工作效率。

## 📖 项目简介

本项目是一个 **Claude Code Skills 集合**，包含了多个专业领域的 AI 助手技能。通过这些技能，Claude 可以自动识别您的需求并提供专业的帮助，无论是内容创作、数据分析、项目管理还是商业咨询。

### 🎯 核心特性

- ✅ **6 个专业 Skills**：覆盖影视创作、图像生成、旅游规划、企业分析等领域
- ✅ **智能触发**：自动识别关键词，无需手动切换
- ✅ **中文优化**：所有技能都针对中文场景优化
- ✅ **标准规范**：遵循 Claude Code Skills 官方规范
- ✅ **易于扩展**：可快速添加新的自定义技能

## 🚀 快速开始

### 环境要求

- Claude Code（支持 Skills 功能）
- Git（用于克隆项目）

### 安装步骤

```bash
# 克隆项目
git clone <repository-url>
cd claude_code

# 项目已包含 .claude/skills/ 目录，Claude Code 会自动加载
```

### 使用方法

1. 在 Claude Code 中打开此项目
2. Claude 会自动加载 `.claude/skills/` 目录下的所有技能
3. 直接提问即可，Claude 会根据关键词自动选择合适的技能

**示例**：

```
用户：帮我生成一个赛博朋克风格的 Midjourney 提示词
Claude：🎨 [自动使用 Midjourney Prompt Skill]

用户：分析一下特斯拉公司
Claude：💼 [自动使用 Company Analysis Skill]
```

## 📚 包含的 Skills

|          Skill           |              功能              |       适用场景       |
| :----------------------: | :----------------------------: | :------------------: |
| 🎬 **AI Cinematography** | 故事转分镜脚本，生成视频提示词 | 短视频创作、影视策划 |
| 🎨 **Midjourney Prompt** |       AI 图像提示词生成        |  设计创作、图像生成  |
|  ✈️ **Travel Planner**   |          智能旅游规划          |  旅行规划、行程安排  |
|   📊 **SWOT Analysis**   |       企业 SWOT 战略分析       |  战略规划、竞争分析  |
|   📋 **Task Manager**    |     GitHub Issues 任务管理     |  项目管理、团队协作  |
| 💼 **Company Analysis**  |          公司深度分析          |  投资研究、企业调研  |

> 详细说明请查看 [.claude/skills/README.md](.claude/skills/README.md)

## 🏗️ 项目结构

```
claude_code/
├── README.md                    # 主项目说明（本文件）
├── .claude/
│   └── skills/                  # Claude Skills 目录
│       ├── README.md            # Skills 总览
│       ├── ai-cinematography/   # 🎬 影视编剧助手
│       ├── midjourney-gen-prompt/ # 🎨 图像提示词生成
│       ├── travel/              # ✈️ 旅游规划助手
│       ├── swot/                # 📊 SWOT 分析
│       ├── task-manager/        # 📋 任务管理
│       └── company-analysis/    # 💼 公司分析
└── [其他项目文件...]
```

## 💡 使用示例

### 示例 1：创作短视频分镜

```
用户：我想创作一个关于清晨咖啡馆的短视频，30秒，第三人称视角

Claude：好的！让我为您创作分镜脚本 🎬

【使用 AI Cinematography Skill】
- 自动询问故事细节
- 生成分镜头表格
- 提供文生图和图生视频提示词
```

### 示例 2：分析企业战略

```
用户：帮我做一下华为的 SWOT 分析

Claude：好的，我来为您分析华为的战略定位 📊

【使用 SWOT Analysis Skill】
- 搜索最新企业信息
- 分析优势、劣势、机会、威胁
- 提供战略建议
```

### 示例 3：规划旅游行程

```
用户：/目的地 广州出发 哈尔滨 2026-02-01 5天

Claude：已接收您的旅游计划 ✈️

【使用 Travel Planner Skill】
- 分析南北差异
- 生成 7 大模块攻略
- 提供详细行程表
```

## 🛠️ 自定义 Skills

### 创建新的 Skill

1. 在 `.claude/skills/` 目录下创建新文件夹

```bash
mkdir .claude/skills/my-skill
```

2. 创建 `SKILL.md` 文件

```yaml
---
name: my-skill
description: 您的技能描述和触发条件
---
# 您的技能标题

## 核心功能
```

3. 重启 Claude Code 加载新技能

### Skill 开发规范

- 📝 使用 YAML frontmatter 定义元数据
- 🎯 description 要包含触发关键词
- 📖 提供清晰的使用说明和示例
- 🌐 优先使用中文

> 详细开发指南：[.claude/skills/README.md](.claude/skills/README.md)

## 📊 技能使用统计

|       Skill       |  推荐场景  | 难度 | 互动性 |
| :---------------: | :--------: | :--: | :----: |
| AI Cinematography | ⭐⭐⭐⭐⭐ |  中  |   高   |
| Midjourney Prompt | ⭐⭐⭐⭐⭐ |  低  |   中   |
|  Travel Planner   |  ⭐⭐⭐⭐  |  低  |   高   |
|   SWOT Analysis   |  ⭐⭐⭐⭐  |  中  |   中   |
|   Task Manager    | ⭐⭐⭐⭐⭐ |  中  |   低   |
| Company Analysis  |  ⭐⭐⭐⭐  |  高  |   高   |

## 🤝 贡献指南

欢迎贡献新的 Skills！

1. Fork 本项目
2. 创建新的 Skill 分支
3. 按照规范开发新 Skill
4. 提交 Pull Request

### 贡献要求

- ✅ 遵循项目结构规范
- ✅ 提供完整的 SKILL.md 文档
- ✅ 包含使用示例
- ✅ 中英文 description

## 📄 许可证

[选择适合的许可证，如 MIT]

## 🔗 相关资源

- 📖 [Claude Code 官方文档](https://code.claude.com/docs)
- 📚 [Claude Code Skills 指南](https://code.claude.com/docs/en/skills)
- 💬 [项目讨论区](#)（如有）

## 📮 联系方式

- **项目维护者**：[您的名字]
- **问题反馈**：[GitHub Issues]
- **邮箱**：[您的邮箱]

---

**最后更新**：2026-01-10
**版本**：v1.0.0

---

<div align="center">

**🌟 如果这个项目对您有帮助，请给个 Star！🌟**

Made with ❤️ by Claude Code

</div>
