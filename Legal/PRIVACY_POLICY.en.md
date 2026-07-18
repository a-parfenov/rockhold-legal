# {{ site.data.legal.app_name }} Privacy Policy

Last updated: July 19, 2026

Document version: 1.0.0

Status: production cloud MVP candidate. The operator's full details and the account-deletion processing period must be published before external distribution.

Public legal and support section: https://a-parfenov.github.io/rockhold-legal/

Privacy and account deletion: privacy@rockhold.ru.

Support: support@rockhold.ru.

## 1. Overview

{{ site.data.legal.app_name }} is a local-first personal-finance app. Its primary database is stored on the device. A user may create a RockHold account, authenticate with an available provider, and synchronize supported data with the RockHold production server for recovery and multi-device use.

The app does not sell financial data or use it for advertising, profiling, or tracking. Core offline use remains available; server synchronization requires authentication and may be temporarily unavailable.

## 2. Operator And Contact Details

The app provider is the operator of data received by the RockHold server and official support channel.

Before external TestFlight or App Store distribution, the public page must provide the operator's full legal identity and required location details. Privacy and account-deletion requests may be sent to privacy@rockhold.ru; support requests may be sent to support@rockhold.ru. The owner must confirm before release that both channels are continuously monitored.

## 3. Data Processed

On the device, the app processes accounts, balances, transactions, transfers, categories, budgets, currencies, goals, funds, allocations, planned and recurring entries, supported credit-product information, settings, local reminders, backups, and restore journals.

When an account and cloud features are used, the server may receive:

- the account identifier, profile, selected country, language, and base currency;
- email or identity information supplied by Apple, Yandex, or another provider shown in the app;
- installation and device identifiers, session information, and app versions;
- financial entities supported by synchronization, their versions, tombstones, checkpoints, and safe technical diagnostics;
- user-entered text stored in synchronized entities, such as names and notes.

RockHold never receives biometric templates. Face ID and Touch ID are evaluated locally by iOS, and the app receives only the result.

## 4. Purposes

Data is used only to provide authentication and account recovery, synchronization and restore, conflict handling, device and session management, selected finance features, abuse prevention, integrity and incident investigation, and support requested by the user.

## 5. Storage And Exports

The local database is stored in the app container. Synchronized data is stored as structured records on the RockHold production server. The server does not store user `.rockholdbackup` files or Excel exports.

A manual backup uses AES-GCM with a shared app-held key. This protects integrity and deters casual viewing, but it is not strong user-password encryption. Excel exports are readable. After export, the user controls and is responsible for the destination file.

## 6. External Services

Apple processes App Store, TestFlight, Apple ID, and Sign in with Apple data under its terms. Yandex and other displayed sign-in providers process OAuth/OIDC data under their terms. iOS or iCloud may include app data in system backups. GitHub hosts the public legal pages. A user-selected app or file provider receives only a file the user explicitly shares.

The app contains no ad network, third-party product analytics, crash-reporting SDK, bank connection, or payment SDK.

## 7. Account And Data Deletion

Until in-app deletion is released, a user may request complete account deletion by emailing privacy@rockhold.ru. The request should preferably be sent from the email address linked to the RockHold account. The operator may request safe proof of ownership, but will not ask for a password, access token, refresh token, or sign-in code.

After verification, the RockHold account and data that link it to the user are deleted, including profile identifiers, email, sign-in-provider links, and account, device, and session bindings. Active sessions and devices are revoked; the deleted account can no longer be used for login, synchronization, or restore. The related authorization must also be revoked for Sign in with Apple. This is permanent account deletion, not temporary deactivation.

Individual financial records may remain only in irreversibly anonymized form, with no account, user, device, or sign-in-provider identifiers and no technical means to reconnect them to the deleted account. Anonymous records cannot be returned to the user or restored after a new registration. Data that can still be linked back to the user is not anonymous and must be deleted unless retention is legally required.

Local data and exported files are separate copies, and the user must delete previously exported files separately. The current absence of an in-app control does not remove the email deletion process, but a straightforward in-app initiation path is still required before App Store submission.

## 8. Retention

Active-account data is retained while the account is used. After a completed deletion request, personal account data is deleted and any remaining irreversibly anonymized records are no longer associated with the user. Security records or data legally required to be retained are kept only for a published purpose and period. The request-processing period and retention for those exceptions must be approved before external distribution.

## 9. Security

Production transport uses HTTPS. Server access is scoped by authenticated user, profile, dataset, and device boundaries. Ordinary logs must not contain tokens, passwords, authorization codes, full financial payloads, or full entity identifiers.

No system can guarantee absolute security. Users remain responsible for their device, Apple ID, linked sign-in providers, and exported files.

## 10. User Rights

Users may view and change app data, sign out, revoke other sessions, and export a local copy. Complete account deletion and requests for access, correction, or restriction may be requested at privacy@rockhold.ru. After in-app deletion ships, this email will remain available for questions and disputed cases.

## 11. Children

The app is not directed specifically to children. A user who lacks legal capacity should use it with a legal representative where applicable law requires this.

## 12. Changes

This Policy is updated before a release that changes server data, providers, retention, or scope. A material bundled-document change increments its technical version and requires renewed acknowledgement in the app. Public and bundled versions must remain materially consistent.

For users in the Russian Federation, the Russian version controls if translations conflict.
