# SNote Web

`index.html` is the whole web app (no build step), served at https://notes.sampatton.fyi by Cloudflare Pages.
Sign in with a SNote account to view and edit notebooks. Add `#demo` to the address to try sample data without signing in.

- Shows notebooks, paper styles, text boxes, typed pages and ink synced from the SNote app.
- Edit mode: pen, marker, eraser, text boxes, undo/redo, add/delete pages, create/delete notebooks.
- Typed pages: add and edit them (styles, bold/italic/underline, lists, alignment, page breaks); the text flows onto new pages like in the app.
- Import PDF: choose a PDF, name it and pick a folder; each page becomes a notebook page to write on. The file is stored in Firestore in 600 KB pieces (limit 25 MB), so it also appears in the app.

`_headers` limits the page to Google's sign-in and database servers. The previous "Coming Soon" page is in the git history.
