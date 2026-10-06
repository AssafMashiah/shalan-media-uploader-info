---
layout: default
title: Privacy policy — Shalan Media Uploads
permalink: /privacy.html
---
# Privacy policy

## Operator and purpose

Shalan Media Uploads is operated by Assaf Mashiah as a private media-upload utility. It is intended to transfer owner-selected videos to an approved Google Drive folder for the owner's projects.

## Google data access

The application requests the Google Drive `drive.file` scope. It can create files and access application-created files or files the account owner specifically authorizes for this application. It does not request unrestricted access to Google Drive, Gmail, Calendar, or contacts.

The upload workflow processes selected video bytes, filenames, file sizes, checksums, destination folder identifiers, Drive file identifiers, links, and permission metadata needed to verify storage and privacy. Google OAuth access and refresh tokens are used for authorized Google Drive API requests.

## Use, storage, and sharing

Video contents are transferred to Google Drive to complete the requested upload. Temporary local staging may be used during transfer. Operational records may retain filenames, checksums, file identifiers, timestamps, and upload outcomes for verification and duplicate prevention. Credentials are intended to be held in protected service storage and are not included in upload receipts or this public website.

Uploads are private by default. This tool does not automatically create public links or change file-sharing permissions. Account owners may independently choose to share or delete files using Google Drive. Google processes data under its own applicable terms and privacy policy.

This uploader does not sell Google user data, use it for advertising, or use it to train generalized AI models. Separate instructions to a creative agent to process media are outside this uploader's purpose and are not authorized merely by granting its Drive permission.

Shalan Media Uploads' use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Retention and control

Uploaded videos remain in the owner's Google Drive until the owner deletes them or explicitly authorizes a separate retention policy. Local originals are not automatically deleted by this uploader. Temporary staging is removed after processing where possible; failed or interrupted operations may require cleanup. Verification records are retained for operational use until the operator removes them.

The owner can revoke the application's access through [Google Account third-party connections](https://myaccount.google.com/connections). Revocation prevents further authorized uploads but does not itself delete existing Drive files.

## This information website

This static information website does not collect Google OAuth credentials or accept videos. It has no application analytics or advertising scripts. Its hosting provider, GitHub Pages, may process technical access logs under its own privacy policy.

## Contact

For questions or deletion of local operational records, contact [assaf.mashiah@gmail.com](mailto:assaf.mashiah@gmail.com).

[Back to application information](./)
