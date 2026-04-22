# Issue Tracker App


```mermaid
erDiagram

issue {
  TEXT issue_id PRIMARY KEY
  TEXT name
  DATETIME deadline
  BOOL is_done
  TEXT description
  }
```
