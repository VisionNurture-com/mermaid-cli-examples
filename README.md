# mermaid-cli-examples

Examples of checking and rendering Mermaid diagrams with Mermaid CLI (`mmdc`) on GitHub Actions.

## Review flow

```mermaid
flowchart LR
    A[Edit diagram] --> B[Open PR] --> C{Check passes?}
    C -->|Yes| D[Merge]
    C -->|No| E[Fix]
```

## Data flow

```mermaid
flowchart LR
    A[Browser --> B[API]
```
