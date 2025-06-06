# 📘 ProtonVPN GNOME App Setup on Debian

This document explains how to install and use the **ProtonVPN GNOME desktop app** on a Debian system with a graphical interface.

---

## ⮞ Steps Followed on Debian GNOME

### 🔹 Step 1: Download the ProtonVPN Repository Package

In the terminal, run:

```bash
wget https://repo.protonvpn.com/debian/dists/stable/main/binary-all/protonvpn-stable-release_1.0.8_all.deb
```

### 🔹 Step 2: Add the Repository and Update APT
Install the package and update the APT :
```bash
sudo dpkg -i protonvpn-stable-release_1.0.8_all.deb
sudo apt update
```

### 🔹 Step 3: Install ProtonVPN GNOME Desktop App
This will install the GUI version of ProtonVPN, which integrates well with the GNOME desktop.
```bash
sudo apt install proton-vpn-gnome-desktop
```

### 🔹 Step 4: Launch ProtonVPN
- Open the app from your Applications Menu.

- Provide the necessary information and create account.

- Log in with your ProtonVPN username and password.

- Complete authentication.

### 🔹 Step 5: Connect to VPN
- Choose a country or server from the list.

- Click Connect.

- Now you can connect to VPN.

### 🔹 Step 6: Verify VPN is Working
- Open your browser.

- Visit https://whatismyipaddress.com to check before and after VPN connection.

### 🔹 Step 7: Disconnect When Finished
- From the ProtonVPN app:

- Click Disconnect

- You are now back to your original network connection

---

## 🖼️ Screenshot of Before VPN connection
![ip_before](https://github.com/user-attachments/assets/e2474890-1ef6-4320-ac65-d8e8fcb37f33)

---

## 🖼️ Screenshot of After VPN connection
![ip_after](https://github.com/user-attachments/assets/b853e2d5-2da0-4eaa-a4fd-9a3085721dcc)

---

### 🌐 Browsing speed
`Before VPN`: 110 Mbps

`After VPN`:56 Mbps

---
## 🔍 Summary
| Benefits                       | Limitations                    |
|-------------------------------|--------------------------------|
| Hides your real IP address     | May slow down internet speed   |
| Encrypts internet traffic      | Free VPNs may have data limits |
| Protects privacy on public Wi-Fi | Some VPNs log user data       |
| Bypasses geo-restrictions      | Can be blocked by some sites   |
| Enhances online security       | Requires trust in VPN provider |

