# Review Guidelines - Direct Review

## IMPORTANT: Do NOT use subagents for this review.

Review all files yourself in a single pass. Read the entire diff carefully, then report all findings.

Do not use the Task tool to spawn file-group-reviewer subagents. Instead:
1. Read the complete diff
2. Analyze each file's changes yourself
3. Cross-reference changes across files for consistency
4. Write all findings directly to the candidates JSON

This ensures you have full context across all files simultaneously, which helps catch cross-file bugs that subagents reviewing in isolation might miss.
