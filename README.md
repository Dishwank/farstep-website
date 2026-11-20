# Farstep Overseas Consultancy website

A responsive, static multi-page website rebuilt using the public Farstep reference website as the content and navigation reference.

## Files
- `index.html` — Home page and WhatsApp counselling form
- `services.html` — University applications, test preparation, visa guidance and education loans
- `universities.html` — Informational directory of universities in seven destinations
- `about.html` — About Farstep
- `contact.html` — Contact and counselling enquiry page
- `styles.css` — Responsive styles
- `script.js` — Mobile navigation, year and WhatsApp form handling
- `assets/farstep-logo.png` — Farstep logo supplied earlier

## Contact
The phone number `+91 93920 84263` is retained. Enquiry forms open WhatsApp with a pre-filled message to `https://wa.me/919392084263`. The visitor must press Send in WhatsApp. This static site does not store enquiries or send email automatically.

## Preview locally
Open `index.html` in a browser. For best results, run a local static server, e.g. `python -m http.server 8000`, then visit `http://localhost:8000`.

## Deploy to Vercel
1. Create a GitHub repository, e.g. `farstep-website`.
2. Upload all files and folders from this project (keep `assets/` in place).
3. In Vercel, choose **Add New → Project**, import the GitHub repository.
4. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (or leave the default for a static site if Vercel detects it).
5. Deploy.
6. In the new Vercel project, open **Settings → Domains**, add `farstepoverseas.live` and `www.farstepoverseas.live`.
7. Copy the exact DNS records Vercel displays into Spaceship DNS. Do not guess record values; use the values Vercel provides.

## Important
- No backend/database is configured. The forms create a WhatsApp message and do not save submissions on a server.
- University listings are informational only and do not imply formal partnerships.
- Review all company claims, contact details, legal/privacy wording and destination information before publishing.
