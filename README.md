# mac-watch

Checks every 10 minutes that a URL (secret `MAC_WATCH_URL`) answers with "Online". After 3 failed tries it sends one Telegram alert, a "back online" message on recovery, and an hourly reminder while down.

Secrets: `MAC_WATCH_URL`, `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`. Nothing sensitive is in the code.
