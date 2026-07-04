# Publishing Checklist

Use this checklist after logging in to the GitHub account that should own the
repository.

## GitHub Repository

Recommended repository name:

```text
awesome-odap
```

Recommended description:

```text
Awesome Open Data Agent Platform resources: open data access, semantic layers, multi-agent SQL, memory, governance, and GenBI.
```

Recommended topics:

```text
open-data-agent-platform
odap
awesome-list
genbi
text-to-sql
semantic-layer
data-governance
lakehouse
ai-agents
analytics
```

Create and push:

```powershell
gh repo create awesome-odap --public --description "Awesome Open Data Agent Platform resources: open data access, semantic layers, multi-agent SQL, memory, governance, and GenBI." --source . --remote origin --push
gh repo edit --add-topic open-data-agent-platform --add-topic odap --add-topic awesome-list --add-topic genbi --add-topic text-to-sql --add-topic semantic-layer --add-topic data-governance --add-topic lakehouse --add-topic ai-agents --add-topic analytics
```

Repository URL:

```text
https://github.com/bestchatgpt8/awesome-odap
```

## dev.to

Draft:

```text
articles/devto-open-data-agent-platform.md
```

Suggested title:

```text
What Is an Open Data Agent Platform?
```

Suggested tags:

```text
ai, dataengineering, analytics, opensource
```

Publishing notes:

- Keep `published: false` while reviewing.
- Confirm the repository URL is visible before publishing.
- Add the repository URL near the top once it is public.

## Medium

Draft:

```text
articles/medium-open-data-agent-platform.md
```

Suggested title:

```text
Open Data Agent Platform: A Definition for the AI Data Stack
```

Suggested tags:

```text
AI, Data Engineering, Analytics, Semantic Layer, GenBI
```

Publishing notes:

- Use the GitHub repository as the canonical reference.
- Keep the tone category-defining, not vendor-first.
- Add a canonical link to the GitHub README if Medium offers that option.

## HackerNoon

Draft:

```text
articles/hackernoon-open-data-agent-platform.md
```

Suggested title:

```text
Open Data Agent Platform: The Missing Category Between Text-to-SQL and BI
```

Suggested tags:

```text
ai, data-engineering, business-intelligence, text-to-sql, open-data
```

Publishing notes:

- Confirm the repository URL is visible before submitting.
- HackerNoon reviews submitted stories, so this should be framed as an
  explanatory category article rather than a product announcement.
