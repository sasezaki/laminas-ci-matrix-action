---
description: TypeScriptファイル編集後の自動整形
---

# TypeScriptファイル編集後のワークフロー

TypeScriptファイル（`.ts`）を編集した後は、以下の手順を実行してください。

## 手順

1. TypeScriptファイルの編集を完了する

// turbo
2. Lintと自動修正を実行する
```bash
npm run lint-fix
```

これにより、コードスタイルが自動的に整形され、修正可能なlintエラーが修正されます。
