# {{ site.data.legal.app_name }} Privacy and Personal Data Processing Policy

Revision date: July 19, 2026

Document version: 1.0.0

Public version: https://a-parfenov.github.io/rockhold-legal/

Personal data and account-deletion enquiries: privacy@rockhold.ru.

App support: support@rockhold.ru.

## 1. General Provisions

This Policy sets out how {{ site.data.legal.app_name }} (the “App”) processes and protects users’ personal data and the financial data entered by users in the App.

The personal-data operator and RockHold service provider is Anton Sergeevich Parfenov (Парфенов Антон Сергеевич), acting as an individual (the “Operator”).

This Policy applies to data processed when the App is used, a RockHold account is created or used, a user contacts support, or server synchronization is used. It does not govern processing by third parties, including Apple, sign-in providers, iCloud, and file services selected by the user; their own notices and terms apply to such processing.

## 2. Definitions

**User** means an individual who uses the App.

**Account** means a RockHold account used for authentication and server synchronization.

**Financial Data** means information entered by the User for personal-finance records, including accounts, transactions, categories, budgets, currencies, and other supported entities.

**Server Synchronization** means the transfer and reconciliation of supported data between the User’s device and the RockHold server after authentication.

## 3. Data Processed

On the device, the App may process Financial Data, including accounts, balances, transactions, transfers, categories, budgets, currency preferences, goals, funds, planned and recurring entries, credit-product information, settings, local notifications, backups, and information required to restore the local database.

When an Account and Server Synchronization are used, the Operator may process:

- the Account identifier, profile preferences, country, language, and base currency;
- the email address and information supplied by the sign-in provider selected by the User;
- information about the App installation, device, session, and App version;
- Financial Data supported by Server Synchronization, their technical versions, deletion markers, checkpoints, and diagnostic information that does not contain the contents of financial records;
- text entered by the User in synchronized entities, including names and notes.

The App does not receive or store biometric templates. Face ID and Touch ID are evaluated by iOS, and the App receives only the verification result.

In the current version, Server Synchronization does not upload goals, funds, allocations, allocation adjustments, the local-notification journal, local backup and export files, App-lock state, or authentication secrets.

## 4. Purposes and Legal Grounds

The Operator processes data solely to provide the App’s functions: registration and sign-in, Account and session management, Server Synchronization and data restoration, conflict resolution, selected financial features, information security, abuse prevention, technical incident diagnosis, and responding to the User’s request.

Processing is carried out in connection with the User’s actions in using the App and performance of these terms of use, with consent where required by applicable law, and to comply with the Operator’s legal duties and protect the service while respecting the User’s rights and legitimate interests.

The Operator does not sell Financial Data or use it for advertising, behavioural profiling, or cross-context tracking.

## 5. Storage, Transfers, and External Services

The primary working database is stored in the App container on the User’s device. Data supported by Server Synchronization is stored in structured form on the RockHold server. The server does not receive `.rockholdbackup` files or Excel files created manually by the User.

A `.rockholdbackup` backup is protected using AES-GCM with a key embedded in the App. This provides integrity protection and helps prevent casual viewing, but is not strong user-password encryption. In particular, it is not encryption using a password known only to the User. Excel exports are readable. After an export, the User determines the file’s storage location, recipient, and access controls.

When the App is used, certain data may be processed by the following parties under their own terms and notices:

- Apple, in connection with App Store, TestFlight, Apple ID, and Sign in with Apple;
- Yandex and other sign-in providers explicitly displayed in the App, in connection with OAuth/OIDC authentication;
- iOS and iCloud, if the User enables system backup of App data;
- GitHub, as the host of the public legal pages;
- an app or file service selected by the User, only when the User explicitly sends it a file.

The App contains no advertising networks, third-party product analytics, crash-reporting SDKs, bank-connection integrations, or payment SDKs.

## 6. Account and Financial Data Deletion

The App provides two separate actions with different consequences.

### 6.1. Account Deletion

