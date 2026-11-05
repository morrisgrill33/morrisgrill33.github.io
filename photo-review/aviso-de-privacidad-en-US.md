---
layout: page
title: Photo Review Full Privacy Notice
permalink: /photo-review/aviso-de-privacidad-en-US.html
lang: en-US
---

**Effective date:** October 8, 2026

## 1. Data controller and contact

The controller of personal data related to Photo Review is **Mauricio Zárate Barrera**, whose address is **Grand Masters 48, Fracc. Junto al Río, Temixco, Morelos, Mexico**, and whose email for privacy matters is **morrisgrill@gmail.com** (the “Controller”).

Photo Review is a general-audience iPhone app; it is not designed or marketed specifically for children. It lets users browse photo library categories and albums, review photos and videos, keep them or mark them for deletion, manage pending items, and view subscription offers. Distribution is planned in **Mexico, the United States, and Canada**, with this notice available in Spanish, US English, and Canadian French. The app is offered by **Mauricio Zárate Barrera**.

For any question, request, or complaint about this notice or data processing, you may email **morrisgrill@gmail.com**, the Controller’s contact channel.

## 2. Scope of this notice

This notice explains what information Photo Review processes, why it uses it, where it is kept, when providers such as Apple or Google are involved, and what choices users have. It covers use of the iOS app, including Photos permissions, item review, the pending list, integrated advertising, and subscription purchases.

This notice does not replace the privacy notices of Apple, Google, advertisers, or external websites opened from an ad. Each provider is responsible for its own privacy practices.

## 3. Information related to the photo library

Photo Review uses PhotoKit, the iOS framework for accessing and modifying the photo library, only after the user grants the permission requested by iOS. Depending on the permission granted, the app can access available photos and videos, smart categories—for example, favorites, recent items, videos, screenshots, selfies, and other groups provided by Photos—and, with full access, user-created albums.

To display and sort items, the app may use the following on the device:

- The local identifier iOS assigns to each Photos item.
- The media type—image or video—and creation date provided by Photos.
- The identifier and name of a category or album.
- A thumbnail supplied by PhotoKit to represent the photo or video on screen.

The app processes this information to build categories, display cards, remember progress, and carry out decisions to keep or delete items. The version described by this notice does not include facial recognition, identification of people, OCR, or searches based on image content.

**Photos, videos, and their thumbnails are not uploaded to Photo Review servers or attached to advertising requests made by the app.** The reviewed code does not use its own server, a user account, or a backend to store photo library content.

If a photo or video is optimized in iCloud and the system needs to retrieve it for display, PhotoKit may request it from Apple/iCloud services in accordance with the user’s Photos and iCloud settings. That transfer is managed by the operating system and Apple; it is not an upload of content to the Controller’s servers.

Photos may contain information the user considers private or sensitive. Photo Review does not intentionally extract or classify faces, location, or other sensitive attributes for advertising or profiling. Users control which items the app can see through iOS Photos permissions.

## 4. Photos permissions and user control

The app requests permission to read and modify the photo library when needed to display items and allow confirmed deletion. iOS may grant full access, limited access to selected items, or deny access. With limited access, Photo Review can use only the items iOS allows it to see; some categories or albums may be unavailable.

Users can change or revoke permission in **iOS Settings > Privacy & Security > Photos > Photo Review**. When access is revoked, categories and cards that depend on the photo library may become unavailable.

Marking an item using the deletion gesture or button **does not delete it immediately**. The app keeps its identifier in the local pending list, where the mark can be undone. A change to the photo library is requested only when the user chooses **Delete selected**. iOS may display its own confirmation or authorization. Deleted items are subject to the recovery features and time limits of the Photos app, including **Recently Deleted**, if iOS places them there.

## 5. Information stored on the device

Photo Review keeps the minimum data needed to maintain the pending list and resume review in the app’s private storage. In particular, SwiftData may store:

- The local identifier of each photo or video marked for deletion.
- The identifier and name of the source category or album.
- The date the item was marked, the status of a deletion request, and, if an error occurs, the error text needed to display or retry the operation.
- The review checkpoint for each category: collection type and identifier, displayed name, identifier of the last item whose decision was saved, and update date.

