# Join CUMT Alethic Insight Lab

CUMT Alethic Insight Lab welcomes students interested in AI research, engineering, open-source collaboration, and long-term learning.

## Two Products

- **Recruitment exam:** [current exam-server repository](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-platform) and the candidate [recruitment-exam-kit](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit); the kit name stays unchanged.
- **Internal member and organization platform:** [alethicinsight-member-platform](https://github.com/CUMT-Alethic-Insight-Lab/alethicinsight-member-platform) contains member workflows, organization API and a single CLI/MCP infra package. This is an independent internal product, not an exam extension or candidate-kit dependency.

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

- Platform source code: [recruitment-exam-platform](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-platform)
- Session cleaning: [`cleaner.py`](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/blob/main/cleaner.py)
- Downloads: [Releases](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-kit/releases)

Only cleaned session records are uploaded — keys, personal files, and unrelated content are removed locally before upload.

## After You Join

In-depth onboarding lives in [open-onboarding](https://github.com/CUMT-Alethic-Insight-Lab/open-onboarding), with hands-on practice in [contribution-playground](https://github.com/CUMT-Alethic-Insight-Lab/contribution-playground).

## Sensitive Materials

This public repository must not contain real recruitment questions, past machine test problems, interview questions, scoring rubrics, candidate evaluations, or internal review notes.

Contact: contact@alethicinsight.org


## Maintainer Update

2026-11-17: With explicit user authorization, the exam repository was restored from `alethicinsight-platform` to `recruitment-exam-platform`; GitHub retains the old URL redirect. Its root `server/` runs only the exam, but `main` still contains the member copy pending [PR #7](https://github.com/CUMT-Alethic-Insight-Lab/recruitment-exam-platform/pull/7); source deduplication is not complete. The kit name is unchanged. No PR merge, deployment, or data migration is included.
