---
title: Vault Armory 2.3.2 — Build 230
summary: Improved App Store support, stronger Web Vault protections, and safer attachment handling.
published: 2026-11-12
updated: 2026-11-12
featured: true
draft: false
---

Build 230 focuses on reliability, security, and making Vault Armory's support options easier to use.

## Improved App Store support

Support options now load directly from the App Store, including Apple's current product availability and localized prices.

The support screen also provides clearer loading information, better error messages, and an option to retry the App Store connection when products are temporarily unavailable.

## Stronger Web Vault protections

This update strengthens the Web Vault without changing how your encrypted records work.

- Web sessions use a shorter authorization period than mobile sessions.
- Inactive Web Vault sessions automatically lock.
- Updated Privacy Policy and Terms changes require clear acceptance before opening the vault.
- Additional browser security headers and request limits help protect account endpoints.

## Safer attachment handling

Attachment requests now receive stricter validation before upload or download.

Vault Armory verifies attachment ownership, supported file types, and file size limits while continuing to store vault content in encrypted form.

## Your encryption stays the same

Vault records continue to be encrypted and decrypted on your device or in your browser. The Vault Armory API stores the encrypted vault data and cannot read the contents of your records.

Thank you for using Vault Armory and supporting its continued development.
