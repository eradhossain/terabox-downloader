# Terabox Telegram Bot

A Telegram bot that downloads files from Terabox links and forwards them to a specified channel.

## Features

- Converts Terabox links to direct download links
- Downloads files from direct links
- Forwards files to a specified Telegram channel
- Supports multiple Terabox domains

## Deployment on Koyeb

1. Create a Koyeb account at https://app.koyeb.com
2. Install Koyeb CLI: `curl -fsSL https://cli.koyeb.com/install.sh | bash`
3. Login to Koyeb: `koyeb login`
4. Deploy the application:
   ```bash
   koyeb app init terabox-bot
   koyeb app deploy
   ```

## Environment Variables

The following environment variables are required:
- `BOT_TOKEN`: Your Telegram bot token
- `TARGET_CHANNEL_ID`: The ID of the target Telegram channel 