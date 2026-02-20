# My Demo Website

## Uptime Status

![UptimeObserver status](https://img.shields.io/uptimeobserver/status/33Zw1rnH6veb4OLcskqvj6g9Lj4tnyxZ41)

---

## UptimeObserver + Telegram Setup

### 1. Connect Telegram
1. Go to UptimeObserver → Integrations → Telegram.
2. Copy the connect command (e.g., `/connect XXXXXXXX:X`).
3. Open Telegram, find `UptimeObserverBot`, and send the command.
4. Bot confirms the integration.
(Optional): Test with the **Test Telegram Alert** button.

### 2. Enable Alerts on Monitors
1. Go to a monitor → Monitor Detail page.
2. Add Alert → select **Telegram** as Alert Type.
3. Choose event (e.g., Monitor Down, Monitor Up).
(Optional): Embed Badge in Website
- **Markdown example**:
  `![UptimeObserver status](https://img.shields.io/uptimeobserver/status/:api-key)`
- **HTML example**:
  `<img alt="UptimeObserver status" src="https://img.shields.io/uptimeobserver/status/:api-key">`
