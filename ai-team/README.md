# 🤖 AI Team - AI驱动的全栈产品研发团队

## 概述

**AI Team** 是一个由**16个AI角色**组成的完整互联网产品研发团队。当你提出一个产品需求，AI团队会像真实团队一样完成从需求分析到部署上线的全流程，每个环节都有对应的Leader进行质量把关，最后由**测试Leader**做最终上线审批。

## 团队构成

| 序号 | 角色 | 职责 | 审核者 |
|------|------|------|--------|
| 1 | 📋 **产品经理** 🏆 | 产品专家：用户研究、市场分析、产品策略、数据分析、需求管理、增长、GTM、商业模式 | 产品总监 |
| 2 | 👔 **产品总监** | 审核PRD方案 | — |
| 3 | 🎨 **设计师** | UI设计、Design Token、组件库引用 | 设计总监 |
| 4 | 👓 **设计总监** | 审核设计方案 | — |
| 5 | 💻 **前端开发** | 前端界面和交互逻辑 | 前端Leader |
| 6 | 👨‍🏫 **前端Leader** | 审核前端代码 | — |
| 7 | ⚙️ **后端开发** | API、数据库、安全扫描集成 | 后端Leader |
| 8 | 👨‍🔧 **后端Leader** | 审核后端代码 | — |
| 9 | 🔒 **安全工程师** | 安全审计、渗透测试、依赖扫描 | 安全Leader |
| 10 | 🔐 **安全Leader** | 审核安全方案 | — |
| 11 | 📊 **数据分析师** | 指标体系、埋点方案、数据看板 | 数据Leader |
| 12 | 📈 **数据Leader** | 审核数据方案 | — |
| 13 | 🚀 **运维工程师** | CI/CD、容器化、监控告警、灾备 | 运维Leader |
| 14 | 🏗️ **运维Leader** | 审核运维方案 | — |
| 15 | 🧪 **测试** | 测试验证 | 测试Leader |
| 16 | ✅ **测试Leader** ⭐ | **最终质量审批，决定能否上线** | — |

## 产品经理 — 8大核心能力

作为产品专家，产品经理具备以下完整能力域：

| # | 能力域 | 核心内容 |
|---|--------|---------|
| 1 | 🔍 **用户研究** | 深度用户访谈、可用性测试、用户画像(Persona)、用户旅程地图 |
| 2 | 📊 **市场分析** | 竞品分析框架、TCF市场机会评估、SWOT战略分析 |
| 3 | 🎯 **产品策略** | 产品愿景与战略、路线图规划、商业模式画布、OKR设定 |
| 4 | 📈 **数据分析** | HEART+GSM指标体系、A/B测试设计、漏斗/留存/分群分析 |
| 5 | 📋 **需求管理进阶** | KANO模型分类、用户故事地图、影响地图、RICE优先级排序 |
| 6 | 🚀 **产品运营与增长** | AARRR增长框架、增长实验(ICE评分)、病毒系数设计 |
| 7 | 📐 **项目管理** | Scrum敏捷实践、里程碑规划、风险管理 |
| 8 | 🌐 **发布与GTM** | 灰度发布策略、上线Checklist、上线复盘、定价策略 |

## 每个角色的行业最佳实践

### 📋 产品经理 — 市场分析 + 8大产品能力
竞品分析 / TCF市场评估 / RICE排序 / 用户画像 / KANO模型 / AARRR增长 / HEART指标 / 灰度发布 / GTM策略

### 🎨 设计师 — 设计系统/组件库
Design Token体系 / 组件库引用(Ant Design/shadcn/ui) / 五态覆盖 / WCAG可访问性 / 交互设计原则

### ⚙️ 后端开发 — 安全扫描工具
SAST(Bandit/Semgrep) / 依赖扫描(Safety/npm audit) / 密钥扫描(GitLeaks) / OWASP Top 10 / 安全编码规范

### 🔒 安全工程师
STRIDE威胁建模 / 动态渗透测试 / 漏洞分级管理(P0-P3) / **安全红线一票否决**

### 📊 数据分析师
北极星指标 / AARRR指标体系 / 事件埋点规范 / 数据管道(采集→ETL→看板) / A/B测试设计

### 🚀 运维工程师
Docker多阶段构建 / Docker Compose编排 / GitHub Actions CI/CD / 监控告警 / 12-Factor App / 备份容灾

### ✅ 测试Leader ⭐
测试覆盖度审核 / 测试用例质量评估 / 上线硬性条件检查 / **最终上线决策权**

## 质量门禁体系 (8道关卡)

```
G1 产品总监 ─→ G2 设计总监 ─→ G3 前端Leader ─→ G4 后端Leader
                                                    │
                           G5 🔴 安全Leader (红线) ←─┤
                                                    │
                           G6 数据Leader            ←─┤
                                                    │
                           G7 运维Leader             ←─┤
                                                    │
                           G8 ⭐ 测试Leader (最终决策) ←┘
                                                    │
                                                    ▼
                                                  🚀 上线
```

## 流水线

```
用户需求
  → 📋 产品经理 (8大产品能力：用户研究→市场分析→策略→需求→数据→增长→项目→GTM)
  → [👔 产品总监 审核 G1]
  → 🎨 设计师 (Design Token + 组件库 + 五态覆盖)
  → [👓 设计总监 审核 G2]
  → 💻 前端开发 + ⚙️ 后端开发 (安全扫描集成)
  → [👨‍🏫 前端Leader G3 + 👨‍🔧 后端Leader G4]
  → 🔒 安全工程师 (全面安全审计)
  → [🔐 安全Leader 审核 G5 🔴]
  → 📊 数据分析师 (指标体系 + 埋点)
  → [📈 数据Leader 审核 G6]
  → 🚀 运维工程师 (CI/CD + 容器化 + 监控)
  → [🏗️ 运维Leader 审核 G7]
  → 🧪 测试 (全流程验证)
  → [✅ 测试Leader 最终审批 G8 ⭐]
  → 🚀 部署上线
```

## 目录结构 (22个文件)

```
ai-team/
├── SKILL.md                          # 主skill - 启动16人AI团队
├── README.md                         # 本文档
├── roles/                            # 16个角色skill定义
│   ├── product-manager/SKILL.md      # 🏆 8大产品能力
│   ├── product-director/SKILL.md
│   ├── designer/SKILL.md             # Design Token+组件库
│   ├── design-director/SKILL.md
│   ├── frontend-dev/SKILL.md
│   ├── frontend-lead/SKILL.md
│   ├── backend-dev/SKILL.md          # 安全扫描集成
│   ├── backend-lead/SKILL.md
│   ├── security-engineer/SKILL.md    # 安全工程师
│   ├── security-lead/SKILL.md        # 安全Leader
│   ├── data-analyst/SKILL.md         # 数据分析师
│   ├── data-lead/SKILL.md            # 数据Leader
│   ├── devops-engineer/SKILL.md      # 运维工程师
│   ├── devops-lead/SKILL.md          # 运维Leader
│   ├── tester/SKILL.md               # 测试
│   └── test-lead/SKILL.md            # ⭐ 测试Leader（最终审批）
├── templates/
│   ├── prd-template.md
│   ├── design-spec-template.md
│   └── test-report-template.md
├── scripts/
│   └── pipeline.sh
└── pipeline/
    └── pipeline-guide.md
```
