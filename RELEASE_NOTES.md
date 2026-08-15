# AI Quota 0.1.0 — Public Beta 2

This update improves menu bar reliability, Claude live-rate forecasts, authentication recovery, and localization.

## Highlights

- Opt-in **Start with Mac** control using the native macOS Login Items service
- Automatic compact menu bar icon when the full percentages do not fit or overlap a MacBook notch
- Current usage in the compact icon tooltip and a red critical-state indicator
- More reliable Claude `%/min` measurement when provider reset timestamps drift by a few seconds
- Historical forecast fallback while a live Claude rate is temporarily unavailable
- Fewer false Claude sign-outs during temporary credential rotation or provider errors
- Official Shoong and JOGAK icons, updated JOGAK description, and refined Recommended Apps section
- Reviewed English, Korean, Japanese, German, French, Spanish, Portuguese, Hindi, Indonesian, and Filipino localization

## Beta notes

- Live speed and limit time are estimates.
- Provider quota values can update later than local response activity.
- AI Quota is an independent, unofficial app. Provider interfaces may change or become unavailable without notice.
- Updates are installed manually in this beta.

## Verification

The macOS app is signed with a Developer ID certificate, notarized by Apple, and accompanied by a SHA-256 checksum. Apple notarization verifies the app package and does not represent endorsement by OpenAI or Anthropic.

`AI-Quota-0.1.0-42-macOS-arm64-x86_64.zip`

SHA-256: `e24bc3427ad0262498c9ac55778166dabc8a9fd4e20e427c368dc12b9d42de5f`
