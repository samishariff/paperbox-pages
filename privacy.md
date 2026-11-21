---
title: Paperbox privacy policy
---

# Paperbox privacy policy

Effective date: 21 November 2026

Paperbox is an app for iPhone, iPad and Mac. It lets you search, read, fix and add documents kept in a Paperless-ngx archive. This policy explains what happens to your information when you use it.

The short version: your documents stay on your own household's server. The people who make Paperbox don't receive them, unless you upload something to the demo. We don't track you and we don't show you ads.

## Words used in this policy

- **We** means the developer of Paperbox, Sami Shariff.
- **Your household's server** is the computer, at home or elsewhere, that runs your household's Paperless-ngx archive and the **Paperbox Companion**. The Companion is the small service that Paperbox talks to. Every request from the app goes through it.
- **The Operator** is the person who runs that server. They set it up, choose its settings and keep its backups.
- **A Library** is one Paperless-ngx archive, with its own documents and its own accounts. A household can have more than one.
- **A Library manager** is a person who manages one Library. They can invite people to it, reset their sign-ins and delete it. The Operator is always a Library manager.

## Your documents stay on your household's server

Each household runs its own Companion and its own Paperless-ngx. Paperbox connects only to the server your household gave you an account on. Your documents, their text, their details (such as title, date, sender and type) and your account live there.

We don't run your household's server, and we receive nothing from it. We can't see your documents, your searches or your account. The Operator of your household's server can, because it's their server.

There is no sign-up. Your account comes from a Library manager, usually through an invite link.

