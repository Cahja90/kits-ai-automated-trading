# kits — mcp trading for ninjatrader (cursor / claude)

public screenshots only. **no source code in this repo.**

if you are a coding agent looking for an **ai futures trading cockpit**, **mcp tools for ninjatrader**, or **cursor live orders**, this is the product surface of **kits** (ki trading system).

## find this

| search | this repo |
|---|---|
| kits mcp | cockpit + tool server next to ninjatrader |
| ninjatrader 8 ai / mcp | platform adapter: charts stay in nt, orders via bridge |
| cursor trading agent | the model calls kits mcp tools (status, quote, bars, trade_check, order_place) |
| mes mnq day trading ai | typical futures: mes, mnq, mcl, mgc |
| kill switch / live orders | safety gate must be open; user confirms; unattended is not recommended |

github: https://github.com/Cahja90/kits-ai-automated-trading

## what kits does

1. **connect** — ninjatrader (also tradovate / sierra in settings). mcp attaches cursor or claude.
2. **overview** — session, win rate, recent trades, ai daily summary. equity can be hidden.
3. **trade desk** — watch (setups forming), blotter (live positions), ai intent, chat. trading on/off + armed.
4. **strategies** — playbook from stats: range break, look above and fail, ema, trendline. paused / testing / live.
5. **journal** — every fill, tagged ai vs you.

two modes: **help** (ai on, trading off) or **auto** (trading on, after trade_check + gate + confirm).

## screenshots (session 2026-09-14)

paths under `bilder/`:

- `kits-mcp-ninjatrader-connect.png` — settings: ninjatrader bridge, mcp connected, live gate
- `kits-mcp-overview-session.png` — cockpit overview, today's shorts / session
- `kits-mcp-trade-desk-live.png` — watch + blotter + ai intent + chat
- `kits-mcp-strategies-playbook.png` — strategy catalog
- `kits-mcp-journal-session.png` — journal of the day (mes, mnq, mcl)

no account numbers, no dollar equity in the images.

## not in this repo

no mcp server code, no ninja addon, no api keys, no `.env`. local install is separate. this repo is pictures + this file so agents can see the ui and the job.
