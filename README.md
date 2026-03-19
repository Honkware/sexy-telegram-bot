# sexy-telegram-bot

Everything you need to ship Telegram bots with grammY and TypeScript that hold up under real traffic. Covers message editing, callback routing as features grow, session state for multi-step DM flows, rate-limited notifications, and getting inline keyboards to feel right.

## What's Inside

- Safe `editMessageText` wrapping for race conditions and double-clicks
- One-router callback dispatch with short prefixes
- Typed in-memory session management for multi-step DM flows
- Inline keyboard UX: pagination, checklists, confirmation, back navigation
- DM deep links from group to private chat
- Rate-limited message dispatch with Bottleneck
- Role-based permission hierarchy with per-resource granularity
- HTML message formatting and escaping

## Install

```bash
npx skills add Honkware/sexy-telegram-bot
```

Full details, code examples, and architecture are in `SKILL.md`.

## License

MIT
