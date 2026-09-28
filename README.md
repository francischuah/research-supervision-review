# Research Supervision Review System — Version 1.1

Static HTML, CSS and JavaScript. No build step, server, account or database is needed.

## Open and try it

Open `index.html` in a modern desktop browser. A fictional DBA case study review is loaded on first use. Select **Preview report** to inspect the populated report; select **Print / Save as PDF** and choose A4 portrait in the browser print window. For the intended colours, enable **Background graphics** if your browser offers that setting. For best results, turn off browser generated headers and footers.

## Your review workflow

1. Choose **New**, then **New review** beside a template. Enter student and review details.
2. Work through the criteria in the left sidebar. Edit statuses, summaries, detailed comments and requested actions.
3. Complete **Priority revisions** and **Overall comments**, then preview and print.
4. Changes automatically save in this browser; **Save** forces an immediate save. Use **Saved reviews** to reopen, duplicate for another round or delete. Duplication advances the numeric round while retaining the supervisor review as a starting point for the next round.
5. Use **Export JSON** for a backup or transfer to another browser. **Import JSON** creates a separate review. Export regularly: browser storage is tied to the browser and device and can be cleared.

In **Template manager**, create, rename, duplicate and delete reusable templates, and edit their criteria, order, sections and expectations. **Save current criteria as template** copies titles, section names and expectations without copying any supervisor judgements. Editing a template affects future reviews only.

## Publish on GitHub Pages

Create a GitHub repository, upload the five application files (`index.html`, `style.css`, `data.js`, `report.js`, `app.js`) to its root, and commit. In repository **Settings → Pages**, select **Deploy from a branch**, choose the default branch and `/ (root)`, then save. Open the Pages URL after deployment finishes. Changes saved inside the app stay in that browser; the public repository contains only the application code and fictional demonstration data. Do not commit exported student review JSON or actual research records to a public repository.

## Version 1.1 boundaries

- Browser storage is local to a device and can be lost; JSON export is the backup route.
- The browser's print engine controls pagination and optional page numbers. Long text may split across pages; inspect the PDF before sending.
- There is no sign-in, cloud sync, shared editing, cross-round comparison or attachment support.
