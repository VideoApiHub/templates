# n8n Templates

Import these workflows into your n8n instance to automate video rendering with VideoApiHub.

## Templates

| File | Description |
|------|-------------|
| [auto-video.json](auto-video.json) | Google Sheet → VideoApiHub render → YouTube upload pipeline |
| [Google Sheet to Video Creation and Posting to Youtube.json](Google%20Sheet%20to%20Video%20Creation%20and%20Posting%20to%20Youtube.json) | Scheduled workflow: Google Sheet → VideoApiHub render → YouTube Shorts upload |

## How to Import

1. Open your n8n instance.
2. Go to **Workflows → Import from File**.
3. Select the `.json` template file.
4. Connect your credentials (see sticky notes in the workflow for guidance).

## Required Credentials

- **VideoApiHub API** — get your API key from [videoapihub.com/dashboard](https://videoapihub.com/dashboard)
- **Google Sheets OAuth2** — for reading/writing row data
- **YouTube OAuth2** — for uploading rendered videos
