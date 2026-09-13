## To get the most useful work from Codex while conserving your limits:

1. Give one clear objective per task. Include the expected result, relevant files, constraints, and how you will judge success.

2. Ask Codex to inspect and plan first for complex work, then implement and verify. For example: “Inspect the repository, propose a plan, make the change, run the relevant checks, and report the files changed.”

3. Keep tasks focused. Split unrelated features into separate threads so each thread has a clean context.

4. Avoid repeatedly pasting large files or logs. Tell Codex which files to inspect and provide only the relevant error output.

5. Use lower reasoning effort for simple edits and explanations. Reserve higher reasoning levels for debugging, architecture, or multi-step work; higher effort can use more tokens and time. [OpenAI model guidance](https://developers.openai.com/api/docs/guides/latest-model)

6. Ask for concise progress reports and summaries after major milestones. This keeps the working context easier to manage.

7. Have Codex validate the result with targeted tests or checks rather than rerunning every possible test after every small change.

8. Batch related changes into one request when they use the same files and goal. This avoids repeating repository inspection.

9. Start a fresh thread when the current context becomes crowded. This does not restore your five-hour allowance, but it gives the new task a cleaner context.

10. Use the most capable model only when the task benefits from it. For routine file edits, a faster model with lower reasoning is usually more efficient.

Your current five-hour allowance is already at 0%, so these improvements will apply after the reset at 16:06. Your weekly allowance still has 84% remaining.
