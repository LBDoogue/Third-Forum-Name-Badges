# Name Tag Generator

A self-contained, browser-based name tag generator built for events. Create, customize, and print professional name badges — no server or installation required.

## Features

- **Four tag styles** — Classic, Coral Bold, Minimal, and Garden
- **Match names** — Add up to two match names per badge (great for networking events, icebreakers, or pairing programs)
- **CSV import** — Bulk upload names and matches from a spreadsheet
- **Logo placement** — Upload logos, resize them precisely (10%–500%), and drag to position freely on the tags
- **Per-badge control** — Select individual badges to customize which logos and matches appear on each one
- **Inline editing** — Click the pencil icon on any badge to update names after entry
- **Layout presets** — Save and load logo arrangements for reuse across events
- **Project save/load** — Export your entire project as a JSON file and pick up where you left off, on any browser or machine
- **Print-ready** — Landscape layout, 4 tags per 8.5×11" sheet (4.5" × 3.75" each), with print-optimized CSS

## Getting Started

1. Open `index.html` in any modern browser
2. Enter your event name
3. Add names manually or upload a CSV (columns: Name, Match 1, Match 2)
4. Upload logos and position them
5. Hit 🖨 Print

No dependencies. No build step. No internet connection needed after loading.

## CSV Format

```
Name,Match 1,Match 2
Alex Chen,Morgan Lee,Priya Sharma
Jordan Rivera,Taylor Brooks,Sam Patel
```

A header row is auto-detected and skipped. Comma and tab delimiters both work.

## Project Files

Save your work as a `.json` project file using the 💾 Save Project button. This captures everything — names, matches, logos (embedded as base64), positions, sizes, style, and presets. Open it on any machine with 📂 Open Project.

## License

See [LICENSE](LICENSE) for details.
