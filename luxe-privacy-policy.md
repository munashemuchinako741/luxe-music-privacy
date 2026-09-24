# Privacy Policy for Luxe Music

**Effective Date:** May 2024 (Last Updated: March 2026)

Welcome to **Luxe Music** ("the App", "we", "us", or "our"). We are committed to protecting your privacy and providing a secure, transparent experience. Luxe Music is designed as an **offline-first local audio playback and media management application**. 

This Privacy Policy explains what information Luxe Music accesses, how that information is used, and how your privacy is protected when you use our application on Android, iOS, Linux, Windows, macOS, or Web.

---

## 1. Core Privacy Philosophy: Offline-First

Luxe Music operates primarily on your device. We believe your personal music library, listening habits, playlists, and settings belong exclusively to you. 

- **No Remote Tracking:** We do not track, profile, sell, or rent your personal data.
- **No Third-Party Ads:** The App does not contain third-party advertising frameworks or ad-tracking networks.
- **Local Storage:** All app data—including playlists, playback queues, listening history, equalizer settings, and app configurations—is stored locally on your device.

---

## 2. Information We Access and Process

Luxe Music accesses only the data required to deliver core music playback and app customization features:

### A. Local Audio Files & Metadata
* **Data Accessed:** Audio files (MP3, FLAC, M4A, AAC, WAV, etc.) stored on your device storage or SD card, alongside associated metadata (song title, artist, album name, genre, duration, track number, and album cover artwork).
* **Purpose:** To discover, organize, display, and play your audio files within the application.
* **Storage & Transmission:** Metadata is indexed and cached locally on your device. Your audio files and metadata are **never uploaded to external servers**.

### B. Speech and Voice Commands (Optional)
* **Data Accessed:** Audio input recorded via your device's microphone when you explicitly activate voice search or voice controls.
* **Purpose:** To convert spoken commands (e.g., "Play artist", "Search song") into app navigation and playback actions.
* **Storage & Transmission:** Speech processing is handled locally on device or through your operating system's native speech recognition service. Audio recordings are **never stored, saved, or transmitted** by Luxe Music to external servers.

### C. Motion & Device Sensors (Optional)
* **Data Accessed:** Accelerometer and motion sensor events.
* **Purpose:** To enable motion-based controls such as "Shake to Skip Track" or "Shake to Play/Pause".
* **Storage & Transmission:** Motion data is processed in real-time on your device and is **never logged or transmitted**.

### D. Biometric & Security Data (Optional)
* **Data Accessed:** Fingerprint, Face ID, or system passcode credentials when App Lock is enabled.
* **Purpose:** To restrict unauthorized access to the application or private playlists.
* **Storage & Transmission:** Luxe Music relies entirely on your device's operating system security hardware (Android BiometricPrompt / iOS LocalAuthentication). The App **never receives, sees, or stores raw biometric data**.

### E. Device State & Network Connectivity
* **Data Accessed:** Basic system status (network availability, screen state, audio output routing like headphones or Bluetooth disconnects).
* **Purpose:**
  * To automatically pause playback when headphones disconnect.
  * To handle audio focus during phone calls or system notifications.
  * To provide online status checks if you open external links (e.g., artist web pages).

---

## 3. Permissions Requested and How They Are Used

Luxe Music requests only essential runtime permissions required for system features:

| Permission | Platform | Purpose |
| :--- | :--- | :--- |
| **Storage / Media Audio** (`READ_MEDIA_AUDIO`, `READ_EXTERNAL_STORAGE`) | Android / iOS | Required to scan and play audio files stored on your device. |
| **Microphone** (`RECORD_AUDIO`) | Android / iOS | Optional. Requested only if you choose to use voice commands. |
| **Foreground Service & Notifications** (`FOREGROUND_SERVICE_MEDIA_PLAYBACK`, `POST_NOTIFICATIONS`) | Android | Required to maintain uninterrupted background playback, display lock screen controls, and show media notifications. |
| **Biometrics** (`USE_BIOMETRIC`, `USE_FINGERPRINT`) | Android / iOS | Optional. Used only if you enable App Lock security features. |

You can grant or revoke any of these permissions at any time through your device's **System Settings**.

---

## 4. Third-Party Services and Analytics

Luxe Music **does not** integrate third-party data analytics services (such as Firebase Analytics, Google Analytics, Facebook SDK, or Mixpanel) and **does not** run third-party advertising services.

If you click an external link within the App (e.g., developer support links or web searches), your default web browser will open, and the destination website's privacy policy will govern your interaction on that site.

---

## 5. Data Security and Retention

- **Local Encryption:** Sensitive local credentials (such as an optional app passcode) are encrypted using standard platform secure storage mechanisms (`flutter_secure_storage` via Android KeyStore / iOS Keychain).
- **Data Retention & Removal:** All app data resides strictly on your device. You can clear all cached data, settings, and playlists at any time by clearing the App Data in your device's settings or by uninstalling the application. Uninstalling Luxe Music does **not** delete your physical music files from your device.

---

## 6. Children's Privacy

Luxe Music is a general-audience audio player and does not knowingly collect personal data from anyone, including children under the age of 13 (or 16 in the European Union). Because Luxe Music does not collect personal information online, it fully complies with the Children's Online Privacy Protection Act (COPPA) and the General Data Protection Regulation (GDPR).

---

## 7. Your Rights and Choices

Depending on your region (e.g., GDPR, CCPA/CPRA), you have rights regarding your personal data. Because Luxe Music stores all data locally on your device and does not collect or transmit personal data to remote servers:
- **Access & Export:** All your playlists, favorites, and history are visible and accessible directly inside the App.
- **Deletion:** You can delete your app data at any time by clearing the app storage or uninstalling Luxe Music.
- **Control Permissions:** You can manage or revoke hardware permissions (Microphone, Storage, Notifications) at any time in your OS Settings.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect app updates, platform policy revisions, or legal requirements. Updated versions will be published within the application or repository with an updated "Last Updated" date.

---

## 9. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy or the security of Luxe Music, please contact us at:

- **Developer:** Nashe Technologies / Luxe Music Team
- **Email:** nashetech.co.zw@nashetech.com 
- **Website:** coming soon