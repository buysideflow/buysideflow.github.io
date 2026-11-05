# BuySideFlow Homepage

Home page of [BuySideFlow](https://buysideflow.github.io/), a point-in-time benchmark for LLM agents in investment research.

The leaderboard is rendered from [`data/leaderboard.json`](data/leaderboard.json). Append one object to that file to add a result. Do not set `rank`; the page sorts by `overall`.

```json
{
  "model": "Model name",
  "scaffold": "Agent scaffold",
  "status": "Submitted",
  "overall": 0.0,
  "date": "2026-11-05",
  "organization": "Organization",
  "url": "https://example.com"
}
```

`overall` is the score shown in the table, as a percentage on all 408 tasks. `date` and `url` are optional. `url` turns the organization name into a link.
