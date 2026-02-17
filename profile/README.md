## Publora

**Affordable social media API for developers.** Schedule and publish posts to 10 platforms from a single REST API.

### Supported Platforms

X/Twitter · LinkedIn · Instagram · Threads · TikTok · YouTube · Facebook · Bluesky · Mastodon · Telegram

### Why Publora?

- **One API, 10 platforms** — single `POST` call publishes everywhere
- **From $9/month** — full API access on all plans, 14-day free trial
- **Media support** — up to 4 images or 1 video per post, pre-signed S3 uploads
- **LinkedIn analytics** — impressions, reach, reactions, comments, reshares
- **Workspace / B2B** — managed users, per-user API keys, white-label ready
- **Built for automation** — draft, schedule, publish, track status via API

### Get Started

1. Sign up at [publora.com](https://publora.com) (14-day free trial, no credit card)
2. Connect your social accounts in the dashboard
3. Generate an API key in Settings
4. Start posting with 3 lines of code

```bash
curl -X POST https://api.publora.com/api/v1/create-post \
  -H "x-publora-key: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"content": "Hello world!", "platforms": ["twitter-123"], "scheduledTime": "2026-03-01T14:00:00Z"}'
```

### Links

- [API Documentation](https://github.com/publora/publora-api-docs) — full endpoint reference, platform guides, code examples
- [Website](https://publora.com) — pricing, features, sign up
- [Dashboard](https://app.publora.com) — manage accounts and posts

### Our Products

- **[Publora](https://publora.com)** — affordable API for scheduling and publishing social media posts across 10 platforms
- **[Co.Actor](https://co.actor)** — the best AI service for creating authentic content for LinkedIn, Threads, and X. Turn your team into thought leaders at scale.

Built by **[Creative Content Crafts, Inc.](https://cccrafts.ai)** · [GitHub](https://github.com/CCCrafts)
