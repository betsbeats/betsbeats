# BetsBeats

One US sports pick a day, sealed before kickoff.

Every pick is written down, hashed with SHA-256 and published as that hash before the game starts. After the game the full text and the salt are revealed, so anyone can recompute the hash and check that the pick was not changed. Wins and losses both stay on the public record.

- Record and every settled pick: https://betsbeats.com/results
- Check a pick yourself: https://betsbeats.com/verify
- Free betting calculators (odds converter, expected value, parlay): https://betsbeats.com/bet-calculator
- Today's free pick: https://betsbeats.com/free

## Open source

- [`seal-verify`](https://github.com/betsbeats/seal-verify): recompute a BetsBeats seal locally in Node or Python, no dependencies.
- [`betsbeats-mcp`](https://github.com/betsbeats/betsbeats-mcp): a read-only MCP server so AI assistants can verify a pick and read the record.

21+. Analysis and entertainment, not financial advice. Picks lose as well as win. BetsBeats does not take bets. If gambling stops being fun, call 1-800-GAMBLER.
