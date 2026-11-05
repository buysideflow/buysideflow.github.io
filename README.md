# BuySideFlow Homepage

Home page of [BuySideFlow](https://buysideflow.github.io/), a point-in-time benchmark for LLM agents in investment research.

The leaderboard is rendered from [`data/leaderboard.json`](data/leaderboard.json). Append one object to that file to add a result. Do not set `rank`; the page sorts by `overall`.

```json
{
  "model": "Model name",
  "scaffold": "Agent scaffold",
  "organization": "Organization",
  "url": "https://example.com",
  "date": "2026-11-05",
  "status": "Submitted",
  "overall": 0.0,
  "equity": 0.0,
  "fund": 0.0,
  "fixed_income": 0.0,
  "macro": 0.0,
  "sql_native": 0.0,
  "sql_python": 0.0
}
```

Scores are percentages on all 408 tasks. Use `"Verified"` for `status` after the result has been checked.
