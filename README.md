# 🔧 Arch Linux System Update Script

## 🚀 Ultimate Arch-Based System Maintenance Utility

A stylized and powerful Bash function to fully update and clean your Arch Linux or Arch-based distribution (like **Manjaro**, **EndeavourOS**, **Garuda**, etc.) — including **pacman**, **AUR**, **Flatpak**, and **Snap** support — all in one command.

---

## 📋 Features

- 🔄 Sync and upgrade official packages using `pacman`
- 🧩 Update AUR packages via `yay`
- 🧹 Identify and remove orphaned packages
- 🧼 Clean package cache to free up space
- 📦 Update Snap and Flatpak packages (if installed)
- ✅ Styled output with clear steps and status
- 🧠 Sudo elevation at the start, so you're not prompted repeatedly

---

## 📦 Supported Package Managers

| Package Manager | Description              | Required? |
|-----------------|--------------------------|-----------|
| `pacman`        | Core Arch package manager| ✅ Yes     |
| `yay`           | AUR helper               | ✅ Yes     |
| `snap`          | Canonical's Snap system  | ⚠️ Optional |
| `flatpak`       | Flatpak apps             | ⚠️ Optional |

---

## 💻 Example Output

```bash
🔥  SYSTEM UPGRADE INITIATED
🕒 Started at: Tue Jul  9 17:00:00 IST 2025

[1/7] 🔄 Updating system packages (pacman)...
[2/7] 🧩 Updating AUR packages (yay)...
[3/7] 🧹 Checking for Orphaned Packages...
[4/7] 🧼 Cleaning Package Cache...
[5/7] 📦 Refreshing Snap Packages...
[6/7] 📦 Updating Flatpak Packages...
[7/7] ✅ Final Status Check...

✅  SYSTEM STATUS: ABSOLUTE PERFECTION ACHIEVED
💡 All Done Lord Vader. The Death Star is clean and updated.
```

---

## 🛠️ Installation

1. Open your terminal.
2. Edit your shell configuration file:

```bash
nano ~/.zshrc   # for Zsh users
# or
nano ~/.bashrc  # for Bash users
```

3. Paste the `update()` function from [this script](#) into the file.
4. Save and reload your shell:

```bash
source ~/.zshrc   # or ~/.bashrc
```

5. Now run:

```bash
update
```

---

## ⚠️ Requirements

- Arch-based distro (e.g., Arch, Manjaro, EndeavourOS)
- `yay` installed (`sudo pacman -S yay`)
- Optional: `flatpak` and `snapd` if you want those package types supported

---

## 📂 File Info

- **Filename:** `arch-update-function.zsh` (or `.sh`)
- **Function name:** `update`
- **Tested on:** Arch Linux, Manjaro, EndeavourOS

---

## 📜 License

MIT License — free to use, modify, or share.# 🔧 Arch Linux System Update Script

## 🚀 Ultimate Arch-Based System Maintenance Utility

A stylized and powerful Bash function to fully update and clean your Arch Linux or Arch-based distribution (like **Manjaro**, **EndeavourOS**, **Garuda**, etc.) — including **pacman**, **AUR**, **Flatpak**, and **Snap** support — all in one command.

---

## 📋 Features

- 🔄 Sync and upgrade official packages using `pacman`
- 🧩 Update AUR packages via `yay`
- 🧹 Identify and remove orphaned packages
- 🧼 Clean package cache to free up space
- 📦 Update Snap and Flatpak packages (if installed)
- ✅ Styled output with clear steps and status
- 🧠 Sudo elevation at the start, so you're not prompted repeatedly

---

## 📦 Supported Package Managers

| Package Manager | Description              | Required? |
|-----------------|--------------------------|-----------|
| `pacman`        | Core Arch package manager| ✅ Yes     |
| `yay`           | AUR helper               | ✅ Yes     |
| `snap`          | Canonical's Snap system  | ⚠️ Optional |
| `flatpak`       | Flatpak apps             | ⚠️ Optional |

---

## 💻 Example Output

```bash
🔥  SYSTEM UPGRADE INITIATED
🕒 Started at: Tue Jul  9 17:00:00 IST 2025

[1/7] 🔄 Updating system packages (pacman)...
[2/7] 🧩 Updating AUR packages (yay)...
[3/7] 🧹 Checking for Orphaned Packages...
[4/7] 🧼 Cleaning Package Cache...
[5/7] 📦 Refreshing Snap Packages...
[6/7] 📦 Updating Flatpak Packages...
[7/7] ✅ Final Status Check...

✅  SYSTEM STATUS: ABSOLUTE PERFECTION ACHIEVED
💡 All Done Lord Vader. The Death Star is clean and updated.
```

---

## 🛠️ Installation

1. Open your terminal.
2. Edit your shell configuration file:

```bash
nano ~/.zshrc   # for Zsh users
# or
nano ~/.bashrc  # for Bash users
```

3. Paste the `update()` function from [this script](#) into the file.
4. Save and reload your shell:

```bash
source ~/.zshrc   # or ~/.bashrc
```

5. Now run:

```bash
update
```

---

## ⚠️ Requirements

- Arch-based distro (e.g., Arch, Manjaro, EndeavourOS)
- `yay` installed (`sudo pacman -S yay`)
- Optional: `flatpak` and `snapd` if you want those package types supported

---

## 📂 File Info

- **Filename:** `arch-update-function.zsh` (or `.sh`)
- **Function name:** `update`
- **Tested on:** Arch Linux, Manjaro, EndeavourOS

---

## 📜 License

MIT License — free to use, modify, or share.
