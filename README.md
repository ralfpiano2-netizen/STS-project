# STS Project: Flexible E-Commerce Plastic Packaging Recovery

Terminal Assessment for MO-SS036 Science, Technology and Society (Section S2103), BSIT-AI-Powered Product Development, by Ralf Kevin I. Piano.

The project studies how clean flexible plastic film from e-commerce (poly mailers, bubble wrap, stretch film) can be recovered in the Philippines. This repository holds the desired outcome: a practical planning toolkit for a barangay, school or community pilot, together with the presentation.

The toolkit is a planning proposal. It does not claim actual waste reduction or recycling outcomes, and every peso figure is a placeholder until it is replaced with a real quote.

## The Film Recovery Toolkit

Open `index.html` in a browser, or publish the repository with GitHub Pages. No build step and no server are needed. The page works on desktop, tablet and phone, in light and dark mode.

| Part | What it does |
|---|---|
| Guidelines | What to accept and refuse, and how to handle, store and hand over film |
| Batch log | Records each batch from drop-off to the recycler's receipt, with net weight, traceability and error checks |
| Costs | Preliminary cost assessment: equipment, monthly operating cost, financing split, cost per tonne and producer fee |
| Readiness | Six conditions to verify before the pilot starts, with an automatic GO or NO-GO |

The parts share data, so the Overview dashboard updates as you work. Entries are saved in your own browser (local storage); export a copy to share it.

## Repository contents

```
index.html                               the whole app (single file)
presentation/
  STS-Problem-Solving-Presentation.pptx  15-slide terminal assessment deck
downloads/
  Film-Recovery-Toolkit.xlsx             unified workbook: guidelines, batch log, costs, readiness
  Recovery-Tracking-Tool.xlsx            tracking tool on its own
  Preliminary-Cost-Assessment.xlsx       cost assessment on its own
logo/
  ecofilm-recovery-logo.svg / .png  app logo (green parcel with a leaf sprout)
```

## Limits

- App data is stored per browser. There is no shared database.
- The workbooks were recalculated and checked in LibreOffice, not in desktop Excel.
- The presentation was built programmatically and checked by rendering, not opened in desktop PowerPoint.