The app does not store media files, copies of photos, videos, thumbnails, or PhotoKit objects in SwiftData. The local database is configured without CloudKit synchronization or a Photo Review backend.

The selected language and a usage counter for spacing out ads may also be kept in local iOS preferences. The counter resets when an ad interval is used up. It is not used as an account identifier.

The above data is used on the device itself. The operating system may include app data in device backups, according to the user’s backup settings. The Controller does not receive those backups.

## 6. Advertising and Google Mobile Ads

The reviewed version integrates the Google Mobile Ads SDK to load native ads within the review flow. The code sets an interval of eight reviewed photos: when applicable and another photo remains to be reviewed, an ad card is inserted. The app does not request those ads when it detects an active subscription. The final frequency or availability may also depend on ad configuration and the provider’s response.

Ad requests limit content to Google’s general-audience rating. This rating limits the type of advertising content; it does not mean that a verified age is sent to Google or that the setting alone addresses privacy rules applicable to children.

The SDK may automatically process information needed to deliver, measure, protect, and diagnose ads. According to the Google Mobile Ads documentation for iOS, this information may include IP address, available device or advertising identifiers, advertising data and interactions, crash logs, and performance or diagnostic metrics. Google may use this data in accordance with its own notices, tools, device settings, and legal requirements. The SDK may communicate with Google and participating advertising providers.

The app does not send photos, videos, thumbnails, or local photo library identifiers to Google as ad request parameters. If a user taps interactive ad elements, uses the interaction gesture configured by the SDK, or opens the ad’s destination, Google, the advertiser, and the destination website or app may receive information about that interaction and process it under their own notices.

Ads are identified within the interface. Users can skip the card using the available button or gesture. A rightward interaction is configured as a custom click gesture for the SDK and may be recorded as an advertising interaction; the final behavior and destination depend on the ad served.

