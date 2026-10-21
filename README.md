<p align="center">
  <picture>
    <img src="https://mailwell.app/assets/icon-256.png?v=2" width="128" height="128" alt="Mailwell app icon">
  </picture>
</p>

<h1 align="center">Mailwell</h1>

<p align="center">
  A calm, fast mail app for the Mac. Every account in one window, and your mail stays on your Mac.
</p>

<p align="center">
  <a href="https://github.com/luke-southwell/mailwell-releases/releases/latest/download/Mailwell.dmg"><b>Download for Mac</b></a>
  &nbsp;·&nbsp; <a href="https://mailwell.app">mailwell.app</a>
  &nbsp;·&nbsp; <a href="https://mailwell.app/docs">Docs</a>
  &nbsp;·&nbsp; <a href="https://mailwell.feedbackland.com">Feedback</a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://mailwell.app/assets/window-dark-1280.webp?v=1140">
    <img src="https://mailwell.app/assets/window-light-1280.webp?v=1140" alt="The Mailwell window: a sidebar with Favorites and accounts, the inbox list, and a conversation open on the right." width="900">
  </picture>
</p>

## What it is

Mailwell is a native Mac app, written in Swift. It talks straight to your mail provider, keeps a copy of your mail on your Mac, and searches it there, so it's quick and it works offline. There are no Mailwell servers in between and no analytics.

I built it because I couldn't find what I wanted. The fast, nice-looking apps mostly only did Gmail, or they wanted my mail or my password on their servers. The ones that kept mail on my Mac felt slow and busy. So this is the one I wanted to use.

## Works with

Gmail, iCloud, Microsoft 365 and Outlook.com, Fastmail, Kagi Mail, FranklyMail, Yahoo, and any IMAP or JMAP server. Fastmail, Kagi Mail and FranklyMail connect over JMAP, so new mail shows up the moment it arrives. Microsoft 365 signs in with Microsoft directly, so there's no IMAP to set up.

## What it does

- **One window for every account**, with a unified inbox. Or use **profiles** to keep Work and Personal apart and switch with ⌃1, ⌃2.
- **Inbox tabs** for Primary, Social, Promos and Updates on every provider, plus your own splits for the senders or folders you care about. Sorted wrong? **Move Sender to Tab** puts that sender in the right one from then on.
- **A light, quiet list**, grouped by date, with Archive, Snooze, Flag and Trash right on the row when you hover.
- **Search on your Mac**, with people suggestions as you type.
- **Quick Forwards.** Turn an address you forward to often, like receipts to Ramp or flights to Flighty, into a one-click button.
- **A shortcut for everything**, with Mailwell's keys or Gmail's. Undo with ⌘Z for archives, moves and sends.
- **Undo Send, Send Later, snippets and real formatting**, on every account.
- **Sign-in codes** in the notification with a Copy button.
- **Rules** that sort mail as it arrives, which you can try on your inbox first.
- **AI only if you want it.** It's off by default. Turn it on for thread summaries with Apple Intelligence or your own API key.
- **A read-only MCP switch** so Claude can search your mail through Mailwell, off until you turn it on.

## Your mail stays yours

- Mail and search live on your Mac. Passwords and sign-ins are in the macOS Keychain.
- Remote images and tracking pixels are blocked until you allow them.
- No analytics. The only thing kept on my side is the free trial, as a scrambled code.

More in the [privacy policy](https://mailwell.app/legal).

## Get it

- **Requires** macOS 14 Sonoma or later on Apple silicon.
- **Free for 14 days**, no card needed. Then $5 a month or $49 a year, for up to 3 Macs.
- **Founder lifetime license** while Mailwell is new: $59 for the first 50 people, then $129, until December 31, 2026.
- **Updates** come through the app itself. Every build is signed with a Developer ID and notarized by Apple.

[Download the latest version](https://github.com/luke-southwell/mailwell-releases/releases/latest/download/Mailwell.dmg), open the disk image and drag Mailwell to Applications. Release notes for every version are under [Releases](https://github.com/luke-southwell/mailwell-releases/releases).

## About this repository

This repo hosts Mailwell's downloads and the update feed (`appcast.xml`, attached to each release). The app's source code is private.

Mailwell is made by one person, me. Questions, bugs or ideas go to [hello@mailwell.app](mailto:hello@mailwell.app) or the [feedback board](https://mailwell.feedbackland.com), where you can vote on what comes next.

— Luke
