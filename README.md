# Cycle

**A period tracker that can't leak your data, because it never has any to leak.**

Cycle runs entirely on your phone. There are no accounts, no servers, no analytics and no ads. What you log is stored only in your browser on your device. Nobody else has a copy: not us, not an app store, not a cloud backup. That means nobody can sell it, subpoena it from us, or lose it in a breach.

**[Open Cycle →](https://thedarkone26.github.io/cycle-period-tracker/)**

## Why this exists

Period tracking apps hold some of the most sensitive health data there is, and most of them store it on company servers. Since *Roe v. Wade* was overturned, that data can be requested by courts and law enforcement. Cycle is built so that the only copy is in your hands.

## Features

- **Period, flow, symptom and note logging** with a monthly calendar
- **Predictions** for your next period, fertile window and estimated ovulation, based on your last six cycles
- **Handles real life:** log every day of your period or just the first day; a forgotten month doesn't throw off predictions; shows when you're late
- **Irregular cycle notice** when your cycles vary by a week or more
- **Backup and restore** to a file you keep, with merge or replace
- **Instant wipe** of everything on the device
- **Works offline** and installs to your home screen like a normal app

## Install it on your phone

**iPhone (Safari):** open the link above → tap **Share** → **Add to Home Screen** → **Add**.

**Android (Chrome):** open the link above → tap **⋮** → **Add to Home screen** (or **Install app**).

After the first visit it works with no internet connection at all, including in airplane mode.

## How your privacy is protected

| | |
|---|---|
| **Storage** | Your entries live in your browser's `localStorage` on your device only. |
| **Network** | The app makes no network requests. A Content Security Policy in the page blocks it from contacting any server, even by accident. |
| **Hosting** | The page is served by GitHub Pages. Like any website, GitHub sees that the page was loaded; it never sees anything you log. You can also download `index.html` and host it yourself. |
| **No third parties** | No analytics, fonts, trackers or libraries are loaded from anywhere. |
| **Check it yourself** | It's one HTML file. Read the source, or turn on airplane mode and use it. |

**Things to know**

- Anyone who can unlock your phone can open the app. A passcode lock is on the roadmap.
- Clearing your browser's site data deletes your entries. Use **Settings → Download Backup** now and then, and keep that file somewhere safe.
- Backup files contain your full history in plain text. Treat them like the private records they are.
- Predictions are estimates based on your past cycles. **Do not use them as birth control.**

## Roadmap

- [ ] Optional passcode lock with on-device encryption
- [ ] Discreet mode (neutral app name and icon)
- [ ] Track period end dates and period length automatically

## Support

Cycle is free and always will be. If it helps you, you can [leave a tip on Cash App](https://cash.app/$deweyspoon87).

## License

[MIT](LICENSE) © Spoon Labs
