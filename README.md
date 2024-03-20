# SequenceDiagram
```mermaid
sequenceDiagram
    participant Browser
    participant Server
    dotcom->>iframe: loads html w/ Browser url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
