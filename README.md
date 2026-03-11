LeakShieldReal-Time Secret
IssueGuard works as a Google Chrome extension that scans the text written in a GitHub issue in real time. When a user writes or pastes content in the issue description, the tool automatically checks for sensitive information such as API keys, passwords, tokens, or credentials.

First, the system uses regex (pattern matching) to find possible secret-like text. Then, a fine-tuned CodeBERT machine learning model analyzes those candidates and decides whether they are actually secrets or normal text.

If a real secret is detected, the extension highlights it and alerts the user, so they can remove it before submitting the issue. This helps developers avoid exposing confidential information publicly on GitHub.

In simple terms, IssueGuard protects developers by detecting and warning them about sensitive data before it gets leaked in issue reports.
