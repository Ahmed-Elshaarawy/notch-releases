# Laptop Notch — Privacy Policy

_Last updated: November 6, 2026_

Laptop Notch ("the app") runs on your computer. It has **no accounts, no analytics, no ads and
no tracking**, and the developer does not collect, receive or store any of your data.

## What the app reads, and where it stays
Everything below is read and shown **on your device only** and is never sent to the developer:
- **Notifications** (Windows: only with your permission) — shown in the notch.
- **Now playing** media (title, artist, artwork) from your music apps.
- **Clipboard** history — kept in memory on your device only; you can clear it in Settings.
- **Copied text for Instant convert** (off by default) — short copied text is checked on your
  device for an amount, unit or time to convert; nothing is kept.
- **Verification codes** found in your notifications — shown in the notch. When you copy one,
  it is marked so clipboard histories (including Windows' Win+V and cloud clipboard) don't keep it.
- **YouTube videos** (Windows, "YouTube features" in Settings) — to recognise a YouTube video
  playing in your browser, the app reads the address of that browser tab and keeps only the
  video's ID. "Continue watching" remembers up to 3 videos you closed midway, for 7 days, in a
  local file; turning it off deletes the list.
- **Screenshots** you take with the Shelf's Screenshot button, and (only if you turn it on)
  new files in your Pictures › Screenshots folder — added to the shelf on your device.
- **Network status** — whether you're online, and the names of VPN connections, to tell you
  when the connection or a VPN drops.
- **Calendar** events from calendar links you add in Settings — used for meeting reminders.
- **Files** you drop on the shelf — the app keeps a reference, not a copy elsewhere.
- **System info** (battery, CPU, memory, sensors, volume, brightness), and which app uses the
  most CPU when the battery drains fast. "Mute from the notch" changes the mute state of your
  recording devices when you ask it to; the app never records audio.
- Messages from coding agents (e.g. Claude Code) running on your computer.

Settings are stored in a local file on your device.

## When the app connects to the internet
Only to provide a feature you use, directly to these services:
- **Weather** — your approximate location (rounded to about 1 km) is sent to
  [Open-Meteo](https://open-meteo.com/) to get the forecast.
- **Synced lyrics** — the current song's title, artist and album are sent to
  [LRCLIB](https://lrclib.net/) to find lyrics.
- **Calendar** — the app downloads the calendar links you add.
- **YouTube thumbnails** — the video's ID is sent to YouTube's image server (`i.ytimg.com`) to
  show its picture.
- **Exchange rates** (Instant convert, off by default) — only a currency code (for example
  "USD") is sent to [Frankfurter](https://frankfurter.dev/) (`api.frankfurter.dev`), or to
  [ExchangeRate-API](https://www.exchangerate-api.com/) (`open.er-api.com`) for currencies
  Frankfurter doesn't cover, at most once every 12 hours. The amount and the copied text are
  never sent.
- **Connection check** — the app opens a connection to Cloudflare's public address (`1.1.1.1`)
  and closes it again, sending no data, to see whether you're online: on Windows only when
  Windows reports limited connectivity, on macOS and Linux every 10 seconds while connection
  alerts are on.
- **Updates** (non-Store versions) — the app checks this GitHub repository for a new version.

These services have their own privacy policies. No other data leaves your device.

## Children
The app is not directed at children and collects no personal information from anyone.

## Changes and contact
Changes to this policy are published at this address. Questions:
[open an issue](https://github.com/Ahmed-Elshaarawy/notch-releases/issues).
