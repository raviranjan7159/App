# 🔐 SecretVault

### Your Privacy. Your Secrets. Your Control.

**SecretVault** is a privacy-focused Android password and sensitive information manager that securely stores your passwords, private notes, and confidential information directly on your device.

Built around a zero-knowledge approach, SecretVault encrypts your data locally, ensuring that your master password remains yours. No cloud servers, no trackers, and no unnecessary data collection.

<p align="center">
  <strong>🔒 100% Offline · AES-256-GCM · Encrypted Backups</strong>
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔐 Master Password | Protect your entire vault with a master password. |
| 🛡️ AES-256-GCM | Authenticated encryption for stored secrets. |
| 📝 Secret Management | Add, view, and edit passwords and private notes. |
| 🔍 Instant Search | Quickly find secrets by title or keyword. |
| ☑️ Multi-Select | Select and delete multiple secrets at once. |
| 🔄 Auto-Lock | Automatically locks the vault after 60 seconds of inactivity or when leaving the app. |
| 🔑 Password Change | Change your master password without losing saved secrets. |
| 📦 Encrypted Backup | Export your vault into password-protected `.secret` files. |
| ♻️ Backup Restoration | Import encrypted backups to restore your secrets. |
| 📵 Offline First | Designed to operate without internet connectivity. |
| 🚫 No Cloud Backup | Disables Android automatic cloud backups to protect local vault data. |

---

## 🚀 Getting Started

### 1. Install SecretVault

Download the latest APK from the repository's Releases section (when available).

1. Download the APK.
2. Open the downloaded file on your Android device.
3. Allow installation from unknown sources if requested.
4. Tap **Install**.
5. Launch SecretVault.

### 2. Create Your Vault

1. Open SecretVault.
2. Enter a strong Master Password (minimum 6 characters).
3. Confirm your Master Password.
4. Tap **Create Vault**.
5. Your encrypted vault is ready!

> ⚠️ **Important:** Your Master Password cannot be recovered. If you forget it, your encrypted data may become permanently inaccessible. Keep a secure offline backup of your password.

### 3. Unlock Your Vault

1. Launch SecretVault.
2. Enter your Master Password.
3. Tap **Unlock**.
4. Access your saved secrets.

The application automatically locks after 60 seconds of inactivity or when you leave the app.

---

## 📖 User Guide

### 📝 Add, View & Edit Secrets

**Add a Secret**
1. Tap the `+` button.
2. Enter a title and secret content.
3. Tap **Save**.

**View a Secret**
1. Tap any saved item.
2. View its contents.
3. Use the Back Arrow to return.

**Edit a Secret**
1. Open a saved item.
2. Tap the Pencil icon.
3. Update the title or content.
4. Save your changes.

### 🔑 Change Master Password

1. Unlock your vault.
2. Tap the Key icon in the top navigation bar.
3. Enter your current Master Password.
4. Enter and confirm your new Master Password.
5. Tap **Change Password**.

Your saved secrets remain available after a successful password change.

### 🔍 Search Secrets

1. Tap the Search icon.
2. Enter a title or keyword.
3. Browse the filtered results.
4. Tap `X` to clear the search.

### ☑️ Multi-Select & Delete

1. Long-press any secret card.
2. Tap additional cards to select them.
3. Review the selected item count.
4. Tap the Trash icon to delete selected secrets.
5. Tap `X` to exit selection mode.

---

## 📦 Encrypted Backup & Restore

SecretVault supports encrypted `.secret` backup files, allowing you to transfer or restore your vault.

### Export Vault

1. Open the vault.
2. Tap the three-dot menu (`⋮`).
3. Select **Export Vault**.
4. Create a Backup Password.
5. Tap **Export**.
6. Choose a destination such as Downloads, SD Card, or Google Drive.
7. Save your `.secret` backup file.

### Import Vault

1. Open the three-dot menu (`⋮`).
2. Select **Import Vault**.
3. Choose your `.secret` file.
4. Enter the Backup Password.
5. Tap **Import**.

Your saved secrets will be restored into the vault.

> 🔐 Backup passwords are separate from your Master Password. Keep them safe. Losing the backup password may make the backup permanently inaccessible.

---

## 🛡️ Security & Privacy

Security is at the heart of SecretVault.

### Encryption

- **AES-256-GCM:** Authenticated encryption for protecting stored secrets.
- **Encrypted Backups:** Exported `.secret` files are protected using a separate Backup Password.
- **PBKDF2:** Backup password derivation uses 600,000 hashing iterations, according to the application's implementation.

### Privacy

- Designed for offline operation.
- No cloud-based secret synchronization.
- No third-party tracking by design.
- Android automatic cloud backup is disabled to reduce the risk of unencrypted database exposure.

### Automatic Protection

- Automatic vault locking after 60 seconds.
- Encryption keys are intended to be cleared from memory when the vault locks.
- Master Password is not stored as plain text.

**Important:** Security depends on the actual implementation, Android device security, password strength, and cryptographic key management. These protections should be independently reviewed before relying on SecretVault for highly sensitive information.

---

## ❓ Frequently Asked Questions

**Q: What happens if I forget my Master Password?**

There is no password recovery mechanism. If you forget your Master Password, your encrypted vault data may become permanently inaccessible.

**Q: Can someone read my `.secret` backup file?**

The backup is encrypted and requires the correct Backup Password to restore. Without it, the contents should remain inaccessible.

**Q: Does SecretVault require an internet connection?**

No. SecretVault is designed to work offline.

**Q: Is my information uploaded to a server?**

SecretVault is designed for local storage without cloud synchronization or external data transmission.

**Q: Can I transfer my vault to another phone?**

Yes. Export an encrypted `.secret` backup, transfer it to your new phone, and import it using the correct Backup Password.

**Q: Can I change my Master Password?**

Yes. Use the Key icon inside the unlocked vault to change it.

---

## 🧰 Technology Stack

- Android
- Java / Kotlin (depending on project implementation)
- Android SDK
- Gradle
- AES-256-GCM
- PBKDF2 for backup password derivation

---

## 📂 Repository

**GitHub Repository:**  
https://github.com/raviranjan7159/App

**Project Directory:** `SecretVault`

---

## ⚠️ Disclaimer

SecretVault is provided for personal privacy and information management. Users are responsible for remembering their passwords and maintaining secure backups.

Always verify the application's security implementation before storing highly sensitive information.

---

## 👨‍💻 Developer

**Developed by:** Ravi Ranjan

**Project:** SecretVault

**Platform:** Android

---

<p align="center">
  🔐 <strong>SecretVault — Your Secrets Stay Yours.</strong>
  <br/>
  Made with ❤️ for Privacy and Security.
</p>
