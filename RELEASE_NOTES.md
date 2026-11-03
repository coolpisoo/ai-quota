# AI Quota 0.1.5 — Public Beta 5

This update improves usage tracking across sleep/wake, long-running Codex conversations, and Claude quota resets.

## Improvements

- Restarts live activity and graph timing after the Mac wakes, refreshes quota immediately, and retries after the network settles.
- Keeps a valid local Codex connection when no new usage event has arrived during sleep or idle time.
- Uses newer quota observations instead of older restored cache, and refreshes local records when the panel opens.
- Finds recent usage from conversations started weeks or months ago.
- Reserves space for `100%` in the menu bar so a Claude quota reset does not unexpectedly widen the item; retries numeric display after a temporary compact fallback.
- Includes Claude connection and quota-response compatibility improvements from recent local builds.

## Known limitations

- The menu bar can still use a compact icon when there is insufficient space. Open the panel to see available quotas.
- Live burn rate and limit times are estimates; provider values may arrive in coarse increments or with a delay.
- The company-account Claude reset fix has automated coverage; the next real account reset still needs confirmation.
- A clean-Mac installation test and a physical Intel Mac smoke test have not been performed for this release.
- Provider interfaces may change or become unavailable. Updates are installed manually in this beta.

AI Quota is independent and is not affiliated with, endorsed by, or sponsored by OpenAI or Anthropic.

## Download verification

The universal app is signed with Developer ID, notarized by Apple, and provided with a SHA-256 checksum. Apple notarization verifies the app package and does not indicate provider endorsement.

`AI-Quota-0.1.5-61-macOS-arm64-x86_64.zip`

SHA-256: `dcda560cb469e38ceb4c9e6bd64a15ebca646593cb5d7d2cbbc719d66b41d649`

