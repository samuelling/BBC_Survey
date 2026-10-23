# BBC_Survey

Annual report form for the BBC (Brain, Behavior & Cognition) PhD program, served as a static page with GitHub Pages.

- `index.html` is the whole form. Students and advisors pick their name, fill in their section, and submit with their BU email.
- Drafts save in the visitor's own browser. Submissions go to a Google Apps Script web app (set `ENDPOINT` near the top of the script in `index.html`) that checks the email against the roster and appends a row to a private Google Sheet.
- The Apps Script holds the email allowlist and is deliberately not stored in this repo.
