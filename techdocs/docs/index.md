# app

<!-- https://devsson.betsson.tech/docs/default/component/docs-technical-principles/documentation/ -->

```kroki-mermaid
sequenceDiagram
GitLab->>Kroki: Request rendering
Kroki->>Mermaid: Request rendering
Mermaid-->>Kroki: Image
Kroki-->>GitLab: Image
```
