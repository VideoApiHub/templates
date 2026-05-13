# VideoApiHub Templates

Ready-to-use automation templates for [VideoApiHub](https://videoapihub.com) — render videos at scale with your favourite automation platform.

## Platforms

| Folder | Platform | Status |
|--------|----------|--------|
| [`n8n/`](n8n/) | n8n | ✅ Available |
| [`zapier/`](zapier/) | Zapier | 🔜 Coming soon |
| [`make/`](make/) | Make (Integromat) | 🔜 Coming soon |

## Quick Start

1. Pick a template from the platform folder you use.
2. Import it into your automation tool.
3. Connect your **VideoApiHub API key** and any other required credentials (Google Sheets, YouTube, etc.).
4. Customise the config node / variables and run!

## Available Templates

### n8n

| Template | Description |
|----------|-------------|
| [auto-video](n8n/auto-video.json) | Reads rows from a Google Sheet → renders videos with VideoApiHub → uploads to YouTube. Fully automated pipeline with status tracking and retry logic. |
| [Google Sheet to Video Creation and Posting to Youtube](n8n/Google%20Sheet%20to%20Video%20Creation%20and%20Posting%20to%20Youtube.json) | Scheduled workflow that reads rows from a Google Sheet, renders videos via VideoApiHub, and posts them to YouTube as Shorts. |

## Contributing

Have a template to share? PRs welcome! Please strip credentials before submitting.

## Links

- [VideoApiHub Docs](https://videoapihub.com/docs)
- [n8n Community Node](https://www.npmjs.com/package/n8n-nodes-video-api-hub)
