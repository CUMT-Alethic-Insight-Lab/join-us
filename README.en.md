# Join CUMT Alethic Insight Lab

CUMT Alethic Insight Lab welcomes students interested in AI research, engineering, open-source collaboration, and long-term learning.

## Two Products

- **Recruitment exam:** [current exam-server repository](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-platform) and the candidate [recruitment-exam-kit](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit); the kit name stays unchanged.
- **Internal member and organization platform:** temporarily in the [same source repository](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-platform). Member workflows, organization API and the single CLI/MCP infra package are an internal product, not exam extensions or kit dependencies. `infra-handoff` is private operations handoff only.

**Source isolation pending correction PR:** the first-stage target is independently runnable `member-platform/server` and `member-platform/infra/...`, with root `server/` reserved for exams. At audit baseline `229e69c`, organization and exam APIs still share a database, accounts and startup flow. This navigation change does not claim isolation or production deployment. Review runtime isolation first; decide remote renaming and separate-repository mapping later. No new repository or nonexistent `main/member-platform` source link is advertised.

## Recruitment Process

Our general process is:

```text
application form + machine test + interview
```

See [Process](docs/en/process.md).

## Preparation

You do not need to know everything before applying. We care about learning ability, technical honesty, collaboration, and the ability to reason about your own work.

See [Preparation](docs/en/preparation.md).

## AI Assistance

AI assistance is allowed, but it must be disclosed and verified.

See [AI Assistance Policy](docs/en/ai-assistance-policy.md).

## Machine Test, in the Open

The machine test runs on our open-source platform. The session-cleaning code — what is collected from your AI sessions and how private information is removed before review — is public and auditable.

- Platform source code: [alethicinsight-platform](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-platform)
- Session cleaning: [`cleaner.py`](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/blob/main/cleaner.py)
- Downloads: [Releases](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/releases)

Only cleaned session records are uploaded — keys, personal files, and unrelated content are removed locally before upload.

## After You Join

In-depth onboarding lives in [open-onboarding](https://github.com/CUMT-Alethic-Insight-Lab/open-onboarding), with hands-on practice in [contribution-playground](https://github.com/CUMT-Alethic-Insight-Lab/contribution-playground).

## Sensitive Materials

This public repository must not contain real recruitment questions, past machine test problems, interview questions, scoring rubrics, candidate evaluations, or internal review notes.

Contact: contact@alethicinsight.org

