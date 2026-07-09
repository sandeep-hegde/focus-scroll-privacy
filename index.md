# Focus Scroll — Privacy Policy

**Effective date:** July 9, 2026
**Applies to:** Focus Scroll Chrome extension, version 1.2.1 and later

Focus Scroll is a distraction-free article reader. Its privacy posture is
simple: **everything stays on your device. What you read is your business.**

This page explains exactly what the extension stores, where, and what it
never does.

---

## What Focus Scroll stores

**1. Reader preferences** — your chosen theme, text size, typeface, and focus
zone width. Stored via Chrome's `storage.sync` area so your settings follow
you between your own computers (see "A note on Chrome Sync" below).

**2. Highlights and notes** — if you highlight text in an article, the
extension stores the highlighted text, any note you attach to it, the
highlight color, the addresses (URLs) of any links contained inside the
highlighted text (so exports can reproduce them as working links), and the
article's title and web address (URL). This is stored via Chrome's
`storage.local` area, **on your device only**, so your highlights reappear
the next time you open the same article.

**3. Reading position** — where you were in an article, kept in the tab's
session storage so reopening the reader returns you to the same spot. This
is cleared automatically when the tab closes.

**4. A one-time update marker** — when the extension updates to a version
with new features, it stores the old and new version numbers (nothing else)
so the reader can show a short "what's new" notice once. The marker is
deleted as soon as the notice is shown.

That is the complete list.

## What Focus Scroll never does

- **No transmission.** The extension has no server. Nothing you read,
  highlight, or write is ever sent anywhere — not to us, not to anyone.
- **No tracking or analytics.** No usage statistics, no telemetry, no
  crash reporting, no identifiers.
- **No browsing history collection.** The extension only touches a page
  when you explicitly activate it (toolbar icon or keyboard shortcut), and
  it never records which pages those were, beyond the highlights you
  yourself choose to save.
- **No accounts.** There is nothing to sign up for and no profile of you
  anywhere.
- **No ads, no selling of data.** There is no data to sell.
- **No remote code.** All code ships inside the extension package and is
  reviewed by the Chrome Web Store.

## A note on Chrome Sync

Reader *preferences* (theme, text size, typeface, focus zone — not your
highlights or notes) are stored using Chrome's built-in `storage.sync`
feature. If you are signed into Chrome with sync enabled, Chrome itself —
operated by Google, not by Focus Scroll — copies these few settings between
your devices under your Google account. If you don't use Chrome sync, they
simply stay local. Your highlights and notes are **never** synced; they
remain only on the device where you created them.

## Your data, your control

- **Export:** you can export any article's highlights and notes as a
  Markdown file or copy them to the clipboard at any time, from the
  Highlights panel inside the reader.
- **Delete:** removing a highlight deletes it immediately. Uninstalling the
  extension removes all stored highlights, notes, and preferences from your
  device (synced preferences are also removed from Chrome sync).

## Permissions, in plain language

| Permission | Why it's needed |
|---|---|
| `activeTab` | Lets the extension read the current page's content **only at the moment you activate it**, to extract the article text. |
| `scripting` | Lets the extension display the reader view on the page you activated it on. |
| `storage` | Saves your preferences, highlights, and notes as described above. |

The extension has no permission to run in the background on pages you visit,
and does not do so.

## Changes to this policy

If a future version of Focus Scroll ever changes what is stored or where
(for example, an optional sync feature), this policy will be updated before
that version ships, with the change noted here and in the extension's
changelog.

## Contact

Questions about this policy or the extension:
**advaya.cws@gmail.com**
