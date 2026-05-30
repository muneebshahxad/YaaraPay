# Security Policy

## Supported Versions

Currently, only the latest release is supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability within YaaraPay, please report it directly to the developer.

We take security seriously and will investigate all reports. Please do not disclose vulnerabilities publicly until they have been addressed.

### Encryption
YaaraPay uses **AndroidX Security-Crypto** to store all sensitive credentials (like JWT Tokens) in `EncryptedSharedPreferences`. We recommend keeping your device updated to the latest Android version to benefit from the latest security patches.
