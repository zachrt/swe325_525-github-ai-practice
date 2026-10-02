# AI Interaction Log

## AI Interaction 1
* Date: 2026-10-01
* Assistant: Gemini
* Purpose: Explanation of Git concepts
* Prompt or summary: Explain the difference between a repository, branch, commit, pull request, and issue.
* Useful suggestion: Explained that branches are isolated spaces and PRs are merge proposals.
* Decision: accepted
* Reason: Used these definitions to draft my workflow-notes.md.
* Related GitHub URL: https://github.com/zachrt/swe325_525-github-ai-practice/blob/feature/github-ai-workflow/workflow-notes.md

## AI Interaction 2
* Date: 2026-10-01
* Assistant: Gemini
* Purpose: README Review
* Prompt or summary: Review my README.md for clarity and suggest revisions.
* Useful suggestion: Suggested adding a section explicitly stating the scope of the project.
* Decision: revised
* Reason: Took the scope idea but kept the wording shorter than the AI suggested.
* Related GitHub URL: https://github.com/zachrt/swe325_525-github-ai-practice/blob/feature/github-ai-workflow/README.md

## AI Interaction 3
* Date: 2026-10-01
* Assistant: Gemini
* Purpose: PR Checklist
* Prompt or summary: Suggest a checklist for a complete pull-request description.
* Useful suggestion: Recommended explicitly linking the issue and listing out the commits.
* Decision: accepted
* Reason: I will use this exact checklist structure for my Pull Request.
* Related GitHub URL: https://github.com/zachrt/swe325_525-github-ai-practice/pull/2

## Reflection Questions

1. Which GitHub action or object was most useful to you, and why?
Pull requests were the most helpful tool. Having one view to check my branch diffs, link issue #1, and walk through my acceptance checklist made tracking the work much easier than checking raw terminal output.

2. Which AI suggestion did you accept, and what made it useful?
I accepted the PR description checklist. It gave me a clear outline so I didn't forget key items like linking the original issue or marking off verification steps.

3. Which AI suggestion did you revise or reject, and why?
I revised the AI's proposed README text. The generated output felt overly formal for a small documentation lab, so I stripped out the extra fluff to keep it concise.

4. What did you verify yourself instead of trusting the AI?
I verified all the local Git commands and URL links myself. I ran `git log --oneline` in my terminal to confirm my commit history and tested every link in my browser to ensure none pointed to 404s.

5. What would you change in your GitHub workflow next time?
Next time I'd commit smaller chunks of work as I go. For this lab I ended up committing whole files once they were finished, but making smaller, more frequent commits while drafting would give a cleaner history log.
