# SABnzbd-Discord-Notifier

Send real-time SABnzbd download notifications to your Discord server using a simple Python script.

## Features

- ✅ Notifications for download started, completed, failed, or paused
- ⚠️ Customizable messages and Discord embed colors
- 🔧 Easy setup with a webhook URL
- 🖥 Cross-platform support (Windows/Linux/Mac)

## Configuration

Open the py and add your Discord webhook URL:

WEBHOOK_URL = "YOUR_DISCORD_WEBHOOK"

In SABnzbd CONFIG - Notifications - Notification Script , add the script and set the following parameters:

%c "%n" "%f"

%c – Job

%n – Status

%f – File name

## Requirements

- Python 3.8+
- SABnzbd with script support
- Discord webhook

## Download

Get the latest release from GitHub:

[Download Latest Release](https://github.com/OriginalShrapnel/SABnzbd-Discord-Notifier/releases/latest)

