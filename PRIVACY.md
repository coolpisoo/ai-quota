# AI Quota Privacy Notice

Last updated: August 13, 2026

AI Quota is designed as a local-first macOS application. The developer does not operate an AI Quota backend, analytics service, advertising service, or telemetry collector.

## Data the app processes

Depending on the services you connect, AI Quota may process:

- quota usage percentages, reset times, and account plan labels provided by ChatGPT/Codex or Claude/Claude Code;
- local token counters, rate-limit metadata, task state, and response-event timing used to estimate live activity;
- local usage history used for trend and forecast calculations;
- connection state required to request usage information from the selected provider;
- macOS preferences such as display mode and enabled monitoring features.

## Conversation content

AI Quota does not upload conversation content to the developer. Local activity readers are intended to use usage counters, rate-limit fields, task state, and event timing rather than displaying or collecting prompt and response text.

## Where data is stored

Usage cache, history, calibration values, and preferences are stored locally on your Mac. Any provider login or credential information remains in the storage managed by macOS, the provider, WebKit, Codex, or Claude Code as applicable.

AI Quota does not copy provider passwords into its own database. macOS may show a Keychain permission prompt when you explicitly connect a feature that needs access to an existing Claude Code sign-in.

## Network communication

When a provider connection requires it, AI Quota communicates directly with the relevant provider service to request usage information. The provider’s own privacy policy and terms apply to that communication. AI Quota does not route these requests through a developer-operated server.

## Sharing and sale

The developer does not sell personal information. AI Quota does not include third-party advertising, behavioral analytics, or cross-app tracking SDKs.

## Retention and deletion

Disconnecting a provider removes the corresponding locally stored usage cache and history managed by AI Quota. Deleting AI Quota removes the app itself; macOS may retain preferences or provider-managed credentials until they are removed through the corresponding system or provider tool.

## Security

Public downloads are signed with a Developer ID certificate, notarized by Apple, and published with a SHA-256 checksum. Install only from the official release page and verify the checksum when possible.

## Contact

Privacy questions: [coolpisoo@gmail.com](mailto:coolpisoo@gmail.com)

