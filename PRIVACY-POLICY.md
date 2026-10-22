# Lock Screen Bible Privacy Policy

**Effective date and last updated: October 23, 2026**

**Developer: HustleUp** · **Contact: [hustlin.up@gmail.com](mailto:hustlin.up@gmail.com)**

## Apps covered

This policy covers the following Android Bible apps provided by HustleUp. They share the data practices described below, although their interface languages and included Bible editions differ.

- **Lock Screen Bible: Daily Pause** — English · `com.hustleup.lockscreenbible.en`
- **Biblia al encender la pantalla** — Español · `com.hustleup.lockscreenbible.es`
- **Bíblia ao acender a tela** — Português (Brasil) · `com.hustleup.lockscreenbible.ptbr`
- **Bibel am Sperrbildschirm** — Deutsch · `com.hustleup.lockscreenbible.de`
- **잠금화면 성경: 말씀 한 구절** — 한국어 · `com.hustleup.lockscreenbible.ko`
- **Bible sur écran verrouillé** — Français · `com.hustleup.lockscreenbible.fr`
- **Bibbia sullo schermo bloccato** — Italiano · `com.hustleup.lockscreenbible.it`
- **Biblia na ekranie blokady** — Polski · `com.hustleup.lockscreenbible.pl`
- **Bibliya sa paggising** — Tagalog · `com.hustleup.lockscreenbible.tl`

## At a glance

No account is required. The included Bible texts, reading, search, bookmarks and settings work on your device. We do not operate a backend that receives your Bible searches, saved verses or reading history, and we do not add our own analytics or crash-reporting service. Advertising involves Google data processing. Opening external study, video or sharing features sends the content you choose to the receiving service, as explained below. There are no paid products or subscriptions.

## Reading data and settings on your device

The app stores your selected Bible version, bookmarks, reading position and rotation, selected topics, appearance and colors, clock and animation choices, setup progress, display frequency, quiet hours, reminder preferences, and optional ad-reward expiry locally. Available versions and topics depend on the edition. Reference and word searches run against the bundled offline Bible database; the app does not send these searches to us.

The Recent list keeps the last 50 viewed verse references and Bible-version identifiers, newest first. Viewing a verse again moves it to the top. Lock-screen previews and search-result lists are excluded. Clear this list from Saved → Recent → Clear history without removing bookmarks or your reading position. Control names are localized in other editions.

Local timestamps record recent reading, the last verse-card display and the detected next alarm. They help avoid frequent reminders, limit card frequency and give alarms priority. This reading and settings data is not supplied by the app as advertising targeting data.

## Optional lock-screen display and permissions

If you enable lock-screen verses, a foreground service receives Android screen-on events and maintains an ongoing notification with a pause control. Display-over-other-apps access lets the verse card appear above your existing device lock. It does not replace or bypass your PIN, password or biometrics, or read other apps' screen contents. Verse text is visible to anyone who can see your screen while this feature is enabled.

The app checks Android's available audio mode, playback state and next scheduled alarm time to yield to detected calls, alarms or active audio. It does not record sound or request microphone, contacts, call-log or phone-state access, and does not read call contents or phone numbers. Detection depends on Android and the device. The bottom dismissal control closes our card; it does not read payment information or launch Wallet.

Notification permission is used for the service notification and optional reading reminders, not to read other apps' notifications. Boot-completed access restores an enabled service after restart when Android permits. Internet and network-state access support advertising and connected features. You can pause lock-screen verses in the app or its notification and revoke display or notification access in Android settings.

## Optional reading reminders

You can enable two reminders using local-time settings. They are scheduled on the device with Android background work, may be delayed by system restrictions, and are skipped during quiet hours or after recent reading. Pausing lock-screen verses does not switch off reminders; disable reminders separately if you no longer want them. Reminder times and local reading timestamps are not sent to a developer server.

## Google advertising and privacy choices

Google Mobile Ads (AdMob) serves separate banner placements in the unlocked companion app and on the app's visible verse lock-screen card. Optional rewarded ads appear only in the unlocked companion. Completing a rewarded ad grants 24 hours without companion banners on that device; lock-screen banners remain. The expiry is stored locally. All Bible reading, study links, searches and themes remain available without watching a rewarded ad.

The Google Mobile Ads SDK collects and shares information for advertising, measurement, analytics and fraud prevention. This can include your IP address and approximate location inferred from it; app and ad interactions such as launches, taps and video views; diagnostic and performance information; and device or account identifiers, including advertising ID and app set ID where available. Google documents encryption of SDK data in transit using TLS. The app requests nonpersonalized ads. This does not mean that ads process no data or require no consent. We do not supply your Bible searches, saved verses, selected versions, topics, reading history, photos or religious beliefs as ad targeting data. Ad revenue and performance reports may be available to us through AdMob; we do not receive your local Bible-reading records through those reports.

