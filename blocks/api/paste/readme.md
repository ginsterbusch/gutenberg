# Paste

This folder contains all paste specific logic (filters, converters, normalisers...). Each module is tested on their own, and in addition we have some integration tests for frequently used editors.

## Support table

| Source | Formatting | Headings | Lists | Image |
|---| --- | --- | --- | --- |
| Google Docs | Yes | Yes | Yes | Yes (URL) |
| Apple Pages | Yes | No |  Yes | No |
| MS Word | Yes | Yes | Yes | No |
| MS Word Online | Yes | Yes | Yes | Yes (base64) |
| Markdown | Yes | Yes | Yes | Yes (URL) |
| Legacy WordPress | Yes | Yes | Yes | Partial (shortcodes coming) |
| Evernote | | | | |
| Web | Yes | Yes | Yes | Yes (URL) |

## Other notable capabilities

* Filters out analytics trackers in the form of images.
* Direct image data pasting coming soon.
