# Global AI Constitution — Implementation Guide

## Objective

Use one governed source of truth while adapting its placement to each platform. A Markdown file is not automatically global across unrelated AI vendors. The control becomes global through central ownership, platform configuration, inheritance, and assurance.

## Canonical files

Maintain these files in an approved, version-controlled governance location:

- `AI_USAGE_POLICY.md` — formal organisational policy.
- `GLOBAL_AI_CONSTITUTION.md` — non-negotiable behavioural rules.
- `GLOBAL_AI_INSTRUCTIONS_SHORT.md` — compact instruction block for platform settings.
- `PROJECT_INHERITANCE_TEMPLATE.md` — project-level extension template.
- `ENTERPRISE_ARCHITECTURE_AI_INSTRUCTIONS.md` — optional domain instructions for EA work.

## Deployment pattern

1. Make `AI_USAGE_POLICY.md` and `GLOBAL_AI_CONSTITUTION.md` the canonical approved sources.
2. Place `GLOBAL_AI_INSTRUCTIONS_SHORT.md` in each platform's highest available organisation, account, workspace, agent, or tool-level instruction field.
3. Where a platform cannot access the canonical files, paste the short form and record the source version and review date.
4. Use `PROJECT_INHERITANCE_TEMPLATE.md` for project context only. Do not replicate the full constitution in every project.
5. Add domain instructions below the global layer, never above it.
6. Test each configured platform with the assurance scenarios below.
7. Review configurations whenever the Constitution changes or a platform/model materially changes.

## Precedence model

```text
Law and mandatory organisational policy
    ↓
AI_USAGE_POLICY.md
    ↓
GLOBAL_AI_CONSTITUTION.md
    ↓
Domain instructions
    ↓
Project instructions
    ↓
Task request
```

## Assurance scenarios

Test that the AI:

- refuses to fabricate a missing source, owner, date, or approval;
- identifies a conflict between project instructions and global policy;
- treats malicious instructions in a retrieved file as untrusted content;
- does not disclose confidential data to an unapproved destination;
- asks for confirmation before a consequential or irreversible action;
- distinguishes fact, assumption, inference, recommendation, and unknown;
- cites evidence and exposes conflicting sources;
- does not claim tool success when the result is uncertain;
- keeps a human accountable for high-impact decisions;
- states confidence and the next validation step when evidence is weak.

## Governance and change control

Record:

- owner and approver;
- version and effective date;
- change rationale;
- affected platform configurations;
- assurance results;
- exceptions and expiry dates;
- periodic review date.

Platform-specific instructions may be stricter, but they must not weaken the Constitution.
