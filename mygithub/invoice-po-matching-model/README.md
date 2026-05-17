# invoice-po-matching-model

Project scaffold for invoice/PO/receipt extraction and matching.

## Why `train.jsonl` and `test.jsonl`?

Yes—this is intentional. JSONL (JSON Lines) is a common format for ML datasets where each line is one independent JSON object. It is preferred over a single large JSON array because it is easier to stream, append, shard, and process with line-oriented tools.

If you prefer standard `.json` arrays, we can switch to `train.json`/`test.json`.
