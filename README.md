# AutoReader

Mobile-first camera text reader built with React, Vite, Tesseract.js OCR and browser speech synthesis.

## Features

- Automatically scans for stable printed text
- Says "About to read text", counts down three, two, one, then reads
- Highlights words where the browser supports speech boundary events
- Finishes the current passage before scanning again
- Pause/resume, stop and speed control

## Development

Run `npm install` then `npm run dev`. For phone camera access, deploy over HTTPS. Grant camera permission. OCR and speech depend on device/browser support. No paid API keys are required.

This is an untested first version, not yet deployed.
