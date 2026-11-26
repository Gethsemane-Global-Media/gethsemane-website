# Gethsemane Kingdom Network Int'l website

Static website for Gethsemane Kingdom Network International (GKNI) and its training arm, the Gethsemane School of Ministry (GSOM). Plain HTML, CSS and JavaScript with no build step.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Church homepage: service times, sermons, testimonies, events, giving, visit and prayer request form |
| `about.html` | Who we are, vision and missions, emblem, founder, journey |
| `arms.html` | The four arms of expression and the six service units |
| `sermons.html` | Sermons |
| `story.html` | Our story |
| `gsom.html` | Gethsemane School of Ministry: courses, training, values, Wave 7 (registration closes 30 January 2027) |
| `register.html` | GSOM Wave 7 registration form |

Images live in `img/` (GSOM images in `img/gsom/`).

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Before going live

- **Wave 7 registration is connected.** `register.html` sends each registration to the Google Form "GSOM Wave 7 Registration (website)" in the GSOM (gsom.gkni@gmail.com) Drive. If questions are added or renamed there, update `FORM_FIELDS` in `register.html` with the new entry ids.
- **Church forms are not connected.** The prayer request form and the newsletter sign-up (`index.html`) only show a preview message. Connect them to a form service that forwards to the right inbox.
- **Placeholders to replace:** church street address and city, bank name and account number for giving, and the Get directions link.
- **Links with no destination:** App Store / Google Play badges, and "Terms and conditions apply" on the GSOM page.
- **Content to confirm with the church:** the "80+ students" figure and the timeline on the About and Story pages.
