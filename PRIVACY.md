# Privacy Policy

**Quick Relay for Telegram** ("the Extension") respects your privacy. This policy explains what data the Extension collects, how it is used, and your choices.

## Data Collected

The Extension stores the following data locally in your browser using `chrome.storage.local`:

- **Bot Token**: The Telegram Bot API token you provide in Settings. This is required to send messages on your behalf.
- **Chat/Channel IDs**: The identifiers of Telegram channels or groups you configure as message destinations.
- **Message Content**: The text, images, files, and other content you choose to send via the Extension.

## How Data Is Used

- The **Bot Token** and **Chat IDs** are sent directly to Telegram's Bot API (`api.telegram.org`) only when you send a message or validate your configuration.
- **Message Content** (text, images, files) is transmitted to Telegram's servers via their Bot API when you explicitly send or queue a message.
- **No data is sent to any third party** other than Telegram's API servers.

## Data Storage

- All settings and configurations are stored **locally** in your browser's `chrome.storage.local`, which is encrypted at rest by Chrome.
- The Extension does **not** operate its own servers and **does not** collect, log, or transmit telemetry, analytics, or usage data.

## Third-Party Access

- **Telegram**: When you send a message, the content and your bot token are transmitted to Telegram's API servers. Telegram's privacy policy applies to that data once received.
- **Image/File Hosts**: When you send an image from a website, the Extension fetches that image from its original URL and relays it to Telegram. The image host may log that request.

## Data Retention & Deletion

- All data remains in your browser's local storage until you remove it via the Extension's Settings page or clear your browser data.
- You can delete all stored data at any time by removing the Extension from Chrome.

## Permissions Justification

- `storage`: To save your bot token and channel configuration locally.
- `contextMenus`: To provide right-click options for sending content to Telegram.
- `activeTab`: To capture screenshots of the current tab.
- `host_permissions`: To fetch images from websites you choose to send, and to communicate with `api.telegram.org`.

## Contact

For questions about this privacy policy, please open an issue on the GitHub repository.

*Last updated: May 2026*
