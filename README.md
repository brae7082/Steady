# Steady Bodyweight Coach — v3

## Improvements from your first workout

- The exercise's exact variation name appears again immediately above the rep/seconds target in the logging card.
- Scapular pulls are counted as repetitions, not timed holds. A short pause is part of each repetition.
- Negative pull-ups/dips/Nordics are counted as lowering repetitions, not seconds. Work toward a controlled 10-second descent per repetition.
- The Progress tab has an explicit Save button on every exercise, shows the target and unit, and allows editing the target.
- All seven days are available under Settings → Workout days. Select exactly three and tap Save workout days.
- Replaced misleading generic stick figures with step-by-step movement cues and a direct YouTube search for the specific variation. **Video search results are not vetted and videos are not yet embedded**; adding curated embedded demonstrations remains a future improvement.
- Added Android installation guidance in Settings.

## Android installation

1. Extract the ZIP and upload the files **inside** this folder to a secure HTTPS static host (GitHub Pages, Netlify, or Cloudflare Pages). The app must be served from a URL; opening an extracted `index.html` from Files is not sufficient for installation.
2. Open the HTTPS address in **Chrome for Android**.
3. Tap the ⋮ menu → **Install app** (or **Add to Home screen**). Follow the prompt.
4. If Chrome doesn't offer installation, check that the site is served over HTTPS and that `manifest.webmanifest` and `sw.js` are accessible.

## Important data warning

Workouts are saved to the browser's `localStorage`, scoped to the site's origin. To preserve existing data, replace the old files **at the same website address and in the same browser profile**. Before replacing anything, open the previous app and select Settings → Export my workout data to create a backup. **Export is available, but importing a backup is not implemented yet.** A different domain, browser, or installation can start with empty history. Do not delete the previous app until you confirm your history is present.

## Reminders

The app can request notification permission and save reminder time and days. Actual background scheduled push reminders are **not implemented** and need a hosted push backend.

## Fitness safety

Verify the stability of all supports and anchors, use controlled form, and avoid pain. This is a configurable workout companion, not individualized medical advice.
