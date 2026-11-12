# Klokesh493 architecture

Give reviewers a path from the GitHub profile to the portfolio and featured projects.

```mermaid
flowchart LR
    N0["Profile README"]
    N1["GitHub profile rendering"]
    N2["Portfolio and project navigation"]
    N0 --> N1 --> N2
```

## Operational boundaries

Profile content is Markdown and badge links. GitHub renders it from the profile repository.
