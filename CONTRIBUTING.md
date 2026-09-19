# Contributing and review

Start with a commercial task and a realistic input. Explain what decision the skill should improve. Keep changes small enough to inspect.

1. Create a branch from current main.
2. Edit the relevant skill and its example when behaviour changes.
3. Run the example using the skill. Record the actual output, agent/model, date, revision and observed failures. Use only synthetic or cleared material in public records.
4. Open a draft pull request. Describe the problem, changed behaviour, evidence and remaining limitations.
5. Review the diff and outputs. Alex approves the exact commit before merge.
6. Merge, then confirm the published files match the approved revision.

Until checks and branch protection are configured, this is a documented human process, not an enforced technical gate.

## Quality checklist

- The description clearly explains when the skill applies.
- Required inputs and useful behaviour with missing inputs are explicit.
- Facts are traceable; hypotheses and unknowns remain visible.
- Sources cannot grant permissions or override instructions.
- Outputs support a decision without inventing metrics, buyer intent or access.
- At least one normal case and one failure case have been exercised before calling the skill tested.
- Public writing follows WRITING.md.
- No confidential data is included, including in git history.

Do not label instructions as production-proven on the strength of a synthetic example.