The User may initiate complete Account deletion in the settings of an authenticated Account. Before this action is performed, the App requires fresh identity verification using the selected sign-in method. For an Account linked to Sign in with Apple, fresh Apple authorization is required and the associated authorization is revoked as applicable.

After confirmation, the Account and the information that links it to the User are deleted: the email address, profile identifiers, sign-in-provider links, and device and session bindings. Active sessions are terminated. A deleted Account cannot be used to sign in, synchronize, or restore data. Account deletion is not a temporary deactivation.

Raw Financial Data linked to the Account is deleted. Before deletion, statistical aggregates may be created only if they are irreversibly anonymized: they contain no Account, profile, device, dataset, entity, or sign-in-provider identifiers, user-entered names or notes, exact activity sequence, or other means of re-identifying the User. Such aggregates cannot be returned to the User or used to restore data after a new registration.

Removing an email address while retaining raw Financial Data and persistent technical links is not anonymization.

### 6.2. Financial Data Deletion

The “Delete financial data” action does not delete the Account. It clears working Financial Data on the device and, where an Account is active, creates a new empty server data generation. The prior server generation and the raw records synchronized with it are deleted as part of that operation and cannot be used for sign-in, synchronization, or restoration.

Before clearing data, the App creates a local safety backup where the restore mechanism requires it. That copy remains on the device until it is removed by the User or the App. Local data and previously exported files are separate copies: files sent to other apps or file services must be deleted separately by the User.

The User may contact privacy@rockhold.ru about deletion or a disputed case. The Operator will never request a password, access token, refresh token, or sign-in code by email.

## 7. Retention

Active-Account data is processed while the Account is in use. A deletion initiated in the App is applied to the live database after successful fresh identity verification. A substantiated deletion request sent to privacy@rockhold.ru is reviewed and completed without undue delay and no later than 30 calendar days, unless applicable law requires a different period.

To confirm a deletion operation safely after loss of network access or the authentication session, the server may temporarily keep a technical receipt: a random request identifier and one-way technical fingerprint without an email address, Account identifier, sign-in-provider data, or financial content. The receipt is deleted after confirmation of local cleanup or automatically within 30 days if that confirmation is absent. Expired OAuth state is removed automatically.

Isolated database backups may contain state that existed before deletion and are replaced within 30 days. They are not used for ordinary sign-in, synchronization, or user restoration. In disaster recovery, the service is not returned to operation until the confirmed-deletion sequence and the corresponding operation-log checkpoint have been checked.

Security logs contain only a technical event type, time, and a safe request identifier. They must not include tokens, passwords, authorization codes, complete Financial Data, or complete entity identifiers. Such logs are retained for no more than 90 days and deleted automatically. Longer retention is permitted only to the extent and for the period expressly required by applicable law.

## 8. Data Security

Data is transmitted to the server over HTTPS. Access to server data is separated by authenticated User, profile, dataset, and device. The Operator takes reasonable organizational and technical measures to protect data against unlawful or accidental access, alteration, blocking, copying, disclosure, dissemination, or destruction.

No information system can guarantee absolute security. The User remains responsible for securing their device, Apple ID, connected sign-in methods, and exported files.

## 9. User Rights and Enquiries

The User may view and update data in the App, sign out, revoke other sessions, export a local copy, delete Financial Data, or initiate Account deletion. Requests for access, correction, restriction of processing, or deletion of personal data may be sent to privacy@rockhold.ru. Questions about the App may be sent to support@rockhold.ru.

The App is not directed specifically to children. A User who lacks full legal capacity must use the App with a legal representative where required by law.

## 10. Final Provisions

This Policy is updated before a release that changes the categories of server data, providers, retention periods, or other material processing terms. A material change to the bundled version requires renewed acknowledgement in the App. The public and bundled versions of this Policy must remain materially consistent.

For Users in the Russian Federation, the Russian version of this Policy governs. If the Russian and English versions conflict, the Russian version prevails.
