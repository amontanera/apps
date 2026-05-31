# Privacy Policy — Photo Puzzle

_Last updated: 31 May 2026_

Photo Puzzle ("the app") is a sliding-tile puzzle game published by an independent developer ("we", "us") under the package name `io.github.amontanera.photopuzzle`. This page explains what data the app handles, where it goes, and how to contact us about it.

## Short version

- We don't ask for your name, email, phone number, or any account.
- Your photos never leave your device.
- The app reaches out to a few well-known public APIs to fetch artworks (The Met, Art Institute of Chicago, Pixabay).
- The app uses Google Firebase to collect anonymous crash reports and aggregate usage events that help us fix bugs and improve the game.
- The app uses Google Play Billing to process the optional one-time Pro purchase and optional tips. We never see or store your payment details.

## What data we collect

### 1. Photos and folders you select
When you pick a folder via Android's system folder picker (SAF), the app scans it for image files and uses them as puzzle pools. **The photos are read locally and never uploaded anywhere.** The only thing stored is the list of folder URIs you chose, on your device.

### 2. SMB network share credentials (optional, Pro)
If you add a network folder via the SMB option, the server address, share name, and any username/password you enter are stored locally on your device only. They are used by the app to connect to your home server and are never transmitted to us or to any third party.

### 3. In-app analytics — Firebase Analytics (Google)
The app sends anonymous, aggregate usage events (for example: a puzzle was started, a grid size was selected, the trial expired) to Google Firebase Analytics. These events contain no personal information and cannot be linked back to you. Google assigns a random, resettable "Firebase Installation ID" to each install, which you can reset by clearing the app's data.

Documentation: <https://firebase.google.com/support/privacy>

### 4. Crash reports — Firebase Crashlytics (Google)
If the app crashes, Firebase Crashlytics sends a stack trace and basic device information (model, OS version, locale, available memory) to us via Google. Crash reports do not contain your photos or any content you created.

Documentation: <https://firebase.google.com/support/privacy>

### 5. In-app purchases — Google Play Billing
If you choose to unlock Pro or send a tip, the transaction is handled entirely by Google Play. We receive a confirmation of purchase from Google but never see your card or payment account details. Pro entitlement is stored as a single boolean flag on your device.

### 6. Third-party public APIs
When you pick a museum source, the app makes outgoing requests to the following public APIs to fetch artworks:

- **The Metropolitan Museum of Art Open Access API** — <https://metmuseum.github.io/>
- **Art Institute of Chicago API** — <https://api.artic.edu/docs/>
- **Pixabay API** — <https://pixabay.com/api/docs/>

These requests carry only the standard HTTP information (your device's IP address, user-agent). We do not send them any personal information about you. Each provider has its own privacy practices linked above.

## What data we do not collect

- No name, email, phone number, address, or any contact info.
- No precise or coarse location.
- No advertising ID.
- No contacts, calendar, microphone, camera (the app only reads from folders you explicitly pick).
- No browsing history.
- No third-party advertising networks.

## Multiplayer ("Puzzle Party")

The hosting and joining of multiplayer parties happens entirely over your local Wi-Fi network. No party data, photo, or device identifier is sent to any server we control. The host device serves photos directly to guest phones on the same LAN.

## Data retention and deletion

All app data is stored locally on your device. To delete everything the app knows, simply uninstall the app or use Android Settings → Apps → Photo Puzzle → Storage → Clear data.

Crash and analytics data sent to Firebase is retained according to Google's defaults (typically up to 14 months for analytics, longer for crashes). You can request deletion of any Firebase data associated with your install by contacting us — please include the timeframe of your usage so we can locate the records.

## Children

Photo Puzzle is suitable for all ages and is rated PEGI 3 / ESRB Everyone. It does not knowingly collect any data from children. If you are a parent and believe we have inadvertently collected data from your child, please contact us and we will delete it.

## Changes to this policy

We may update this policy as the app evolves. Material changes will be reflected in the "Last updated" date at the top.

## Contact

For privacy questions, requests, or data deletion:

- Email: **albanm.app@gmail.com**
- Developer support page: <https://ko-fi.com/albanm>

---

App package: `io.github.amontanera.photopuzzle`
Developer: Alban M. 
