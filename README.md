# 長照財務核銷 Agent

`ai-to-agent-expense-review` · v0.1.0 · 2026-11-19

每到月底，同一張發票常要填進不同表格。這套任務圖卡讓 Agent 先整理單據與對帳資料，承辦人再核對原始單據、判斷差異並核定金額。

![長照財務核銷流程自動化任務圖卡](assets/task-card.png)

## 怎麼用

1. 先用 [虛構案例](examples/demo.md) 練習。正式使用時，準備單據掃描圖、付款紀錄、核銷規則及報表範本。
2. 將 [任務圖卡文字版](docs/task-card.md) 和資料交給具備圖片與表格讀取能力、且獲准處理這批資料的 Agent。可以說「請依任務圖卡整理本批單據，交付明細、附件索引與待確認清單。」
3. 核對每筆明細能否回查原圖，確認票面、實付及撥款各有自己的欄位。由人員核定金額後，才將月報定稿。

本版提供任務規格、圖卡及練習案例。辨識效果取決於所選工具和掃描品質。缺少核銷規則或付款佐證時，相關欄位應列為待確認。

## 專案內容

- [任務圖卡文字版](docs/task-card.md)
- [虛構案例與預期結果](examples/demo.md)
- [社群文章](docs/social-post.md)
- [版本紀錄](CHANGELOG.md) · [貢獻方式](CONTRIBUTING.md) · [授權](LICENSE) · [發布摘要](RELEASE-NOTES.md)

後續可用同一份案例比較不同工具的辨識與對帳結果。

AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2026 AI to Agent | 2027 AI to AGI Agent
