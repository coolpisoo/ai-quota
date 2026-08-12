# AI Quota Support

## Before contacting support

1. Confirm that you are using the latest release.
2. Open AI Quota and refresh the provider once.
3. Confirm that Codex or Claude Code is installed and signed in if you use its local activity feature.
4. If a connection failed, disconnect only that provider and reconnect it from AI Quota.

## Common questions

### Why does the provider’s percentage update later than the waveform?

The waveform reflects recent local response activity. Provider quota percentages may be reported in coarse increments or refreshed later, so the two signals do not always change at the same moment.

### Is the live burn rate exact?

No. `%/min` is an estimate calibrated against available provider quota changes and recent local activity. It is intended to show direction and pace, not to replace the provider’s official billing or usage record.

### Why does macOS ask for Keychain access?

AI Quota asks only when you explicitly connect a feature that needs to reuse an existing Claude Code sign-in. If you do not enable that connection, AI Quota should not request access automatically.

### How do I quit or uninstall the app?

Choose **Quit App** at the bottom of the AI Quota panel. Then drag **AI Quota.app** from Applications to the Trash.

## Report a problem

Email [coolpisoo@gmail.com](mailto:coolpisoo@gmail.com) with:

- your macOS version;
- Mac model and chip;
- AI Quota version and build number;
- provider affected;
- the approximate time the problem occurred;
- a screenshot with account details removed.

Do not send passwords, passkeys, login codes, access tokens, Keychain exports, or complete conversation logs.

