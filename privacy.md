# Privacy Policy — Nature & Space Facts

*Last updated: 2026-04-20*

Nature & Space Facts ("the service", "we") is a first-party video publishing
tool operated by a single creator. This policy describes what information we
collect when the creator uses the tool to upload their own videos to their own
accounts on third-party platforms (YouTube, TikTok).

## 1. Information we collect

- **OAuth tokens** issued by YouTube (Google) and TikTok, stored locally on
  the creator's workstation so the tool can upload videos on the creator's
  behalf.
- **Video files** produced by the creator's own pipeline, stored locally.
- **Upload metadata** (titles, descriptions, hashtags, scheduled publish
  times) stored in a local SQLite database.

We do **not** collect information from any users other than the creator.

## 2. How we use the information

OAuth tokens are used solely to authenticate requests to the respective
platform APIs on the creator's behalf. Upload metadata is used to schedule
publishing, track which videos have been posted, and surface analytics on
the creator's own content.

## 3. Sharing

We do not share any information with third parties. All data is stored
locally and under the creator's sole control.

## 4. Retention

OAuth tokens are retained until the creator revokes them from their platform
account settings or deletes the local token file. Video metadata is retained
in the local database for the lifetime of the project.

## 5. Security

The tool runs on the creator's private workstation. Tokens are stored in a
pickle file outside any public repository. The creator is responsible for
securing their device.

## 6. Third-party services

The tool calls the following APIs on the creator's behalf:

- **YouTube Data API v3** and **YouTube Analytics API v2** (Google LLC) —
  governed by Google's privacy policy at <https://policies.google.com/privacy>.
- **TikTok Content Posting API** (TikTok Pte. Ltd.) — governed by TikTok's
  privacy policy at <https://www.tiktok.com/legal/privacy-policy>.
- **NASA Image & Video Library** (public, no authentication) — for sourcing
  royalty-free footage used in videos.
- **Wikimedia Commons** (public, no authentication) — for sourcing
  Creative-Commons-licensed imagery.
- **Anthropic API** (Anthropic PBC) — for generating script text.

## 7. Children

The service is not directed at children under 13 and does not knowingly
collect information from them.

## 8. Changes to this policy

Material changes will be noted at the top of this document with a new
"Last updated" date.

## 9. Contact

For questions about this policy, contact the creator via the contact email
listed on the `@NatureSpaceFacts` YouTube channel About page.
