<div align=center>

# WizzDiscord

[![BetterDiscord](https://img.shields.io/badge/BetterDiscord-Plugin-7289da?style=for-the-badge&logo=discord&logoColor=white)](https://betterdiscord.app/)
[![Platform](https://img.shields.io/badge/Platform-Win%20%7C%20Linux%20%7C%20Mac-lightgrey?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**Bring the chaotic nostalgia of MSN Messenger straight into Discord!**

WizzDiscord is a BetterDiscord plugin that replicates the iconic "Nudge" (Wizz) feature. When an authorized user mentions you, your Discord client shakes violently, and the legendary specific sound is played.

</div>


## Features

*   **Visual Impact:** Creates a violent (but brief) screen shake effect using pure CSS injection.
*   **Iconic Audio:** The original sound is embedded within the plugin (Base64). No external MP3 files required.
*   **Access Control:** By default, **nobody** can wizz you. You must manually authorize friends via a specific Whitelist.
*   **Chaos Mode:** A setting to allow **everyone** to wizz you (use at your own risk).
*   **Anti-Spam:** Built-in 5-second cooldown to prevent audio spamming.
*   **Easy Management:** Right-click context menu integration to Add/Remove users easily.


## Installation

### Prerequisites
You need **[BetterDiscord](https://betterdiscord.app/)** installed on your Discord client.

### Steps

1.  Download `WizzDiscord.plugin.js` from the [Releases](https://github.com/1posix/discord-wizz) page.
2.  Move the file into your BetterDiscord **Plugins** folder.

**How to find the folder?**
In Discord, go to `User Settings` > `BetterDiscord` > `Plugins` and click **"Open Plugin Folder"**.

**Manual Paths:**
*   **Windows:** `%APPDATA%\BetterDiscord\plugins`
*   **Linux:** `~/.config/BetterDiscord/plugins`
*   **macOS:** `~/Library/Application Support/BetterDiscord/plugins`

Once dropped, enable it using the toggle switch in BetterDiscord.


## How to Use

### 1. Whitelisting a Friend (The Safe Way)
By default, the plugin is in **Whitelist Mode**. To let a friend Wizz you:

1.  **Right-click** on their user name or avatar (in chat, member list, or DM).
2.  Click **"✅ Wizz: Authorize"**.
3.  A green toast notification will confirm they are now allowed.

From now on, if they tag you (`@YourName`), your screen will shake! To revoke access, right-click again and select **"🚫 Wizz: Block"**.

### 2. Settings Panel
Go to `Plugins` tabs and click the **Settings (⚙️)** icon next to WizzDiscord.

*   **Allow Everyone:** If checked, the whitelist is ignored. Anyone mentioning you will trigger the Wizz.
*   **Allowed Users:** Visual list of IDs currently authorized. You can manually remove them here.

---

**License: MIT**
