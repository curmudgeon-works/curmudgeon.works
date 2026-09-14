# Curmudgeon Keyboard — Play Console cheat sheet (v0.1.0, 2026-09-13)

## Create app
- App name: Curmudgeon Keyboard
- Default language: English (United States)
- App or game: App · Free
- Declarations: tick both (Developer Program Policies, US export laws)

## Bundle to upload
~/Documents/curmudgeon/releases/Curmudgeon_Keyboard_0.1.0_vc1.aab
(package app.curmudgeon.keyboard, versionCode 1, versionName 0.1.0, signed with the upload key in ~/.android-keys)
Track: Testing → Closed testing → create track "Alpha" → upload → add tester emails → release name "0.1.0 (1)".
Release notes: First closed test. Swipe typing uses our own decoder; suggestions, spacing and learning behave as designed. Tell us what annoys you: support@curmudgeon.works

## Store listing (Main store listing)
- Short description (≤80, 71 chars): Keeps its hands off your data. Open source, made by one annoyed person.
- Full description (2327 chars, limit 4000):
Curmudgeon Keyboard is made by one person who got fed up with keyboards that think they know better. Here is exactly what it is and isn't.

WHAT IT DOES
• Remembers the words you teach it and keeps remembering them. Learned words fade only if you stop using them, and never all at once.
• A full row of suggestions ranked by how you actually type.
• You decide about spaces after punctuation, capitalisation and autocorrect. It never overrides the same correction twice.
• Swipe typing with our own decoder. It is built from expired patents and published research, not from any third-party gesture library, and every line of it is in the public source.
• Long-press symbols arranged like a physical keyboard, and you can remap every one of them in Settings.
• Hold backspace to delete word by word, with multi-level undo if you hold too long.
• Tight keys, a compact layout, and a settings screen you can prune down to only what you use.

WHAT IT DOESN'T DO
• No internet permission. The app cannot send anything anywhere. No ads, no accounts, no analytics, no crash reporting to us.
• Contacts are read only if you turn on the option to suggest names, and only on the phone.
• The personal dictionary permission is used to sync your learned words with Android's own user dictionary, so a backup or a reinstall keeps them.

OPEN SOURCE, ALL THE WAY
This is a fork of HeliBoard, licensed GPL-3.0, and the full source of exactly this build is on GitHub. Anyone can read it, build the same APK, or fork it. Please do. If you build on it, keep the attribution and we are happy.
Source: https://github.com/rahulj-rj/HeliBoard

WHERE IT IS RIGHT NOW
This is an early release from a project that is still moving fast.
• Only the English (US) dictionary ships in the app for licensing reasons. Other languages can be added by importing a dictionary file.
• The swipe decoder is new and still being tuned. Precise swipes are good; sloppy ones are not there yet. Every release should improve it.
• There is a Swipe Trainer tool behind the debug settings if you want to see what the decoder is thinking.

TELL US WHAT ANNOYS YOU
Complaints are the roadmap. Email support@curmudgeon.works or open an issue on GitHub. Reviews here are read too, but we cannot reply to them with questions.

Privacy policy: https://curmudgeon.works/privacy/
- App icon 512×512, feature graphic 1024×500, ≥2 phone screenshots: TODO (I can generate icon + feature graphic; screenshots from a Pixel via adb)
- Category: Tools · Tags: keyboard, productivity
- Contact email: support@curmudgeon.works · Website: https://curmudgeon.works · Privacy policy: https://curmudgeon.works/privacy/

## "Set up your app" questionnaires
- App access: All functionality is available without special access.
- Ads: No, the app does not contain ads.
- Content rating (IARC): Category "Utility, Productivity, Communication, or Other"; answer No to every content question → rated Everyone.
- Target audience: 18 and over only (keeps it out of the Families programme; no children's content).
- News app: No. · COVID-19 contact tracing: No. · Government app: No. · Financial features: none. · Health: none.
- Data safety: "Does your app collect or share any of the required user data types?" → No. (Contacts are read on-device only when the user enables the option; nothing is transmitted, so it is not "collected" under Play's definition.) Security practices: data is not encrypted in transit (nothing is transmitted); users can request deletion: not applicable / no data. 
- App category "Tools". Store presence: not designed for children.
- Advertising ID: No.

## Later (production access application after the 14-day test)
Keep tester feedback messages. Form asks: how you recruited testers, what feedback you got, what you changed, who the app is for.
