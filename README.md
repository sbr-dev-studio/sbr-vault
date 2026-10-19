# 🔒 SbrVault

<p align="center">
  <a href="https://github.com/sbr-dev-studio/sbr-vault/releases">
    <img src="https://img.shields.io/github/v/release/sbr-dev-studio/sbr-vault?color=blue&style=for-the-badge" alt="Release">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2B-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/.NET-10.0-purple?style=for-the-badge" alt=".NET 10">
  <img src="https://img.shields.io/badge/Security-AES--256--GCM-green?style=for-the-badge" alt="Security">
  <img src="https://img.shields.io/badge/Privacy-Zero_Cloud-orange?style=for-the-badge" alt="Zero Cloud">
</p>

---

**SbrVault** is an advanced, high-security, and lightweight personal password manager and encrypted vault for Windows. Built natively with **C# .NET 10** and **WPF**, it delivers uncompromising privacy, strict local-first data isolation, and professional-grade security tools like a built-in file shredder and travel mode.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 🛡 **Authenticated Encryption** | All stored records are protected using **AES-256-GCM**[cite: 3]. |
| 🔑 **Argon2id Key Derivation** | Industry-standard hashing algorithm to resist hardware brute-force attacks. |
| 💻 **Local-First Privacy** | Zero cloud dependency by default. Your vault files stay strictly on your local device[cite: 3]. |
| 📁 **Inside-Cell Records** | Structured storage for documents, finances, work projects, and encrypted file attachments[cite: 3]. |
| ⭐ **Favorites & Color Labels** | Instant visual categorization, color-based search, and quick access to pinned items[cite: 3]. |
| 🔍 **Global Vault Search** | Fast searching across the entire vault (`Ctrl+K`) with strict protection for sensitive secrets[cite: 3]. |
| 🗑️ **Secure File Shredder** | Guaranteed 3-pass file and folder deletion with MFT sanitization to prevent forensic recovery[cite: 3]. |
| ✈️ **Travel Mode** | Temporarily hide sensitive cells for a defined period (24h to 7 days) at the data layer[cite: 3]. |
| ⚡ **Modern WPF Interface** | Reactive desktop experience featuring manual drag-and-drop ordering and smooth animations[cite: 3]. |

---

## 🚀 Quick Start Guide

1. Head over to the **[Official Releases](../../releases)** section.
2. Download the latest compiled package (`SbrVault-v0.1.1.zip`).
3. Extract the archive into any folder on your computer.
4. Launch `SbrVault.exe`.

---

## 🛡️ Security Architecture

- **Encryption Standard:** AES-256-GCM (Galois/Counter Mode)[cite: 3].
- **Key Derivation Function (KDF):** Argon2id.
- **Secure Destruction:** 3-pass file shredding (Random data, inverted data, zero-fill) combined with Master File Table (MFT) renaming.
- **Data Preservation:** Full backward compatibility with existing local vaults without requiring forced migrations.

---

## 💻 System Requirements

- **OS:** Windows 10 / Windows 11 (64-bit)
- **Framework:** .NET Desktop Runtime 10.0 *(or self-contained deployment)*

---

<p align="center">
  Developed with ❤️ by <b>SBR DEV</b>
</p>
