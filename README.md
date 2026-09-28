# Research Review System — Version 1.3

Static HTML, CSS and JavaScript. No build step, server, account or database is needed.

## Purpose

A supervisor- or examiner-facing academic review form that generates a professional A4 report. It can be used for supervision, proposal review, progress review, internal or external thesis examination, dissertation examination, viva/oral examination and MBA/project-paper review.

The report identity is dynamic: enter any **Report title** (for example, *Research Supervision Review Report*, *PhD Thesis Examination Report*, *External Examiner Report* or *MBA Project Paper Review Report*) and a **Reviewer role**. University/institution and school/faculty are optional metadata only and are no longer hard-coded into the report header.

## Open and try it

Open `index.html` in a modern desktop browser. A fictional DBA case-study review is loaded on first use. Select **Preview report** to inspect the populated report; select **Print / Save as PDF** and choose A4 portrait. Enable **Background graphics** if your browser offers that setting and turn off browser-generated headers/footers for the cleanest PDF.

## Review workflow

1. Choose **New**, then select a template. Enter candidate/student, research and review details.
2. Set the **Report title**, **Reviewer name** and **Reviewer role** to match the purpose of the report. Review round is optional.
3. Work through the criteria in the left sidebar. Edit status, summary, current assessment, reviewer comment and required action.
4. Complete **Priority revisions** and **Overall comments**, then preview and print.
5. Changes save automatically in this browser. Use **Export JSON** for a portable backup and **Import JSON** to restore or transfer a review.

In **Template manager**, create, rename, duplicate and delete reusable templates, and edit their criteria, order, sections and expectations. Editing a template affects future reviews only.

## Publish on GitHub Pages

Upload the application files to the root of the existing GitHub Pages repository and commit. This version uses versioned filenames (`style-v1.3.css`, `data-v1.3.js`, `report-v1.3.js`, `app-v1.3.js`) to avoid browser-cache conflicts. Delete older versioned application files if they are no longer referenced by `index.html`.

The public repository contains only application code and fictional demonstration data. Do not commit exported real-student or examination JSON records to a public repository.

## Version 1.3 boundaries

- Browser storage is local to a device and can be lost; JSON export is the backup route.
- Browser print controls pagination and optional page numbers. Inspect the PDF before sending.
- There is no sign-in, cloud sync, shared editing, cross-round comparison or attachment support.
- The system is reviewer-facing; it does not collect student/candidate responses.
