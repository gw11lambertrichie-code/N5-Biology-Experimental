NATIONAL 5 BIOLOGY — EXPERIMENTAL SKILLS LAB
===========================================

WHAT IT IS
A free, offline-capable, phone-friendly progressive web app with 79 original multiple-choice challenges covering aims, variables, controls, validity, reliability, graphing, conclusions, evaluation, fieldwork and evaluating evidence.

DEPLOYMENT TO GITHUB PAGES
1. Make a NEW public GitHub repository, e.g. N5-Biology-Experimental-Skills.
2. Upload all files and the icons folder to the ROOT of the repository. The main directory must contain index.html, manifest.webmanifest, service-worker.js, question-bank.json, README-SETUP.txt and the icons folder.
3. Choose Settings > Pages > Deploy from a branch > main > /(root), then Save.
4. Your site address will be https://YOUR_USERNAME.github.io/N5-Biology-Experimental-Skills/
5. Share that HTTPS link in Google Classroom.

For upgrades, upload revised files and change CACHE_NAME in service-worker.js to e.g. v2 to refresh offline cache.
Do not upload a ZIP file as the site content; extract the ZIP locally and upload the contents.

USING ON A PHONE
Open the hosted link in Safari on iPhone (Share > Add to Home Screen) or Chrome on Android (menu > Add to Home screen / Install app, if offered). On supported phones the app can run offline after its assets have been cached on first visit.

PRIVACY AND FEEDBACK
Progress is stored in localStorage, in that browser on that device only. The app does not collect names, send results to a server or sync across devices. The pupil can export a CSV summary or clear their progress.

QUESTION SOURCES AND ALIGNMENT
These are original, self-contained questions—not reproductions of SQA/Qualifications Scotland past papers or official marking instructions. Question design is informed by:
- Qualifications Scotland National 5 Biology Course Specification (June 2026 v5.0, for session 2026–27), especially scientific inquiry/analytical skills and the stated definitions of control, validity and reliability in the support notes.
- Qualifications Scotland National 5 Biology Question Paper Brief (June 2026), which includes planning, processing, conclusions and evaluation in the assessed skills.
- Qualifications Scotland National 5 Biology Course Report 2025, which identifies difficulty describing why a study was invalid (Q11(c)), stating conclusions rather than merely restating results (Q9(d)(ii)), identifying controls/controlled variables (Q14(a)(ii)) and writing an evidence-supported conclusion in the assignment.
Question contexts and demand are inspired by the National 5 papers, not copied from them. This app does not award exam marks or replace official guidance.

TO EDIT QUESTIONS
Each question is stored twice: as structured data in question-bank.json for auditing or revision, and embedded inside index.html so the webpage opens locally with no network. Editing only question-bank.json will NOT update the running app: the embedded DATA in index.html must also be updated to match. Keep a source backup before editing.
