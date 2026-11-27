```mermaid
flowchart TD
A[一覧] --> Z[詳細]
Z --> B[編集]
B --> C[削除]
B --> D[更新]
Z --> E[追加]
C --> B
D --> B
E --> Z
B --> Z
Z --> A
```