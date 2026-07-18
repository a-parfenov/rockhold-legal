# {{ site.data.legal.app_name }} Terms of Use

Last updated: July 19, 2026

Document version: 1.0.0

Status: production cloud MVP candidate. Provider details and the account-deletion lifecycle must be completed before external distribution.

Public legal and support section: https://a-parfenov.github.io/rockhold-legal/

Support: support@rockhold.ru.

Privacy and account deletion: privacy@rockhold.ru.

## 1. Acceptance

By using the app, the user acknowledges these Terms and the Privacy Policy. The accepted document versions are stored locally; a material update requires renewed acknowledgement.

## 2. Purpose

{{ site.data.legal.app_name }} supports personal-finance records, including accounts, transactions, transfers, categories, budgets, currencies, goals and funds, planned entries, local reminders, backups, restore, and Excel export.

The app is not a bank, broker, payment service, or accounting, tax, investment, or legal adviser. It does not execute banking transactions or guarantee financial outcomes.

## 3. Local-First And Cloud Features

The primary working database is stored on the device. The production cloud MVP includes a RockHold account, sign-in through displayed providers, and synchronization of supported data with the RockHold server.

Loss of connectivity should not block core local use. Synchronization may be delayed, retried, or require an explicit user choice when local and server state conflict. “Synced” applies only to data and entity families supported by the current server contract.

Manual backup, server sync, and Excel export are separate mechanisms and do not replace one another.

## 4. Account And Authentication

Users are responsible for protecting their device, Apple ID, Yandex account, and any other linked sign-in method. Tokens, verification codes, and active sessions must not be shared.

RockHold may restrict or revoke a session when compromise, abuse, limit violations, or data-protection needs are detected.

## 5. Account Deletion

Until in-app deletion is released, complete account deletion may be requested at privacy@rockhold.ru. The operator may safely verify account ownership without requesting a password, token, or sign-in code.

After completion, the account, email, profile identifiers, sign-in-provider links, and session and device bindings are deleted. Access ends permanently: the deleted account cannot be used for login, synchronization, or restore. This is not temporary deactivation.

Individual financial records may remain only in irreversibly anonymized form that cannot be linked to the user or used to restore access. Non-anonymized data is deleted unless retention is legally required. Before App Store submission, the same request must also be initiable directly within the app.

Deleting a finance account, signing out, resetting a financial dataset, and deleting the user account are separate actions. The app must explain each consequence before confirmation.

## 6. Data Accuracy

Users are responsible for entered amounts, currencies, dates, categories, and credit-product parameters. When a required exchange rate is unavailable, the app should report that condition instead of silently using a 1:1 conversion.

## 7. Backup And Export

Restore may replace all local data. Users should verify the source and preview before applying it. The app creates a safety backup where required by the restore contract.

A `.rockholdbackup` file uses AES-GCM with a shared app-held key, not encryption with a user-only password. Excel exports are readable. Exported files may contain financial data and become controlled by the user and selected destination service.

## 8. Notifications And Biometrics

Local notifications may appear on the lock screen depending on iOS settings. Face ID and Touch ID are local system checks and do not provide biometric templates to the app.

## 9. Service Availability

The developer aims to keep data and services available but cannot guarantee uninterrupted operation of the server, network, sign-in providers, iCloud, or third-party file services. A cloud failure must not silently delete or replace local data.

## 10. Acceptable Use

Users must not bypass authentication or limits, attack the service, access another person's data, automate abuse, or use the app unlawfully.

## 11. Support And Law

Support requests may be sent to support@rockhold.ru; complete account-deletion and privacy requests may be sent to privacy@rockhold.ru. Before external release, the owner must confirm that both channels are monitored and publish the provider's full details, the deletion-processing period, and a method for formal requests.

Mandatory consumer and statutory rights remain unaffected. Unless a complete custom license is published in App Store Connect, Apple's Standard EULA applies together with these supplemental Terms where permitted.

## 12. Changes

Material changes are published before the corresponding release and require renewed acknowledgement in the app. For users in the Russian Federation, the Russian version controls if translations conflict.
