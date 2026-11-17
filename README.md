# Join CUMT Alethic Insight Lab

[English](README.en.md) | [简体中文](README.zh-CN.md)

The single entry point for joining the lab: recruitment process, transparent machine-test platform, and post-join onboarding.

新成员招新总入口：招新流程、透明公开的机试平台、加入后的深入上手路径。

## Two Products / 两个产品

| Product 产品 | Entry and boundary 入口与边界 |
| --- | --- |
| Recruitment exam 招新考试 | [Exam server source / 考试服务端当前源码仓](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-platform) + [recruitment-exam-kit](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit) candidate kit; the kit name stays unchanged. 套件名称不变。 |
| Internal member and organization platform 内部成员与组织平台 | [alethicinsight-member-platform](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-member-platform): member workflows, organization API and a single CLI/MCP infra package. 成员事务、组织 API 及同包 CLI/MCP 属于独立内部产品，不是考试增量或考生套件依赖。 |

## How to Join / 如何加入

| Step | Links |
| --- | --- |
| Recruitment process 招新流程 | [Process](docs/en/process.md) / [招新流程](docs/zh-CN/process.md) |
| Preparation guide 准备建议 | [Preparation](docs/en/preparation.md) / [准备建议](docs/zh-CN/preparation.md) |
| AI assistance policy AI 辅助规则 | [AI Assistance](docs/en/ai-assistance-policy.md) / [AI 辅助使用规则](docs/zh-CN/ai-assistance-policy.md) |

## Machine Test, in the Open / 机试环节透明化

The machine test runs on our open-source platform. The session-cleaning code — what is collected from your AI sessions and how private information is removed before review — is public and auditable.

机试使用我们开源的招新平台。会话清洗代码——从你的 AI 会话中收集什么、评审前如何去除隐私信息——完全公开、可审查。

| Resource | Link |
| --- | --- |
| Platform source code 平台源码 | [alethicinsight-platform](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-platform) |
| Session cleaning 会话清洗 | [`cleaner.py`](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/blob/main/cleaner.py) |
| Downloads 下载 | [Releases](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/releases) |

Only cleaned session records are uploaded — keys, personal files, and unrelated content are removed locally before upload. Questions are welcome via Issues in the platform repository.

我们只上传清洗后的会话记录——密钥、个人文件与无关内容在上传前已于本地去除。如有疑问，欢迎在平台仓库提 Issue。

## After You Join / 加入之后

| Resource | Link |
| --- | --- |
| In-depth onboarding 深入上手 | [open-onboarding](https://github.com/CUMT-Alethic-Insight-Lab/open-onboarding) |
| Contribution practice 贡献练手 | [contribution-playground](https://github.com/CUMT-Alethic-Insight-Lab/contribution-playground) |

## What This Repository Does Not Contain / 本仓库不包含

Real recruitment questions, past machine-test problems, interview questions, scoring rubrics, candidate evaluations, or internal review notes.

真实招新题、往届机试题、面试题、评分标准、候选人评价或内部评审记录。

## Contact / 联系

contact@alethicinsight.org
