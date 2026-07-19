# {{ site.data.legal.app_name }} Terms of Use

Revision date: July 19, 2026

Document version: 1.0.0

Public version: https://a-parfenov.github.io/rockhold-legal/

RockHold provider: Anton Sergeevich Parfenov (Парфенов Антон Сергеевич), acting as an individual.

Support: support@rockhold.ru.

Privacy and Account-deletion enquiries: privacy@rockhold.ru.

## 1. Scope and Acceptance

These Terms govern the use of {{ site.data.legal.app_name }} (the “App”). By using the App, the User confirms that they have reviewed these Terms and the Privacy and Personal Data Processing Policy. Information about the accepted version may be stored locally; the App requests renewed acknowledgement when the documents materially change.

The App is provided by Anton Sergeevich Parfenov (Парфенов Антон Сергеевич), acting as an individual (the “Operator”). “User” means an individual using the App. “Account” means a RockHold account used for authentication and Server Synchronization.

## 2. Purpose of the App

The App is intended for personal-finance records, including accounts, transactions, transfers, categories, budgets, currencies, goals, funds, planned entries, local notifications, backups, and Excel export.

The App is not a bank, broker, payment service, accounting, tax, investment, or legal adviser. It does not perform banking transactions, provide investment advice, or guarantee financial results.

## 3. Local and Server Functions

The primary working database is stored on the User’s device. After creating an Account, the User may use Server Synchronization for data supported by the RockHold server.

Lack of network access does not prevent core local use. Synchronization may be postponed, retried, or require the User’s choice where local and server versions of data are incompatible. A synchronization status applies only to entity types supported by the active server feature.

Manual backup, Server Synchronization, and Excel export are separate means of working with data and do not replace each other.

## 4. Account and Access Security

The User must keep secure the means of access to their device, Apple ID, Yandex account, and other connected sign-in methods. Passwords, tokens, verification codes, and access to an active session must not be shared with third parties.

The Operator may restrict or terminate a session where there are signs of compromise, abuse of App functions, violation of applicable limits, or a need to protect data or the service.

## 5. Account and Financial Data Deletion

Account deletion, sign-out, Financial Data deletion, and deletion of the local database are separate actions. The App presents the consequences of each action before confirmation.

Complete Account deletion is initiated in the settings of an authenticated Account and requires fresh identity verification using the selected sign-in method. After completion, the Account, email address, profile identifiers, sign-in-provider links, and session and device bindings are deleted. Access to the deleted Account ends permanently: it cannot be used to sign in, synchronize, or restore data. This is not a temporary deactivation.

Raw Financial Data linked to the Account is deleted. Before deletion, only irreversibly anonymized statistical aggregates may be created, without user or persistent technical identifiers, names, notes, exact activity sequence, or a means of re-identifying the User.

The “Delete financial data” action retains the Account, clears working Financial Data, creates a new empty server data generation, and deletes the prior server generation and its synchronized raw records. Before clearing data, the App creates a local safety backup where the restore mechanism requires it.

## 6. Data Accuracy and Backups

The User is responsible for the accuracy of entered amounts, currencies, dates, categories, and other parameters. If an operation requires an exchange rate that is unavailable, the App must report that condition rather than silently applying a 1:1 rate.

Restoring a backup may replace all local data. Before confirmation, the User should check the source and data preview. A `.rockholdbackup` file is protected with AES-GCM using a key embedded in the App; it is not encryption with a user-only password. Excel files are readable. Exported files may contain financial information and, after transfer, are controlled by the User and the service selected by the User.

Isolated server database backups may contain state that existed before Account deletion for no more than 30 days and are used only for disaster recovery. Ordinary sign-in, synchronization, and user restoration are not performed from such backups.

## 7. Notifications and Biometrics

Local notifications may appear on the lock screen depending on iOS settings. Face ID and Touch ID are used only as local system verification and do not provide the App with biometric templates.

## 8. Service Availability

The Operator takes reasonable steps to maintain the availability of the App and server functions but does not guarantee uninterrupted or error-free operation. Availability may be affected by networks, server infrastructure, the App Store, iCloud, sign-in providers, and third-party file services. A server-function failure must not result in an undisclosed deletion or replacement of local data.

## 9. Acceptable Use

The User must not bypass authentication or restrictions, access another person’s data, interfere with the service, use automated means to abuse the App’s functions, or use the App in violation of law or third-party rights.

## 10. Enquiries, Applicable Law, and Amendments

Support enquiries may be sent to support@rockhold.ru. Enquiries about personal data or Account deletion may be sent to privacy@rockhold.ru. The Operator will never request a password, token, or sign-in code by email.

Mandatory consumer rights and other rights that cannot be limited by agreement remain unaffected. Unless a separate complete license is published in App Store Connect, Apple’s Standard EULA applies together with these Terms to the extent permitted.

Material amendments are published before the corresponding App release and require renewed acknowledgement. For Users in the Russian Federation, the Russian version applies; if translations conflict, the Russian version prevails.
