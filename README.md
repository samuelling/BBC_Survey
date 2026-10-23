# BBC_Survey

Annual report form for the BBC (Brain, Behavior & Cognition) PhD program, served as a static page with GitHub Pages.

- `index.html` is the whole form. Each student and each student-advisor pair gets a personal link (`...#code`) by email; the code decides who you are and which form you see.
- Answers autosave to a Google Apps Script web app (`ENDPOINT` in `index.html`), which stores drafts and submissions in a private Google Sheet, so people can resume on any device.
- The Apps Script holds the roster, emails and codes, and sends the invitation emails. It is deliberately not stored in this repo.
