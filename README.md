# SequenceDiagram
```mermaid
sequenceDiagram
    participant Browser
    participant Server
    Browser->>Server: loads html w/ [Browser url](https://studies.cs.helsinki.fi/exampleapp/spa)
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
