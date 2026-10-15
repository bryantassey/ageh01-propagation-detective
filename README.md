# AGEH-01 Propagation Detective

A mobile-friendly, two-phase nursery discovery and reflection lab for Week 08 (20 points).

## Publish with GitHub Pages
1. Create a new GitHub repository (for example `ageh01-propagation-detective`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. After GitHub publishes, use `https://YOUR-USERNAME.github.io/ageh01-propagation-detective/` in Canvas as an external URL or an iframe if your Canvas security settings permit.

## Student workflow
1. Enter name and date.
2. Explore numbered specimens #01–#11; add one or more photos, choose a method, and describe evidence.
3. After the live instructor-led review, choose **Reflect**. **This locks initial observations**.
4. Mark each original answer correct/incorrect, record the demonstrated method, and write a short reflection.
5. Download the illustrated PDF and upload to Canvas.

## Data and privacy
GitHub Pages serves only the static application. **Student photos and responses are not uploaded to GitHub.** They stay in browser memory/localStorage when space allows and in student-downloaded JSON backups and PDFs. Encourage students to download backups frequently. Browser storage may fail or be cleared, and using private browsing is discouraged. Student backups include their photographs and name; students should keep them private.

The PDF generator loads jsPDF from Cloudflare CDN. Internet access is needed for initial library loading. For best reliability, open the activity online during lab.

## Instructor grading (20 points)
- 8: photos and initial observations
- 4: initial method choices and reasoning (not correctness)
- 6: self-checks and reflections
- 2: final PDF submission

## Included methods
Division; Stolons / Runners; Stem Cuttings; Leaf Cuttings; Rhizomes; Bulbs; Stem Tubers; Grafting; Budding (T-bud); Air Layering; Micropropagation. Corms are reference-only; Other / Unsure is also selectable.

## Important
Students can repeat methods across specimens. Number-to-method answer keys are **not embedded** in the application, because the instructor selects the actual plants and reviews them in person. The app is designed for completion-based grading.


## iPhone PDF fallback (v1.1)

If the external jsPDF script fails to load, tap **Print / Save as PDF (Safari)** in the Export tab. A self-contained illustrated report opens in a new tab. Tap **Print / Save as PDF**, then on iPhone expand the print preview (pinch outward), tap **Share**, and choose **Save to Files**. This report includes all photos and responses and does not depend on external JavaScript libraries.

To update GitHub Pages, replace the repository-root `index.html` with the included revised version. Existing student JSON backup files remain compatible.


## Version 1.3: Offline PDF export

The Download PDF Report button generates a PDF directly in the student browser without a third-party library or print dialog. The backup JSON format is unchanged from earlier versions. Keep the Safari report view as a fallback. For iPhone, open the site in Safari, tap Download PDF Report, then locate the file in Downloads/Files and submit it to Canvas. Test on student devices before class.

## Version 1.4 improvements
- Larger PDF report text with compact, multi-specimen pages when space permits.
- A reflection self-check consistency warning when Correct/Incorrect does not agree with the original and discussed method.
- Native file sharing on supported mobile browsers using the Web Share API, with direct PDF download as fallback. On iOS, choose Save to Files from the system share sheet. Android sharing destinations depend on installed apps.
- The existing version 1 backup JSON format and storage key are unchanged.