Google's User Messaging Platform manages applicable consent and privacy choices. Consent forms appear in the unlocked companion. Ad requests are gated by the consent SDK's request-eligibility result; lock-screen banners are released when the card closes, the screen turns off or the Activity leaves the foreground. Where available, open **Ad privacy** in the companion to change your choices. You can also reset or delete your advertising ID in supported Android settings. Google determines retention of its advertising data under its policies; clearing this app's storage does not delete data already held by Google.

See the [Google Privacy Policy](https://policies.google.com/privacy), [how Google uses information from apps using its services](https://policies.google.com/technologies/partner-sites), and [Google advertising information](https://policies.google.com/technologies/ads).

## External study prompts and YouTube

When you choose to open a study prompt in Google AI Mode or Google Search, the displayed verse text, reference, selected Bible-version label and preset study questions are included in a Google search URL. A Catholic-edition prompt may also identify that edition's interpretive context. The prompt is shown before you choose to open it. Local Bible search is separate and stays on your device. We do not receive or store Google's answers. Google, your browser and your account settings determine processing and retention of the external request. AI responses may be inaccurate.

Choosing YouTube opens an external search URL with the displayed verse reference, such as “Galatians 2:20.” It does not send your bookmarks, reading history, full verse text or selected Bible version, and does not automatically play a video. Google/YouTube and the receiving browser or app handle the search and any later viewing under their policies. Video results are not reviewed by us. These actions can reveal an interest in the selected Bible passage to the receiving service.

Copying a verse or study prompt places the chosen text on Android's clipboard. Android manages clipboard access; if you paste it into another app, that app receives it. External destinations from the verse lock screen use Android's unlock flow when the device is securely locked.

## Sharing and optional background photos

Share cards are rendered on your device with the verse, reference, version and applicable source credits. You can use a plain background or choose a picture through Android's photo picker. The app accesses only the picture you select, without requesting broad photo-library permission. The app does not upload it to a developer server. If the picker offers a cloud provider, that provider handles retrieval under its own policy.

Previewing or selecting a picture does not share it. If you choose to share, Android's share sheet lets you select a receiving app. Text sharing passes the verse and attribution. Image sharing passes the completed card, accompanying text and a temporary read-access grant through Android FileProvider. The receiving app can retain or forward this content under its own policies; a shared card includes any background photo you chose.

Generated PNG cards are kept in the app's private cache. When another card is generated, the app attempts to delete cached card files older than 24 hours; this is not a guaranteed 24-hour deletion timer. Android may clear cache earlier. Clearing app storage or uninstalling removes app-owned cache, but does not remove copies you already shared or saved elsewhere.

## Retention, deletion and security

Local preferences and bookmarks remain until you change them, clear app storage or uninstall. Recent history is limited to 50 references and can also be cleared separately. The app disables Android app backup and excludes its data from Android cloud backup and device transfer; manufacturer-specific transfer tools may behave differently. Local app data is protected by Android's application sandbox. No storage or transmission method can guarantee absolute security.

We cannot remotely retrieve or erase data that stays only on your device. To remove it, use Android Settings → Apps → this app → Storage → Clear data, or uninstall. Names vary by device. To manage data independently held by Google or a sharing destination, use that service's privacy controls and contact channels. These services may process data outside your country under their own policies.

If you email us, we receive your email address, message and any attachments you send. We use these to answer your request, provide support and meet applicable obligations, retaining them only as long as needed for those purposes. Do not send passwords, payment details or sensitive personal information in support messages. We do not sell your support correspondence or local reading records.

Depending on your location, you may have rights to access, correct or delete personal data, restrict or object to processing, withdraw consent, request portability, or complain to a privacy authority. Contact [hustlin.up@gmail.com](mailto:hustlin.up@gmail.com) for questions or requests concerning data we control. We will explain what we hold and how we can help. There is no app account to delete.

## Teens and children

These apps are intended for teenagers aged 13 and older and adults. They are not directed to children under 13. If you believe a child under 13 has provided personal information directly to us, contact [hustlin.up@gmail.com](mailto:hustlin.up@gmail.com) so we can investigate and remove information we control as appropriate.

## This policy website

This static policy site is hosted on GitHub Pages. We add no advertising, analytics scripts, tracking pixels or forms to it. GitHub may process technical request information, including IP addresses, to provide and secure hosting. See the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Opening the policy does not send your app's bookmarks or reading history to the site.

## Policy changes and contact

We may update this policy when the apps or data practices change. The policy will show the updated effective date. Questions or privacy requests: **HustleUp**, [hustlin.up@gmail.com](mailto:hustlin.up@gmail.com).
