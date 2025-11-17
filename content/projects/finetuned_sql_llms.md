---
title: "Text-to-SQL Finetuned LLMs"
date: 2025-01-03
hiddenInHomeList: true
type : "Transformers"
---

In this project, I fine-tuned small language models to convert **English questions → SQL queries**.

### Goal

Make it easy for non-technical users to query structured data by just typing:

> "Show me all users who signed up last week with more than 3 orders"

and get back:

```sql
SELECT *
FROM users
WHERE signup_date >= DATE('now', '-7 days')
  AND order_count > 3;
```

What’s inside
	•	Finetune_SQL.ipynb – notebook for preparing training data, formatting prompts, and running the fine-tuning loop
	•	README with the high-level idea