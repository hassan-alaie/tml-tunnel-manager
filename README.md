# TML Tunnel Manager

A macOS SSH SOCKS4 tunnel manager with menu bar integration, auto-update support and license management.

> Licensed software — support is provided to licensed users only.  
> Contact: **tml.softdev@gmail.com**

---

## Requirements

- macOS 13.0 or later
- Apple Silicon or Intel Mac

---

## Installation

1. Download the latest release from the [Releases](https://github.com/hassan-alaie/tml-tunnel-manager/releases/latest) page:
   - `TML.Tunnel.Manager.X.X.zip` — the app
   - `install.sh` — installer script
   - `uninstall.sh` — uninstaller script

2. Extract the ZIP file

3. Open Terminal and navigate to the folder containing the extracted app and install.sh:
   ```bash
   cd ~/Downloads
   ```

4. Run the installer:
   ```bash
   bash install.sh
   ```

5. The app will be installed to `/Applications`

6. **If you see a "damaged" or "not opened" warning:**
   - Open **System Settings → Privacy & Security**
   - Scroll down to the **Security** section
   - You will see a message about TML Tunnel Manager being blocked
   - Click **Open Anyway**
   - Enter your password if prompted
   - The app will now open normally ✅

---

## First Launch

1. Open **TML Tunnel Manager** from Applications or Spotlight
2. Allow **Notifications** when prompted (required for connection alerts)
3. Go to **Registration…** in the menu bar icon
4. Copy your **Hardware Fingerprint**
5. Contact **tml.softdev@gmail.com** for pricing and registration
6. Include your **name** and **fingerprint** in your email
7. Enter your name and license key in the Registration window

---

## Features

- **SSH SOCKS4 tunnels** — connect to multiple SSH servers simultaneously
- **Menu bar icon** — colored status indicator (grey/yellow/green/red)
- **Auto-solve arithmetic prompts** — handles challenge-response authentication automatically
- **Keychain integration** — saves passwords securely, prompts only when password changes
- **Notifications** — alerts on connect, disconnect and errors
- **Auto-update** — checks for updates at launch and daily via Sparkle
- **Launch at Login** — option in menu bar icon
- **Hide at Launch** — starts minimized
- **Show in Dock** — toggle dock icon visibility

---

## Menu Bar Options

| Option | Description |
|--------|-------------|
| Tunnel rows | Click to connect/disconnect individual tunnels |
| Disconnect All | Disconnects all active tunnels and clears errors |
| Launch at Login | Start app automatically at login |
| Hide at Launch | Start app hidden (no window shown) |
| Settings… | Configure tunnels and preferences |
| Show in Dock | Toggle dock icon |
| Show Main Window | Bring main window to front |
| Check for Updates… | Manually check for new version |
| About TML Tunnel Manager | App info and license status |
| Registration… | Register your license |
| Quit | Quit the app |

---

## Notifications

Remember to allow notifications from System Settings → Notifications → TML Tunnel Manager. Set to **Alerts** for persistent notifications.

---

## Uninstallation

1. Open Terminal
2. Navigate to the folder containing `uninstall.sh`
3. Run:
   ```bash
   bash uninstall.sh
   ```
4. This removes the app, configuration, saved passwords and all leftovers

---

## Configuration File

The tunnel configuration is stored at:
```
~/Library/Preferences/net.tml.tunnelmanager.v2.plist
```

To delete it:
```bash
rm -f ~/Library/Preferences/net.tml.tunnelmanager.v2.plist
```

---

## Updates

TML Tunnel Manager checks for updates automatically at launch and daily.  
When an update is available, a dialog will appear with release notes and the option to install.

**Minor updates** (e.g. 6.5 → 6.6): Same license key works.  
**Major updates** (e.g. 6.x → 7.0): New license key required — contact **tml.softdev@gmail.com**.

---

## Support

For licensing, pricing or support contact:  
📧 **tml.softdev@gmail.com**

Please include your **name** and **hardware fingerprint** (available in Registration window) when requesting a license.

---

*© TML - The Missing Link*
