# Ahara — Food & Ayurveda Database (starter app)

This is a mobile-friendly Progressive Web App (PWA) prototype. It includes searchable food cards, category filters, nutrition fields, Ayurvedic fields, detail views, and a local editor.

## Run locally
Open `index.html` in a modern browser. For install/offline PWA features, serve the folder over HTTPS or localhost.

## Publish free
1. Create a GitHub account and a new public repository.
2. Upload all files in this folder to the repository root.
3. Open repository **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. GitHub will provide a public website URL. Open it on your phone and use the browser menu → **Add to Home screen** / **Install app**.

## Important prototype limitations
- Current sample data and edits are stored in the visitor's browser (`localStorage`). Your edits do not sync to other phones or visitors.
- The demo editor code `2468` is visible in this source and is NOT secure. Do not use it as real owner authentication.
- To meet the intended production setup (only you can add/edit, everyone can search, shared data across devices), the next step is to connect a hosted database and real owner authentication, e.g. Supabase. This requires creating a free project and configuring its public URL/key and access policies.
- Nutrition figures are approximate sample values. Ayurvedic descriptions are illustrative and must be checked against the chosen classical references before publication. This app is an educational reference, not medical advice.

## Food data fields
Name, category, calories, protein, carbohydrates, fat, Rasa, Guna, Virya, Vipaka, Dosha effect, notes.
