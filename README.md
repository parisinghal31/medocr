# MedOCR

On-device OCR that turns medical / lab reports into structured data, right in the browser.

**Live demo:** https://parisinghal31.github.io/medocr/

## Features
- Upload images (JPG, PNG, WEBP) or PDFs, including multi-page PDFs, via button or drag & drop
- OCR runs locally with Tesseract.js (WebAssembly), so reports never leave the device
- Extracts patient details (name, age, sex, ID, doctor, dates) and test results (value, unit, reference range)
- Auto-flags results as HIGH / LOW / NORMAL against reference ranges
- Editable fields, re-parse after correcting OCR text
- Export to JSON or CSV

## Tech
HTML, CSS, vanilla JavaScript · Tesseract.js · PDF.js · Canvas API for image preprocessing

## Run locally
Open `index.html` in a browser. No build step or server needed.
