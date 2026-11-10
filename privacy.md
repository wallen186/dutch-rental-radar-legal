---
title: Privacy Policy | Dutch Rental Radar
---

# Privacy Policy

*Effective 10 November 2026*

## Who we are

Dutch Rental Radar is a private, invite-only household application operated by its owner for personal use and hosted on the Base44 platform.

This policy explains what information the application stores and how its Google integrations work.

See also our [Terms of Use](./terms.html).

## What the app stores

The application may store the following information:

- **Account:** Your name, email address, and sign-in method. Sign-in is handled by Base44, and a sign-in token is kept in your browser to maintain your session.
- **Household:** The household name and the email addresses of its members.
- **Information you enter:** Property listings, addresses, rent and other costs, housing features, availability, links, listing statuses, favorites, notes, pros and cons, manually entered commute and amenity estimates, search preferences, and uploaded property photos.
- **Discovered listings:** Listing details extracted from rental alert emails, such as addresses, rent, size, number of rooms, and listing URLs.
- **Import history:** Gmail message identifiers or fingerprints of pasted alerts, providers, processing timestamps, listing counts, and synchronization outcomes. Alert email bodies are not stored.

Household data is accessible to authorized members of the household and the application owner.

## Gmail integration (optional)

Dutch Rental Radar can connect to a Gmail account through Base44's Gmail integration to discover rental listings.

### Permissions

The integration requests read-only Gmail access (`gmail.readonly`) and access to the connected account's email address.

The application cannot send, modify, label, or delete email messages.

Google grants read-only access to the entire connected mailbox. The restrictions described below are enforced by the application's own code, not by Gmail's authorization scope.

Base44 manages the connection credentials. Access tokens are not stored in Dutch Rental Radar's application entities.

### Who can initiate synchronization

Only application administrators and members of an authorized household containing an administrator can initiate email synchronization.

Synchronization runs only when a user explicitly selects the Sync action. Automatic synchronization is currently disabled.

### Which messages are processed

When synchronization is requested, the application searches for up to 50 messages received within the preceding seven days, or up to 30 days when that option is selected.

Messages must match the configured rental-alert sender domains.

The sender is checked again before processing. Messages from other senders are skipped.

The application reads the headers and text or HTML bodies of matching messages. Attachments are not opened.

### No AI processing

Rental alerts are processed using fixed parsing rules in the application's own code.

No email content, pasted alert text, or extracted listing text is sent to an AI service.

Information the parser cannot identify is left blank rather than invented.

### Information retained

The application retains extracted rental listing information, source identifiers, processing timestamps, provider information, and synchronization results.

Error information may include a Gmail message identifier, sender domain, or brief Gmail error description.

Complete email bodies are not stored.

Manually pasted alerts are processed using the same approach. Their original text is not retained; a fingerprint may be stored to prevent duplicate imports.

### Use of Gmail information

Gmail information is used only to identify and present rental listings in the authorized household workspace.

It is not sold, used for advertising, or shared for marketing purposes.

Access is limited to authorized household members, the application owner, and Base44 as the platform providing the functionality.

Dutch Rental Radar's use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

You can revoke Gmail access at any time through your [Google Account permissions](https://myaccount.google.com/permissions).

## Google Maps integration

When an authorized household member selects **Calculate commute**, the rental property's address and the configured office address are sent to Google Maps Platform through Base44's managed Google Maps integration.

The application uses Google's Geocoding and Routes services to retrieve walking, cycling, and public transportation information.

Google's travel times, distances, and route details are displayed temporarily in the active interface.

They are not permanently stored in the application's database, written to its application logs, or incorporated into saved property match scores.

The displayed results disappear when the user leaves or refreshes the page.

Selecting **Open in Google Maps** opens the relevant journey in Google's service.

Google processes information under its [Privacy Policy](https://policies.google.com/privacy). Use of Google Maps features is also subject to the [Google Maps/Google Earth Additional Terms of Service](https://maps.google.com/help/terms_maps/).

## Other data practices

Dutch Rental Radar does not display advertisements, sell personal information, or share household data for marketing purposes.

The application does not generate its own analytics events.

Base44, as the hosting platform, may collect standard operational, security, and technical information under its own privacy practices.

## Public legal website

These legal documents are hosted publicly through GitHub Pages, separately from the private Dutch Rental Radar application.

GitHub may process technical information associated with visits to these public pages under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

The public legal website does not provide access to private household data.

## Retention and deletion

Application data remains until an authorized household member deletes it or the application owner deletes it following a request.

You may contact the owner to request access to, correction of, or deletion of your information, or removal from a household.

## Contact

Questions about privacy, access, or deletion requests can be directed to:

**CONTACT_EMAIL_HERE**

## Changes to this policy

This policy may be updated to reflect changes to the application or its integrations.

The effective date at the top of this document identifies the current version.

---

[Return to Legal Homepage](./) | [Terms of Use](./terms.html)
