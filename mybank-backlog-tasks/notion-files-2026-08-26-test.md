# Notion Files Weekly Merge Test - 2026-08-26

Test run time: 2026-08-26 12:58:17 CST

## Source

- Notion ID: `3abc8b05af6d80eebe93c9b59e3f122b`
- Notion URL: `https://app.notion.com/p/3abc8b05af6d80eebe93c9b59e3f122b?v=3abc8b05af6d80898949000cd7cdf70b&source=copy_link`

## Result

- Target folder check: success
- Notion web connection: success
- Notion page data read: failed, no page/file records were returned
- Downloaded files: 0
- Markdown merge: test report only, because no Notion files were readable
- Slack API connection: success
- Slack upload/message: failed, Slack API returned `invalid_auth` with the placeholder token

## Required Before Full Run

1. Provide or connect a Notion integration/session with access to the target page and nested pages/databases.
2. Provide or connect Slack authorization for the Cathay Web workspace with permission to upload files to channel `D09RDG5URE3`.

Once both permissions are available, the automation should be tested again with a real download and Slack upload.