See the [Google Privacy Policy](https://policies.google.com/privacy) and the SDK data description in [Google Mobile Ads data disclosure for iOS](https://developers.google.com/admob/ios/privacy/data-disclosure). Advertising information and available ad controls may vary by country, operating system, device settings, and the consent technologies implemented.

## 7. Purchases and subscriptions

The app offers weekly and annual auto-renewable subscription purchases through StoreKit, Apple’s purchasing system. Before a purchase, Apple displays the price, currency, period, taxes, and applicable terms for the relevant storefront.

Apple processes payment and manages the transaction, renewal, cancellation, and restoration of purchases. Photo Review checks with StoreKit for an active subscription to stop displaying ads. The Controller does not receive or store full card numbers or payment credentials. Apple may process account, payment, and transaction information under its own notices and terms.

Users can manage or cancel a subscription in their Apple/App Store account settings and restore eligible purchases from the app. Available links are **[Manage Apple subscriptions](https://apps.apple.com/account/subscriptions)** and the **[Apple Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)**. Availability, pricing, renewal, and refunds are subject to Apple’s and the storefront’s terms.

## 8. Purposes and user decisions

Information is used for the following purposes:

1. **Provide the core feature:** access authorized categories and albums, display photos and videos, remember where users left off, and retain their pending decisions.
2. **Carry out requested actions:** remove items from the pending list or ask iOS to delete in a batch only those items the user confirmed.
3. **Manage the subscription:** check with StoreKit for the purchase and validity needed to enable the ad-free experience.
4. **Display and measure advertising:** load ads, limit their frequency, record ad interactions through the SDK, and fund free access.
5. **Maintain preferences:** locally retain the selected language and the minimum state needed for ad frequency.
6. **Handle issues:** display Photos, StoreKit, or SDK errors in the app and allow operations to be retried where appropriate.

Photos access occurs only after users grant the corresponding permission in iOS. When Google UMP determines that an advertising privacy decision is required, the app requests that decision before starting Google Mobile Ads. Purchases are processed when users confirm the transaction through Apple. The app does not request a date of birth or create a user account.

## 9. Transfers and providers

Photo Review does not maintain its own backend or send the Controller a copy of the photo library. To operate certain features, direct communication may occur with:

- **Apple**, for Photos/iCloud system permissions and services, app distribution, StoreKit, purchase validation, and subscription management.
- **Google and participants in its advertising service**, for loading, measuring, protecting, and diagnosing ads and interactions with them.
- **Advertisers and external destinations**, when a user interacts with an ad and a third-party link or app is opened.

These providers may process information in countries other than the user’s country under their own notices, contracts, and transfer mechanisms. For publication, the Controller must confirm the provider entities corresponding to the actual Apple and Google accounts and agreements, as well as applicable international transfers.

Local Photos identifiers are not sold, and Photo Review does not provide photos or videos to advertisers. The reviewed code does not include integration with a proprietary analytics platform, CRM, account registration, or third-party advertising other than Google Mobile Ads.

## 10. Data retention and deletion

Pending-item identifiers remain in local storage until users unmark them or until Photos confirms deletion and the app removes the entry. If the operation fails, the app may retain the pending item and error to allow a retry.

The review checkpoint is kept locally to allow users to continue a category and is deleted or updated when its session ends or restarts. Preferences remain on the device until changed or the app’s data is deleted. The Controller does not keep these records on a central server.

Uninstalling Photo Review normally deletes its local app data, without affecting device backups or data Apple, Google, or other providers must retain under their own policies. Uninstalling the app does not cancel an Apple subscription; users must cancel it in their account.

## 11. Security

The app uses private iOS storage and limits local information to identifiers and review state needed for its features. Access to the photo library is controlled by operating system permissions. The Controller does not operate a central photo database or a user account for this version.

No measure can guarantee absolute security. Users should protect access to their device, keep iOS up to date, review Photos permissions, and avoid sharing the device with unauthorized people. Apple and Google apply their own measures to the services they manage.

## 12. User rights and choices

Users can:

- Grant, limit, or revoke Photos permission in iOS Settings.
- Review, undo, or remove deletion marks from the local list before confirming the batch.
- Confirm deletion and manage it afterward in Photos, including **Recently Deleted** where applicable.
- Change the language in the app.
- Manage, cancel, or restore purchases through Apple.
- Request information about personal data processing for which the Controller is responsible, exercise rights of access, rectification, cancellation, or objection (ARCO), withdraw consent where applicable, or limit use or disclosure under applicable law.

To exercise rights or make a request, email **morrisgrill@gmail.com** and provide your name, a way to receive a response, the right you wish to exercise, and information that allows the related data to be located. If acting on behalf of another person, indicate that relationship. The Controller may request only the information strictly necessary to verify identity or representation under applicable law. Do not email photos, passwords, card numbers, or other unnecessary sensitive data.

Some records exist only on the device, and the Controller cannot access them remotely. To delete them, users can remove marks in the app, manage the item in Photos, change permissions, or uninstall the app. Requests concerning purchases, advertising identifiers, or information managed by Apple or Google should also be directed to those providers through their official channels.

## 13. Children

Photo Review is intended for a general audience and is not designed or marketed specifically for children. The app does not create accounts or ask users their age. The photo library may contain images of children; these are displayed locally only within the granted permission and are not sent to Photo Review servers or to ad requests created by the app. Ad requests limit content to Google’s general-audience rating, and UMP presents privacy choices appropriate to the region. The app does not send the user’s age or configure requests as specifically child-directed. Use by children and associated data processing are subject to applicable laws and to the age settings and parental controls of the device and Apple account.

If the Controller becomes aware of having received a child’s personal information in a manner incompatible with applicable law, the Controller will take appropriate measures, which may include deletion where possible.

## 14. Changes to this notice

The Controller may update this notice when the app, providers, purposes, or legal obligations change. The current version will indicate its update date and will be available at [https://morrisgrill33.github.io/photo-review/aviso-de-privacidad-en-US.html](https://morrisgrill33.github.io/photo-review/aviso-de-privacidad-en-US.html). If a change requires new consent, it will be requested through the app or another means permitted by applicable law before the corresponding processing takes place.

## 15. Data protection authority

If users believe their request was not handled appropriately, they may contact the competent personal data protection authority in their jurisdiction. In Mexico, they may consult the **Secretaría Anticorrupción y Buen Gobierno** (Ministry of Anti-Corruption and Good Governance) and the rights protection procedure provided in the [Ley Federal de Protección de Datos Personales en Posesión de los Particulares](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) (Federal Law on the Protection of Personal Data Held by Private Parties). The Ministry’s official information is available at [gob.mx/BuenGobierno](https://www.gob.mx/buengobierno).
