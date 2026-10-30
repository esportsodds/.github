# EsportsOdds

The CS2 data API: matches, maps, vetoes, round and player stats, team rankings and a de-vigged market odds line, with
history back to 2020. Self-serve, flat monthly plans.

- **Start free:** a sandbox key reads a fixed sample of past matches (2,000 requests, no card). [Sign up](https://esportsodds.gg/signup)
- **Python:** `pip install esportsodds` ([esportsodds-python](https://github.com/esportsodds/esportsodds-python)): standard library only, with an MCP server for AI assistants.
- **Docs:** [docs.esportsodds.gg](https://docs.esportsodds.gg) and the [OpenAPI spec](https://docs.esportsodds.gg/openapi.yaml)
- **Pricing:** flat monthly plans from 50,000 requests a month. [Details](https://esportsodds.gg/pricing)

```bash
curl -H "Authorization: Bearer $ESPORTSODDS_API_KEY" \
  "https://api.esportsodds.gg/v1/cs2/matches?tournament=019f23d2-5a32-71d0-ac4b-dfc7eb5dd3f0&limit=5"
```

A neutral data and analytics API for developers, media and data products. Not for sportsbooks. 18+, informational.