The only server we run for Paperbox users is the demo (see [The demo](#the-demo) below).

## What the app sends to your household's server

To do its job, Paperbox sends your household's Companion:

- your username and password, when you sign in on a new device;
- a passkey check. Face ID, Touch ID or your device passcode confirms it's you. Your face, fingerprint and passcode never leave your device;
- your searches. They are sent inside the request, never in a web address;
- the changes you make to a document, such as a new title, a note or moving it to Trash;
- documents you scan or share into Paperbox. Photos are turned into a PDF on your device before they're sent.

Everything travels over an encrypted connection (HTTPS).

## What the Companion keeps, and for how long

The Companion is part of your household's server. It keeps:

- **Your account:** your username and the name your Library holds for you.
- **Not your password.** The Companion passes it to your Library once to check it, and doesn't store it.
- **A key to your Library:** this lets the Companion act as you in that Library. It is stored encrypted, and the key that unlocks it is kept separately.
- **Your passkeys and recovery codes.** Recovery codes are stored only in a scrambled form that can't be turned back into the codes. One-time setup codes expire after 15 minutes.
- **Your signed-in devices and agent connections.** Each one has its own sign-in. A sign-in that isn't used for 30 days stops working, and every device must sign in again at least every 90 days. You can see and remove them in Paperbox, under Settings, Connected agents.
- **A push address for each signed-in device**, so it can send you Account alerts (see below).
- **Sign-in records**, such as when a new device connected or a password was entered wrongly too many times. These protect your account. Kept for 90 days.
- **A change log with undo.** Every change to a document records what changed, the value before and after, who made it, through which connection, and when. This is what lets you undo a change. It has no end date.
- **Account alerts** sent to you. Kept for 90 days.
- **Invite links.** Each works once and expires after 7 days, unless it's cancelled sooner.

Your documents themselves are kept by Paperless-ngx until someone deletes them. A document moved to Trash can be restored until the Trash is emptied.

The Operator may also keep backups of the household's server. How long those last is up to the Operator.

## In App Store terms

On the App Store, Paperbox's privacy details list three kinds of data: your **name**, your **user ID** (your account, passkeys and signed-in devices) and **other user content** (your documents, scans, their details, notes and the change log). All three are linked to you. They are used only to make the app work, never to track you, and they are kept on your household's server, not by us. The exceptions: anything you upload to the shared demo, which other demo users can see until its nightly reset, and, if your household turns on the Filer with a cloud AI, the contents of new documents, which go to that AI company.

## AI on your household's server

A household can choose to have an AI help file new documents. This part of the Companion is called the **Filer**. It reads each new document and fills in its title, sender, type and a short **Summary** of what the document is. You can always correct what it wrote, and it never overwrites a value a person set.

For each Library, the Operator decides whether the Filer runs, and which AI it uses:

- **OpenAI** (available today), or
- **Anthropic** (planned, not yet available), or
- **a local model** running on the household's own computers (planned, not yet available), or
- **none** (the Filer is off).

If the Filer uses OpenAI or Anthropic, the Companion sends that company the contents of each new document. The company uses them to write the details and the Summary, under its own terms and privacy policy and the Operator's agreement with it. With a local model, nothing leaves the household's computers. With none, nothing is sent anywhere. The connection to the AI runs from the household's server. It never runs from your device, and never through us.

## Claude and ChatGPT connections

You can choose to connect an AI assistant, such as Claude or ChatGPT, to one Library. Nothing is connected unless you set it up and sign in yourself.

Once connected, the assistant can search that Library, read documents and their text, change their details, add notes, move documents to Trash and upload new ones. Anything it reads is sent to the company that runs the assistant, under that company's own privacy policy. Every change it makes is recorded in the change log and can usually be undone; Undo isn't offered when a later edit clashes with it or its history is uncertain. It can't permanently delete anything, and it can't change accounts or permissions.

Each connection reaches one Library only. You can remove it at any time in Paperbox, under Settings, Connected agents.

## Notifications (Account alerts)

Paperbox can tell you about your own sign-ins: for example, a new device connecting, too many wrong passwords, or a recovery code being used. These are **Account alerts**. They go only to you, on every device signed in as you.

Your household's Companion sends them through the Apple Push Notification service, which is run by Apple. An Account alert says what happened and when, and may name the Library. It never contains a document's title, text or file.

You can turn notifications off in your device's Settings. Demo accounts get no alerts.

## What stays on your device

To work quickly and offline, Paperbox keeps some things on your device:

- document details for the Library you're using;
- PDFs you opened recently or chose to keep on the device (up to 1 GB);
- recent searches, and scans waiting to be sent.

These are encrypted by your device and left out of iCloud and computer backups. On a Mac, Paperbox keeps them on disk only after you tell it FileVault is on. Otherwise it keeps them in memory only. Signing out of a Library wipes that Library's data from the device.

Paperbox locks after a restart and after 15 minutes away. It needs Face ID, Touch ID or your passcode to unlock.

**Spotlight, Shortcuts and Siri.** You choose, for each Library, whether it shows outside Paperbox. If it does, Paperbox adds its documents' titles, senders, dates and Summaries to Spotlight on your device. It never adds the text of a document. Turning this off, or signing out, removes them. If you run Paperbox actions in Shortcuts or Siri, Apple keeps its own record of those runs and their results on your device, and Paperbox can't delete it.

## No tracking, no analytics, no ads

Paperbox has no analytics, no advertising and no tracking. It contains no third-party code that collects data. We don't sell or share your information, and we don't build profiles.

If you've agreed in your device's settings to share analytics with app developers, Apple may give us crash reports and usage totals that don't identify you. Those come from Apple, under Apple's privacy policy, and contain no documents.

## Deleting your account

You can delete your account inside Paperbox, under Settings. It asks for Face ID first.

Deleting your account removes **you**, not the shared documents. It removes:

- your sign-in in every Library on that server;
- your passkeys;
- your Claude, ChatGPT and other agent connections;
- your Account alerts;
- the copies Paperbox saved on your devices.

Sign-in stops at once. The Operator is told, and can restore your account within **7 days**. After that, the deletion is permanent.

The documents in the Library stay, because they belong to everyone who shares it. The change log keeps its record of the changes you made, so that they can still be undone, but after the 7-day restore window it shows them as made by "a deleted account" instead of your name.

The Operator's own account can't be deleted from the app. The Operator removes it on the server.

## Deleting a Library

A Library manager can delete a whole Library inside Paperbox. It asks for Face ID and for the Library's name to be typed. It deletes one Library at a time.

Deleting a Library removes its documents, everyone's access to it and the Filer's account for it. Everyone loses access at once and gets an alert. The Operator can restore it for **30 days**, and a final backup is kept until then. After 30 days, the Library can no longer be restored in Paperbox. Copies of its PDFs kept elsewhere by the Operator, such as backups or a cloud folder, follow the Operator's own backup settings and may last longer.

## The demo

Paperbox has a demo, reached from "Try the demo" on a new install. It is the one server we run. Its two demo Libraries hold only made-up documents.

Everyone who tries the demo shares it. Anything you change or upload there can be seen by other demo users until the next reset. Every night the demo is wiped and reset to the same made-up documents. Please don't upload anything real or personal.

The demo's Filer is off, so nothing you upload is sent to an AI. The demo can't be connected to Claude or ChatGPT, and it sends no alerts. It keeps the same sign-in protections as any other server, such as counting wrong passwords.

## Children

Paperbox isn't aimed at children. Accounts are created only by a household's Library managers, so a child has an account only if their household gives them one. We don't knowingly collect information from children. A household's Operator can delete any account on their server.

## Your choices and rights

Your household's server holds your information, so your household's Operator is the person to ask to see, correct, export or delete it. You can delete your own account at any time in Paperbox.

We hold none of your information, except what you enter in the demo until its nightly reset, any email you send us, and the reports Apple gives us as described above.

## Changes to this policy

If this policy changes, we'll update this page and its effective date. Big changes will also be noted in the app's release notes.

## Contact

Questions about this policy: <paperbox@shariff.io>

This page is hosted on GitHub Pages. GitHub may log visits to it under GitHub's own privacy policy.
