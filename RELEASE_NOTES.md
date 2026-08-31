# AI Quota 0.1.3 — Public Beta 4

This update brings Claude Code live activity into the Developer ID beta and improves compatibility with recent Claude quota responses.

## Highlights

- Uses recent local Claude Code activity from `~/.claude/projects` for the live waveform and burn-rate estimates
- Combines available Claude quota windows with recent local activity for reset and limit forecasts
- Supports Claude’s newer `limits` usage response format
- Makes refresh state more resilient to transient authentication, provider, and stale background-refresh failures

## Known limitations

- After a Mac screen unlock or app relaunch, provider percentages may temporarily disappear from the menu bar. This recovery issue is still under investigation.
- Claude quota windows may be unavailable for Free or API-only accounts.
- Live speed and limit time are estimates, and provider values can update later than local activity.
- AI Quota is an independent, unofficial app. Provider interfaces may change or become unavailable without notice.
- Updates are installed manually in this beta.

## Verification

The universal macOS app is signed with a Developer ID certificate, notarized by Apple, and accompanied by a SHA-256 checksum. Apple notarization verifies the app package and does not represent endorsement by OpenAI or Anthropic.

`AI-Quota-0.1.3-52-macOS-arm64-x86_64.zip`

SHA-256: `51569abe4b8217d072df784cef9ce8f652238bb8c544188500916c980bd1aceb`
