# 行途 XingTu · 开源仓库矩阵

> 核对日期：2026-11-02。这里记录 GitHub 上已经存在、可公开访问的项目与职责，不代表全部功能已部署、经过回归测试或仍在持续开发。运行状态、功能与许可均以对应仓库实际文件和验收记录为准。

## 三个对外入口，各司其职

| 入口 | 职责 | 内容边界 |
| --- | --- | --- |
| [GitHub Profile](https://github.com/xingtu1996) / [主页仓](https://github.com/xingtu1996/xingtu1996) | 项目导航、开源概览、身份介绍 | 不存私有工作记录，不维护第二套项目详情 |
| [GitHub Pages](https://xingtu1996.github.io) / [源码](https://github.com/xingtu1996/xingtu1996.github.io) | 简洁名片、精选文章与跳转 | 只展示经过公开审核的内容，不作为全部项目的权威清单 |
| 官网 / 作品集（当前使用 `xingtu1996.pages.dev`） | 长内容、案例展示、作品详情、未来自有域名入口 | 网站源码与发布配置单独治理；不得把私有仓库地址当公开下载入口 |

**仓库索引在本文件维护，项目细节以各仓 README 为准，文章以 `xingtu-articles` 已公开档案为准。** 三处入口可以互相跳转，但不宜各自复制一套不断变化的数量、项目阶段和成果数字。

## 公开仓库（26 个：按职责分类，非成熟度排名）

### 个人入口（2）

| 仓库 | 用途 |
| --- | --- |
| [xingtu1996](https://github.com/xingtu1996/xingtu1996) | GitHub 个人主页与矩阵导航 |
| [xingtu1996.github.io](https://github.com/xingtu1996/xingtu1996.github.io) | GitHub Pages 名片与文章导航 |

### 方法、学习与案例决策（5）

| 仓库 | 用途 |
| --- | --- |
| [xingtu-ai-engineering](https://github.com/xingtu1996/xingtu-ai-engineering) | AI 工程化方法与实践框架 |
| [xingtu-learn](https://github.com/xingtu1996/xingtu-learn) | 学习过程、实验、复盘 |
| [xingtu-portfolio](https://github.com/xingtu1996/xingtu-portfolio) | 经过脱敏的 ADR、设计权衡和项目模式 |
| [xingtu-sdd](https://github.com/xingtu1996/xingtu-sdd) | 规格驱动开发方法与模版 |
| [xingtu-cloud-neutral](https://github.com/xingtu1996/xingtu-cloud-neutral) | 工具与平台可迁移性实践 |

### Agent 工程与交付组件（14）

| 仓库 | 用途 / 关系 |
| --- | --- |
| [xingtu-harness](https://github.com/xingtu1996/xingtu-harness) | 生态装配入口；依赖组件由各仓维护 |
| [harness-kit](https://github.com/xingtu1996/harness-kit) | 可初始化、维护工作区的 Harness 工具 |
| [xingtu-skills](https://github.com/xingtu1996/xingtu-skills) | 技能与提示词资产索引 |
| [dsh-xingtu-skills](https://github.com/xingtu1996/dsh-xingtu-skills) | 面向 DSH 的技能适配/打包 |
| [xingtu-hooks](https://github.com/xingtu1996/xingtu-hooks) | Agent 执行环节钩子 |
| [xingtu-rules](https://github.com/xingtu1996/xingtu-rules) | 可移植协作规则 |
| [xingtu-mcps](https://github.com/xingtu1996/xingtu-mcps) | MCP 相关组件 |
| [xingtu-cli](https://github.com/xingtu1996/xingtu-cli) | CLI 工具入口 |
| [xingtu-tools](https://github.com/xingtu1996/xingtu-tools) | 脚本与辅助工具 |
| [xingtu-prompts](https://github.com/xingtu1996/xingtu-prompts) | 提示词库与复用材料 |
| [xingtu-workflows](https://github.com/xingtu1996/xingtu-workflows) | 人工/Agent SOP 与过程闸门；不是自动执行引擎 |
| [xingtu-scheduled](https://github.com/xingtu1996/xingtu-scheduled) | 定时任务的脱敏 Registry；不代表对应任务实时运行 |
| [xingtu-super-agent](https://github.com/xingtu1996/xingtu-super-agent) | XSA 跨 Agent 协作研究，**Research Preview**；目前不宣称已完成可用平台 |
| [xingtu-design](https://github.com/xingtu1996/xingtu-design) | 开源视觉设计材料与规范入口 |

### 内容生产与公开表达（4）

| 仓库 | 用途 |
| --- | --- |
| [xingtu-articles](https://github.com/xingtu1996/xingtu-articles) | 已公开文章与素材档案；未审核稿不得同步 |
| [md2wechat](https://github.com/xingtu1996/md2wechat) | Markdown 到公众号排版 |
| [book2vido](https://github.com/xingtu1996/book2vido) | 文本到视频的实验与工具 |
| [article2pod](https://github.com/xingtu1996/article2pod) | 文章到播客的实验与工具 |

### 评测工具（1）

| 仓库 | 用途 |
| --- | --- |
| [tokenhub-bench](https://github.com/xingtu1996/tokenhub-bench) | 模型/效率评测与基准测试 |

## 与非公开工作区的边界

- 未发布文章、发布包草稿、企业案例原始证据、执行 Session、账号资料、内部路径、凭证与定时任务真实配置留在受控工作区；**不自动把私有资料镜像进公开仓库**。
- 项目卡和文章应包含：公开来源、验证日期、适用边界、证据链接；涉及第三方的直接引语应留授权记录，必要时不公开。
- 公开仓不展示个人真实姓名、邮箱、电话或公司内部识别信息；新增公开文件要检查正文、HTML、资源元数据、提交历史与历史文件链接。
- `xingtu-fde` 属于规划中的 FDE 案例/技能方向；**截至本次核对未找到对应仓库**，创建和公开前需单独审查结构及授权。

## 成熟度标记规范

采用 **想法 / 研究预览 / 可复现实验 / 可用工具 / 稳定维护 / 已归档** 六个状态。只有项目自身有版本、验证记录、安装/运行说明时才可标注“可用”；只有有维护政策及记录时才可标注“稳定维护”。

不要使用仓库已创建、GitHub Actions 存在、PR 已提交作为“已上线 / 已部署 / 已通过验证”的替代证据。不要固化文章数、技能数、任务数、成本、收益等未经当次核对的数据。

## 下一轮治理的检查表

- [ ] 将 GitHub Profile、Pages、官网的主导航统一到这一套分类；审查已有页面中的数字化业绩、客户指向及外部链接
- [ ] 为每个项目确认 owner、项目边界、运行方式、成熟度和生命周期状态
- [ ] 对重叠仓库确认“权威源 / 聚合仓 / 兼容分发 / 历史保留”关系，**不因定位重叠而自动合并或删除**
- [ ] 发布前运行公开内容脱敏检查、链接检查与可访问性测试
- [ ] 对新项目 PR、站点上线、域名迁移、公开范围变化执行人工审核

本清单只描述公开仓库。所有未审核的改造以 Draft PR 交付，不自动合并或发布。
