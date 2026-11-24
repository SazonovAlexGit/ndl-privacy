# Privacy Policy for the NDL iOS App

> **Draft.** In-app deletion of the server profile is planned for the final build.

Effective date — 15.11.2026  
App operator — Sazonov Aleksey  
Contact for personal data inquiries — sazonov.alex79@gmail.com

This policy describes how data is processed in the NDL iOS app and on the app server. The National Dive League certificate registry keeps its own records. Requests to change or delete entries in that registry are handled by its operator.

## What data we process

- **Profile and certificates.** When you request certificates, the app sends your first name, last name, and date of birth to the registry at `ndl-global.com`. To verify and sync your profile, the app server also checks these details through the registry and stores your first name, last name, date of birth, and an internal profile identifier. Certificate details, photos, QR codes, and registry response data received from the registry are stored on the device so certificates can be opened offline. If the registry provides a link for generating a QR code, the app contacts `api.qrserver.com` and passes the profile link supplied by the registry to create the image.
- **Author application.** To review an application, we receive your profile details, email, information about yourself, a description of planned publications, and an attached certificate photo. This data is used to review the application, contact you, and manage author access. The email and application attachment are used for processing the application and are not shown in the feed.
- **News.** The server stores drafts and published posts, including the title, text, selected photos or videos, category, tags, city, and an external link if you add them. Drafts are available to the author and to authorized staff when maintaining the app. After publication, the news content and author name are available to feed readers. To track “Like” reactions, the server stores an internal app installation identifier and reactions.
- **Support requests.** If you submit a request, we store your profile details, the request type and text, the email you provide, and any selected attachment. We use them to reply and resolve the issue, including restoring author access.
- **Location.** With iOS permission, the app uses your current location to find nearby dive centers and to suggest a city when creating a news post. For search and city lookup, coordinates or the search area are sent to Apple through system Maps services. The city you choose is saved in the publication. When you open a place in Yandex Maps, information about the opened place is sent to Yandex. [Apple Maps Privacy](https://www.apple.com/legal/privacy/data/en/apple-maps/) · [Yandex Privacy Policy](https://yandex.com/legal/confidential/)
- **Notifications and access protection.** When you enable news notifications, the server stores an Apple Push Notification service (APNs) token, an installation identifier, language, and subscription status. Apple receives the token and data needed to deliver the notification. Apple App Attest is used to protect author access. The app sends the server a key identifier, attestation proof, and signed request assertions. Author tokens and the key identifier are stored on the device in the Keychain. App diagnostic logs may include network error codes and HTTP statuses.
- **Logbook, planner, and equipment.** Dive records, photos you add to them, saved plans, and equipment details are stored in the app data on the device. NDL does not send them to its server when you use these sections. If you separately attach the same file to an application, support request, or news post, it is sent for that feature.

The app obtains photos and videos through the system media picker when you choose the files yourself. That data is used for the selected feature. We do not use the data described above for personalized advertising, cross-app tracking, or sale to third parties.

## Who receives the data

Server profiles and records are stored in the app database; media and attachments are stored in the app object storage. Authorized administrators and moderators may access them within the scope of their duties. Data is transmitted over HTTPS.

The NDL registry, the QR code provider, and Apple receive information to the extent described for the relevant feature. Email services process the address and message content when a reply or author code is sent. When you open an external website, that site’s terms and privacy policy apply.

Data may also be disclosed to the extent required by applicable law.

## Retention and deletion

Local data remains while you keep it in the app. Logbook entries, plans, and equipment details can be deleted in the corresponding sections. Uninstalling the app from a device does not by itself delete the server profile, applications, or publications.

The server profile and author-access data are kept for as long as the related features are used. Drafts and publications are kept until deleted by the author or the operator. Applications, support requests, and attachments are kept for one calendar month. Data in backups is removed after a one-week rotation cycle. If the law requires certain information to be retained, it is kept only as needed for the required period.

To request access to your data, correction, or deletion, write to the email above. To protect the profile, we may ask you to confirm that the request comes from its owner. Deleting an NDL iOS profile does not delete training records from the external certificate registry.

You can withdraw location and notification permission in iOS Settings. News notifications can also be turned off with the switch in NDL Settings. Withdrawing permission stops the related access or delivery and does not by itself delete previously stored data. Requests to delete previously submitted data can be sent using the contacts above.
