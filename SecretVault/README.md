# 🔐 SecretVault — User Guide & Overview

Welcome to **SecretVault**, your private, ultra-secure digital vault for storing passwords, sensitive notes, and confidential information directly on your Android device.

SecretVault is built with **Zero-Knowledge Architecture**, meaning your data is encrypted on your phone using military-grade encryption. **Only you hold the key to unlock your secrets** — no cloud servers, no trackers, and no unauthorized access.

---

## 🚀 Getting Started

### 1. Creating Your Vault
1. Launch **SecretVault** for the first time.
2. Enter a strong **Master Password** (at least 6 characters long) and confirm it.
3. Tap **Create Vault**. Your vault is now encrypted and ready to use!

> ⚠️ **Important Security Note**: Your Master Password is never stored anywhere on your phone or on any server. If you lose your Master Password, your data cannot be recovered. Please memorize it or keep a safe offline copy!

### 2. Unlocking Your Vault
1. Open the app and enter your **Master Password**.
2. Tap **Unlock** to access your secrets.
3. The app automatically locks itself when you leave or when inactive for 60 seconds to protect your privacy.

---

## 🌟 How to Use SecretVault Features

### 📝 Adding & Viewing Secrets
* **Add a Secret**: Tap the **`+` (Plus)** button at the bottom right, enter a title and secret content, then tap **Save**.
* **View a Secret**: Tap any item in your list to reveal its full contents. Tap the **Back Arrow** when finished.
* **Edit a Secret**: Open an item and tap the **Edit (Pencil)** icon in the top right corner to modify your title or content.

---

### 🔑 Changing Your Master Password
You can update your master password at any time without losing any of your saved secrets:
1. Open your unlocked vault.
2. Tap the **Key (🔑)** icon in the top navigation bar.
3. Enter your **Current Master Password**, then enter and confirm your **New Master Password**.
4. Tap **Change Password**.

---

### 🔍 Searching Secrets by Title
1. Tap the **Search (🔍)** icon in the top navigation bar.
2. Type any title or keyword. Your secrets list will filter in real-time as you type.
3. Tap the **`X`** button to clear the search and return to your full list.

---

### ☑️ Selecting & Deleting Multiple Items (Multi-Select)
1. **Long-press** any item card to enter selection mode.
2. Tap other items to select or deselect them. A checkbox will appear on selected cards, and the top bar will show how many items are selected (e.g., `"3 selected"`).
3. Tap the **Trash (🗑️)** icon in the top bar to delete all selected items at once.
4. Tap the **`X`** icon in the top bar to exit selection mode at any time.

---

### 📦 Exporting & Importing Encrypted Backups (`.secret`)

SecretVault lets you safely back up your data to an encrypted file (`.secret`) and restore it on another phone or after a device reset.

#### How to Export a Backup
1. Tap the **Three Dots (`⋮`)** menu in the top right corner of the vault screen.
2. Select **Export Vault**.
3. Set a **Backup Password** to lock your backup file.
4. Tap **Export**. A system file window will open with a suggested name (e.g. `SecretVault_20261109_1940`).
5. Choose where you want to save the file (Google Drive, SD Card, Downloads folder) and tap **Save**.

#### How to Import / Restore a Backup
1. Tap the **Three Dots (`⋮`)** menu and select **Import Vault**.
2. Select your `.secret` backup file from your storage or cloud drive.
3. Enter the **Backup Password** you used when creating that backup.
4. Tap **Import**. All secrets from the backup file will be restored into your vault!

---

## 🛡️ Security & Privacy Guarantees

* **AES-256 GCM Encryption**: Every secret is protected using authenticated AES-256 bit encryption, the industry gold standard for military and financial security.
* **Auto-Lock Security**: If you switch to another app or leave your phone unattended, SecretVault locks itself automatically after 60 seconds and wipes encryption keys from RAM.
* **No Unencrypted Cloud Leaks**: SecretVault disables OS automatic cloud backups to prevent unencrypted database copies from uploading to Google Cloud.

---

## ❓ Frequently Asked Questions (FAQ)

#### Q: What happens if I forget my Master Password?
Because SecretVault uses zero-knowledge encryption, there is no "Forgot Password" or recovery link. If you forget your Master Password, no one can decrypt your data.

#### Q: Can someone read my exported `.secret` backup file?
No. Your exported `.secret` files are completely encrypted using your **Backup Password** with 600,000 rounds of cryptographic hashing. Without that backup password, no text or data can be read from the file.

#### Q: Is my data sent to the internet?
No. SecretVault operates **100% offline** on your device. It does not send any data to external servers or third parties.
