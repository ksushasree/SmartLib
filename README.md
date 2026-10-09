# SmartLib AI

Smart library web app: explainable book recommendations, natural-language finder,
catalogue search and filters, book comparison, student dashboard, librarian dashboard.

## Run
Open `index.html` in a browser (no install, no server needed).
`smartlib-standalone.html` is the same app in one file.

## Files
- index.html - page shell
- styles.css - navy/white/teal theme (light and dark)
- app.js - catalogue seed data, recommendation engine, views, actions

## Demo login
Librarian: librarian@smartlib.demo / Librarian@123
Students: register from the Login page.

## Important limits
- Data is saved in the browser's localStorage (per browser, per device). There is no backend or database yet.
- Password hashing (SHA-256 + salt) is a demo only; real auth needs a server.
- Catalogue records are SAMPLE data: titles are real, but copies, shelves and availability are illustrative.
- Not included: Express API, PostgreSQL schema/migrations, API docs, automated tests, syllabus file upload, ISBN/publisher search.

## Next step
Move the data and actions in app.js (D, A.*) behind an Express + PostgreSQL API with
server-side sessions and role checks.
