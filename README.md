# VCC Vehicle Report Card

An interactive, fillable, and printable web app styled to [Vancouver Community College (VCC)](https://www.vcc.ca/) brand standards. It replicates the "Your Vehicle Report Card" multi-point vehicle inspection form used by the VCC Automotive program.

## Features

- **Single HTML file** — no frameworks, no build tools, no dependencies
- **VCC brand styling** — navy blue `#002855`, accent red `#C41230`, and VCC logo (inline SVG mark + wordmark)
- **All 7 inspection sections** faithfully recreated:
  1. Visual 360° Perimeter Inspection
  2. Visual Under Hood Inspection
  3. Visual Under Vehicle Inspection
  4. Visual Brake Inspection
  5. Visual Tire Inspection
  6. Visual Fluid Level Check and Fill
  7. Visual Diesel Inspection
- **Tri-state status indicators** — click any indicator to cycle through:
  - ✅ Green — Checked OK
  - 🔵 Blue — Requires Future Attention
  - 🔴 Red — Requires Immediate Attention
  - ☐ Empty — Not yet inspected
- **All fields fillable** — text inputs, checkboxes, radio buttons, and text areas
- **Print-optimized** — clean single-page letter-paper output via `@media print` CSS
- **Print & Reset Form** buttons

## How to Use

1. **Open `index.html`** in any modern web browser — no server required.
2. **Fill in the header** fields: date, customer name, service advisor, dealer code, R.O.#, VIN, and odometer.
3. **Work through each section** — click tri-state indicators to set the inspection status for each item.
4. **Enter measurements** where needed (brake pad thickness in mm, tire tread depth in 32nds, etc.).
5. **Add comments** and technician/customer signature in the Comments section.
6. **Fill in the next maintenance appointment** details at the bottom.
7. **Print** — click the "🖨️ Print Form" button to print or save as PDF.
8. **Reset** — click "🔄 Reset Form" to clear all fields and start over.

## Printing Tips

- The print button triggers the browser's native print dialog.
- For best results, set paper size to **Letter (8.5" × 11")** in portrait orientation.
- Enable **"Background graphics"** in your browser's print settings to preserve colored status indicators and section headers.
- To save as PDF, choose **"Save as PDF"** as the printer destination.
- The form is designed to fit on a **single page** — the print stylesheet automatically scales content to fit.

## Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No internet connection required — fully self-contained