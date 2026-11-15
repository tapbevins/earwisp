---
title: Earwisp privacy policy
permalink: /privacy/
---


**Effective 15 November 2026.** Earwisp is a free audiobook player and recommendation app for Android and Windows, made by Tyler Bevins, an independent developer in New Zealand. Contact: **earwisp@gmail.com**.

## The short version

- **Earwisp has no server and no accounts.** Your library, ratings, notes, listening history and settings stay on your own devices.
- **There are no ads, analytics, tracking or crash-reporting services.**
- To look up book details, covers and recommendations, Earwisp contacts some outside services, starting when it first reads your audiobook folder. **Only the information needed for each request goes to them.** They are listed below, with how to turn each one off.
- **AI features and anything that sends audio need a key you add yourself** or a button you press. Nothing is recorded or sent in the background.
- You can delete everything Earwisp stores, at any time, from **Settings › Your data**.

## What stays on your device

Earwisp stores these on your phone and/or computer, in the app's own private storage:

- **The scan of your audiobook folder:** titles, authors, series, lengths, cover thumbnails and file locations.
- **What you enter:** ratings, notes, statuses, bookmarks, your place in each book, saved books, followed authors and narrators, and your preferences.
- **Voice notes (Android):** the text of each note. The recording itself is deleted after two days unless you turn on Settings › Listening › Keep voice recordings.
- **Listening history:** time listened per book per month, including statistics you import from other players (for example Smart AudioBook Player) or from Goodreads or Audible exports you choose to import.
- **API keys you add** for AI services. These are encrypted: on Android with the Android Keystore, on Windows with your Windows account.
- **Cached book details and covers,** so they don't need to be fetched again.
- **Loudness measurements** for the Even volume feature. Each book is measured on your device; nothing is sent anywhere.

**What Earwisp writes in your audiobook folder.** Earwisp never changes your audio files. It does add:

- **A "!Earwisp" folder** with a spreadsheet of your statistics and a backup of your Earwisp data, updated about once a day. If your audiobook folder is synced to a cloud service, that service's own terms apply to these files.
- **A small tag file in each book's folder** (`earwisp.json`), holding Earwisp's own ID for the book so a moved or renamed book keeps your ratings and place. You can turn this off in the welcome or in Settings › Book tags.
- **Only when you ask,** Earwisp renames or moves book folders: the Tidy tool, and "Rename the folder too" when you edit a book's details.

**Phone–computer sync.** If you pair your phone with your computer, the two exchange your Earwisp data, and any audiobooks and covers you choose to copy, directly over your local Wi-Fi network. Every message is encrypted with a key created when you pair. Nothing goes through the internet or any server.

## What is sent to outside services, and when

| Service | When | What is sent |
|---|---|---|
| **Audible** catalog (api.audible.com and its regional sites) | When Earwisp looks up details for the books in your folder, and when you search or view picks, series lists, similar books or narrator/author releases. On to begin with; turn it off with **Settings › Fetch details from Audible** | Search words, book titles and authors, and Audible book IDs |
| **Open Library** (openlibrary.org, with covers from covers.openlibrary.org and archive.org) | Book details, search and covers | Search words, book titles and authors |
| **Wikidata** (wikidata.org) | Book details such as series and year | Book titles |
| **Amazon image servers** | To show cover images found through Audible | A request for the cover image |
| **Google Gemini, Groq or Anthropic Claude** (only if you add your own key) | AI picks, AI search, and Ask AI in the Player | For picks and search: a **taste summary**, made up of books you loved or rated low (with your ratings and hours listened), your chosen interests, listening hours by genre and narrator, and the titles and authors of books you own (so they aren't suggested again), plus what you type. For Ask AI: the book's title, author and series, how far through it you are, chapter names, your recent questions and answers, and your question |
| **Google Gemini** (only with your own key, when you ask for a recap) | "Recap the last 30 minutes" in Ask AI | A clip of the audiobook's own audio from the part you just heard. Earwisp deletes the clip from Google's file storage once the answer comes back |
| **Groq** (Android, only with your own key) | When you speak a voice note or review | Your recording, to be turned into text |
| **Your phone's speech service** (Android, when you have no Groq key) | When you speak a voice note or review | Your speech goes to the speech recogniser set on your phone (usually Google's or Samsung's), which may process it online under that provider's terms |
| **Google Play services** (Android only) | When you scan the pairing code from your computer | The camera image is processed by Google's code scanner on your device |
| **GitHub** (Windows only) | A check for a newer version when Earwisp starts and every few hours | A request for the latest release |

**What every request carries:** like any internet request, each one includes your device's IP address. The services above receive the information as independent providers under their own terms and privacy policies, which Earwisp doesn't control.

- **Google's free Gemini tier** may use what you send to improve Google's products. Groq and Anthropic don't use API data for training by default; check each provider's current terms.
- **No AI service is used unless you add your own key.**
- **The microphone** (Android) is used only while you are recording a voice note, and Earwisp asks for permission first.

**Links:** buttons such as "Open on Audible" or "Search Goodreads" open those websites in your browser. What happens there is covered by those sites' own policies.

## What Earwisp does not do

- No advertising, and no selling or sharing of your data.
- No analytics or usage tracking, and no crash-reporting service. On Android, Google Play may give the developer anonymous crash and performance statistics (Android vitals) under Google's terms.
- No accounts, and no collection of your name, email or location.

## Your rights and choices

- **See and delete your data:** it's all on your devices. **Settings › Your data › Delete all my data** removes what Earwisp stores in the app; uninstalling the app does too. The "!Earwisp" folder and the tag files in your audiobook folder stay until you delete them.
- **Export:** Settings › Your data › Back up, and the spreadsheet export.
- **Stop data going to a service:** turn off **Fetch details from Audible**; don't add an AI key (or remove it); don't record voice notes.

Because the developer doesn't receive or hold your data, there is nothing for the developer to access, correct or delete on your behalf. Questions are still welcome at **earwisp@gmail.com**.

**This policy is written to meet:**

- **New Zealand's Privacy Act 2020.** If you have a concern, contact the developer first. You can also complain to the Office of the Privacy Commissioner (privacy.org.nz).
- **The EU and UK GDPR.** If you're in the EU or UK, you have the right to complain to your local data protection authority.

## Children

Earwisp isn't directed at children under 13 (16 in some countries). It doesn't knowingly collect information from children, and it doesn't collect personal information from anyone.

## Changes

If this policy changes, the new version will be posted here with a new effective date. Significant changes will also be noted in the app's release notes.
