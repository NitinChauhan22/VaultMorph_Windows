# Changelog

All notable changes to VaultMorph will be documented in this file.

This project follows semantic versioning.

---

## [1.0.0] - 2026-03-29

### 🚀 Initial Public Release

VaultMorph v1.0.0 is the first official public release of the Windows offline password manager.

---

### ✨ Features

- Secure password storage with AES-256-GCM encryption
- Argon2id-based master password key derivation
- 100% offline vault (no cloud sync)
- Secure notes storage
- Built-in TOTP 2FA authenticator (Google/Microsoft compatible)
- Encrypted backup and restore (.vmb format)
- CSV import and export support
- Password health analysis (weak/reused passwords)
- Auto-lock on inactivity or window focus loss

---

### 🔒 Security

- Industry-standard AES-256-GCM encryption
- Argon2id (memory-hard) key derivation
- Per-field encryption with unique nonce
- Encrypted storage using SQLite
- Master key protected via Windows secure storage
- Memory cleanup on vault lock
- No telemetry or data collection

---

### ⚠️ Design Decisions

- Fully offline architecture (no cloud or sync support)
- Master password is never stored and cannot be recovered
- Security prioritized over convenience features

---

### 🚧 Known Limitations

- Windows platform only (no macOS/Linux support)
- No cloud synchronization (offline-only by design)
- No browser extension support
- Community edition limited to 100 password entries

---

### ⚠️ Important Notes

- Loss of master password results in permanent data loss
- Users are responsible for maintaining secure backups
- This software is provided "as is" without warranty

---

## [Unreleased]

### Planned

- Performance improvements
- UI enhancements
- Additional security hardening