# Gareth's Home Assistant

Personal Google Nest and Gmail integrations operated by Gareth Barber for his own Home Assistant instance. This is not a public sign-up service or an official Google product.

The Nest integration displays device and thermostat status and provides household climate controls. The Gmail integration reads delivery notifications to display courier status, tracking references and Amazon order details in a private deliveries dashboard.

## Privacy policy

These integrations access only accounts explicitly authorized by their owner. Nest data can include home and device identifiers, thermostat measurements and settings, and other device information covered by the permissions granted during sign-in. Gmail access is used to search delivery emails and extract shipment and order information. Gmail IMAP requires the broad mail.google.com permission, which technically permits reading, composing, sending and permanently deleting email; the delivery integration is configured to read notifications, not send or delete messages.

OAuth credentials and integration data are stored in the owner's Home Assistant installation and may be included in its configured history and backups. They are kept while needed for the household dashboards and integrations, subject to Home Assistant's history and backup retention settings. Removing authorization prevents future access; deleting the integration and its retained history or backups is needed to remove locally retained data.

Account data is not published in this repository, sold, used for advertising, or intentionally transferred to unrelated third parties. Google and Home Assistant integrations communicate as required to provide their functions. Any sharing or remote access to the owner's Home Assistant instance is controlled by the owner. Google account access can be revoked at https://myaccount.google.com/connections.

This application's use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements.

## Terms of use

This setup is for the owner's personal household use. It is provided as-is, without a guarantee of availability, completeness or accuracy. Delivery statuses depend on emails received and recognised; climate controls depend on device and network availability. The owner remains responsible for account security, permissions, backups, and decisions made using the displayed information. No public account registration or paid service is offered. Google and other providers' own terms continue to apply.

## Contact

For questions, contact the operator through https://github.com/garethbarber-web/oura-home-assistant-policies/issues.

Last updated: 1 November 2026.
