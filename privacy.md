---
title: Privacy Policy — RoolsVideoCUT
---

# Privacy Policy

_Last updated: 2026-05-20_

## 1. Overview

RoolsVideoCUT ("the Software") is a self-hosted desktop application. All processing happens on the user's own computer. The project owner does not operate any server that collects user data, and there is no shared backend or analytics service.

This policy describes what data the Software handles on the user's local machine and what data is transmitted to third-party platforms when the user explicitly initiates an action.

## 2. Data the Software Handles Locally

When operated by the user on their own computer, the Software handles:

- **Gameplay recordings and rendered clips** — supplied by and owned by the user, stored on the user's local disk.
- **OAuth tokens** — refresh tokens and access tokens issued by connected platforms (e.g. TikTok, YouTube). Stored locally in the Software's own SQLite database. Used solely to authenticate API calls the user initiates.
- **Connected-account display name** — fetched once after authorization, cached locally for display purposes.
- **Application logs** — written to the user's local disk for debugging.

None of this data is transmitted to the project owner or to any third party other than the platform the data is explicitly being sent to (e.g. when the user clicks "Upload to TikTok," the rendered video file is sent to TikTok).

## 3. Data Transmitted to Third Parties

When the user explicitly initiates an upload, the Software transmits the following to the relevant platform:

- the video file the user selected for upload;
- the caption, hashtags, and privacy setting the user entered;
- the OAuth access token, to authenticate the request.

The Software does not transmit any other data to third parties.

## 4. Third-Party Privacy Policies

Connected platforms collect and process data according to their own privacy policies. Relevant references:

- TikTok Privacy Policy: <https://www.tiktok.com/legal/privacy-policy>
- Google / YouTube Privacy Policy: <https://policies.google.com/privacy>

The user is responsible for reviewing and accepting those policies separately.

## 5. Data Retention and Deletion

All data handled by the Software is stored locally and remains under the user's direct control. To delete:

- **OAuth tokens**: disconnect the relevant platform from within the Software, or delete the row from the local `oauth_tokens` table.
- **Recordings, clips, logs, database**: delete the relevant files from the user's local disk.

To remove the Software's access on the platform side, revoke authorization in the platform's account settings (e.g. <https://www.tiktok.com/setting/apps>).

## 6. Cookies and Tracking

The Software does not use cookies, web beacons, or any tracking technology. It does not phone home, does not report usage analytics, and does not contact any project-owned server.

## 7. Children

The Software is not directed at children under 13 (or the equivalent minimum age in the user's jurisdiction).

## 8. Changes

This Privacy Policy may be updated from time to time. The "Last updated" date at the top of this page reflects the most recent revision.

## 9. Contact

For questions about this Privacy Policy, contact the project owner at the email address registered with the linked TikTok / YouTube developer accounts.
