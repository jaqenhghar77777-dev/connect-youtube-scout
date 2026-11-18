# CONNECT YouTube Scout — Privacy Policy

**Last updated:** 18 November 2026  
**Status:** Public notice for a proposed operator-controlled, one-time API pilot. The live pilot has not been activated.  
**Contact:** zl6798566@gmail.com

## 1. About the client

CONNECT YouTube Scout is an experimental, locally operated software client for testing the technical retrieval of public YouTube comments through the official **YouTube Data API v3**. It is part of an independently developed review/comment collection research project. It is not a public website or service and is not affiliated with or endorsed by YouTube or Google.

The proposed initial pilot is limited to one public video, a maximum of four API request attempts, and aggregate technical results. Access is limited to the operator. As of the date above, no live API collection has occurred in this pilot.

## 2. What information may be accessed

During a separately approved pilot, the client may temporarily receive API responses containing public comment text, comment IDs, thread and reply relationships, timestamps, and other fields included in the approved minimal response projection. Such comments may contain personal information voluntarily posted by their authors.

The initial pilot is designed not to request YouTube account authorization, private account data, OAuth tokens, or nonpublic videos. It does not request contact details or account credentials from commenters.

The operator may enter a project API key into a hidden local terminal prompt. The key is intended to be used only for authenticated calls to the official API and is not intended to be written to persistent storage, logs, or reports.

## 3. Purpose and use

The sole purpose of the proposed first pilot is to validate whether the collector can retrieve public comment threads and replies through documented YouTube API methods, respect API request limits, classify errors, and produce aggregate diagnostic counts.

The pilot will not use the collected comments for advertising, targeted profiling, resale, public redistribution, or automated contact with commenters. Any later analytics, storage, sharing, commercial use, or expansion to additional platforms requires an updated notice and separate review.

## 4. Processing, storage, and retention

The pilot is designed to process comment text and identifiers transiently in local process memory and discard them when the process exits. It is designed not to persist raw comments, comment identifiers, API responses, or API credentials to disk, or send them to remote AI models.

The operator may separately keep non-identifying aggregate technical diagnostics (for example: number of requests, error categories, and counts of observed records), subject to review and applicable platform policies. No public comment content will be included in those diagnostics.

These are the intended controls of the proposed pilot, not a guarantee against compromised devices, operating-system-level memory capture, or third-party infrastructure outside the client's control.

## 5. Sharing, advertising, and tracking

The proposed pilot does not provide raw comment content or identifiable comment records to third parties, advertise to commenters, sell API data, place cookies, or operate client analytics trackers. API requests necessarily communicate with Google's YouTube API infrastructure, which handles requests under its own policies.

The client is operated locally and is not currently offered to external users.

## 6. Access, requests, and concerns

For questions about this pilot, privacy practices, or requests concerning any data processed by the operator, contact: **zl6798566@gmail.com**.

The initial pilot does not use OAuth authorization, so it does not obtain access to a signed-in viewer's private YouTube account. If a later version introduces authorized-account features, it must clearly disclose those features, obtain applicable user consent, provide a way to revoke access, and handle related deletion requests. Google's account permissions page is: https://security.google.com/settings/security/permissions

## 7. YouTube and Google terms

This client uses YouTube API Services and is subject to the applicable [YouTube Terms of Service](https://www.youtube.com/t/terms), [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service), and [YouTube API Services Developer Policies](https://developers.google.com/youtube/terms/developer-policies).

By using this API client, a user agrees to be bound by the YouTube Terms of Service. The operator must review and accept this privacy policy before enabling the client. Google's handling of information is described in the [Google Privacy Policy](https://policies.google.com/privacy).

## 8. Changes

This notice will be reviewed before a live pilot and updated if collection methods, data fields, retention, intended use, access, or sharing change. A future public-facing version would need an appropriate visible privacy-policy presentation and consent mechanism before other people could use the client.
