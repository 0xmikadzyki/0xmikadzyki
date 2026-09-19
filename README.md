<p align="center">
  <img src="ghost-banner.png" alt="GHOST" width="100%">
</p>

<table>
<tr>
<td valign="top" width="62%">

**0xmikadzyki** — onchain data, read-only. Pipelines, not promises.

I build the boring half of the stack: the part that ingests a whole chain, counts it exactly, and answers *where did the money go* without asking anyone to trust a screenshot.

Current desk is **[GHOST](https://github.com/0xmikadzyki/ghost)** — the fund-flow pipeline behind an explorer for **Robinhood Chain** (Arbitrum Orbit L2, chain id 4663). Full-chain backfill of ERC-20 `Transfer` events, **1,432,014,401 transfers** folded into ClickHouse, eight read-only JSON routes on top. Every number in that repo is a response field, not an estimate — reproducible by anyone with a free HyperSync token.

No keys. No custody. No contract address — if something claims to be this project and asks for a wallet, it is not mine.

### What I run now

- **[GHOST](https://github.com/0xmikadzyki/ghost)** — fund-flow pipeline, Robinhood Chain, read-only API
- **the backfill** — 1.4B transfers, exact counts, latency measured not guessed
- **the graph** — token movement between addresses, depth-2 in ~1s

### Stack I actually touch

![Python](https://img.shields.io/badge/python-111111?style=for-the-badge&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/fastapi-111111?style=for-the-badge&logo=fastapi&logoColor=009688)
![ClickHouse](https://img.shields.io/badge/clickhouse-111111?style=for-the-badge&logo=clickhouse&logoColor=FFCC01)
![Docker](https://img.shields.io/badge/docker-111111?style=for-the-badge&logo=docker&logoColor=2496ED)
![Ethereum](https://img.shields.io/badge/evm-111111?style=for-the-badge&logo=ethereum&logoColor=8A92B2)

</td>
<td valign="top" width="38%" align="center">

<img src="https://github.com/0xmikadzyki.png" width="240" alt="0xmikadzyki">

<br><br>

<a href="https://github.com/0xmikadzyki/ghost"><img src="https://img.shields.io/badge/GHOST-EB25D5?style=for-the-badge&logoColor=white" alt="GHOST"></a>

<br>

onchain data, read-only

1.4B transfers indexed

chain 4663

</td>
</tr>
</table>
