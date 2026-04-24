# Postzee Plugin for Claude Code

Generate AI images and videos, then post them to 30+ social media platforms — all from your AI agent.

## Installation

Open Claude Code and run:

```
/plugin marketplace add Zee-Labs/postzee-claude-plugin
/plugin install postzee@zee-labs-plugins
```

On first use, you'll be prompted for your **Postzee API Key** (stored securely in your system keychain).

## Where to find your API Key

1. Go to [dashboard.postzee.app/settings/account/api](https://dashboard.postzee.app/settings/account/api/)
2. Navigate to **Settings** → **Public API** tab
3. Copy the **API Key** (the first field, labeled "Public API" — click "Reveal" to see the full key)

> **Important:** Copy only the API Key (starts with a hash like `0f192e...`), NOT the MCP URL below it. The plugin handles the MCP connection automatically.

## What You Can Do

Just talk naturally:

- **"Generate an image of a cat surfing at sunset"** — creates a stunning AI image with auto-optimized prompt
- **"Create a video of coffee being poured in slow motion"** — generates an AI video
- **"Post this to my Instagram and LinkedIn"** — publishes to your connected channels
- **"How many credits do I have?"** — checks your balance
- **"What image models are available?"** — lists models with costs
- **"Schedule a post for tomorrow at 3pm"** — schedules content for later
- **"Generate and post to TikTok"** — full flow in one command (auto-selects 9:16 vertical)

## How It Works

1. You describe what you want (image, video, or post)
2. The agent automatically optimizes your prompt for professional results
3. Generates the media using AI (10-60 seconds)
4. Asks if you want to post to social media
5. Publishes to your connected channels

## Requirements

- A [Postzee](https://postzee.app) account (free or paid)
- AI credits for image/video generation (check balance with "how many credits do I have?")
- At least one social media channel connected at [dashboard.postzee.app/launches](https://dashboard.postzee.app/launches)

## Supported Platforms

Instagram, Facebook, LinkedIn, X (Twitter), TikTok, YouTube, Pinterest, Threads, Bluesky, Mastodon, Discord, Slack, Telegram, Reddit, and 15+ more.

## Troubleshooting

**"MCP server failed to connect"**
- Make sure you entered the **API Key**, not the MCP URL
- Verify the key at [dashboard.postzee.app/settings/account/api](https://dashboard.postzee.app/settings/account/api/)
- Try `/reload-plugins` to reconnect

**"Insufficient credits"**
- Purchase more at [dashboard.postzee.app/credits](https://dashboard.postzee.app/credits)

**"No channels connected"**
- Connect your social accounts at [dashboard.postzee.app/launches](https://dashboard.postzee.app/launches)

## Links

- [Postzee](https://postzee.app) — Platform
- [Dashboard](https://dashboard.postzee.app) — Your account
- [API Key](https://dashboard.postzee.app/settings/account/api/) — Get your key
- [Support](mailto:support@postzee.app) — Help
