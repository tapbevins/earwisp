---
title: Earwisp privacy policy
permalink: /privacy/
---


**Effective 21 October 2026.** Earwisp is a free audiobook player and recommendation app for Android and Windows, made by Tyler Bevins, an independent developer in New Zealand. Contact: **earwisp@gmail.com**.

## The short version

- **Earwisp has no server and no accounts.** Your library, ratings, notes, listening history and settings stay on your own devices.
- **There are no ads, analytics, tracking or crash-reporting services.**
- To look up book details, covers and recommendations, Earwisp contacts some outside services. **Only the information needed for each request goes to them**, and only when you use the feature. They are listed below.
- You can delete everything Earwisp stores, at any time, from **Settings › Your data**.

## What stays on your device

Earwisp stores these on your phone and/or computer, in the app's own private storage:

- **The scan of your audiobook folder:** titles, authors, series, lengths, cover thumbnails and file locations. Earwisp only reads your audiobook folder; it never changes your audio files.
- **What you enter:** ratings, notes, statuses, bookmarks, your place in each book, saved books, followed authors and narrators, and your preferences.
- **Listening history:** time listened per book per month, including statistics you import from other players (for example Smart AudioBook Player) or from Goodreads or Audible exports you choose to import.
- **API keys you add** for AI services. These are encrypted: on Android with the Android Keystore, on Windows with your Windows account.
- **Cached book details:** details and covers looked up for books, so they don't need to be fetched again.

**Optional copies you control:**

- **Backups in your audiobook folder.** Earwisp can keep a spreadsheet and a backup of your data in a "!Earwisp" folder inside your audiobook folder. You choose that folder; if it's synced to a cloud service, that service's own terms apply.
- **Phone–computer sync.** If you pair your phone with your computer, the two exchange your Earwisp data directly over your local Wi-Fi network. Every message is encrypted with a key created when you pair. Nothing goes through the internet or any server.

## What is sent to outside services, and when

| Service | When | What is sent |
|---|---|---|
| **Audible** catalog (api.audible.com and its regional sites) | When you look up book details, search, or view picks, series lists, similar books or narrator/author releases | Search words, book titles and authors, and Audible book IDs |
| **Audnexus** (api.audnex.us) | Backup for book details when Audible doesn't answer | Audible book IDs |
| **Open Library** (openlibrary.org) | Backup for covers | Book titles and authors |
| **Amazon / Open Library image servers** | To show cover images | A request for the cover image |
| **Google Gemini, Groq or Anthropic Claude** (only if you add your own key) | AI picks, AI search, and Ask AI in the Player | For picks and search: a **taste summary**, made up of books you loved or rated low (with your ratings and hours listened), your chosen interests, listening hours by genre and narrator, and the titles and authors of books you own (so they aren't suggested again), plus what you type. For Ask AI: the book's title, author and series, how far through it you are, chapter names, and your question |
| **Google Play services** (Android only) | When you scan the pairing code from your computer | The camera image is processed by Google's code scanner on your device |

**What every request carries:** like any internet request, each one includes your device's IP address. The services above receive the information as independent providers under their own terms and privacy policies, which Earwisp doesn't control.

- **Google's free Gemini tier** may use what you send to improve Google's products. Groq and Anthropic don't use API data for training by default; check each provider's current terms.
- **No AI service is used unless you add your own key.**

**Links:** buttons such as "Open on Audible" or "Search Goodreads" open those websites in your browser. What happens there is covered by those sites' own policies.

## What Earwisp does not do

- No advertising, and no selling or sharing of your data.
- No analytics or usage tracking, and no crash-reporting service. On Android, Google Play may give the developer anonymous crash and performance statistics (Android vitals) under Google's terms.
- No accounts, and no collection of your name, email or location.

## Your rights and choices

- **See and delete your data:** it's all on your devices. **Settings › Your data › Delete all my data** removes everything Earwisp stores; uninstalling the app does too. Backups you made in your audiobook folder stay until you delete them.
- **Export:** Settings › Your data › Back up, and the spreadsheet export.
- **Stop data going to a service:** don't add an AI key (or remove it), and don't use the lookups that contact the services above.

Because the developer doesn't receive or hold your data, there is nothing for the developer to access, correct or delete on your behalf. Questions are still welcome at **earwisp@gmail.com**.

**This policy is written to meet:**

- **New Zealand's Privacy Act 2020.** If you have a concern, contact the developer first. You can also complain to the Office of the Privacy Commissioner (privacy.org.nz).
- **The EU and UK GDPR.** If you're in the EU or UK, you have the right to complain to your local data protection authority.

## Children

Earwisp isn't directed at children under 13 (16 in some countries). It doesn't knowingly collect information from children, and it doesn't collect personal information from anyone.

## Changes

If this policy changes, the new version will be posted here with a new effective date. Significant changes will also be noted in the app's release notes.
