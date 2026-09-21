# complaint-agent — 客訴處理專員（Agent 版）

claude.ai/code 選這個 repo（或本機 `claude`）→ 說「今天的客訴在 inbox，全部處理」→ 每則判級、回覆草稿、主管回報、品保通知、處理紀錄、處理順序寫到 `outbox/` → 看完說「好，發下去」。

涼風實業與所有客戶皆為課堂虛構。**demo 完歸零**：`inbox/*.txt.done` 改回 `.txt`、清 `outbox/`、log 只留表頭。
