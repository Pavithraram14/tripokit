# Tripokit website project

A responsive five-page static website for Tripokit, using the supplied logo and an orange / aviation-blue visual identity.

## Pages
- `index.html` — Home
- `about.html` — About Tripokit
- `services.html` — Airline reservation support, reservation executives, airport coordination, itinerary and group enquiries
- `leadership.html` — Director Kapil Dev, Co-Director Anguri Devi and General Manager Sumithra Devi
- `contact.html` — Contact details, map-direction link and enquiry form

## Run locally
Open `index.html` in a modern browser. For a local development server, run from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customisation
- Replace `assets/tripokit-logo.jpeg` if you receive a higher-resolution transparent logo.
- Edit colours and layout in `assets/style.css`.
- Edit mobile navigation and enquiry form behaviour in `assets/script.js`.
- The contact form uses `mailto:` and opens the visitor's email application; it does not submit to a server. Connect a secure form backend before using it for online lead collection.
- Photography loads from Unsplash and Google Fonts load from Google Fonts, so those visual assets require an internet connection.

## Important content note
The site describes reservation and airport coordination as enquiry/support services. Do not advertise live airline inventory, confirmed ticketing, direct airport-system connectivity or airport access unless Tripokit has the required provider agreements, system integrations and authorisations. Leadership biographies are written as role-based introductions; add verified career histories, photographs and achievements only after approval.
